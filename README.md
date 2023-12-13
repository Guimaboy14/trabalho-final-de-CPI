# trabalho-final-de-CPI

SISTEMAS DE RESERVAS PARA UM RESTAURANTE

#layout figma link https://www.figma.com/file/MdTXQhYzpyj1dTWmPQRtRe/Telas-Programa%C3%A7%C3%A3o-para-Internet-1?type=design&node-id=0-1
________________________________________________________________________________________________________________________________________________
#regras de negócio

limte de mesas disponíveis 20
aviso quando estiver lotado ou sem mesas disponíveis
horários de reservas proibido entre 00:00 e 10:00 manhã
só pode reservar 3 dias de antecedência da data atual
____________________________________________________________________________________________________________________________________________
#entrar na pasta cd reservas

python -m venv env

#caso de erro abra powersheel como admin e usa este código Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned

#ativa máquina virtual .\env\Scripts\Activate.bat

#instalando django pip install django

#cria super usuário python manage.py createsuperuser

#cria models python manage.py makemigrations

#cria tabelas no banco de dados python manage.py migrate

#iniciando projeto python manage.py runserver
