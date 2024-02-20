# LH_CD_VITOR
Projeto Ciência de dados Incidium

O arquivo notebook .ipynb contem o relatório desenvolvido

O projeto desenvolvido abaixo consiste em 5 etapas:

1. **Importação e Tratamento dos Dados**
   - Nesta etapa, é realizado a importação dos dados do github, verificando a presença de valores nulos e os tipos de cada variável.

2. **Análise Exploratória**
   - Exploração dos dados para obter insights iniciais, estatísticas descritivas e compreensão geral do conjunto de dados.

3. **Identificação das Regiões Mais Bem Avaliadas**
   - Analise os dados para identificar as regiões que apresentam maior quantidade de avaliações mensais, além do preço.

4. **Visualização de Correlações entre as Variáveis**
   - Utilização de um mapa de calor para identificar o grau de correlação entre algumas variáveis.

5. **Criação de um Modelo Regressivo para Inferência de Preços**
   - Nesta ultima etapa é realizada a construção de um modelo regressivo para inferir os preços da diária dos imóveis. Durante a construção é realizada a etapa de separação, treinamento e validação do modelo gerado.
  

Para rodar o modelo basta importar as bibliotecas com o código:

!pip install -r requirements.txt 

e para rodar o modelo  .pkl :

import pickle

with open("modelo.pkl", "rb") as f:
    model = pickle.load(f)
    
prever_valor(dados,model,X_test.head(0))

Este projeto foi desenvolvido por Vitor Cabral, qualquer dúvida estou a disposição no linkedin https://www.linkedin.com/in/v%C3%ADtorcabral/ =) !

