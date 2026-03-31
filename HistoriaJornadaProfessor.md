# Busca rápida de obra no catálogo com localização física

## 1. História de Usuário (Narrativa)

- **Como** Regis, professor de história, apressado, estudioso e que precisa se manter constantemente atualizado  
- **Eu quero** visualizar rapidamente a localização física detalhada (andar, setor e estante) de uma obra selecionada no catálogo digital  
- **Para** encontrar o livro com precisão dentro da biblioteca, evitando perda de tempo durante minha rotina corrida de pesquisa  

---

## 2. Detalhes da Tela (Informações na tela e Protótipo Conceitual)

**Nome da Tela:** Detalhe da Obra com Localização  

### Estrutura Geral (Mobile First)
Layout vertical, escaneável, com foco em leitura rápida e hierarquia clara da informação.

### Elementos da Interface

#### 1. Header (fixo no topo)
- Ícone de voltar (←)
- Título da página: **Detalhes da Obra**

#### 2. Card da Obra (destaque visual)
- Capa do livro (thumbnail à esquerda)
- Título da obra (negrito, destaque)
- Autor(es)
- Ano de publicação (opcional, menor destaque)

#### 3. Seção: Informações Gerais
- Subtítulo: **Sobre a obra**
- Descrição breve ou sinopse  
  - Máx. 3 linhas com opção **“ver mais”**

#### 4. Seção: Localização na Biblioteca (PRINCIPAL FOCO UX)
- Subtítulo: **Onde encontrar**
- Ícone visual de localização 📍
- Informações organizadas em lista clara:
  - **Andar:** Ex: 2º andar  
  - **Setor:** Ex: História Moderna  
  - **Estante:** Ex: Estante H3  
- Destaque visual:
  - Box com fundo contrastante para rápida identificação

#### 5. Mapa Simplificado (opcional — recomendado)
- Mini mapa esquemático da biblioteca com ponto destacado
- Botão: **Ver no mapa completo**

#### 6. Ações Rápidas (botões)
- Botão primário: **Traçar rota até o livro**
- Botão secundário: **Salvar nos favoritos**

#### 7. Feedback Visual
- Indicador de disponibilidade:
  - 🟢 Disponível  
  - 🔴 Indisponível  

---

## 3. Critérios de Aceitação (BDD — Behavior Driven Development)

- **Dado que** Regis acessou o sistema da biblioteca e realizou uma busca por título, autor ou assunto  
- **Quando** ele seleciona uma obra específica na lista de resultados  
- **E** acessa a tela de detalhes da obra  
- **Então** o sistema deve exibir de forma clara e destacada a localização completa (andar, setor e estante)  
- **E** apresentar essas informações no topo da hierarquia visual da tela  
- **E** permitir rápida leitura em menos de 3 segundos (escaneabilidade)  
- **E** oferecer opção de visualização em mapa ou rota dentro da biblioteca  
- **E** indicar o status de disponibilidade da obra  
- **E então** Regis consegue identificar rapidamente onde está o livro e seguir diretamente até ele sem fricção ou dúvidas

# Visualização da localização da obra no mapa da biblioteca

## 1. História de Usuário (Narrativa)

- **Como** Regis, professor de história, apressado, estudioso e que precisa se manter constantemente atualizado  
- **Eu quero** visualizar em um mapa digital interno da biblioteca a localização exata da estante da obra selecionada  
- **Para** ir diretamente ao local correto com segurança, otimizando meu tempo de pesquisa  

---

## 2. Detalhes da Tela (Informações na tela e Protótipo Conceitual)

**Nome da Tela:** Mapa da Biblioteca com Localização da Obra  

### Estrutura Geral (Mobile First)
Interface visual, limpa e interativa, com foco em orientação espacial rápida e mínima carga cognitiva.

### Elementos da Interface

#### 1. Header (fixo no topo)
- Ícone de voltar (←)
- Título da página: **Mapa da Biblioteca**

#### 2. Card Resumido da Obra (fixo ou colapsável)
- Miniatura da capa
- Título da obra
- Autor
- Localização resumida:
  - Ex: 2º andar • História Moderna • Estante H3

#### 3. Área Principal: Mapa Interativo
- Mapa esquemático da biblioteca (visão simplificada)
- Elementos visuais:
  - Setores identificados por cores
  - Corredores e áreas de circulação
  - Indicador de “Você está aqui” (caso disponível)
- Destaque visual da localização:
  - Ponto pulsante ou marcador destacado na estante correta
  - Setor destacado com cor diferenciada

#### 4. Legenda do Mapa
- Cores dos setores
- Ícones utilizados (ex: localização, estante, entrada)

#### 5. Controles de Navegação
- Zoom (+ / -)
- Botão: **Centralizar localização da obra**
- Botão: **Mostrar minha localização** (se disponível)

#### 6. Ação Principal
- Botão fixo (sticky): **Traçar rota até a estante**

#### 7. Feedback Visual
- Animação leve indicando o caminho sugerido (linha tracejada ou contínua)
- Destaque progressivo da rota

---

## 3. Critérios de Aceitação (BDD — Behavior Driven Development)

- **Dado que** Regis está na tela de detalhes de uma obra  
- **Quando** ele clica na ação **“Ver no mapa”**  
- **E** acessa a tela de mapa da biblioteca  
- **Então** o sistema deve exibir um mapa digital com a estrutura da biblioteca  
- **E** destacar visualmente o setor e a estante onde a obra está localizada  
- **E** apresentar a localização de forma clara, com contraste e fácil identificação  
- **E** permitir interação com o mapa (zoom e navegação)  
- **E** oferecer a opção de traçar uma rota até o local da estante  
- **E então** Regis consegue se orientar rapidamente e ir diretamente ao ponto correto sem dúvidas ou retrabalho

# Identificação rápida da estante a partir do código de chamada

## 1. História de Usuário (Narrativa)

- **Como** Regis, professor de história, apressado, estudioso e que precisa se manter constantemente atualizado  
- **Eu quero** visualizar e interpretar rapidamente o código de chamada da obra junto com sua correspondência física na estante  
- **Para** confirmar com segurança que estou no local correto sem perder tempo procurando entre várias prateleiras  

---

## 2. Detalhes da Tela (Informações na tela e Protótipo Conceitual)

**Nome da Tela:** Identificação da Estante por Código de Chamada  

### Estrutura Geral (Mobile First)
Layout orientado à ação imediata, com foco em leitura rápida, validação visual e redução de ambiguidade no ambiente físico.

### Elementos da Interface

#### 1. Header (fixo no topo)
- Ícone de voltar (←)
- Título da página: **Localização da Estante**

#### 2. Card da Obra (resumo essencial)
- Miniatura da capa
- Título da obra
- Autor
- Código de chamada (em destaque visual forte)

#### 3. Seção: Código de Chamada (PRINCIPAL FOCO UX)
- Subtítulo: **Código de chamada**
- Código exibido em destaque (tipografia monoespaçada, alto contraste)
  - Ex: **HIS 940.2 R344h**
- Botão: **Copiar código**
- Microtexto de apoio:
  - “Use este código para localizar o livro na estante”

#### 4. Seção: Como encontrar na estante
- Subtítulo: **Como localizar**
- Instruções objetivas e escaneáveis:
  - Ordem de organização (ex: numérica e alfabética)
  - Exemplo visual de leitura do código
- Destaque para:
  - Primeira parte (assunto)
  - Segunda parte (numeração)
  - Terceira parte (autor)

#### 5. Seção: Localização Física Complementar
- Informações:
  - **Andar:** 2º andar  
  - **Setor:** História  
  - **Corredor:** C  
  - **Estante:** H3  

#### 6. Indicador Visual de Confirmação (in loco)
- Mensagem: **“Você está na estante correta?”**
- Botões:
  - ✅ Sim, encontrei  
  - ❌ Não, preciso de ajuda  

#### 7. Ação de Apoio
- Botão secundário:
  - **Ver no mapa novamente**

#### 8. Feedback Visual
- Uso de cores e ícones para reforçar correspondência:
  - Código ↔ Estante
- Possível uso de QR code na estante (integração futura)

---

## 3. Critérios de Aceitação (BDD — Behavior Driven Development)

- **Dado que** Regis acessou a tela de detalhes de uma obra  
- **Quando** ele visualiza o código de chamada exibido  
- **E** se desloca fisicamente até a estante indicada  
- **Então** o sistema deve apresentar o código de forma clara, legível e destacada  
- **E** explicar como interpretar o código para localização correta  
- **E** exibir as informações complementares de localização (andar, setor, corredor e estante)  
- **E** permitir que Regis valide rapidamente se está no local correto  
- **E** oferecer suporte adicional caso ele não encontre a obra (ex: voltar ao mapa)  
- **E então** Regis consegue identificar com precisão a estante correta e localizar o livro sem esforço ou confusão


# Validação da localização das obras no protótipo

## 1. História de Usuário (Narrativa)

- **Como** Regis, professor de história, apressado, estudioso e que precisa se manter constantemente atualizado  
- **Eu quero** validar se a localização exibida no sistema corresponde corretamente à posição real da obra na biblioteca  
- **Para** confiar que a ferramenta é precisa e que irá me poupar tempo nas próximas pesquisas  

---

## 2. Detalhes da Tela (Informações na tela e Protótipo Conceitual)

**Nome da Tela:** Validação da Localização da Obra  

### Estrutura Geral (Mobile First)
Interface simples, objetiva e orientada a feedback rápido, reduzindo esforço cognitivo e incentivando validação imediata após a ação física.

### Elementos da Interface

#### 1. Header (fixo no topo)
- Ícone de voltar (←)
- Título da página: **Confirmar Localização**

#### 2. Card da Obra (contexto rápido)
- Miniatura da capa
- Título da obra
- Autor
- Código de chamada

#### 3. Seção: Localização Informada pelo Sistema
- Subtítulo: **Localização exibida**
- Informações:
  - **Andar:** 2º andar  
  - **Setor:** História  
  - **Corredor:** C  
  - **Estante:** H3  

#### 4. Seção: Validação do Usuário (PRINCIPAL FOCO UX)
- Pergunta central (destaque):
  - **“Você encontrou o livro exatamente nesta localização?”**

- Opções de resposta (botões grandes, touch-friendly):
  - ✅ **Sim, estava correto**
  - ⚠️ **Parcialmente correto**
  - ❌ **Não estava correto**

#### 5. Feedback Qualitativo (condicional)
- Exibido se resposta ≠ “Sim”
- Campo de entrada:
  - Placeholder: *“Descreva o que estava diferente…”*
- Sugestões rápidas (chips selecionáveis):
  - Estante incorreta
  - Setor errado
  - Dificuldade em encontrar
  - Mapa confuso

#### 6. Indicador de Confiança
- Microcopy:
  - “Seu feedback ajuda a melhorar a precisão do sistema”

#### 7. Ação Principal
- Botão: **Enviar avaliação**

#### 8. Feedback Pós-envio
- Mensagem de sucesso:
  - “Obrigado! Sua contribuição melhora a experiência de todos”
- Opção:
  - **Buscar outro livro**

---

## 3. Critérios de Aceitação (BDD — Behavior Driven Development)

- **Dado que** Regis utilizou o sistema para localizar uma obra na biblioteca  
- **Quando** ele chega fisicamente até a estante indicada  
- **E** acessa a tela de validação da localização  
- **Então** o sistema deve apresentar a localização previamente informada de forma clara  
- **E** permitir que Regis avalie rapidamente a precisão da informação  
- **E** oferecer opções simples e rápidas de feedback (correto, parcial ou incorreto)  
- **E** permitir detalhamento adicional em caso de inconsistência  
- **E** registrar o feedback para melhoria contínua do sistema  
- **E então** Regis sente confiança crescente na ferramenta ao perceber que sua experiência contribui para torná-la mais precisa e eficiente  
