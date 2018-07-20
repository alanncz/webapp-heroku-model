# Modelo de webapp para implantação no heroku com maven

# Executando deploy :

``heroku login``

Enter your Heroku credentials.


``heroku create <nome da aplicacao>``


``mvn clean heroku:deploy-war``
