
Para rodar o projeto
mvn spring-boot:run
mvn spring-boot:run -X

mvn clean install
mvn spring-boot:run


Acesse o swagger
http://localhost:8080/swagger-ui.html

Acesso no banco
http://localhost:8080/h2-console

Inserir dados
INSERT INTO produto(name,price) VALUES ('Farofa',20.0);

