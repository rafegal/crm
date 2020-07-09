# CRM

Projeto criado para a plataforma de ensino open education [Digital Innovation One](https://digitalinnovation.one/)

O projeto trata-se da elaboração de um CRUD de Cliente utilizando Python, Django e Bootstrap com autenticação.
É abordado tópicos importante do Django como models, forms e class-based views.
No lab também é demonstrado como hospedar a aplicação no Heroku de forma gratuita e simples.
A aplicação hospedada no Heroku tem um processo de deploy automatizado após algumas configurações e também é utilizado banco de dados PostgreSQL para persistências das informaçõs em base de dados.

### Comandos para levantar a aplicação

**Instalar as dependências**  
```pip install -r requirements.txt```   

**Criar as tabelas**   
```python manage.py migrate```   

**Criar usuário admin**  
```python manage.py createsuperuser```   

**Levantar a aplicação**  
```python manage.py runserver```   

CRUD: Create (Criação), Read (Consulta), Update (Atualização), Delete (Remoção)
