# Auth Wiki Server
Server for Auth Wiki.
<br>

### How to run
- Clone the repo `git clone https://github.com/Falence/auth_wiki_server.git` and `cd` into it.
- Create a virtual environment `python -m venv env` and activate it `source env/Scripts/activate`.
- Install all packages `pip install requirements.txt`.
- Setup your local myqsl DBMS.
- Run migrations `python manage.py migrate`.
- Run server `python manage.py runserver`.

### Endpoints
The following endpoints are available on this server:
- `api/register`: creates a new user
- `api/login`: logs in user. 
- `api/logout`: logs user out