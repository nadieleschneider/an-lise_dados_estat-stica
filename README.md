# Análise Exploratória de Dados - PNAD 2015

Este repositório contém os códigos e os estudos práticos desenvolvidos no âmbito da **Análise Exploratória de Dados e Estatística Descritiva**, utilizando o clássico dataset da **Pesquisa Nacional por Amostra de Domicílios (PNAD) de 2015** do IBGE.

---

## 📌 Visão Geral do Projeto

O objetivo deste projeto é aplicar técnicas de tratamento, manipulação e visualização de dados em Python para extrair insights socioeconómicos relevantes da população brasileira investigada na PNAD 2015. 

O fluxo abrange desde a preparação inicial do ambiente, tratamento de tipos de variáveis, cálculo de distribuições de frequência absolutas e percentuais, até a representação gráfica de indicadores de renda e escolaridade.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **Linguagem:** Python
* **Ambiente de Desenvolvimento:** Google Colab / Jupyter Notebook
* **Bibliotecas Principais:**
  * `Pandas`: Manipulação, limpeza e sumarização de DataFrames.
  * `NumPy`: Suporte a computação numérica e ajuste de compatibilidade de exibição (`np.set_printoptions`).
  * `Matplotlib`: Construção de gráficos estatísticos (barras, linhas, distribuições).

---

## 📊 Estrutura e Etapas da Análise

1. **Configuração do Ambiente e Leitura dos Dados:**
   * Montagem do Google Drive e importação do conjunto de dados (`dados.csv`).
   * Configuração de opções do Pandas e NumPy para melhor legibilidade dos resultados.

2. **Classificação e Tipologia das Variáveis:**
   * **Qualitativas Ordinais:** Ex.: *Anos de Estudo*.
   * **Qualitativas Nominais:** Ex.: *Sexo*, *Cor*.
   * **Quantitativas Discretas:** Ex.: *Idade*.
   * **Quantitativas Contínuas:** Ex.: *Altura*.

3. **Distribuição de Frequências:**
   * Geração de tabelas de frequência absoluta e percentual com o método `value_counts(normalize=True)`.
   * Personalização e formatação visual avançada utilizando o Pandas Styler para o padrão brasileiro de formatação numérica.

4. **Visualização Gráfica de Dados:**
   * Gráficos de barras para análise da distribuição dos anos de estudo com marcação da média.
   * Gráficos de linha cruzando a renda média em função dos anos de estudo.

---

## 🚀 Como Executar o Projeto

1. Certifique-se de ter o Python instalado ou abra os blocos de notas diretamente no **Google Colab**.
2. Faça o download ou o upload do ficheiro de dados (`dados.csv`) para o seu diretório de trabalho.
3. Execute as células sequencialmente para reproduzir as tabelas de frequência e os gráficos gerados.

---
*Projeto desenvolvido como parte do percurso de capacitação em Análise de Dados e Ciência de Dados.*
