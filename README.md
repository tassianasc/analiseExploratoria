
# Análise Exploratória dos Dados dos Vencedores do Oscar

Este repositório contém uma análise exploratória dos dados dos vencedores do Oscar ao longo dos anos, abordando características como ano de nascimento, etnia, religião e outras informações pessoais. O projeto foi desenvolvido com Python, utilizando `pandas` para manipulação de dados e `matplotlib` e `seaborn` para visualizações.

## Estrutura do Projeto

- `codigo.ipynb`: Notebook Jupyter com a análise detalhada.
- `tabelaOscar.csv`: Dataset utilizado para a análise, com informações sobre vencedores do Oscar.

## Objetivo

O objetivo do projeto foi explorar dados demográficos e características dos vencedores do Oscar, investigando padrões e tendências de variáveis como etnia, religião e ano de nascimento.

## Etapas da Análise

1. **Importação de Bibliotecas**
   - Utilizamos `pandas`, `matplotlib`, e `seaborn` para manipulação e visualização de dados.

2. **Carregamento e Visualização Inicial dos Dados**
   - O dataset foi carregado usando `pandas` e inspecionado com a exibição das primeiras entradas.

3. **Renomeação de Colunas**
   - As colunas foram renomeadas para nomes mais claros em português:
     - `birth_year` para `ano_nascimento`
     - `birth_date` para `data_nascimento`
     - `birthplace` para `local_nascimento`
     - `race_ethnicity` para `etnia`
     - `religion` para `religiao`
     - `sexual_orientation` para `orientacao_sexual`
     - `year_edition` para `ano_edicao`
     - `category` para `categoria`
     - `movie` para `filme`

4. **Tratamento de Dados Faltantes**
   - Valores ausentes em `data_nascimento` foram preenchidos com "Data desconhecida".
   - Na coluna `religiao`, uma nova categoria "Desconhecida" foi criada para lidar com valores ausentes.

5. **Análise Exploratória**
   - **Religião**: Contagem das religiões representadas, com visualização em gráfico de barras para facilitar a compreensão.

6. **Visualização dos Dados**
   - Gráficos de barras foram utilizados para representar visualmente a frequência de religiões no dataset, trazendo uma visão clara das categorias e contagens de cada grupo.

## Tecnologias Utilizadas

- **Python**
- **Bibliotecas**: `pandas`, `matplotlib`, `seaborn`

## Como Utilizar este Repositório

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu_usuario/nome_do_repositorio.git
   ```
2. Instale as dependências necessárias:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Abra o notebook `codigo.ipynb` para acompanhar a análise.

## Resultados e Conclusões

A análise revelou tendências interessantes entre os vencedores do Oscar, possibilitando uma visão das diversas representações de etnia, religião e outros aspectos demográficos ao longo das edições do prêmio.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir um *issue* ou enviar um *pull request*.
