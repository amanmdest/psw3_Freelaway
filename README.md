<h1 align='center'>Freelaway - Aplicação de Trabalhos Freelancer</h1>

<h2 align='center'>Plataforma full-stack desenvolvida na 10º PyStack Week conduzida pelo professor Caio Sampaio.</h2>

## Rode localmente
1. Clone o repositório:
```bash
  git clone https://github.com/amanmdest/DjangoPollsTutorialDIO.git
```
2. Instale dependências(recomenda-se ter um ambiente virtual para as instalações, neste projeto utilizei o Pyenv):
```bash
  pip install -r requirements.txt
```
4. Migrações Banco de Dados:
```bash
  python manage.py makemigrations
  python manage.py migrate
```
5. Para poder usar o painel do admin é preciso criar um superuser:
```bash
  python manage.py createsuperuser
```
6. Rode o projeto localmente:
```bash
  python manage.py runserver
```
e acesse: http://127.0.0.1:8000/

## 📷 Imagens
<kbd>
  <img src="media/login.png" alt="login" width="600" />
</kbd>
<kbd>
  <img src="media/cadastro.png" alt="cadastro" width="600" />
</kbd>
<kbd>
  <img src="media/jobs.png" alt="jobs" width="600" />
</kbd>  
