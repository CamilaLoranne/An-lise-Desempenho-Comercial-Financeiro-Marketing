# Dashboard Analítico de Desempenho Comercial, Financeiro e de Marketing

Este repositório contém um dashboard analítico desenvolvido para fornecer uma visão detalhada sobre o desempenho comercial, financeiro e de marketing da empresa. Ele foi projetado para apoiar a tomada de decisões estratégicas por meio de indicadores consolidados e detalhamento operacional, fornecendo uma visão de 360 graus sobre o desempenho da organização.

## Objetivo
O dashboard visa fornecer:
- **Análise Comercial**: Informações detalhadas sobre vendas, estoque, e o desempenho de cada empreendimento.
- **Análise Financeira**: Insights sobre a receita, fluxo de caixa e margens financeiras.
- **Análise de Marketing**: Eficiência de campanhas, geração de leads e conversões.

## Público-Alvo
O dashboard foi desenvolvido para ser utilizado por:
- Diretoria Executiva
- Gestores Comerciais
- Gestores Financeiros
- Gestores de Marketing

## Funcionalidades

### Métricas e Fórmulas Utilizadas
O dashboard utiliza métricas chave para acompanhar o desempenho da empresa. Algumas das principais incluem:
- **% de Cancelamento**: Proporção de vendas canceladas em relação ao total.
- **Ticket Médio Concluído**: Valor médio das vendas concluídas.
- **VGV Realizado**: Valor total das vendas realizadas.
- **Receita Mensal e Acumulada**: Monitoramento da receita gerada por mês e acumulada ao longo do tempo.
- **Velocidade de Vendas**: Análise de quantas unidades são vendidas por mês.

### Drillthrough: Detalhamento por Empreendimento
A página de **detalhe do empreendimento** é configurada como um **drillthrough**, permitindo ao usuário explorar dados de um empreendimento específico, acessando informações mais detalhadas de vendas, financeiro e marketing, baseadas no filtro do empreendimento selecionado.

## Tecnologias Utilizadas
- **Power BI Desktop**: Para modelagem e visualização de dados.
- **Power Query**: Para transformação de dados e tipagem de colunas.
- **DAX**: Para cálculos e inteligência de tempo no modelo de dados.

## Estrutura do Repositório
- **/capturas de tela**: Imagens do dashboard para ilustrar as funcionalidades.
- **/docs**: Documentos de apoio, como a documentação técnica e outras análises.
- **Análise.pbix**: O arquivo principal do Power BI com o dashboard completo.
- **Bases_Analist.Dados.xlsx**: Fontes de dados utilizadas no modelo do Power BI.

## Fontes de Dados
O dashboard é alimentado por 6 fontes principais de dados:
- **Empreendimentos**
- **Vendas**
- **Financeiro**
- **Leads**
- **Obras**
- **Marketing**

## Como Rodar o Projeto

1. Baixe e instale o **Power BI Desktop** [aqui](https://powerbi.microsoft.com/desktop/).
2. Abra o arquivo `.pbix` presente na pasta **/src**.
3. Conecte as fontes de dados, caso necessário, e execute o modelo.
