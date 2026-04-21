# 📘 Histórias de Usuário — Funcionário Operacional (Organização de Acervo)

---

# 📱 Touchpoint: Login do Funcionário

## 1. História de Usuário (Narrativa)

* **Como** Funcionário operacional da biblioteca
* **Eu quero** acessar o sistema por meio de um login simples e rápido
* **Para** visualizar minhas tarefas e iniciar meu trabalho sem perda de tempo

---

## 2. Detalhes da Tela (Informações na tela e Protótipo Conceitual)

### Estrutura (Mobile First)

* **Header**

  * Logotipo da biblioteca

* **Título**

  * “Acesso do Funcionário”

* **Campos de entrada**

  * Matrícula / ID do funcionário
  * Senha

* **Ações**

  * Botão primário: “Entrar”
  * Link secundário: “Esqueci minha senha”

* **Feedback**

  * Mensagem de erro (login inválido)
  * Loading ao autenticar

---

## 3. Critérios de Aceitação (BDD)

* **Dado que** o funcionário acessa o sistema
* **Quando** ele insere sua matrícula e senha
* **E** toca no botão “Entrar”
* **Então** o sistema deve autenticar o usuário
* **E** redirecioná-lo para o painel de tarefas

---

# 📱 Touchpoint: Painel de Tarefas

## 1. História de Usuário (Narrativa)

* **Como** Funcionário operacional
* **Eu quero** visualizar minhas tarefas organizadas por prioridade e prazo
* **Para** entender rapidamente o que devo fazer primeiro

---

## 2. Detalhes da Tela

* **Header**

  * Título: “Minhas Tarefas”

* **Lista de tarefas**

  * Nome da tarefa
  * Status (Pendente / Em andamento / Concluída)
  * Prioridade (Alta / Média / Baixa)
  * Prazo

* **Filtros**

  * Por prioridade
  * Por status

* **Ordenação automática**

  * Prioridade + prazo

---

## 3. Critérios de Aceitação (BDD)

* **Dado que** o funcionário está logado
* **Quando** acessa o painel de tarefas
* **E** visualiza a lista
* **Então** o sistema deve exibir tarefas ordenadas por prioridade
* **E** permitir identificação rápida do que é mais urgente

---

# 📱 Touchpoint: Detalhe da Tarefa

## 1. História de Usuário (Narrativa)

* **Como** Funcionário operacional
* **Eu quero** visualizar detalhes claros da tarefa selecionada
* **Para** entender exatamente o que precisa ser feito

---

## 2. Detalhes da Tela

* **Título**

  * Nome da tarefa

* **Informações**

  * Descrição
  * Objetivo
  * Localização (seção/estante)

* **Checklist**

  * Etapas da tarefa

* **Ação**

  * Botão: “Iniciar tarefa”

---

## 3. Critérios de Aceitação (BDD)

* **Dado que** o funcionário seleciona uma tarefa
* **Quando** a tela de detalhes é exibida
* **E** ele lê as instruções
* **Então** ele deve compreender claramente o que executar
* **E** poder iniciar a tarefa

---

# 📱 Touchpoint: Gerador de Rota

## 1. História de Usuário (Narrativa)

* **Como** Funcionário operacional
* **Eu quero** que o sistema gere automaticamente uma rota otimizada
* **Para** reduzir deslocamento e tempo de execução

---

## 2. Detalhes da Tela

* **Título**

  * “Rota Otimizada”

* **Informações**

  * Ordem de execução
  * Tempo estimado

* **Ação**

  * Botão: “Gerar rota”

---

## 3. Critérios de Aceitação (BDD)

* **Dado que** o funcionário iniciou uma tarefa
* **Quando** solicita a geração de rota
* **E** confirma a ação
* **Então** o sistema deve calcular a melhor sequência de execução
* **E** apresentar a rota otimizada

---

# 📱 Touchpoint: Mapa com Rota

## 1. História de Usuário (Narrativa)

* **Como** Funcionário operacional
* **Eu quero** visualizar a rota em um mapa claro
* **Para** saber exatamente por onde começar e seguir

---

## 2. Detalhes da Tela

* **Mapa**

  * Estantes destacadas
  * Caminho sugerido
  * Posição atual

* **Legenda**

  * Setores e cores

* **Ação**

  * Botão: “Iniciar rota”

---

## 3. Critérios de Aceitação (BDD)

* **Dado que** a rota foi gerada
* **Quando** o mapa é exibido
* **E** o funcionário visualiza o trajeto
* **Então** ele deve compreender o caminho sem dificuldade
* **E** iniciar a execução

---

# 📱 Touchpoint: Tela do Livro

## 1. História de Usuário (Narrativa)

* **Como** Funcionário operacional
* **Eu quero** acessar os dados de um livro
* **Para** verificar localização e informações corretas

---

## 2. Detalhes da Tela

* **Informações**

  * Título
  * Autor
  * Categoria
  * Localização

* **Status**

  * Disponível / Indisponível

* **Ação**

  * Botão: “Editar”

---

## 3. Critérios de Aceitação (BDD)

* **Dado que** o funcionário seleciona um livro
* **Quando** acessa seus detalhes
* **E** analisa as informações
* **Então** deve conseguir validar os dados
* **E** acessar a edição se necessário

---

# 📱 Touchpoint: Edição de Livro

## 1. História de Usuário (Narrativa)

* **Como** Funcionário operacional
* **Eu quero** corrigir informações do livro
* **Para** manter o acervo atualizado

---

## 2. Detalhes da Tela

* **Campos editáveis**

  * Localização
  * Categoria
  * Status

* **Ação**

  * Botão: “Salvar alterações”

---

## 3. Critérios de Aceitação (BDD)

* **Dado que** o funcionário identifica um erro
* **Quando** edita os dados
* **E** salva as alterações
* **Então** o sistema deve atualizar o registro
* **E** refletir a mudança imediatamente

---

# 📱 Touchpoint: Registro de Ocorrência

## 1. História de Usuário (Narrativa)

* **Como** Funcionário operacional
* **Eu quero** registrar problemas encontrados
* **Para** informar a gestão e manter controle do acervo

---

## 2. Detalhes da Tela

* **Campos**

  * Tipo de problema
  * Prioridade
  * Descrição

* **Ação**

  * Botão: “Registrar ocorrência”

---

## 3. Critérios de Aceitação (BDD)

* **Dado que** o funcionário encontra um problema
* **Quando** preenche os dados
* **E** envia o registro
* **Então** o sistema deve salvar a ocorrência
* **E** vinculá-la à tarefa

---

# 📱 Touchpoint: Atualização de Tarefa

## 1. História de Usuário (Narrativa)

* **Como** Funcionário operacional
* **Eu quero** atualizar o status da tarefa
* **Para** informar o andamento do trabalho

---

## 2. Detalhes da Tela

* **Opções**

  * Concluída
  * Concluída com problema
  * Não concluída

* **Campo adicional**

  * Justificativa

* **Ação**

  * Botão: “Atualizar status”

---

## 3. Critérios de Aceitação (BDD)

* **Dado que** o funcionário finaliza uma tarefa
* **Quando** seleciona o status
* **E** confirma a atualização
* **Então** o sistema deve registrar o status
* **E** atualizar o painel

---

# 📱 Touchpoint: Envio de Feedback

## 1. História de Usuário (Narrativa)

* **Como** Funcionário operacional
* **Eu quero** enviar feedback sobre dificuldades e melhorias
* **Para** contribuir com a gestão do sistema

---

## 2. Detalhes da Tela

* **Campos**

  * Tipo de feedback
  * Comentário

* **Ação**

  * Botão: “Enviar feedback”

---

## 3. Critérios de Aceitação (BDD)

* **Dado que** o funcionário deseja relatar algo
* **Quando** preenche o formulário
* **E** envia o feedback
* **Então** o sistema deve registrar a informação
* **E** disponibilizar para gestão

---

# 📱 Touchpoint: Histórico de Tarefas/Feedbacks

## 1. História de Usuário (Narrativa)

* **Como** Funcionário operacional
* **Eu quero** visualizar histórico de tarefas e respostas
* **Para** acompanhar retorno da gestão

---

## 2. Detalhes da Tela

* **Lista**

  * Tarefas realizadas
  * Feedbacks enviados
  * Respostas da gestão

---

## 3. Critérios de Aceitação (BDD)

* **Dado que** o funcionário acessa o histórico
* **Quando** visualiza os registros
* **E** analisa as respostas
* **Então** deve acompanhar o retorno
* **E** entender decisões tomadas

---

# 📱 Touchpoint: Painel Atualizado em Tempo Real

## 1. História de Usuário (Narrativa)

* **Como** Funcionário operacional
* **Eu quero** ver tarefas atualizadas em tempo real
* **Para** ajustar prioridades rapidamente

---

## 2. Detalhes da Tela

* Atualização automática
* Indicadores de mudança
* Notificações leves

---

## 3. Critérios de Aceitação (BDD)

* **Dado que** novas demandas surgem
* **Quando** o sistema atualiza os dados
* **E** o funcionário visualiza o painel
* **Então** as informações devem estar atualizadas
* **E** refletir mudanças imediatamente

---

# 📱 Touchpoint: Uso Recorrente

## 1. História de Usuário (Narrativa)

* **Como** Funcionário operacional
* **Eu quero** utilizar o sistema diariamente de forma simples
* **Para** executar tarefas com autonomia e eficiência

---

## 2. Detalhes da Tela

* Acesso rápido
* Continuidade de sessão
* Interface familiar

---

## 3. Critérios de Aceitação (BDD)

* **Dado que** o funcionário utiliza o sistema com frequência
* **Quando** acessa novamente
* **E** inicia suas atividades
* **Então** deve conseguir retomar rapidamente
* **E** executar tarefas sem fricção

---

## ✅ Resultado Final
