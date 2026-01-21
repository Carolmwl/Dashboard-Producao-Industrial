# 🏭 Manufacturing Performance Dashboard

## 📊 Visão Geral do Projeto
Este projeto apresenta uma solução de Business Intelligence desenvolvida em **Power BI** voltada para o setor industrial. O dashboard monitora o fluxo de produção de ponta a ponta, permitindo que gestores de manufatura acompanhem a eficiência das linhas de produção, a performance dos operadores e a qualidade final dos produtos.

A solução transforma dados operacionais em insights estratégicos para a redução de desperdícios e a otimização da capacidade produtiva da planta.

![Dashboard de Produção Industrial](dashboard_producao.jpg)

## 🎯 Problema de Negócio e Solução
O gerenciamento de uma planta industrial exige controle rigoroso sobre o tempo de máquina e a perda de materiais. Sem uma visão centralizada, é difícil identificar quais produtos estão gerando mais prejuízo ou em quais meses a disponibilidade das máquinas caiu.

Este dashboard resolve essas dores ao:
* **Identificar Gargalos de Qualidade:** Apontando exatamente quais produtos possuem o maior índice de rejeição.
* **Monitorar a Disponibilidade:** Quantificando o impacto das horas paradas na capacidade produtiva total.
* **Analisar Sazonalidade:** Visualizando picos e quedas de produção ao longo do ano para melhor planejamento de demanda.

## 📈 Principais KPIs e Métricas (Dados Reais do Projeto)
O dashboard utiliza indicadores críticos para a gestão da produção:
* **Qualidade (99,32%):** Altíssima precisão produtiva, com mais de 3 milhões de unidades aprovadas frente a apenas 21 mil rejeitadas.
* **Disponibilidade (77,69%):** Revela uma oportunidade de melhoria operacional, evidenciada pelas **8.890 horas paradas**.
* **Produção Mensal:** Volume total produzido com picos identificados em Julho (318 Mil) e Janeiro (310 Mil).
* **Top Rejeição por Produto:** O item *Racing Madness 2009 E169* lidera as perdas com 285 unidades descartadas, seguido pela linha de *Home Theater Systems*.

## 🛠️ Ferramentas e Tecnologias Utilizadas
* **Power BI:** Desenvolvimento de todo o ambiente de BI.
* **DAX (Data Analysis Expressions):** Criação de métricas complexas para cálculo de % de Qualidade e Disponibilidade.
* **Modelagem de Dados:** Estruturação de tabelas de fatos (produção) e dimensões (calendário, produtos, operadores).
* **UI/UX Design:** Aplicação de *Dark Theme* com alto contraste para facilitar a leitura em ambientes de chão de fábrica (monitores de monitoramento).

## 🧠 Funcionalidades
* **Filtros por Operador:** Permite analisar a produtividade individual ou por equipe.
* **Gráfico de Barras Dinâmico:** Ranking de produtos rejeitados para atuação rápida na causa raiz.
* **Análise Temporal Completa:** Segmentação por Ano, Mês e Dia para rastreabilidade total.
* **Indicadores de Status (Gauges):** Visualização imediata do atingimento de metas de qualidade e eficiência.

## 🚀 Como Executar o Projeto
1. Clone este repositório.
2. Certifique-se de ter o **Power BI Desktop** instalado.
3. Abra o arquivo `.pbix` para interagir com os dados.

---
*Desenvolvido por [Caroline Mann Wharton Luzio](https://www.linkedin.com/in/caroline-mann-wharton-luzio/)*
