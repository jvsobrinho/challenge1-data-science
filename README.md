# Challenge Alura - Data Science 1

Este repositório contém a solução para o desafio de Data Science da Alura, no qual analisamos dados de vendas, desempenho e avaliações de clientes de quatro lojas fictícias da Alura Store para determinar qual delas deve ser vendida pelo Senhor João.

---

## Descrição

O objetivo deste projeto é auxiliar na decisão estratégica de venda de uma das quatro lojas da rede, por meio de análises de faturamento total, categorias de produtos, avaliações de clientes, produtos extremos (mais e menos vendidos) e frete médio.

A solução inclui carregamento e manipulação de dados com **Pandas**, visualizações com **Matplotlib** e interpretação dos resultados para embasar a recomendação final.

---

## Estrutura do Repositório

- `AluraStoreBr.ipynb` – Notebook com toda a análise, gráficos e relatório final.  
- `base-de-dados-challenge-1/` – Pasta contendo os CSVs das quatro lojas.  
- `README.md` – Este arquivo, explicando propósito, instalação e uso.

---

## Pré-requisitos

- Python 3.8 ou superior.  
- Bibliotecas: `pandas`, `matplotlib`, `uv`, `typing`.

---

## Instalação

Este projeto utiliza o **`uv`** para gerenciar as dependências de ambiente.

1. Clone o repositório:

   ```bash
   git clone https://github.com/jvsobrinho/challenge1-data-science.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd challenge1-data-science
   ```

3. (Opcional) Crie e ative um ambiente virtual com **`uv`**:

   ```bash
   uv venv
   uv activate
   ```

4. Instale as dependências necessárias:

   ```bash
   uv install
   ```

5. Após a instalação, você estará pronto para rodar o notebook.

---

## Uso

1. Abra o notebook (`AluraStoreBr.ipynb`) em um ambiente Jupyter ou Google Colab.
2. Execute todas as células em ordem, começando pelo carregamento dos dados.
3. Visualize os gráficos gerados e leia o relatório final, que recomenda a loja a ser vendida com base nos critérios analisados.

---

## Resultados

O notebook inclui:

- Gráfico de faturamento total por loja.
- Barras de vendas por categoria em cada loja.
- Gráficos de pizza para produtos extremos.
- Linhas de faturamento mensal.
- Relatório em Markdown indicando qual loja deve ser vendida.

---

## Contato

Desenvolvido por Joel V. Sobrinho – [GitHub](https://github.com/jvsobrinho)
