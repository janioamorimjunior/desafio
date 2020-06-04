Projeto feito com protractor e com o allure report

para instalar o protractor precisa do npm, atraves do comando:

npm install -g protractor

isso vai instalar as linhas de comando do protractor e do webdriver-manager, esta última que é responsavel de obter uma instancia do selenium server, para baixar/atualizar as instancias dos drivers do selenium é preciso executar a seguinte linha de comando:

webdriver-manager update

depois de clonado o projeto, é preciso instalar as dependências do projeto usando o comando seguinte na raiz da pasta:

npm install

depois só executar o comando protractor na raiz do projeto que o teste vai iniciar;