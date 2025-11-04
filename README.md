# tfidf-article-similarity
# 🔍 Busca de Artigos com TF-IDF e Similaridade do Cosseno

## 📘 Sobre o Projeto
Este projeto tem como objetivo realizar buscas em um conjunto de artigos científicos a partir de uma **consulta (query)** fornecida pelo usuário.  
A busca é feita com base em **modelos de representação vetorial TF-IDF (Term Frequency – Inverse Document Frequency)** e **similaridade do cosseno**, permitindo identificar os artigos mais semanticamente próximos da consulta.  

O sistema também gera uma **visualização 3D interativa** dos vetores da consulta e dos artigos mais relevantes, facilitando a compreensão da relação espacial entre eles.

---

## ⚙️ Tecnologias Utilizadas
- **Python**
- **Google Colab**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib**
- **Plotly**
- **Nltk**
- **Re**

---

## 🧠 Funcionalidades
- Representação vetorial dos textos utilizando **TF-IDF**.  
- Cálculo da **similaridade do cosseno** entre a consulta e os documentos.  
- Exibição dos **artigos mais relevantes** para cada busca.  
- **Visualização 3D interativa** dos vetores da consulta e dos documentos.  
- **Interface por terminal** que permite ao usuário realizar consultas em tempo real.

---

## 📊 Estrutura do Projeto
- 📂 TFIDF-ArticleSearch
- ├── 📜 README.md                # Documentação do projeto
- ├── 📓 TFIDF_ArticleSearch.ipynb # Notebook principal (Google Colab)
- ├── 📁 data/                    # Datasets com artigos científicos
- │   └── train.csv     
- │   └── train.csv    
- ├── 📄 relatorio.pdf             # Relatório acadêmico formatado segundo ABNT
- ├── 🧩 relatorio.tex             # Arquivo LaTeX do relatório

---

## 🚀 Como Executar
1. **Abra o Google Colab** ou qualquer ambiente Jupyter.  
2. **Carregue os arquivos** do projeto (.ipynb e .csv).  
3. Execute as células do notebook na ordem em que aparecem.  
4. Ao final, digite suas consultas no terminal (no Colab, utilize `input()`), por exemplo:
   ```python
   regularization lasso linear regression
   ````
5. Para encerrar o programa, digite:
  ```python
   sair
  ````
---

## 📄 Relatório

O relatório completo do projeto está incluído no arquivo relatorio.pdf
, elaborado conforme as normas da ABNT.
Ele descreve detalhadamente os fundamentos teóricos, a implementação, os resultados obtidos e as considerações finais.

---

## 🧑‍💻 Autor

- João Pedro Dias
- Estudante de Ciência de Dados — FATEC Rubens Lara (Santos/SP)
- 📧 joaopedrodias.profissional@gmail.com 
- 💼 https://www.linkedin.com/in/joaox07