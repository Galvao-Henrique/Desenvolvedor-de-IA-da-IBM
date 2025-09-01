# Glossário: Trabalhando com Dados em Python

| Termo | Definição | Exemplo |
|---|---|---|
| **.csv file** | Arquivo de texto simples para dados tabulares onde cada linha representa uma linha e vírgulas separam valores. | `dados.csv` com: `nome,idade,cidade`<br>`João,30,São Paulo` |
| **.txt file** | Formato de arquivo comum com texto simples sem formatação específica. | `arquivo.txt` com texto simples |
| **Append** | Adicionar algo ao final de objeto existente (dados a arquivo ou elementos a lista). | `lista.append(10)`<br>`arquivo.write("novo texto")` |
| **Attribute** | Propriedade ou característica associada a um objeto, acessada com notação de ponto. | `df.shape`, `array.ndim` |
| **Broadcasting (NumPy)** | Permite combinar arrays com shapes diferentes em operações element-wise estendendo arrays menores. | `array1 + array2` (com shapes diferentes) |
| **Component** | Elemento ou valor específico dentro de array multidimensional, acessado por indexação. | `array[0, 1]` (componente na linha 0, coluna 1) |
| **Computation** | Realizar operações numéricas em arrays e matrizes para computação matemática e científica. | `np.sum(array)`, `np.dot(matrix1, matrix2)` |
| **Data analysis** | Processo de inspecionar, limpar, transformar e interpretar dados para descobrir informações úteis. | Análise exploratória de dados |
| **DataFrames** | Estrutura de dados tabular bidimensional do Pandas para armazenar e analisar dados. | `df = pd.DataFrame(data)` |
| **Dependencies** | Bibliotecas externas que o Pandas utiliza para funcionalidades básicas (ex: NumPy). | `import numpy as np` (dependência) |
| **File attribute** | Propriedades ou metadados associados a arquivos, gerenciados no nível do sistema operacional. | Tamanho, data de criação, permissões |
| **File object** | Objeto que representa arquivo aberto, permitindo leitura ou escrita. | `file = open("arquivo.txt", "r")` |
| **Grid** | Estrutura bidimensional de linhas e colunas para representar dados tabulares. | Matriz, tabela de dados |
| **Hadamard Product** | Operação de multiplicação element-wise de duas matrizes/arrays do mesmo shape. | `array1 * array2` (multiplicação elemento a elemento) |
| **Importing pandas** | Importar biblioteca Pandas com alias "pd". | `import pandas as pd` |
| **Index** | Posição ou identificador para acessar elementos dentro de sequência ou estrutura de dados. | `lista[0]`, `df.index` |
| **Libraries** | Coleções de código pré-escrito com funções e classes reutilizáveis. | `pandas`, `numpy`, `matplotlib` |
| **Linspace** | Função NumPy que gera array de valores igualmente espaçados em intervalo especificado. | `np.linspace(0, 10, 5)` → `[0, 2.5, 5, 7.5, 10]` |
| **NumPy** | Biblioteca fundamental para computação numérica com suporte a arrays multidimensionais. | `import numpy as np` |
| **One dimensional NumPy** | Array linear que armazena elementos em sequência única. | `np.array([1, 2, 3, 4, 5])` |
| **Open function** | Função para acessar e manipular arquivos (leitura/escrita). | `open("arquivo.txt", "r")` |
| **Pandas** | Biblioteca popular para manipulação e análise de dados com estruturas para dados estruturados. | `pd.DataFrame`, `pd.Series` |
| **Pandas library** | Módulos e funções dentro da biblioteca Pandas para estruturas de dados e análise. | `pandas.read_csv()`, `pandas.DataFrame()` |
| **Plotting Mathematical Functions** | Usar bibliotecas como Matplotlib para criar representações gráficas de equações matemáticas. | `import matplotlib.pyplot as plt`<br>`plt.plot(x, y)` |
| **Shape** | Dimensões de um array (número de linhas e colunas). | `array.shape` → `(3, 4)` (3 linhas, 4 colunas) |
| **Slicing** | Extrair porções específicas de array especificando range de índices. | `array[1:4, 2:5]` |
| **Two dimensional NumPy** | Array estruturado com linhas e colunas, resembling matriz ou tabela. | `np.array([[1,2],[3,4]])` |
| **Universal Functions (ufuncs)** | Funções que operam elemento a elemento em arrays para operações matemáticas e lógicas. | `np.sin(array)`, `np.sqrt(array)` |
| **Vector addition** | Adicionar elementos correspondentes de dois ou mais vetores. | `vector1 + vector2` |
| **Visualizations** | Criação de representações gráficas (gráficos, plots) para ilustrar dados e tendências. | `plt.bar()`, `plt.scatter()`, `plt.hist()` |