# 🎬 CineNote – Avaliador de Filmes e Sessões

**CineNote** é um sistema web desenvolvido para facilitar a avaliação de filmes e o gerenciamento de sessões de cinema. Com uma interface moderna, acessível e responsiva, permite que usuários registrem avaliações, notas, comentários e informações de sessões.

---

## 📌 Funcionalidades Principais

### ✅ Avaliação de Filmes
- Cadastro de **nome do filme**, **atores principais**, **gênero**, **sinopse**, **nota (1 a 10)** e **comentário** (opcional).
- Validação de campos obrigatórios e intervalos numéricos.
- Exibição das avaliações com destaque visual e ícone de 🎬.

### ✅ Gerenciamento de Sessões
- Cadastro de sessões com os seguintes dados:
  - Filme (seleção entre os avaliados)
  - Sala
  - Horário (formato data e hora)
  - Capacidade da sala
- Validação de todos os campos e exibição de sessões cadastradas com ícone 🎟️.

---

## 🧪 Plano de Testes (Resumo)

| Caso | Funcionalidade | Entrada | Resultado Esperado | Status |
|------|----------------|---------|---------------------|--------|
| 1 | Nome do Filme vazio | "" | Mensagem de erro: "Esse campo é obrigatório." | ✅ |
| 2 | Nota acima do limite | 11 | Mensagem de erro: "O valor deve ser igual ou menor a 10" | ✅ |
| 3 | Comentário vazio | "" | Aceita normalmente (opcional) | ✅ |
| 4 | Dados válidos do filme | Todos preenchidos corretamente | Avaliação exibida com sucesso | ✅ |
| 5 | Sessão de filme | Campos válidos preenchidos | Sessão exibida com sucesso | ✅ |

---

## 📁 Estrutura do Projeto

