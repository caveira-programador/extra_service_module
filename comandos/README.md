Iniciar o projeto Django

python -m venv venv
venv\Scripts\activate
pip install django
pip install django-crispy-forms
pip install pillow
pip install pylint
django-admin startproject extra_module .

python manage.py startapp servico 
python manage.py startapp solicitacao 
python manage.py startapp perfil       


python manage.py runserver
python manage.py migrate 
python manage.py createsuperuser


Configurar o git

git config --global user.name 'Seu nome'
git config --global user.email 'seu_email@gmail.com'
git config --global init.defaultBranch main
# Configure o .gitignore
git init
git add .
git commit -m 'Mensagem'
git remote add origin URL_DO_GIT
git push origin main -u