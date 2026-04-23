# Curso: Pré-processamento de Dados

Repositório com os códigos utilizados nas aulas de pré-processamento de dados para a cadeira de **Ciência de Dados** da **UNIFOR**.

---

## Tecnologias Utilizadas

- Python 3.x
- Pandas, NumPy
- Jupyter Notebook

---

## Como Usar

**1. Clone o repositório**

```bash
git clone https://github.com/MauricioCE/aula_pre_processamento_de_dados
cd aula_pre_processamento_de_dados
```

**2. Instale Jupyter para VS Code**

[Baixar extensão](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) ou instale direto do VS Code pela aba de extensões

**3. Criar ambiente virtual IMPORTANTE !!!**

Antes de instalar bibliotecas, é recomendo a criação e utilização de um ambiente virutal

**4. Abra o notebook**

Abra os notebooks localizado e siga as instruções nas células

---

## Os Problemas Abordados

**1. Delimitador não padrão**

Ocorre quando o arquivo CSV usa um separador diferente do que o Python espera por padrão (a vírgula `,`). Isso faz com que todos os dados fiquem agrupados em uma única coluna.

---

**2. Valores ausentes**

Alguns datasets podem ter campos sem preenchimento (ex: `vazio`) ou que foram preenchidos com a representação de um valor faltante, como `'NaN'`, `'null'`. Esses valores podem causar um equívoco dos dados processados ou, até mesmo, um erro de execução.

---

**3. Espaços em branco invisíveis**

Espaços extras no início ou no fim do texto (ex: `" Brasil "`). Passam despercebidos visualmente mas causam erros em comparações e agrupamentos.

---

**4. Conversão de tipos de dados**

Às vezes, os dados estão em um formato inadequado para análise, como um valor numérico salvo como texto (string)

---

**5. Mistura de tipos na mesma coluna**

Falta de padronização dos dados. Exemplo: uma coluna com `"Sim"` e `1`, ou `"Não"` e `0`, representando a mesma informação.

---

**6. Duplicatas**

Linhas repetidas que inflam resultados e podem causar vazamento de dados (*data leakage*) entre as etapas de treino e teste.

---

**7. Dados agrupados em uma coluna**

Uma única coluna carrega várias informações (ex: `"Fortaleza - CE"`). Isso dificulta filtros e agrupamentos específicos.

---

**8. Datas em formatos diferentes**

Mistura de padrões (ex: `10/05/2023` e `2023-05-10`). Impede ordenação cronológica e cálculos de intervalo.

---

**9. Inconsistência de representação**

Variações na escrita do mesmo valor (ex: `"Sao Paulo"`, `"são paulo"`, `"SP"`). O sistema os trata como categorias distintas.

---

**10. Outliers (valores atípicos)**

Valores impossíveis ou extremos (ex: `idade = 999`, `salário = -3500`). Distorcem médias, desvios e o comportamento de modelos preditivos.

---

**11. Unidades de medida inconsistentes**

Mistura de unidades na mesma coluna (ex: metros e centímetros, quilos e gramas). Torna os dados incomparáveis entre si.


