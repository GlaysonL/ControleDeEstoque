# Controle De Estoque


Primeiro instale o framework Django
Com o seguinte comando:  pip install django

Execute o comando makemigrations para criar uma migration do seu modelo de entidade baseado na class dentro do models.py

python .\manage.py makemigrations

Após criar a migration, execute o comando abaixo, para aplicar o sql no banco de dados.
python .\manage.py migrate


Para executar a aplicação execute o comando:
python .\manage.py runserver



OBS: Alguns comandos podem estar proibido por default no ambiente windows, portanto é importante executar o comando abaixo:
Set-ExecutionPolicy AllSigned -Force