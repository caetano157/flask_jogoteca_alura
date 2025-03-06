Flask Web App - Portfólio

Este repositório foi realizado durante um estudo para aprender/aprimorar minhas habilidades em flask, desenvolvimento backend, integração com bancos de dados e criação de APIs.

Tecnologias Utilizadas

Python (Flask, SQLAlchemy)
Banco de Dados (MySQL)
HTML, CSS, Bootstrap (Interface do Usuário)
JavaScript

Funcionalidades
Sistema de Autenticação (Login/Logout, Registro de Usuários)
CRUD de Dados (Criação, Leitura, Atualização e Exclusão de registros)
Integração com APIs
Interface Responsiva (Compatível com dispositivos móveis)

Como Rodar o Projeto
Clone este repositório:
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio

Crie e ative um ambiente virtual:

python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate  # Windows

Instale as dependências:

pip install -r requirements.txt

Configure as variáveis de ambiente:

export FLASK_APP=app.py
export FLASK_ENV=development

Ou no Windows (PowerShell):

$env:FLASK_APP="app.py"
$env:FLASK_ENV="development"

Execute a aplicação:

flask run

Acesse no navegador: http://127.0.0.1:5000


