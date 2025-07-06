# MVP2025‑1 – Sérgio Oliveira

Este repositório contém o projeto desenvolvido por **Sérgio Oliveira** como parte do MVP 2025‑1, estruturado em um notebook Jupyter hospedado no Google Colab.

## Objetivo do Projeto

Aplicar técnicas de **aprendizado supervisionado** para classificar o tipo de medicamento mais adequado (Drug A/B/C/X/Y) para pacientes, com base em variáveis clínicas como:

- Idade
- Sexo
- Pressão arterial
- Colesterol
- Relação sódio/potássio

## Organização dos Arquivos

- `notebook.ipynb`: o notebook principal com execução sequencial.
- `README.md`: este arquivo, contendo instruções gerais.

##  Conteúdo do Notebook

1. **Importação de bibliotecas**: `pandas`, `numpy`, `seaborn`, `scikit-learn`, etc.
2. **Carregamento e inspeção dos dados**.
3. **Análise exploratória (EDA)**: visualização e estatísticas descritivas.
4. **Pré‑processamento**:
   - Codificação de variáveis categóricas (One‑Hot).
   - Escalonamento de features se necessário.
5. **Treinamento de modelos**:
   - **Decision Tree**
   - **K‑Nearest Neighbors**
   - **Support Vector Machine**
   - **Random Forest**
6. **Avaliação de performance**:
   - Acurácia
   - Matriz de confusão
   - Relatório de classificação (precision, recall, f1‑score)
7. **Comparação de modelos** e escolha do melhor.

## Como Executar

Este projeto foi desenvolvido e testado no **Google Colab**, que já inclui as bibliotecas necessárias.

###  Executar no Colab

Basta abrir o notebook no Colab e executar todas as células:

[ Abrir no Colab](https://colab.research.google.com/drive/1daCT-Fuf-lAXuSyMOPNdSNu4y-eXJkce)

### 🔹 Executar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/SergioOliveirasci/sergiooliveira_mvp2025-1.git
   cd sergiooliveira_mvp2025-1

pip install -r requirements.txt

pip install notebook

jupyter notebook

Abra o notebook .ipynb e execute.

Resultados Esperados
Modelos comparados com acurácia e relatórios.

Visualizações como gráficos de barras, distribuções, matrizes de confusão.

Insights sobre quais features influenciam mais na classificação.


Licença
Disponível sob a licença MIT. Consulte LICENSE para mais detalhes.

Autor: Sérgio Oliveira
Ano: 2025
