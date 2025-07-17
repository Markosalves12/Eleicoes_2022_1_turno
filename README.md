# 🗳️ Análise das Eleições 2022 - 1º Turno

Projeto de **análise de dados eleitorais das Eleições 2022 (1º turno)** usando **Python + Jupyter Notebook**, com **coleta direta dos dados do site do TSE**.

> 🔗 Repositório: [github.com/Markosalves12/Eleicoes_2022_1_turno](https://github.com/Markosalves12/Eleicoes_2022_1_turno.git)

---

## 📌 Objetivo

Extrair, tratar e analisar dados do Tribunal Superior Eleitoral (TSE) referentes ao **1º turno das eleições de 2022**, utilizando ferramentas de análise de dados para gerar insights e visualizações.

---

## 🧰 Tecnologias Utilizadas

- **Python 3.10+**
- **Jupyter Notebook**
- **Pandas** – Manipulação de dados tabulares
- **Matplotlib / Seaborn / Plotly** – Visualização de dados
- **Requests / BeautifulSoup** – Coleta de dados do site do TSE
- **TQDM** – Barra de progresso durante downloads

---


## 📥 Fonte dos Dados

Os dados são coletados diretamente do site oficial do TSE:

📎 [https://www.tse.jus.br/eleicoes/estatisticas/repositorio-de-dados-eleitorais](https://www.tse.jus.br/eleicoes/estatisticas/)

A coleta é feita por meio de **requisições HTTP e parsing HTML/JSON**, ou utilizando os arquivos `.zip` de resultados das urnas por seção eleitoral.

---

## 📊 Análises Realizadas

- Votação por cargo (presidente, governador, deputado, etc.)
- Distribuição de votos por estado e município
- Análise de abstenções, votos nulos e brancos
- Ranking dos candidatos mais votados por UF
- Mapas e gráficos interativos com Plotly

---

## 🚀 Como executar localmente

### 1. Clone o repositório

```bash
git clone https://github.com/Markosalves12/Eleicoes_2022_1_turno.git
cd Eleicoes_2022_1_turno
