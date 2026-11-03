# Orçamento HTML
Dashboard de acompanhamento por área, com sessão CENTRAL e API `/api/suprimentos-html/orcamento`.

A visão geral usa exclusivamente o total oficial de cada área. O detalhamento mantém contas e subtotais sem somá-los novamente.

Previsto proporcional = orçamento mensal × dias corridos até a referência ÷ dias do mês. A referência vem da extração, nunca avança sem dados novos. Meses encerrados usam 100% do orçamento.

Situação: acima de 105% vermelho; abaixo de 95% amarelo; de 95% a 105% normal. A razão usa magnitudes para despesas negativas. Realização sem orçamento é vermelha e fica sem percentual.

Nenhum arquivo operacional ou credencial faz parte deste repositório. O robô, os arquivos oficiais e a importação ficam no ambiente privado.

## Incorporação
```html
<iframe title="BI - Orçamento" src="https://controladoriagranja.github.io/bi-Orcamento/" width="100%" height="950" style="border:0" allowfullscreen></iframe>
```
Cadastrar o relatório na CENTRAL e conceder os acessos aos usuários.
