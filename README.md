🎬 CineNote – Avaliação de Filmes e Sessões

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
