# 🏋️‍♂️ Análise de Base de Dados de Powerlifting

Este projeto realiza uma análise exploratória da base de dados pública de **competições de Powerlifting**, explorando estatísticas de atletas, categorias de peso e desempenho em diferentes provas.

O objetivo é demonstrar habilidades em **análise** e **ciência de dados com Python**, incluindo manipulação de dados com `pandas` e visualização com bibliotecas populares. Além disso, é um objetivo também, juntar dois temas que gosto em um único lugar Powerlifting e Python =).

---

## 📂 Estrutura do Projeto

* `powerlifting_analisys.ipynb` → notebook principal com as análises.
* `.gitignore` → arquivos e pastas ignorados no versionamento.

---

## 🛠️ Tecnologias Utilizadas

* **Python 3.13.5**
* **Pandas** para manipulação de dados
* **Matplotlib / Seaborn / Plotly**
* **Jupyter Notebook (VS Code)**

---

## 📊 Dataset

O dataset utilizado é o **[OpenPowerlifting](https://www.openpowerlifting.org/)**, que contém registros públicos de competições de powerlifting ao redor do mundo.

> ⚠️ O dataset completo é muito grande (centenas de MB) e **não está incluído neste repositório**.
> Para reproduzir as análises, baixe o arquivo `openpowerlifting.csv` diretamente do site oficial ou de repositórios alternativos.

---

## ▶️ Como Executar o Projeto

1. Clone este repositório:

   ```bash
   git clone https://github.com/joas-ds/analise-powerlifting-db.git
   cd analise-powerlifting-db
   ```

2. Crie e ative um ambiente virtual (exemplo com venv):

   ```bash
   python -m venv .venv
   source .venv/bin/activate   # Linux/Mac
   .venv\Scripts\activate      # Windows
   ```

   Ou use **Conda**:

   ```bash
   conda create -n powerlifting python=3.13
   conda activate powerlifting
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Abra o notebook no VS Code ou Jupyter:

   ```bash
   code powerlifting_analisys.ipynb
   ```

---

## 📌 Exemplos de Análises

* Distribuição de atletas por sexo, idade e categoria de peso.
* Relação entre **peso corporal** e **carga levantada** (squat, bench press, deadlift).
* Comparação de federações e países.
* Evolução temporal das competições.

---

## 📈 Próximos Passos

* Criar visualizações interativas.
* Explorar predições de performance com modelos simples de Machine Learning.
* Publicar insights em um artigo no LinkedIn.

---

## ✨ Autor

**João (joas-ds)**

* 💼 [LinkedIn](https://www.linkedin.com/in/jo%C3%A3o-victor-caetano-narducci/)
* 🐙 [GitHub](https://github.com/joas-ds)
