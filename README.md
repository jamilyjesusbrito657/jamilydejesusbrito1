# 🧩 Modos do Copiloto (Ask, Edit, Plan, Agent e Study)

Os modos do Copiloto foram criados para atender diferentes necessidades durante o desenvolvimento de software. Cada modo possui um objetivo específico, permitindo que você escolha o nível de assistência mais adequado para cada situação.

---

## ❓ Ask — Entender e Analisar

Use o modo **Ask** quando precisar compreender algo antes de realizar alterações.

### O que faz

* Analisa código existente.
* Explica erros e mensagens de exceção.
* Interpreta stack traces.
* Esclarece conceitos técnicos.
* Responde dúvidas sobre arquitetura e lógica.

### O que NÃO faz

* Não cria arquivos.
* Não altera código.
* Não executa mudanças.

### Exemplos

* "Por que esta função está retornando null?"
* "Explique este erro."
* "Como funciona este algoritmo?"

**Objetivo:** Aprender e entender.

---

## ✏️ Edit — Modificar Código Existente

Use o modo **Edit** quando já souber o que deseja mudar.

### O que faz

* Refatora código.
* Corrige bugs.
* Melhora performance.
* Adiciona logs.
* Trata exceções.
* Ajusta estilos e padrões.
* Converte código entre linguagens.

### Exemplos

* "Transforme esta função em async."
* "Adicione tratamento de erro."
* "Otimize esta consulta SQL."

**Objetivo:** Alterar algo que já existe.

---

## 🧭 Plan — Planejar Antes de Executar

Use o modo **Plan** para tarefas maiores que exigem análise prévia.

### O que faz

1. Entende o problema.
2. Divide a solução em etapas.
3. Explica a estratégia.
4. Identifica riscos e dependências.
5. Somente depois propõe a implementação.

### Exemplos

* Criar uma nova funcionalidade.
* Migrar banco de dados.
* Reestruturar arquitetura.
* Implementar autenticação completa.

**Objetivo:** Validar a abordagem antes de programar.

---

## 🤖 Agent — Executar com Autonomia

Use o modo **Agent** para tarefas complexas que envolvem vários arquivos e etapas.

### O que faz

* Analisa o projeto.
* Cria arquivos.
* Modifica múltiplos componentes.
* Mantém contexto entre ações.
* Toma decisões técnicas para atingir o objetivo.

### Exemplos

* Implementar login com JWT.
* Criar CRUD completo.
* Configurar autenticação.
* Integrar APIs externas.
* Adicionar novas funcionalidades.

**Objetivo:** Delegar uma tarefa completa.

---

## 📚 Study — Aprender de Forma Ativa

Use o modo **Study** quando o foco for aprendizado e desenvolvimento de habilidades.

### O que faz

* Ensina conceitos gradualmente.
* Explica vantagens e desvantagens.
* Estimula o raciocínio.
* Propõe exercícios e desafios.
* Adapta o nível de dificuldade.

### Exemplos

* Aprender React.
* Estudar algoritmos.
* Entender arquitetura de software.
* Praticar resolução de problemas.

**Objetivo:** Desenvolver conhecimento e autonomia.

---

# 🧠 Resumo Rápido

| Modo     | Finalidade                         |
| -------- | ---------------------------------- |
| ❓ Ask    | Entender e analisar                |
| ✏️ Edit  | Modificar código existente         |
| 🧭 Plan  | Planejar antes de implementar      |
| 🤖 Agent | Executar tarefas complexas         |
| 📚 Study | Aprender e desenvolver habilidades |

### Regra prática

* Tem uma dúvida? → **Ask**
* Quer alterar algo? → **Edit**
* A tarefa é grande? → **Plan**
* Quer delegar a implementação? → **Agent**
* Quer aprender de verdade? → **Study**
