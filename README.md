### Controle de ponto e acesso utilizando springboot e swagger



#### Construindo uma Api rest para gerenciamento de ponto e controle de acesso  utilizando as seguintes dependências seleciondas no spring initializr:  Spring Data Jpa, Hibernate, Lombok e Swagger para documentar as mudenças no banco de dados JPA H2.

##### Para rodar a aplicação, caso este projeto seja copiado ou colado com o git clone, deve-se mudar o path onde o banco de dados com  persistência será inicializado, no arquivo application.properties que se encontra dentro da pasta resources, na linha spring.datasource.url=jdbc:h2:file:/home/{SEU-USUÁRIO}/{PASTA-ONDE-DESEJA-SALVAR} caso esteja numa distro linux ou macOS, no windows lembre-se de usar a barra inversa "\\".

