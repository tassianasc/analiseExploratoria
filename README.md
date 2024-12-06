# Análise de Dados de Indicados ao Oscar 🎬

Este projeto visa explorar e analisar dados sobre indicados ao Oscar, com foco em características demográficas, frequência de indicações e padrões de diversidade. Utilizamos Python e bibliotecas de visualização para extrair insights e responder a perguntas relevantes sobre o perfil dos indicados.

## Sumário 📑

1. [Contexto](#contexto)
2. [Objetivos da Análise](#objetivos-da-análise)
3. [Etapas da Análise](#etapas-da-análise)
4. [Ferramentas Utilizadas](#ferramentas-utilizadas)
5. [Como Executar a Análise](#como-executar-a-análise)
6. [Principais Resultados](#principais-resultados)

---

### Contexto

Os dados contêm informações demográficas e profissionais dos indicados ao Oscar, incluindo nome, data e local de nascimento, religião, etnia, orientação sexual, categoria de indicação, filme, entre outros. Esta análise visa revelar padrões no perfil dos indicados, oferecendo insights sobre representatividade e diversidade.

### Objetivos da Análise

1. Explorar características gerais dos indicados ao Oscar ao longo dos anos.
2. Analisar distribuições demográficas, como idade, etnia e religião.
3. Identificar padrões de indicações em categorias específicas.
4. Avaliar a distribuição por década e o impacto no perfil demográfico.

### Etapas da Análise

A análise foi realizada com as seguintes etapas:

1. **Importação dos Dados**: Carregamos e verificamos a estrutura dos dados.

   ![Captura de tela de 2024-12-06 10-55-58](https://github.com/user-attachments/assets/8dd2560d-78de-4966-87b7-323dee4db5c2)

3. **Pré-processamento e Limpeza**:
   - Renomeação de colunas para facilitar a leitura.
   - Tratamento de valores ausentes, substituindo valores por categorias "Desconhecida" onde aplicável.
4. **Exploração de Dados**:
   - Frequências de valores categóricos, como religião e etnia.
   - Distribuição de idades e presença de outliers em variáveis numéricas.
5. **Visualizações**:
   - Gráficos de barra e boxplots para explorar categorias, idade e etnia por década.
6. **Resultados Estatísticos**:
   - Contagem de indicações por cidade de nascimento e frequência de indicações por ator.

### Ferramentas Utilizadas

A análise foi conduzida em Python, utilizando as bibliotecas:

- **Pandas**: Para manipulação e análise de dados.
- **Matplotlib** e **Seaborn**: Para visualização de dados.

### Como Executar a Análise

1. Certifique-se de ter o Python instalado (recomenda-se Python 3.8 ou superior).
2. Instale as bibliotecas necessárias:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Baixe o arquivo de dados `tabelaOscar.csv` e o script Jupyter Notebook ou execute o código diretamente em um ambiente Python.

### Principais Resultados

- **Distribuição por Religião**: A análise mostra uma variação significativa na religião dos indicados. 
- **Idade e Categoria**: A distribuição de idade por categoria indicou que certas categorias possuem indicados mais jovens ou mais experientes, dependendo do tipo de papel ou habilidade.
- **Indicações por Etnia e Década**: Analisamos a representatividade ao longo das décadas, observando mudanças na diversidade entre os indicados.
- **Principais Indicados**: Identificamos os atores mais indicados e os filmes mais antigos e recentes no dataset.

### Exemplos de Visualizações

- **Gráfico de Frequência de Religião**: Visualiza a quantidade de indicados de acordo com a religião.
- **Distribuição de Idade por Categoria**: Utilizando um boxplot, a análise mostra a variação etária por categoria de indicação.
- **Etnia por Década**: Com um gráfico de contagem, é possível observar as mudanças na representatividade étnica ao longo do tempo.

---

A análise ajuda a entender melhor o perfil dos indicados ao Oscar, suas origens, e sua diversidade ao longo dos anos, trazendo uma perspectiva histórica e demográfica sobre essa renomada premiação.

--- 

