# Trabalho-para-integra-o-Projeto-Integrado-Do-Dado-ao-Insight-
Análise completa do desmatamento no Brasil usando dados PRODES (2000–2023). Limpeza, visualização, insights e gráficos.

🌳 README — Projeto Integrado: Do Dado ao Insight<br>
Big Data • Computação na Nuvem • Análise Computacional • Qualitativa de Dados
Este repositório contém uma análise completa dos dados de desmatamento do Brasil, utilizando a base PRODES (INPE) disponibilizada por basedosdados.org.
O objetivo é demonstrar como dados ambientais podem gerar insights sociais, econômicos e éticos, além de apoiar planejamento urbano, industrial e agropecuário sustentável.<br>


🗂️ Dataset Utilizado<br>
Fonte: Instituto Nacional de Pesquisas Espaciais (INPE)
Disponibilização: basedosdados.org  
Arquivo: br_inpe_prodes_municipio_bioma.csv  
Período: 2000–2023
Granularidade: Município + Bioma

Principais colunas:

ano

bioma

id_municipio

desmatado

area_total

vegetacao_natural

nao_vegetacao_natural

hidrografia<br>

🔧 Pipeline Implementado no Notebook
O notebook DoDadoAoInsightDesmatamentoMarjaGringel.ipynb contém:<br>

✔ 1. Upload do dataset
Via Google Colab.

✔ 2. Limpeza e processamento
padronização

remoção de duplicatas

filtragem temporal

remoção de valores inválidos

✔ 3. Análise exploratória<br>
agrupamento por ano

agrupamento por bioma

identificação de padrões<br>

✔ 4. Visualização
gráficos (flare, deep)<br>


✔ 5. Insights<br>
ano mais crítico

ano mais preservado

bioma mais afetado<br>

✔ 6. Reflexão ética ampliada
Texto completo incluído no notebook, sem alterações.<br>

📊 Visualizações Incluídas<br>
Linha temporal do desmatamento anual (2000–2023)

Gráfico horizontal do desmatamento por bioma

Destaque dos anos e biomas mais críticos

As visualizações utilizam:

Seaborn

Matplotlib

Pandas<br>

🔍 Principais Insights<br>
Identificação dos anos com maior e menor desmatamento

Biomas mais afetados ao longo das décadas

Tendências gerais e padrões de comportamento

Relação entre biomas e pressão antrópica<br>


🧭 Reflexão Ética e Impacto Social<br>
Os dados do PRODES são fundamentais para:

Planejamento urbano sustentável

Planejamento industrial e agropecuário

Preservação de biomas

Fiscalização ambiental

Políticas públicas baseadas em evidências<br>

⚠️ Questões Éticas<br>
Transparência no uso dos dados

Responsabilidade na divulgação

LGPD ao cruzar dados socioeconômicos

Inclusão digital

Uso responsável de IA

Evitar manipulação política

Evitar fraudes ou adulterações<br>

🧰 Tecnologias Utilizadas<br>
Python

Pandas

Seaborn

Matplotlib

Google Colab

Gamma (para slides)<br>

📈 Objetivo Geral<br>
Demonstrar como dados ambientais podem gerar insights valiosos, apoiar decisões estratégicas e promover desenvolvimento sustentável sem comprometer a integridade dos biomas brasileiros.<br>

## 📄 Slides da Apresentação<br>
[👉 Clique aqui para abrir os slides em PDF](slides/Do-Dado-ao-Insight.pdf)<br>


👤 Autor<br>
Projeto desenvolvido por Marja Gringel, como parte do trabalho integrado Do Dado ao Insight.
