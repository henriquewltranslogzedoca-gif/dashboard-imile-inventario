# Dashboard de inventário iMile

Painel estático em HTML para analisar uma exportação do inventário sem API ou servidor.

## Como usar

Abra o endereço do GitHub Pages, clique em **Escolher arquivo** e selecione a exportação `.xlsx` ou `.csv`. Os dados são processados no navegador e não são publicados no repositório. Carregue uma nova exportação para atualizar os indicadores.

O Excel depende da biblioteca SheetJS carregada por CDN; CSV não precisa dessa dependência. Os indicadores usam `Last scan type` de cada `Waybill No`, com regras ajustáveis em **Ajustar classificação dos status**. O campo `Waybill Status` com valor `Entrega` não indica uma entrega concluída.
