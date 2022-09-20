# Dados Escolares

Projeto realizado no Curso de Pandas: formatos diferentes de entrada e saída (IO) (prof. Guilherme Lima - Alura).

O objetivo do projeto foi aprender a trabalhar com vários tipos e fontes de dados, como JSON, DataFrames, arquivos CSV, páginas HTML e também a usar o SQLite através da biblioteca Pandas.

- O primeiro passo foi ler os nomes dos alunos de um arquivo JSON e transformar a tabela de nomes em um DataFrame. Criamos também IDs para os alunos usando a biblioteca Numpy e e-mail para cada um deles.
- Em seguida, lemos uma página HTML com nomes de diversos cursos que uma escola oferece. Também transformamos os dados em DataFrame e criamos seus IDs.
- Definimos um número aleatório de cursos em que cada aluno estaria matriculado nessa escola.
- Para vincular de fato os alunos em seus respectivos cursos, fizemos uma junção dos IDs dos alunos com os IDs dos cursos.
- Para exibir o resultado foram usados diferentes formatos: arquivo CSV, JSON e HTML.
- Com a biblioteca SQLAlchemy, foi possível criar um banco de dados SQLite para armazenar as matrículas e definir os alunos da próxima turma.
- Por fim, os dados do SQLite referentes aos alunos da próxima turma foram exportados para um arquivo Excel.
