# 🏭 Indústria Brasileira: Análise de Dados (2007-2023)

Dashboard completo com dados reais da Pesquisa Industrial Anual (PIA) do IBGE.

## 📊 Tecnologias utilizadas
- **SQL (DBeaver + SQLite):** extração e consultas analíticas
- **Python (Pandas, Jupyter):** limpeza, transformação e exportação
- **Looker Studio:** visualização interativa e storytelling

## 📁 Estrutura do projeto
| Arquivo | Descrição |
|---------|-----------|
| `tabela_1849_industria.csv` | Dados brutos do IBGE (SIDRA) |
| `industria_limpa.csv` | Dados limpos e estruturados |
| `industria_brasileira.db` | Banco SQLite com a tabela `industria` |
| `limpeza_industria.ipynb` | Notebook Jupyter com o pipeline de limpeza |
| `grafico1_top_estados.csv` | Top estados por unidades industriais |
| `grafico2_evolucao_empresas.csv` | Evolução anual do nº de empresas |
| `grafico3_salario_medio.csv` | Salário médio mensal ao longo do tempo |
| `grafico4_receita_custos.csv` | Receita vs Custos vs Margem |
| `grafico5_setores.csv` | Ranking de setores (VTI por trabalhador) |
| `grafico6_mapa_brasil.csv` | Dados estaduais para o mapa |

## 🔍 Principais insights

1. **🗺️ Concentração regional:** A indústria brasileira é concentrada no eixo Sul-Sudeste — São Paulo sozinho gera mais valor que Norte e Nordeste juntos.

2. **📈 10 anos perdidos:** O número de unidades industriais atingiu o pico em 2014 e só retornou a esse patamar em 2023 — estagnação de uma década.

3. **💰 Salários em alta:** O salário médio mensal saltou de R$ 1.600 (2007) para R$ 4.400 (2023), com forte aceleração pós-2020.

4. **💵 Lucro recorde:** A margem da indústria disparou após a pandemia, sinalizando maior eficiência operacional.

5. **🏭 Duas indústrias:** A Indústria de Transformação emprega mais, mas a Extrativa gera muito mais valor por trabalhador — reflexo da dependência de commodities.

## 🔗 Dashboard no Looker Studio
[[Link para o relatório interativo]([https://datastudio.google.com/s/sKH-MOuP170])

## 📚 Fonte
IBGE - Pesquisa Industrial Anual (PIA) - Tabela 1849
