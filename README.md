## Requisitos

 - Docker e docker-compose

## Instruções

 1. Faça o clone do projeto `git clone`
 2. Na pasta raiz do projeto execute o comando `sudo docker-compose up`
	 2.1 Certifique-se que a porta 8000 não esteja ocupada
 3. Acesse o container web `sudo docker-compose exec web bash`
 4. Rode as migrations `python manage.py migrate`
 5. Acesse o sistema através de http://0.0.0.0:8000 ou http://localhost:8000

Obs.: A persistência dos dados do banco ainda está sendo implementada.
