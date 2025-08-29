# Cadastro de Funcionários - Aplicativo em Python

Este aplicativo permite o cadastro, visualização, edição e exclusão de funcionários. Ele foi desenvolvido em Python, utilizando as bibliotecas `sqlite3`, `streamlit`, `pandas`, e `database` para facilitar o armazenamento e gerenciamento dos dados.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **Streamlit**: Framework para construção de aplicativos web interativos.
- **SQLite3**: Banco de dados relacional leve para armazenamento dos dados dos funcionários.
- **Pandas**: Biblioteca para manipulação e análise de dados.

## Funcionalidades

- **Cadastro de Funcionários**: Permite adicionar novos funcionários com informações como nome, cargo, e salário.
- **Exibição de Funcionários**: Visualização de todos os funcionários cadastrados em uma tabela.
- **Edição de Dados**: Editar informações de funcionários existentes.
- **Exclusão de Funcionários**: Remover funcionários do banco de dados.
- **Armazenamento no Banco de Dados**: Utiliza o SQLite3 para persistir os dados.

## Como Usar

### Pré-requisitos

Certifique-se de ter o Python instalado. Você também precisará instalar as dependências do projeto. Para isso, execute o seguinte comando:

```bash
pip install -r requirements.txt

O arquivo requirements.txt deve conter as seguintes dependências:

streamlit
sqlite3
pandas

Executando o Aplicativo

Para rodar o aplicativo, execute o comando abaixo no terminal:

streamlit run app.py

Isso abrirá o aplicativo em seu navegador, onde você poderá interagir com o sistema de cadastro de funcionários.

Estrutura de Dados

O aplicativo armazena os dados dos funcionários em um banco de dados SQLite. A tabela funcionarios tem a seguinte estrutura:

Coluna	Tipo de Dados	Descrição

id	INTEGER	Chave primária, auto incremento
nome	TEXT	Nome do funcionário
cargo	TEXT	Cargo do funcionário
salario	REAL	Salário do funcionário


Exemplo de Uso

1. Ao acessar o aplicativo, você verá uma interface onde poderá cadastrar um novo funcionário.


2. Preencha os campos com o nome, cargo e salário do funcionário e clique em "Cadastrar".


3. A lista de funcionários será exibida abaixo, com a opção de editar ou excluir qualquer entrada.



Contribuição

Sinta-se à vontade para contribuir para o projeto. Para isso, basta fazer um fork deste repositório, criar uma branch, fazer suas modificações e enviar um pull request.
