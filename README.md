# 🚀 Sistema de Gestão do 1º Hackathon do Curso

Aplicação web completa para gerenciamento e operacionalização do Hackathon, desenvolvida como projeto da disciplina de Engenharia de Software I (IFPR - Campus Pinhais).

O sistema permite a inscrição de participantes, formação de equipes, submissão de projetos com links do GitHub e a avaliação dos projetos por uma banca de jurados com notas e comentários.

---

## 📌 Funcionalidades Principais

### 🎓 Área do Participante / Aluno
- **Autenticação:** Cadastro e login individual com validação de credenciais.
- **Gestão de Equipes:** Criação de novos grupos ou ingresso em equipes existentes.
- **Submissão de Projetos:** Envio do projeto da equipe (título, descrição, categoria e link do repositório no GitHub).
- **Cronograma do Evento:** Visualização da agenda completa do Hackathon com filtro interativo por dia.

### ⚖️ Área do Jurado
- **Painel Geral (Dashboard):** Acompanhamento de estatísticas (projetos submetidos, avaliados e pendentes).
- **Sistema de Avaliação:** Atribuição de notas (0 a 10) e comentários explicativos para cada projeto, com permissão para atualização da avaliação.

---

## 🛠️ Tecnologias Utilizadas

- **Front-end:** HTML5, CSS3 (Flexbox/Grid), JavaScript (ES6+ e IntersectionObserver)
- **Back-end:** PHP 8+ (gerenciamento de sessões e rotas)
- **Banco de Dados:** MySQL / MariaDB (conexão via PDO)
- **Metodologia Ágil:** Kanban (organizado via Trello/GitHub Projects)

---

## 🛡️ Segurança e LGPD

O projeto foi construído aplicando boas práticas de desenvolvimento web e princípios da **LGPD (Lei nº 13.709/2018)**:
- **Prepared Statements (PDO):** Proteção contra ataques de *SQL Injection*.
- **Sanitização (`htmlspecialchars`):** Prevenção contra vulnerabilidades *XSS*.
- **Minimização de Dados (Art. 6º, III - LGPD):** Coleta estrita apenas dos dados necessários para a operação do evento (Nome, E-mail e Matrícula).
- **Direito de Eliminação (Art. 18, VI - LGPD):** Funcionalidade para exclusão de projetos e saída de equipes com limpeza em cascata no banco de dados.

---

## 🚀 Como Executar o Projeto Localmente

### Pré-requisitos
- Servidor local PHP (XAMPP, WAMP, Laragon ou PHP CLI)
- Banco de Dados MySQL

### Passo a passo
1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
