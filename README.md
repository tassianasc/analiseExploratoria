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
   ![Captura de tela de 2024-12-06 10-54-49 1](https://github.com/user-attachments/assets/42b6d1ef-2e9a-4d4e-9a2f-0be5036e96ae)


  
3. **Pré-processamento e Limpeza**:
   - Renomeação de colunas para facilitar a leitura.
     ![Captura de tela de 2024-12-06 10-55-58](https://github.com/user-attachments/assets/e9c57d4d-bc89-4d48-a773-1f85fa1f75d3)

   - Tratamento de valores ausentes de data de nascimento e religião, substituindo valores por categorias "Desconhecida" onde aplicável.
     ![Imagem do WhatsApp de 2024-12-06 à(s) 11 08 53_00997259](https://github.com/user-attachments/assets/17c3eada-6329-494f-af76-066cc58a22df)
![Imagem do WhatsApp de 2024-12-06 à(s) 11 08 53_00997259](https://github.com/user-attachments/assets/accdafee-eb31-4122-ab60-23cb4cb23ee7)

4. **Exploração de Dados**:
   - Frequências de valores categóricos, como religião e etnia.
     ![religiao](https://github.com/user-attachments/assets/1c0227f4-8117-4191-9eaa-7d5b553112a2)
A etnia "White" (Branca) tem uma frequência significativamente maior do que todas as outras etnias, indicando uma representação desproporcional em relação às demais categorias.As outras etnias, como "Black", "Hispanic", "Asian", "Multiracial", e "Middle Eastern", têm frequências bem menores, indicando uma possível desigualdade de representação.

   - Distribuição de idades e presença de outliers em variáveis numéricas.
     ![Imagem do WhatsApp de 2024-12-06 à(s) 11 26 00_c8a3084b](https://github.com/user-attachments/assets/0d50820b-8c88-4bab-ac10-6de5c9b43179)

5. **Visualizações**:
   - Gráficos de barra e boxplots para explorar categorias, idade e etnia por década.
     ![Imagem do WhatsApp de 2024-12-06 à(s) 11 30 03_15588231](https://github.com/user-attachments/assets/cc52505b-34a3-41f9-a476-8fc2690e4a1f)

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

