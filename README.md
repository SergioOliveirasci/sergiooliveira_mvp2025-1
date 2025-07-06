MVP - Análise e Pré-processamento de Dados
Repositório desenvolvido como parte do projeto MVP da disciplina Análise Exploratória e Pré-processamento de Dados - Pós-Graduação em Engenharia de Software para Ciência de Dados - PUC-Rio.

Tema do Projeto
Análise exploratória e pré-processamento de dados utilizando a base de medicamentos do Kaggle, com o objetivo de investigar padrões, correlações e possíveis insights relacionados à prescrição de remédios para diferentes faixas etárias, condições médicas e gêneros.

Dataset
O dataset utilizado neste projeto está disponível no Kaggle:

Nome: Drug Dataset

Link: Kaggle - Drug Dataset

O arquivo foi adicionado neste repositório e também está referenciado diretamente pelo link raw do GitHub para garantir execução automática no Colab.

Tipo de Aprendizado
Este é um problema de classificação supervisionada, pois o dataset possui rótulos (coluna Drug) que indicam a medicação prescrita com base em atributos como idade, pressão arterial e nível de colesterol.

Checklist Atendido
 Definição clara do problema

 Descrição e entendimento dos atributos do dataset

 Análise estatística e visual exploratória

 Identificação de valores ausentes e inconsistentes

 Aplicação de técnicas de pré-processamento como encoding e normalização

 Utilização de gráficos explicativos e interpretação dos resultados

 Código limpo, comentado e com blocos de texto explicativos

 Notebook executável do início ao fim sem erros

Etapas do Projeto
1. Definição do Problema
Investigar quais atributos influenciam na escolha de um determinado medicamento, com foco em possíveis padrões relacionados à faixa etária, sexo, pressão arterial, colesterol e nível de sódio e potássio no sangue.

2. Análise Exploratória
Estatísticas descritivas (média, moda, desvio padrão, valores ausentes)

Distribuição de atributos categóricos e numéricos

Visualização com gráficos de barra, histograma, boxplot e pairplot

Análise de correlações

3. Pré-processamento
Conversão de variáveis categóricas com One-Hot Encoding

Normalização de atributos numéricos

Tratamento de possíveis valores inconsistentes

Preparação dos dados para modelagem futura

Estrutura do Repositório
r
Copiar
Editar
├── README.md               <- Este arquivo
├── mvp_colab_notebook.ipynb <- Notebook no Google Colab com todas as análises
├── drug200.csv             <- Dataset utilizado (cópia local)
📎 Execução
O notebook pode ser executado diretamente via Google Colab:

 Acessar Notebook no Colab

O dataset é carregado automaticamente a partir da versão raw hospedada neste repositório.

Observações
O projeto foi desenvolvido de acordo com os critérios estabelecidos no documento "Requisitos para o Desenvolvimento do MVP".

Todas as decisões de modelagem e pré-processamento estão justificadas em blocos de texto no notebook.

O projeto foca exclusivamente na análise e preparação dos dados; a modelagem preditiva poderá ser explorada em etapas futuras.

Autor
Sérgio Oliveira


