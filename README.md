
# Estoque - Projeto de Desenvolvimento I

Controle de estoque


## Como rodar o projeto?

* Crie um virtualenv com Python 3.
* Ative o virtualenv.
* Instale as dependências.
* Rode as migrações.

```bash

cd estoque
python3 -m venv .venv

(LINUX / MAC)
source .venv/bin/activate

(WINDOWS)
.venv/bin/activate

pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```


 
 
 
