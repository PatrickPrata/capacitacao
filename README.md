# capacitacao

git clone https://github.com/PatrickPrata/capacitacao.git
cd capacitacao

spring.datasource.url=jdbc:mysql://localhost:3306/nome_do_banco
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha

spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.username=sa
spring.datasource.password=password

mvn spring-boot:run

http://localhost:8080/swagger-ui.html

├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── exemplo
│   │   │           └── aplicacao
│   │   │               ├── controller        # Controladores REST
│   │   │               ├── model             # Entidades (Pessoa, Contato)
│   │   │               ├── repository        # Repositórios JPA
│   │   │               ├── service           # Serviços de negócio
│   │   │               └── AplicacaoApplication.java  # Classe principal Spring Boot
│   │   └── resources
│   │       └── application.properties         # Configurações do Spring Boot
│   └── test                                    # Testes unitários e de integração
│
├── pom.xml                                      # Configuração do Maven
└── README.md                                    # Este arquivo
