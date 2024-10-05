<div align="center">
<h1>Blog em Django</h1>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white">
<img src="https://img.shields.io/badge/SQLite-07405E?style=flat&logo=sqlite&logoColor=white">
</div>

## 📘 Sobre

Blog desenvolvido usando Django com listagem de posts e páginas para publicação e edição dos posts.

## 💻️ Tecnologias

- Python 3.11
- Django 5.1
- SQLite 2.8

## ✅ Funcionalidades

- Listagem das postagens
- Criação das postagens
- Edição das postagens

## ⚙️ Instalação e Execução

Clone o repositório e navegue para a pasta do projeto:

```bash
git clone https://github.com/elainefs/django-blog-girls.git
cd django-blog-girls
```

Crie e ative um ambiente virtual:

```bash
python3 -m venv .venv # Para Windows use: python -m venv .venv
source .venv/bin/activate  # Para Windows use: .venv\Scripts\activate
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

Execute os seguintes comandos para a criação do banco de dados:

```bash
python3 manage.py makemigrations
python3 manage.py migrate
```

Crie um super usuário:

```bash
python3 manage.py createsuperuser
```

Execute o servidor:

```bash
python3 manage.py runserver
```

Acesse o blog em:

```
http://localhost:8000/
```

Crie novas publicações em:

```
http://localhost:8000/post/new/
```

Você também pode gerenciar o blog pela interface do Django Admin acessando:

```
http://localhost:8000/admin/
```

## 📄 Licença

Este projeto está sobre a licença MIT. Veja o arquivo [LICENSE](/LICENSE) para mais informações.

<hr>

Made with <3 by [Elaine Ferreira](https://github.com/elainefs)