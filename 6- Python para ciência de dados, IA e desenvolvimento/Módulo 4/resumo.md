# Cheat Sheet: Trabalhando com Dados em Python

## Leitura e Escrita de Arquivos

| Método | Descrição | Sintaxe e Exemplo |
|---|---|---|
| **Modos de Abertura** | Diferentes modos para abrir arquivos para operações específicas. | `r` (leitura), `w` (escrita), `a` (append), `+` (atualização), `b` (binário)<br>`with open("data.txt", "r") as file:`<br>`    content = file.read()` |
| **Métodos de Leitura** | Diferentes métodos para ler conteúdo de arquivo. | `file.readlines()` (todas linhas como lista)<br>`file.readline()` (próxima linha como string)<br>`file.read()` (conteúdo completo como string) |
| **Métodos de Escrita** | Métodos para escrever conteúdo em arquivo. | `file.write(content)` (escreve string)<br>`file.writelines(lines)` (escreve lista de strings)<br>`lines = ["Hello\n", "World\n"]`<br>`file.writelines(lines)` |
| **Iterar sobre Linhas** | Itera através de cada linha do arquivo usando loop. | `for line in file:`<br>`    print(line)` |
| **Open/Close Manual** | Abre e fecha arquivo manualmente. | `file = open("data.txt", "r")`<br>`content = file.read()`<br>`file.close()` |
| **Context Manager** | Gerencia abertura/fechamento automaticamente. | `with open("data.txt", "r") as file:`<br>`    content = file.read()` |

## Pandas - Leitura de Dados

| Método | Descrição | Sintaxe e Exemplo |
|---|---|---|
| **read_excel()** | Lê arquivo Excel para DataFrame. | `df = pd.read_excel("data.xlsx")` |
| **to_csv()** | Escreve DataFrame para arquivo CSV. | `df.to_csv("output.csv", index=False)` |
| **Acessar Colunas** | Acessa colunas específicas no DataFrame. | `df["age"]` (coluna única)<br>`df[["name","age"]]` (múltiplas colunas) |
| **describe()** | Gera estatísticas resumidas de colunas numéricas. | `df.describe()` |

## Pandas - Manipulação de Dados

| Método | Descrição | Sintaxe e Exemplo |
|---|---|---|
| **drop()** | Remove linhas ou colunas especificadas. | `df.drop(['age','salary'], axis=1, inplace=True)` (colunas)<br>`df.drop(index=[5,10], axis=0, inplace=True)` (linhas) |
| **dropna()** | Remove linhas com valores NaN. | `df.dropna(axis=0, inplace=True)` |
| **duplicated()** | Identifica valores duplicados no dataset. | `duplicate_rows = df[df.duplicated()]` |
| **Filter Rows** | Cria novo DataFrame com linhas que atendem condições. | `filtered_df = df[(df["age"] > 30) & (df["salary"] < 50000)]` |
| **groupby()** | Divide DataFrame em grupos baseado em critérios. | `grouped = df.groupby(['category','region']).agg({'sales': 'sum'})` |
| **head()** | Mostra primeiras n linhas do DataFrame. | `df.head(5)` |
| **Import pandas** | Importa biblioteca Pandas com alias. | `import pandas as pd` |
| **info()** | Fornece informações sobre o DataFrame. | `df.info()` |
| **merge()** | Mescla dois DataFrames baseado em colunas comuns. | `merged_df = pd.merge(df1, df2, on=["col1", "col2"])` |
| **Print DataFrame** | Mostra conteúdo do DataFrame. | `print(df)` ou `df` |
| **replace()** | Substitui valores específicos em coluna. | `df["status"].replace("In Progress", "Active", inplace=True)` |
| **tail()** | Mostra últimas n linhas do DataFrame. | `df.tail(5)` |

## NumPy

| Método | Descrição | Sintaxe e Exemplo |
|---|---|---|
| **Import NumPy** | Importa biblioteca NumPy. | `import numpy as np` |
| **np.array()** | Cria array uni ou multidimensional. | `array_1d = np.array([1, 2, 3])`<br>`array_2d = np.array([[1,2],[3,4]])` |
| **Atributos Array** | Operações matemáticas em arrays. | `np.mean(array)` (média)<br>`np.sum(array)` (soma)<br>`np.min(array)` (mínimo)<br>`np.max(array)` (máximo)<br>`np.dot(array1, array2)` (produto escalar) |