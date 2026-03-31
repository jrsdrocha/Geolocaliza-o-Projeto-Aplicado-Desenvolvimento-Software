
## Buscar obra e visualizar localização no mapa

---

## 1. História de Usuário (Narrativa)

* **Como** Márcia Albuquerque, arquiteta visitante da biblioteca, curiosa e exploratória
* **Eu quero** acessar um sistema de busca simples e intuitivo que me permita encontrar uma obra e visualizar sua localização no mapa
* **Para** iniciar minha pesquisa com autonomia, sem depender de ajuda e com segurança de que conseguirei encontrar o material

---

## 2. Detalhes da Tela

### 📱 Estrutura geral (Mobile First)

Tela de entrada com foco em **clareza, acolhimento e incentivo à autonomia**.

---

### 🔝 Header (fixo)

* Logo da biblioteca
* Ícone de menu
* Ícone de ajuda (?)

  * Tooltip: *“Como buscar um livro”*

---

### 🔍 Campo de Busca (principal)

* Placeholder: **“Buscar por título, autor ou assunto”**
* Input com alto contraste
* Ícone de lupa
* Ícone de microfone (acessibilidade)

---

### ✨ Sugestões rápidas

* Chips:

  * Arquitetura
  * Urbanismo
  * Normas técnicas
  * História da arquitetura
* Texto: *“Sugestões para começar”*

---

### 📚 Histórico recente

* Estruturas metálicas
* Le Corbusier
* Ação: **Buscar novamente**

---

### 📍 Acesso ao mapa

* Botão: **Explorar mapa da biblioteca**
* Texto: *“Veja como os setores estão organizados”*

---

### 💬 Mensagem de acolhimento

> “Encontre qualquer obra com facilidade. Você pode buscar e ir direto até a estante 📚”

---

### ⚙️ Estados da interface

* Estado vazio
* Autocomplete em tempo real
* Loading com skeleton

---

### 🎯 Usabilidade

* Busca em destaque
* Linguagem simples
* Sugestões inteligentes
* Acesso rápido ao mapa

---

## 3. Critérios de Aceitação (BDD)

### Cenário 1

* **Dado que** Márcia acessa o sistema
* **Quando** a tela inicial carrega
* **Então** deve haver um campo de busca claro e acessível

---

### Cenário 2

* **Dado que** ela digita um termo
* **Então** o sistema deve mostrar sugestões automáticas

---

### Cenário 3

* **Quando** ela confirma a busca
* **Então** deve ver resultados com opção de mapa

---

### Cenário 4

* **Quando** usa sugestões ou histórico
* **Então** a busca deve ser simples e guiada

---

### Cenário 5

* **Quando** lê a mensagem de apoio
* **Então** deve sentir confiança no sistema

---

## Tela de Busca Ativa

### Objetivo

Foco em **velocidade, feedback e relevância**.

---

### 🔝 Header

* Botão voltar
* Campo ativo
* Ícone limpar
* Ícone busca

---

### ⌨️ Autocomplete

* 📚 Títulos
* 👤 Autores
* 🏷️ Temas

---

### ⏳ Feedback

* Loading
* “Buscando resultados...”

---

### 📚 Resultados (cards)

* Título
* Autor
* Ano
* Tema
* Status
* Código
* Botão: **Ver localização**

---

### 🔎 Filtros

* Disponível agora
* Arquitetura
* Mais recentes

---

### ⚠️ Sem resultados

* “Nenhum resultado encontrado”
* Sugestões alternativas

---

## Tela de Resultados

### Objetivo

**Leitura fácil + confirmação rápida**

---

### 📚 Cards

* Título (destaque)
* Autor
* Ano
* Tema
* Código
* Status
* Botão: **Ver localização no mapa**

---

### 📌 Organização

* Cards verticais
* Status por cor
* Ícones visuais

---

### 💬 Feedback

> “Esta obra está disponível no acervo ✅”

---

## Tela de Detalhes da Obra

### 📖 Informações

* Título
* Autor
* Ano
* Tema
* Código
* Status

---

### 📝 Descrição

* Sinopse
* Uso técnico

---

### 📍 Localização

* Setor
* Corredor
* Estante
* Botão: **Visualizar no mapa**

---

### 💡 Extras

* Sugestões relacionadas
* Favoritar
* Compartilhar

---

## Tela de Mapa

### 🗺️ Mapa Interativo

* Pin da obra
* Código de chamada
* Setor
* “Você está aqui” (opcional)
* Zoom e arraste

---

### 📍 Informações

* Andar
* Setor
* Estante
* Distância estimada

---

### 🎯 Ações

* **Iniciar rota até a obra**
* Voltar

---

## Mapa Geral da Biblioteca

### 🗺️ Visão geral

* Setores coloridos
* Identificação textual
* Estrutura (escadas, corredores)

---

### 📍 Destaque

* Setor do livro destacado

---

### 🧭 Legenda

* Cores por setor
* Ícones explicativos

---

## Navegação por Andares

* Lista de andares
* Destaque do andar correto
* Mapa dinâmico

---

## Conclusão

O sistema foi projetado para:

* Reduzir insegurança
* Aumentar autonomia
* Facilitar navegação física
* Melhorar a experiência do usuário

---

Se quiser, posso transformar isso em um **protótipo (wireframe)** ou em um **fluxo de UX visual** 👀
