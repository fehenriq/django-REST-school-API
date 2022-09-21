# Formulário com Django

Django REST API de clientes  
Deploy no Heroku

## 🔨 Funcionalidades do projeto

Registrar alunos [nome, rg, cpf, data_nascimento, foto]  
Registrar cursos [codigo__curso, descricao, nivel]  
Registrar matrículas [periodo, aluno, curso]  
Relacionamentos [matriculas pega um aluno [alunos] e faz a matricula em um curso[cursos] em um período]  
Validação dos campos cadastrados  

## ✔️ Técnicas e tecnologias utilizadas

- `Python`
- `Django`
- `Django REST Framework`

## 🛠️ Abrir e rodar o projeto

Para abrir e rodar o projeto, execute os comandos:
- python -m venv venv
- venv/scripts/activate
- pip install -r requirements.txt
- py seed.py
- py manage.py makemigrations
- py manage.py migrate
- py manage.py createsuperuser
- py manage.py runserver
