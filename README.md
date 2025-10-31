<p align='center'><img src="media/logo.png" alt="logo" width="600"/></p>
<h1 align='center'>FreelaWay</h1>
<p align='center'>Plataforma de busca e contratação de mão de obra freelancer/ informal, desenvolvida durante a terceira edição do evento PyStack Week, conduzido pelo professor Caio Sampaio.</p>

<div align='center'>
  <img alt="Django" src="https://img.shields.io/badge/Django-092E20.svg?&logo=django&logoColor=green">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-07405E?style=flat&compact=true&logo=sqlite&logoColor=white">
  <img alt="Creative Commons License" src="https://img.shields.io/badge/License-Creative%20Commons-red">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/amanmdest/psw3_Freelaway?color=purple">
</div>

## Interface da Aplicação
<kbd>
  <img src="media/cadastro.png" alt="cadastro" width="400"/>
</kbd>
<kbd>
  <img src="media/login.png" alt="login" width="400"/>
</kbd>  
<kbd>
  <img src="media/jobs.png" alt="jobs" width="400"/>  
</kbd>

## Rode localmente
1. Clone o repositório:
```
  git clone https://github.com/amanmdest/psw3_Freelaway.git
```
2. Crie e ative um *virtualenv*(Linux):
```
  python -m venv venv
  source venv/bin/activate
```
3. Instale as dependências:
```
  pip install -r requirements.txt
```
4. Migrações Banco de Dados:
```
  python manage.py makemigrations
  python manage.py migrate
```
5. Para poder usar o painel do admin é preciso criar um superuser:
```
  python manage.py createsuperuser
```
6. Rode o projeto localmente:
```
  python manage.py runserver
```
e acesse: http://127.0.0.1:8000/
