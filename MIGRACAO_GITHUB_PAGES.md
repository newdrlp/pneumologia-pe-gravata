# Roteiro de migração - gravata

Este repositório replica o padrão validado no piloto saude.

## Modelo

Um repositório separado por clínica, porque GitHub Pages aceita um único CNAME por site.

## DNS no Wix

| Subdomínio | Tipo | Valor |
| --- | --- | --- |
| gravata | CNAME | newdrlp.github.io |

## Validação após DNS

1. Abrir http://gravata.pneumologia-pe.com.br/ e confirmar Server: GitHub.com.
2. Aguardar HTTPS/SSL do GitHub Pages.
3. Abrir https://gravata.pneumologia-pe.com.br/.
4. Abrir https://gravata.pneumologia-pe.com.br/pre-atendimento/.
5. Fazer envio controlado e confirmar chegada no Apps Script/planilha.