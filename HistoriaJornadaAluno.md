# 🔍 Busca de Livro no Catálogo com Visualização de Localização

---

## 📱 Tela Inicial de Busca

### 1. História de Usuário
**Como** Pedro Andrade, um estudante introvertido e produtivo  
**Quero** acessar uma interface de busca simples e direta  
**Para que** eu encontre livros e sua localização sem precisar pedir ajuda  

### 2. Detalhes da Tela
- **Cabeçalho**
  - "Biblioteca Unifor"
  - Ícone de perfil

- **Campo de Busca**
  - Placeholder: "Digite o título, autor ou assunto..."
  - Ícone de lupa + scanner

- **Filtros (Chips)**
  - Disponível agora
  - Livros técnicos
  - Artigos

- **Seção Recomendada**
  - Baseada no curso

- **Feedback**
  - "3.500 livros disponíveis"

- **UX**
  - Autocomplete
  - Microinterações em tempo real

### 3. Critérios de Aceitação
- **Dado** que estou logado  
- **Quando** busco um livro  
- **Então** vejo resultados com status e opção de mapa  

---

## 🔎 Explorar a Tela de Busca

### 1. História de Usuário
**Como** Pedro Andrade  
**Quero** uma busca intuitiva com sugestões  
**Para que** eu encontre livros rapidamente  

### 2. Detalhes da Tela
- **Header**
  - Logo + perfil

- **Saudação**
  - "Olá, Pedro"

- **Busca**
  - Campo destacado

- **Filtros**
  - Disponíveis, Didáticos, Literatura, E-books

- **Sugestões**
  - Recentes e recomendados

- **FAB**
  - Scanner QR/Barcode

### 3. Critérios de Aceitação
- **Dado** que estou na tela inicial  
- **Quando** digito  
- **Então** vejo sugestões e navego para resultados  

---

## ✍️ Digitar Título, Autor ou Assunto

### 1. História de Usuário
**Como** Pedro Andrade  
**Quero** usar busca com autocomplete  
**Para que** eu encontre rapidamente o livro  

### 2. Detalhes da Tela
- **Campo Ativo**
  - Destaque visual
  - Botão "X" para limpar

- **Sugestões**
  - Títulos
  - Autores
  - Indicador de disponibilidade

- **Teclado**
  - Botão "Buscar"

### 3. Critérios de Aceitação
- **Dado** que estou digitando  
- **Quando** escolho sugestão ou busco  
- **Então** vejo resultados filtrados  

---

## 📚 Visualizar Resultados

### 1. História de Usuário
**Como** Pedro Andrade  
**Quero** ver resultados claros com status  
**Para que** eu identifique rapidamente o livro  

### 2. Detalhes da Tela
- **Header**
  - Quantidade de resultados
  - Botão filtro

- **Cards**
  - Capa
  - Título (H2)
  - Autor
  - Status (verde/vermelho)
  - Setor

- **Ações**
  - Favoritar
  - Ver detalhes

### 3. Critérios de Aceitação
- **Dado** que fiz uma busca  
- **Quando** vejo a lista  
- **Então** posso acessar detalhes  

---

## 👉 Selecionar Livro

### 1. História de Usuário
**Como** Pedro Andrade  
**Quero** clicar no livro desejado  
**Para que** eu veja mais detalhes  

### 2. Detalhes da Tela
- **Feedback**
  - Animação ao clicar

- **Card**
  - Título
  - Autor
  - Status
  - Capa

- **Indicador**
  - "Ver detalhes"

### 3. Critérios de Aceitação
- **Dado** que estou na lista  
- **Quando** clico no livro  
- **Então** vou para detalhes  

---

## 📖 Detalhes do Livro

### 1. História de Usuário
**Como** Pedro Andrade  
**Quero** ver detalhes e código de chamada  
**Para que** eu confirme e localize o livro  

### 2. Detalhes da Tela
- **Header**
  - Botão voltar

- **Hero**
  - Capa
  - Título (H1)
  - Autor

- **Disponibilidade**
  - Status + andar

- **Código de Chamada**
  - Ex: `658.8 M827m`
  - Botão copiar

- **Resumo**
  - Sinopse, editora, ISBN

- **CTA**
  - "Ver localização no mapa"

### 3. Critérios de Aceitação
- **Dado** que estou nos detalhes  
- **Quando** clico no mapa  
- **Então** vejo a localização  

---

## 🗺️ Ver Localização no Mapa

### 1. História de Usuário
**Como** Pedro Andrade  
**Quero** ver a localização visual  
**Para que** eu vá direto ao livro  

### 2. Detalhes da Tela
- **Header**
  - Livro + código

- **Mapa**
  - Planta do andar
  - Pin na estante

- **Legenda**
  - Estante, lado, prateleira

- **Controles**
  - Zoom
  - Minha localização

- **Botão**
  - Finalizar

### 3. Critérios de Aceitação
- **Dado** que cliquei no mapa  
- **Quando** carrega  
- **Então** vejo o destino claramente  

---

## 📍 Visualizar Estante no Mapa

### 1. História de Usuário
**Como** Pedro Andrade  
**Quero** ver a estante destacada  
**Para que** eu encontre o livro rapidamente  

### 2. Detalhes da Tela
- **Header**
  - Código de chamada

- **Mapa**
  - Caminho destacado
  - Estante pulsante
  - Pontos de referência

- **Card Inferior**
  - Instruções simples

- **Ações**
  - "Cheguei ao local"

### 3. Critérios de Aceitação
- **Dado** que estou no mapa  
- **Quando** sigo o trajeto  
- **Então** encontro o livro sem dificuldade  

---

## 🎯 Objetivo Geral
Permitir que o usuário encontre livros de forma **autônoma, rápida e sem interação social**, utilizando busca inteligente e visualização clara da localização física.

---------------------------------------------------------------------------------------------------

# 🗺️ Interpretação do Mapa Interno da Biblioteca

---

## 📍 Acessar a Visualização da Localização do Livro

### 1. História de Usuário
**Como** Pedro Andrade, um estudante introvertido que deseja localizar seu material de forma independente  
**Quero** visualizar a localização do livro no mapa a partir do número de chamada  
**Para que** eu saiba exatamente para qual andar e setor devo ir  

### 2. Detalhes da Tela
- **Card de Resumo (Topo)**
  - Capa do livro
  - Título abreviado
  - Código de chamada em destaque

- **Seletor de Andar**
  - Tabs ou botões (Piso Térreo, 1º, 2º)
  - Andar correto já selecionado

- **Mapa Interativo**
  - Planta baixa simplificada
  - Pin pulsante na estante
  - Setor destacado (ex: Engenharia)

- **Legenda**
  - "Estante 14, Corredor B, 2º Andar"

- **Ações**
  - Botão: *Como Chegar*
  - Botão: *Voltar*

### 3. Critérios de Aceitação (BDD)
- **Dado** que estou na tela de detalhe  
- **Quando** clico em "Ver Localização"  
- **Então** vejo o mapa com a estante destacada  

---

## 🧭 Selecionar “Ver no Mapa”

### 1. História de Usuário
**Como** Pedro Andrade  
**Quero** abrir o mapa diretamente da tela do livro  
**Para que** eu não precise interpretar o código manualmente  

### 2. Detalhes da Tela
- **Loading (Skeleton)**
  - Estrutura do mapa enquanto carrega

- **Header Sticky**
  - Miniatura + título
  - Código de chamada

- **Mapa**
  - Planta baixa da biblioteca
  - Pin pulsante

- **Bottom Sheet**
  - Andar + setor
  - Estante + corredor

- **Controles**
  - Zoom (+/-)
  - Alternar andares

### 3. Critérios de Aceitação
- **Dado** que estou na tela do livro  
- **Quando** clico em "Ver no mapa"  
- **Então** o mapa abre centralizado no destino  

---

## 🗺️ Visualizar o Mapa Digital

### 1. História de Usuário
**Como** Pedro Andrade  
**Quero** ver um mapa simples e interativo  
**Para que** eu entenda rapidamente o espaço  

### 2. Detalhes da Tela
- **Header**
  - Título + código

- **Seletor de Andar**
  - Botões flutuantes

- **Mapa**
  - Corredores vs estantes
  - Pontos de referência:
    - Escadas
    - Elevadores
    - Banheiros

- **Caminho Sugerido**
  - Linha pontilhada

- **Bottom Sheet**
  - Setor
  - Corredor e estante

### 3. Critérios de Aceitação
- **Dado** que o mapa foi carregado  
- **Quando** observo o layout  
- **Então** entendo como chegar ao setor  

---

## 🎯 Identificar o Setor no Mapa

### 1. História de Usuário
**Como** Pedro Andrade  
**Quero** ver o setor destacado visualmente  
**Para que** eu identifique rapidamente a área correta  

### 2. Detalhes da Tela
- **Header**
  - Livro + andar

- **Mapa**
  - Setor destacado (cor primária)
  - Demais áreas em cinza

- **Tooltip**
  - Nome do setor

- **Referências**
  - "Você está aqui"
  - Escadas / elevadores

- **Legenda**
  - Direção textual simples

### 3. Critérios de Aceitação
- **Dado** que estou no mapa  
- **Quando** vejo o setor destacado  
- **Então** sei para onde me dirigir  

---

## 📚 Localizar a Estante no Mapa

### 1. História de Usuário
**Como** Pedro Andrade  
**Quero** ver a estante exata destacada  
**Para que** eu vá direto ao ponto  

### 2. Detalhes da Tela
- **Header**
  - Livro + código

- **Mapa (Zoom)**
  - Estante em destaque
  - Outras em cinza

- **Pin Pulsante**
  - Indicação precisa

- **Bottom Sheet**
  - Estante + lado
  - Altura da prateleira
  - Dica contextual

- **Ação**
  - Botão de brilho/contraste

### 3. Critérios de Aceitação
- **Dado** que estou no mapa  
- **Quando** aproximo o zoom  
- **Então** vejo exatamente a estante correta  

---

## 🧾 Consultar Legenda e Indicadores

### 1. História de Usuário
**Como** Pedro Andrade  
**Quero** entender os símbolos e cores do mapa  
**Para que** eu valide minha interpretação  

### 2. Detalhes da Tela
- **Header**
  - Código do livro

- **Legenda (Bottom Sheet)**
  - Cores dos setores
  - Ícones (escada, elevador, estante)

- **Guia Visual**
  - Como identificar o código na estante

- **Filtros**
  - Mostrar/ocultar camadas

- **Feedback**
  - Elementos brilham ao toque

### 3. Critérios de Aceitação
- **Dado** que estou no mapa  
- **Quando** consulto a legenda  
- **Então** confirmo que estou interpretando corretamente  

---

## 🎯 Objetivo Geral
Permitir que o usuário interprete o mapa da biblioteca de forma **rápida, intuitiva e autônoma**, reduzindo a necessidade de ajuda externa e aumentando a confiança durante o deslocamento.

-----------------------------------------------------------------------------------------------------
# 📚 Identificação da Estante a partir do Código de Chamada

---

## 🔎 Visualização do Código de Chamada

### 1. História de Usuário
**Como** Pedro Andrade, um estudante introvertido que preza pela objetividade e independência  
**Quero** visualizar o código de chamada do livro em destaque, com uma explicação visual de como ele se organiza  
**Para que** eu identifique com precisão qual sequência buscar nas estantes sem precisar de ajuda  

### 2. Detalhes da Tela
- **Card de Identificação**
  - Título do livro (H1)
  - Autor

- **Módulo "Número de Chamada"**
  - Fundo de alto contraste
  - Fonte monoespaçada (Courier / Roboto Mono)
  - Tamanho grande
  - Exemplo: `658.8 M827m`

- **Dica Visual**
  - "Procure por este código nas etiquetas laterais das estantes"

- **Mini-Mapa**
  - Ícone indicando setor

- **Ação**
  - Botão: *Manter tela acesa*

### 3. Critérios de Aceitação (BDD)
- **Dado** que estou na tela de detalhe  
- **Quando** observo o número de chamada  
- **Então** consigo iniciar a busca física com confiança  

---

## 🗺️ Associação do Código com o Mapa

### 1. História de Usuário
**Como** Pedro Andrade  
**Quero** ver o código sobreposto no mapa  
**Para que** eu associe diretamente número e localização  

### 2. Detalhes da Tela
- **Header Sticky**
  - Título + código

- **Mapa Interativo**
  - Auto-zoom na estante

- **Pin Inteligente**
  - Marcador pulsante
  - Tooltip com código

- **Legenda**
  - Ex: "Setor de Ciências Sociais (600–670)"

- **Controles**
  - Centralizar em mim
  - Ver foto da estante

### 3. Critérios de Aceitação
- **Dado** que estou no mapa  
- **Quando** vejo o código na estante  
- **Então** identifico corretamente a localização  

---

## 🎯 Destaque da Estante no Mapa

### 1. História de Usuário
**Como** Pedro Andrade  
**Quero** ver a estante destacada com corredor e lado  
**Para que** eu vá direto ao destino  

### 2. Detalhes da Tela
- **Header Sticky**
  - Código visível

- **Mapa**
  - Estante em cor vibrante
  - Pin indicando lado (A/B)

- **Card Inferior**
  - "Estante Encontrada: Corredor 14"
  - Instruções de posicionamento

- **Botão**
  - Orientação por bússola

### 3. Critérios de Aceitação
- **Dado** que estou no andar correto  
- **Quando** vejo o destaque  
- **Então** consigo ir direto à estante  

---

## 🧭 Informação Textual de Localização

### 1. História de Usuário
**Como** Pedro Andrade  
**Quero** ver uma hierarquia clara (Piso > Setor > Corredor > Estante)  
**Para que** eu confirme mentalmente minha rota  

### 2. Detalhes da Tela
- **Header**
  - Código de chamada

- **Card de Localização**
  - Setor (H2)
  - Corredor
  - Estante (destaque)

- **Checklist**
  - Suba ao 1º andar
  - Siga placas
  - Vá até a estante

- **Botões**
  - Lanterna / brilho
  - "Encontrei!"

### 3. Critérios de Aceitação
- **Dado** que visualizei o mapa  
- **Quando** leio as instruções  
- **Então** consigo navegar com segurança  

---

## ✅ Confirmação Final e Busca do Livro

### 1. História de Usuário
**Como** Pedro Andrade  
**Quero** ver a posição do livro na estante  
**Para que** eu encontre rapidamente  

### 2. Detalhes da Tela
- **Header**
  - "Você chegou à Estante"

- **Guia Visual**
  - Diagrama da estante
  - Destaque da prateleira

- **Etiqueta Digital**
  - Código ampliado

- **Resumo**
  - Título e autor

- **Botão**
  - "Encontrei o livro"

### 3. Critérios de Aceitação
- **Dado** que estou na estante correta  
- **Quando** consulto o guia  
- **Então** encontro o livro rapidamente  

---

## 🎯 Objetivo Geral
Reduzir carga cognitiva, ansiedade e dependência de interação social, permitindo que o usuário encontre o livro de forma **autônoma, rápida e segura**.