# Análise de Séries Temporais da Receita Municipal

Este projeto tem como objetivo realizar uma análise de séries temporais da arrecadação do Município de Osasco. A análise é conduzida em Python, utilizando bibliotecas como Pandas, Matplotlib, Seaborn e Statsmodels.

## Funcionalidades Principais

### 1. Coleta de Dados

Os dados de arrecadação são obtidos de fontes públicas e consolidados em um arquivo CSV. O arquivo consolidado já inclui informações adicionais sobre espécie de receita, categoria econômica e fonte de recursos.

### 2. Manipulação e Exploração de Dados

Após a coleta, o código realiza manipulações para indexar os dados por mês e ano, facilitando a análise temporal. A exploração inicial inclui a visualização da estrutura do DataFrame e informações estatísticas.

### 3. Visualização Temporal

Uma visualização simples da arrecadação mensal é gerada para oferecer uma compreensão geral do comportamento da série temporal ao longo do tempo.

### 4. Análise dos Componentes Principais

#### 4.1. Por Fonte de Recurso

A análise inclui a decomposição dos componentes principais (tendência, sazonalidade e resíduos) da arrecadação por fonte de recurso. Isso permite entender padrões específicos de cada fonte.

#### 4.2. Por Espécie de Receita

A decomposição também é aplicada para analisar os componentes da arrecadação por espécie de receita, destacando a tendência, sazonalidade e resíduos específicos de cada categoria.

## Como Utilizar

1. **Instalação de Dependências:**
    Certifique-se de ter as bibliotecas necessárias instaladas.
   
3. **Coleta de Dados:**
    Os dados já consolidados estão disponíveis [neste arquivo CSV](https://raw.githubusercontent.com/moraesjoyces/Series-Temporais-Receitas/main/Series-Receita.csv).

4. **Execução do Código:**
    Execute o código Python em um ambiente compatível (Jupyter Notebook, VSCode, etc.) para explorar os dados e visualizações.

## Considerações

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests para melhorias e correções.

Esse projeto oferece uma visão abrangente da arrecadação municipal, destacando padrões temporais e permitindo uma análise detalhada dos componentes principais ao longo do tempo. O Município de Osasco foi selecionado como piloto, porém pode ser facilmente substituído por qualquer outro do Estado de SP. Além disso, a análise da Fonte do Tesouro e do ISSQN pode ser facilmente expandida para outras fontes e espécies.
