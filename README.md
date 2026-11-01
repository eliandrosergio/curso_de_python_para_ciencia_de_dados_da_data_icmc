# Curso de Python para Ciência de Dados — Data ICMC

Repositório de estudos e anotações do **Curso Online de Python para Ciência de Dados** oferecido pela [Data ICMC](https://data.icmc.usp.br/). Reúne notebooks com conteúdo teórico, exercícios resolvidos e conjuntos de dados de apoio, organizados por aula.

## Sobre o projeto

O objetivo deste repositório é documentar a trajetória de aprendizado ao longo do curso, consolidando os principais conceitos de manipulação e análise de dados com as bibliotecas fundamentais do ecossistema Python: **NumPy** e **Pandas**.

O material está dividido entre os notebooks disponibilizados pelo curso (`curso/`) e as anotações e resoluções pessoais (`my/`).

## Conteúdo por aula

### Aula 3 — NumPy
- Informações básicas de arrays
- Computação vetorizada (aritmética e comparações)
- Indexação e fatiamento (*slicing*)
- Estatística com NumPy
- Funções universais (*ufuncs*)
- Álgebra linear
- Exercícios práticos (1 a 7)

📓 [`my/aula_3_numpy/numpy.ipynb`](my/aula_3_numpy/numpy.ipynb)

### Aula 4 — Pandas
- Introdução ao Pandas: `Series` e `DataFrame`
- Criação de DataFrames a partir de estruturas Python
- Leitura e escrita de arquivos (CSV, Excel, ODS etc.)
- Atributos e métodos gerais
- Acesso, leitura e modificação de linhas e colunas
- Filtragem de DataFrames
- Métodos estatísticos, aritméticos e gerais
- `merge` / `join` e `groupby`
- Manipulação de elementos, renomeação de colunas e índices

📓 [`my/aula_4_pandas/pandas.ipynb`](my/aula_4_pandas/pandas.ipynb)

### Exercícios — Aula 4
- Atividades propostas durante a aula de Pandas

📓 [`curso/aula_4_pandas/Aula_4_Exercicios.ipynb`](curso/aula_4_pandas/Aula_4_Exercicios.ipynb)

## Estrutura do repositório

```
.
├── curso/
│   └── aula_4_pandas/
│       ├── Aula_4_Exercicios.ipynb
│       ├── jamesbond.csv
│       └── sample_data.zip
├── my/
│   ├── aula_3_numpy/
│   │   └── numpy.ipynb
│   └── aula_4_pandas/
│       ├── pandas.ipynb
│       └── data/
│           └── my/
│               ├── carros.csv
│               ├── comentarios.csv
│               ├── notas.csv
│               ├── paises.csv
│               └── minhas_planilhas_001.ods
├── LICENSE
└── README.md
```

## Pré-requisitos

- Python 3.10 ou superior
- [Jupyter Notebook](https://jupyter.org/) ou [JupyterLab](https://jupyterlab.readthedocs.io/)
- Bibliotecas utilizadas durante o curso

## Instalação

```bash
# Clone o repositório
git clone https://github.com/<seu-usuario>/curso_de_python_para_ciencia_de_dados_da_data_icmc.git
cd curso_de_python_para_ciencia_de_dados_da_data_icmc

# (Opcional) Crie e ative um ambiente virtual
python -m venv .venv
source .venv/bin/activate  # Linux/macOS
# .venv\Scripts\activate   # Windows

# Instale as dependências
pip install jupyter numpy pandas openpyxl odfpy
```

## Como executar

Inicie o Jupyter a partir da raiz do repositório e abra o notebook desejado:

```bash
jupyter notebook
# ou
jupyter lab
```

> **Observação:** o arquivo `curso/aula_4_pandas/sample_data.zip` contém os conjuntos de dados de apoio do curso (California Housing, MNIST e Anscombe). Extraia-o antes de executar os notebooks que o referenciam.

## Dados de apoio

Os arquivos em `my/aula_4_pandas/data/my/` são conjuntos de dados criados para fins de estudo e exercícios de leitura, filtragem e manipulação de DataFrames.

## Licença

Distribuído sob a licença **MIT**. Consulte o arquivo [LICENSE](LICENSE) para mais informações.

## Autor

**Eliandro Sérgio**

---

Material de uso educacional, baseado no curso da Data ICMC.
