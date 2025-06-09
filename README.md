cat << 'EOF' > README.md
# 🍽️ Cardápio Digital - Backend

Este é o backend do projeto **Cardápio Digital**, desenvolvido com **Spring Boot** e banco de dados **MySQL**. Ele fornece uma API RESTful para gerenciar itens de um cardápio (como pratos, bebidas, etc), ideal para sistemas de restaurantes, lanchonetes ou delivery.

---

## 🚀 Tecnologias Utilizadas

- ✅ Java 21
- ✅ Spring Boot 3.5.0
- ✅ Spring Web (API REST)
- ✅ Spring Data JPA (Persistência)
- ✅ MySQL Driver
- ✅ Lombok (para reduzir boilerplate)
- ✅ Maven (gerenciador de dependências)

---

## ⚙️ Como rodar o projeto localmente

### Pré-requisitos

- [Java 21+](https://www.oracle.com/java/technologies/javase/jdk21-archive-downloads.html)
- [Maven](https://maven.apache.org/)
- [MySQL Server](https://dev.mysql.com/downloads/installer/)
-[Lombok](https://projectlombok.org/download)
- IDE como Eclipse ou IntelliJ

---

### Passos

1. **Clone o repositório:**

\`\`\`bash
git clone https://github.com/Matthz-max/back-video-1.git
cd back-video-1
\`\`\`

2. **Configure o \`application.properties\`:**

No diretório \`src/main/resources\`, crie ou edite o arquivo \`application.properties\` com os dados do seu banco MySQL:

\`\`\`properties
spring.datasource.url=jdbc:mysql://localhost:3306/cardapio
spring.datasource.username=root
spring.datasource.password=root
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect
\`\`\`

3. **Execute a aplicação:**

\`\`\`bash
./mvnw spring-boot:run
\`\`\`
Ou dentro da IDE, rode a classe principal com \`@SpringBootApplication\`.

---

## 📦 Estrutura de Pastas (exemplo)

\`\`\`
src
├── main
│   ├── java
│   │   └── com.example.cardapio
│   │       ├── CardapioApplication.java
│   │       ├── controller
│   │       ├── model
│   │       ├── repository
│   │       └── service
│   └── resources
│       ├── application.properties
│       └── static/
└── test
\`\`\`

---

## 🧪 Testes

A dependência \`spring-boot-starter-test\` já está configurada. Para rodar os testes:

\`\`\`bash
./mvnw test
\`\`\`

---
 
## Usado como referencia Video 
1. Criando Aplicação Fullstack do Zero com Java Spring e React - Parte 1: Desenvolvimento do Backend
Fernanda Kipper | Dev
https://www.youtube.com/watch?v=lUVureR5GqI

##👨‍💻 Desenvolvedor
Feito com 💙 por [Matthz-max](https://github.com/Matthz-max)
EOF
