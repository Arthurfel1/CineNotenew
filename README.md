<<<<<<< HEAD
<<<<<<< HEAD
# 🎬 CineNote – Avaliador de Filmes

CineNote é um sistema web simples desenvolvido em **Java (Servlet + JSP)** com **JPA/Hibernate** e interface em HTML/CSS/JavaScript. Ele permite ao usuário cadastrar, avaliar e visualizar filmes com comentários e notas.

---

## 📦 Funcionalidades

- ✅ Cadastrar filmes com nome, nota (1 a 10) e comentário (opcional)
- ✅ Listar todos os filmes avaliados
- ✅ Validação dos campos obrigatórios no front-end
- ✅ Persistência dos dados com banco de dados MySQL via JPA

---

## 🚀 Como executar o projeto

### 1. Pré-requisitos

- Java JDK 11 ou superior
- Apache Tomcat 9 ou 10
- MySQL (ou MariaDB)
- Maven ou NetBeans
- Navegador atualizado (Chrome, Firefox, etc.)

---

### 2. Banco de Dados

Crie o banco e as tabelas usando o script a seguir:

📄 `create_tables.sql`

```sql
CREATE DATABASE IF NOT EXISTS cinenote DEFAULT CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
USE cinenote;

CREATE TABLE IF NOT EXISTS filme (
    id BIGINT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(255) NOT NULL,
    nota INT NOT NULL,
    comentario TEXT
);
=======
# 🎬 CineNote – Avaliação de Filmes e Sessões
=======
🎬 CineNote – Avaliação de Filmes e Sessões
>>>>>>> 407609a72cee2fbc820966effbfdae4ff2870e14

CineNote é um sistema web simples e intuitivo para avaliar filmes e gerenciar sessões de cinema.

✅ Funcionalidades

- Avaliação de filmes com:  
  Nome, atores, gênero, sinopse, nota (1 a 10) e comentário  
- Gerenciamento de sessões:  
  Filme, sala, data/hora e capacidade  
- Mensagens de sucesso ao adicionar filmes e sessões  
- Exibição dinâmica das avaliações e sessões  

🧪 Casos de Teste

| Teste | Ação                  | Esperado                                | Resultado |
|-------|-----------------------|----------------------------------------|-----------|
| 1     | Nome do filme vazio   | Erro: "Esse campo é obrigatório."       | ✅        |
| 2     | Nota = 11             | Erro: "O valor deve ser igual ou menor a 10" | ✅   |
| 3     | Comentário vazio      | Aceita normalmente                      | ✅        |
| 4     | Dados válidos         | Exibe avaliação corretamente            | ✅        |
| 5     | Sessão válida         | Exibe sessão corretamente                | ✅        |

▶️ Como Usar

- Abra o arquivo index.html no navegador.  
- Para versão Java Web (JSF), use o NetBeans e um servidor como Tomcat ou GlassFish.

📁 Estrutura

- index.html  
- css/style.css  
- js/script.js  
- plano-de-testes.pdf  
- build/CineNote.war (se aplicável)  
- evidencias/ (commits, repositório, tarefas)  

👨‍💻 Contato

Email: contato@cinenote.com  
Tel: (11) 91234-5678  
Endereço: Rua dos Filmes, 123 – Belo Horizonte  

© 2025 CineNote
>>>>>>> 2be53ee55d89fe9cec2b3a9aaa420150700695ae
