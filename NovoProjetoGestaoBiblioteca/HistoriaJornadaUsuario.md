# 📱 Touchpoint — App / Totem de Acesso

## 1. História de Usuário (Narrativa)

- **Como** Lucas, o explorador indeciso, que acabou de entrar na biblioteca e não sabe por onde começar  
- **Eu quero** acessar rapidamente um sistema digital que me permita iniciar a busca e exploração de livros de forma imediata  
- **Para** começar minha jornada de descoberta com autonomia e encontrar livros sem perder tempo andando sem direção  

---

## 2. Detalhes da Tela (Informações na tela e Protótipo Conceitual)

### Nome da Tela
**Entrada / Início da Experiência**

### Estrutura Geral (Mobile First)

Layout vertical, limpo, com foco em ação imediata e compreensão instantânea.  

A hierarquia visual deve guiar o olhar de forma direta:  
**valor → ação**

---

### Elementos da Interface

#### 1. Header / Branding
- Logotipo da biblioteca (centralizado)  
- Espaçamento confortável  
- Sem menus ou distrações  

---

#### 2. Imagem / Ilustração Principal (Hero)
Ilustração leve ou imagem contextual:
- Pessoa encontrando livro  
- Elementos visuais de navegação (mapa, estante, localização)  

📌 **Objetivo:**
- Reduzir ansiedade  
- Comunicar descoberta guiada  

---

#### 3. Título Principal (H1 — Proposta de Valor)
**“Encontre livros sem se perder na biblioteca”**

- Fonte grande  
- Alto contraste  
- Leitura imediata (até 2 segundos)  
- Visível sem scroll  

---

#### 4. Subtítulo (H2 — Explicação do valor)
**“Busque, explore sugestões e vá direto até a estante com ajuda de um mapa.”**

- Complementa o título  
- Explica o funcionamento de forma simples  
- Reduz incerteza  

---

#### 5. Botão de Ação Principal (CTA)
🟢 **Botão: “Começar agora”**

**Características:**
- Largura ampla (full width ou quase)  
- Cor de destaque forte  
- Área touch-friendly  
- Posicionado na zona de alcance do polegar  
- Feedback visual ao toque  

📌 **Papel na UX:**
- Único caminho possível  
- Reduz tomada de decisão  
- Incentiva ação imediata  

---

#### 6. Microcopy de Apoio
Texto abaixo do botão:  

**“Comece em segundos e encontre o que procura mais rápido.”**

📌 **Função:**
- Reforçar rapidez  
- Reduzir hesitação  

---

#### 7. Comportamento do Sistema (invisível)
- Sessão iniciada automaticamente ao clicar no CTA  
- Geração de token de uso  
- Persistência temporária da navegação  

📌 **Importante:**
- Nenhuma ação adicional do usuário  
- Zero impacto cognitivo  

---

## Diretrizes de UX Aplicadas

- Redução total de fricção na entrada  
- Foco em uma única ação  
- Clareza imediata de valor  
- Interface sem distrações  
- Tempo de decisão mínimo (< 3 segundos)  
- Otimizado para uso em pé / ambiente físico  

---

## 3. Critérios de Aceitação (BDD — Behavior Driven Development)

### Cenário 1: Compreensão imediata da proposta
- **Dado que** Lucas acabou de entrar na biblioteca e acessa o app ou totem  
- **Quando** a tela inicial é carregada  
- **E** ele visualiza o conteúdo apresentado  
- **Então** ele deve entender rapidamente que pode:
  - Buscar livros  
  - Explorar sugestões  
  - Encontrar a localização dentro da biblioteca  

- **E** o título e o botão “Começar agora” devem estar visíveis sem necessidade de scroll  
- **E** a interface deve estar limpa, sem menus ou elementos que desviem a atenção  

---

### Cenário 2: Início da jornada
- **Dado que** Lucas deseja começar a explorar  
- **Quando** ele toca no botão “Começar agora”  
- **E** inicia a interação  
- **Então** o sistema deve:
  - Iniciar automaticamente uma sessão de uso  
  - Redirecioná-lo para a tela inicial com busca e recomendações  

- **E** a transição deve ocorrer de forma fluida e imediata  

---

### Cenário 3: Redução de hesitação
- **Dado que** Lucas está indeciso sobre como começar  
- **Quando** ele visualiza a tela de entrada  
- **E** lê a proposta de valor e o microcopy de apoio  
- **Então** ele deve sentir segurança para prosseguir  
- **E** tomar a decisão de iniciar sem dúvidas ou bloqueios  

---

## Resultado Esperado

Lucas sai do estado de desorientação para ação imediata em poucos segundos.

A experiência começa com:
- Clareza  
- Fluidez  
- Controle  

E estabelece a base para toda a jornada de descoberta dentro da biblioteca.
• Dado que encontrei um livro interessante  
• Quando clico em um item  
• Então devo ser direcionado para a tela de detalhes do livro  
• E manter contexto visual (animação/transição suave)  

---

# 📱 Touchpoint: Tela Inicial

## 1. História de Usuário (Narrativa)

- **Como** Lucas, o explorador indeciso, que entra na biblioteca sem saber exatamente o que procura e valoriza experiências rápidas e intuitivas  
- **Eu quero** visualizar uma tela inicial clara, com busca imediata, sugestões relevantes, categorias organizadas e promoções em destaque  
- **Para** descobrir rapidamente livros interessantes, aproveitar oportunidades e escolher um caminho sem ficar perdido dentro da biblioteca  

---

## 2. Detalhes da Tela (Informações na tela e Protótipo Conceitual)

### Nome da Tela
**Início / Explorar Biblioteca**

---

### Estrutura Geral (Mobile First)

Interface orientada à descoberta rápida, com forte hierarquia visual e foco em reduzir indecisão.  

A tela deve permitir ação em menos de **3 segundos** (buscar, explorar ou aproveitar promoções).

---

### Estrutura Visual Otimizada para Mobile (Top-Down)

#### 1. Header (fixo no topo)
- Ícone de menu (☰) ou logo da biblioteca  
- Título: **Biblioteca**  
- Ícone opcional: favoritos (⭐)  

---

#### 2. Campo de Busca (PRINCIPAL FOCO UX)
- Campo full width, com alto destaque visual  
- Placeholder:  
  **"Busque por título, autor ou tema..."**  
- Ícone de lupa (🔍)  

**Sugestões rápidas (chips):**
- Fantasia  
- Romance  
- Tecnologia  
- Autoajuda  

---

#### 3. Seção: Promoções (NOVO — ALTO VALOR DE NEGÓCIO)

**Subtítulo:** Destaques da biblioteca  

**Formato:** carrossel horizontal (cards grandes)

**Cada card contém:**
- Capa do livro (destaque visual forte)  
- Tag chamativa:
  - “Em destaque”  
  - “Leitura recomendada”  
  - “Semana especial”  
- Título do livro  
- Microcopy opcional:
  - “Seleção da equipe”  
  - “Alta procura”  
- Indicador visual (cor de destaque ou badge)  

👉 **Regras de UX importantes:**
- Máximo de 5–7 itens (curadoria, não volume)  
- Primeira dobra pode mostrar 1 card parcialmente visível (teaser de swipe)  
- Autoplay opcional (lento e não intrusivo)  

👉 **Objetivo:**
- Criar atalho decisório para Lucas  
- Inserir estratégia da biblioteca sem parecer propaganda  

---

#### 4. Seção: Descoberta Rápida

**Subtítulo:** Descubra algo agora  

**Formato:** carrossel horizontal  

- Mais populares 🔥  
- Tendências 📈  
- Escolhas da semana ⭐  

---

#### 5. Seção: Categorias

**Subtítulo:** Explore por categoria  

**Grid (2 colunas):**
- Ficção  
- Não-ficção  
- Romance  
- Fantasia  
- Negócios  
- Tecnologia  
- Biografias  
- Suspense  

---

#### 6. Seção: Novidades

**Subtítulo:** Novidades na biblioteca  

- Lista ou carrossel  
- Tag: “Novo”  

---

#### 7. Seção: Continue Explorando (opcional inteligente)

- “Baseado no que você viu”  
- “Você pode gostar”  

---

#### 8. Comportamento da Hierarquia (CRÍTICO)

**Ordem pensada para decisão:**
1. Busca (ação direta)  
2. Promoções (atalho curado)  
3. Descoberta (exploração guiada)  
4. Categorias (exploração estruturada)  

👉 Isso evita overload e direciona comportamento  

---

#### 9. Feedback Visual

- Skeleton loading nos cards  
- Scroll suave horizontal  
- Destaque visual ao tocar  
- Estados vazios amigáveis  

---

## 3. Critérios de Aceitação (BDD — Behavior Driven Development)

### Cenário 1: Visualização das promoções
- **Dado que** Lucas acessa a tela inicial  
- **Quando** a interface é carregada  
- **E** ele visualiza o conteúdo inicial da tela  
- **Então** ele deve ver a seção “Destaques da biblioteca” com itens promocionais em formato de carrossel  
- **E** os itens devem ser visualmente destacados em relação às demais seções  

---

### Cenário 2: Interação com promoções
- **Dado que** Lucas está explorando a tela inicial  
- **Quando** ele desliza horizontalmente a seção de promoções  
- **E** toca em um item promocional  
- **Então** o sistema deve direcioná-lo para a tela de detalhes do livro correspondente  
- **E** manter consistência visual com os demais fluxos  

---

### Cenário 3: Apoio à decisão rápida
- **Dado que** Lucas está indeciso sobre o que procurar  
- **Quando** ele visualiza as promoções destacadas  
- **Então** ele deve conseguir identificar rapidamente opções relevantes sem precisar buscar  
- **E** reduzir o tempo de decisão para iniciar a exploração  

---

### Cenário 4: Equilíbrio entre conteúdo e usabilidade
- **Dado que** a tela inicial contém múltiplas seções (busca, promoções, categorias, etc.)  
- **Quando** Lucas navega pela tela  
- **Então** nenhuma seção deve competir visualmente com o campo de busca  
- **E** a hierarquia deve manter clareza e escaneabilidade  

---

### Cenário 5: Performance e carregamento
- **Dado que** Lucas acessa o app em ambiente físico  
- **Quando** a tela inicial carrega  
- **Então** a seção de promoções deve carregar rapidamente ou exibir skeleton loading  
- **E** não deve bloquear a interação com as demais funcionalidades da tela  

---

## Resultado Esperado

Lucas consegue sair da indecisão para ação em poucos segundos.

A experiência oferece:
- Clareza  
- Rapidez  
- Direcionamento  

E equilibra descoberta, recomendação e autonomia na exploração da biblioteca.

---

# 📱 Touchpoint: Pesquisa Inteligente (Busca + Recomendações + Resultados)

---

## 1. História de Usuário (Narrativa)

- **Como** Lucas, o explorador indeciso, que não sabe exatamente o que quer e precisa de orientação rápida  
- **Eu quero** pesquisar livros de forma inteligente, podendo digitar termos, explorar sugestões automáticas e visualizar resultados relevantes imediatamente  
- **Para** encontrar livros interessantes com rapidez, sem precisar pensar muito ou navegar sem direção dentro da biblioteca  

---

## 2. Detalhes da Tela (Informações na tela e Protótipo Conceitual)

### Nome da Tela
**Pesquisa Inteligente**

---

## Estrutura Geral (Mobile First)

Interface dinâmica, reativa e orientada à intenção do usuário.  
A tela se adapta em tempo real ao comportamento:

- **Estado vazio → sugestões**
- **Digitando → recomendações inteligentes**
- **Após busca → resultados**

👉 Tudo acontece **na mesma tela**, sem quebra de fluxo.

---

## Estrutura Visual (Top-Down)

---

### 1. Header (fixo)
- Ícone de voltar (←)  
- Campo de busca integrado (sempre ativo)  

---

### 2. Campo de Busca (PRINCIPAL FOCO UX)

- Campo full width  
- Placeholder:  
  **"Busque por título, autor, tema ou categoria..."**  
- Ícone de lupa (🔍)  
- Botão limpar (✕) ao digitar  

👉 **Comportamento:**
- Auto foco ao entrar na tela  
- Sugestões aparecem em tempo real (autocomplete)  

---

# ESTADO 1: Sem digitação (Descoberta Assistida)

---

### 3. Sugestões Rápidas (chips)
- Fantasia  
- Romance  
- Suspense  
- Desenvolvimento pessoal  
- Tecnologia  

---

### 4. Seção: Buscas Populares

**Subtítulo:** Pessoas estão buscando

- “Livros de fantasia”  
- “Romance leve”  
- “Livros rápidos de ler”  

👉 Ajuda Lucas a **começar sem pensar**

---

### 5. Seção: Recomendações Inteligentes

**Subtítulo:** Sugestões para você

Formato: lista/carrossel

Baseado em:
- popularidade  
- contexto geral (sem login)  
- comportamento agregado  

---

# ESTADO 2: Durante digitação (Busca Assistida)

---

### 6. Sugestões Dinâmicas (Autocomplete Inteligente)

Resultados agrupados:

#### a) Sugestões diretas
- Termos próximos ao digitado  

#### b) Livros
- Capa pequena  
- Título  
- Autor  

#### c) Categorias
- Ex: “Fantasia”, “Negócios”  

#### d) Autores
- Nome do autor  

👉 Organização por relevância e intenção  

---

# ESTADO 3: Resultado da Busca

---

### 7. Header Secundário de Contexto

Texto:
**Resultados para "fantasia"**

Botões:
- Filtrar  
- Ordenar  

---

### 8. Lista de Resultados (PRINCIPAL ÁREA)

Formato: lista vertical escaneável

Cada item contém:
- Capa do livro (thumbnail)  
- Título (destaque)  
- Autor  
- Categoria/tag  
- Indicador de disponibilidade:
  - 🟢 Disponível  
  - 🔴 Indisponível  

👉 Interação:
- Clique leva para detalhe do livro  

---

### 9. Filtros (Bottom sheet ou topo)

Opções:
- Categoria  
- Disponibilidade  
- Popularidade  
- Novidades  

---

# 10. Estado Vazio (UX CRÍTICO)

Caso não encontre resultados:

### Mensagem:
**"Não encontramos resultados para sua busca"**

### Sugestões:
- Ver categorias  
- Explorar recomendações  
- Tentar outro termo  

---

## 11. Feedback Visual

- Loading instantâneo (debounce leve)  
- Skeleton na lista  
- Destaque ao tocar  
- Transições suaves  

---

# 3. Critérios de Aceitação (BDD — Behavior Driven Development)

---

## Cenário 1: Acesso à pesquisa
- **Dado que** Lucas acessa a funcionalidade de busca  
- **Quando** a tela de pesquisa é aberta  
- **E** o campo de busca recebe foco automaticamente  
- **Então** ele deve conseguir começar a digitar imediatamente  
- **E** visualizar sugestões mesmo sem inserir texto  

---

## Cenário 2: Busca assistida durante digitação
- **Dado que** Lucas começa a digitar um termo (ex: “fan”)  
- **Quando** o sistema processa a entrada  
- **E** exibe sugestões em tempo real  
- **Então** ele deve visualizar sugestões relevantes (termos, livros, categorias)  
- **E** conseguir selecionar uma opção sem digitar completamente  

---

## Cenário 3: Exibição de resultados
- **Dado que** Lucas realiza uma busca completa  
- **Quando** os resultados são carregados  
- **E** a lista é exibida  
- **Então** o sistema deve apresentar livros relevantes com informações básicas  
- **E** permitir navegação direta para o detalhe da obra  

---

## Cenário 4: Redução de indecisão
- **Dado que** Lucas não sabe exatamente o que buscar  
- **Quando** ele acessa a tela sem digitar  
- **E** visualiza sugestões e buscas populares  
- **Então** ele deve conseguir iniciar uma exploração com baixo esforço cognitivo  
- **E** evitar sensação de bloqueio ou indecisão  

---

## Cenário 5: Performance e fluidez
- **Dado que** Lucas está utilizando o app em tempo real dentro da biblioteca  
- **Quando** ele digita ou interage com a busca  
- **Então** o sistema deve responder rapidamente (sem delays perceptíveis)  
- **E** manter uma experiência fluida e contínua  

---

## Cenário 6: Tratamento de erro (sem resultados)
- **Dado que** Lucas realiza uma busca sem correspondência  
- **Quando** nenhum resultado é encontrado  
- **E** o estado vazio é exibido  
- **Então** o sistema deve sugerir caminhos alternativos (categorias, recomendações)  
- **E** evitar frustração ou abandono da jornada  

---

## Resultado Esperado

Lucas passa de indecisão para descoberta ativa em segundos.

A experiência garante:
- Orientação contínua  
- Baixo esforço cognitivo  
- Respostas imediatas  
- Fluxo contínuo de exploração  

E transforma a busca em um **motor de descoberta guiada dentro da biblioteca**.

---


# 📚 Visualização do Conteúdo Interessado (Detalhe do Livro)

---

## 1. História de Usuário (Narrativa)

- **Como** Lucas, o explorador indeciso, jovem leitor que busca descobertas rápidas sem precisar planejar antes  
- **Eu quero** visualizar uma tela de detalhe do livro com informações claras, atrativas e um botão direto para localizar o livro na biblioteca  
- **Para** decidir rapidamente se esse livro me interessa e iniciar o processo de encontrá-lo sem precisar navegar por muitas telas ou me perder na biblioteca  

---

## 2. Detalhes da Tela (Informações na tela e Protótipo Conceitual)

### Nome da Tela
**Detalhe do Livro (Visualização do Conteúdo)**

---

## Estrutura Geral (Mobile First)

Interface escaneável, focada em decisão rápida e redução de fricção entre **descoberta → ação**.

---

## 1. Header (fixo no topo)

- Ícone de voltar (←)  
- Título da página: **“Detalhes do Livro”**  
- Ícone opcional: salvar/favoritar (☆)  

---

## 2. Card Principal do Livro (Hero Content)

- Capa do livro (destaque visual central)  
- Título do livro (grande e forte)  
- Autor  
- Categoria / gênero (chip visual)  
- Avaliação ou popularidade (opcional: ★★★★☆)  

---

## 3. Seção: Informações Rápidas

### Subtítulo:
**“Sobre este livro”**

- Sinopse curta (máx. 3–5 linhas)  
- Botão: **“ver mais”** (expande conteúdo)  

**Tags de interesse:**
- Ficção  
- Romance  
- Mistério  
- Best-seller  

---

## 4. Seção: Destaques de Interesse

### Subtítulo:
**“Por que este livro pode te interessar”**

Recomendações rápidas baseadas em comportamento:
- “Semelhante a livros populares”  
- “Alta taxa de leitura”  
- “Recomendado pela biblioteca”  

Cards horizontais opcionais:
- Livros similares  
- Sugestões relacionadas  

---

## 5. Seção: Disponibilidade e Localização

### Subtítulo:
**“Disponibilidade”**

Status:
- 🟢 Disponível na biblioteca  
- 🔴 Indisponível (reserva futura)  

Informação simplificada:
- “Disponível para retirada na biblioteca”  

📌 Sem mapa ou rota nesta etapa

---

## 6. Ação Principal (FOCO UX)

Botão primário (CTA):

**“Encontrar na Biblioteca”**  
ou  
**“Ver onde encontrar”**

💡 Função:
- Inicia fluxo de localização do livro  
- Não exibe mapa nesta etapa  

---

## 7. Ação Secundária

Botões alternativos:
- “Explorar livros similares”  
- “Voltar às recomendações”  

---

## 8. Feedback Visual (estado da ação)

Ao clicar no CTA:
- Loading leve ou transição suave  
- Texto de feedback:  
  **“Preparando localização do livro...”**  

---

# 3. Critérios de Aceitação (BDD — Behavior Driven Development)

---

## Cenário 1: Visualização do detalhe do livro

- **Dado que** Lucas navegou pela lista de resultados ou recomendações da biblioteca  
- **Quando** ele seleciona um livro específico  
- **Então** o sistema deve exibir a tela de detalhe com capa, título, autor e sinopse de forma clara e hierarquizada  
- **E** permitir leitura rápida em menos de 5 segundos de escaneabilidade  
- **E** apresentar a ação principal “Encontrar na Biblioteca” visível acima da dobra da tela  

---

## Cenário 2: Intenção de localização

- **Dado que** Lucas está na tela de detalhe do livro  
- **Quando** ele toca no botão “Encontrar na Biblioteca”  
- **Então** o sistema deve iniciar o fluxo de localização do livro  
- **E** preparar a próxima etapa da jornada (visualização de localização)  
- **E** não exibir mapa nesta etapa, apenas transição para o próximo passo  

---

## Cenário 3: Continuidade de exploração

- **Dado que** Lucas está avaliando um livro  
- **Quando** ele não deseja prosseguir com a localização  
- **Então** ele pode acessar recomendações de livros similares  
- **E** continuar explorando novos conteúdos sem perda de contexto  

---

## Resultado Esperado

Lucas consegue transformar interesse em ação com mínimo esforço cognitivo.

A experiência garante:
- Decisão rápida  
- Clareza de informação  
- Caminho direto para ação  
- Continuidade de exploração sem fricção  

E reduz a distância entre **descobrir um livro → encontrar fisicamente na biblioteca**.

----
# 🗺️ Visualização de Localização do Livro com Mapa Digital e Instruções

---

## 1. História de Usuário (Narrativa)

- **Como** Lucas, o explorador indeciso, que entra na biblioteca sem um plano claro e se sente facilmente perdido entre corredores e estantes  
- **Eu quero** visualizar em um mapa digital interativo a localização exata da estante do livro selecionado, com apoio de instruções em texto e áudio para me guiar até o ponto correto  
- **Para** encontrar o livro com rapidez e segurança, sem depender de orientação manual ou circular aleatoriamente pela biblioteca, mantendo uma experiência fluida e sem frustração  

---

## 2. Detalhes da Tela (Informações na tela e Protótipo Conceitual)

### Nome da Tela
**Mapa Digital de Localização do Livro**

---

## Estrutura Geral (Mobile First)

Interface orientada à orientação espacial rápida, com foco em:
- clareza visual  
- leitura imediata  
- redução de esforço cognitivo  

---

## 1. Header (fixo no topo)

- Ícone de voltar (←)  
- Título da página: **“Onde encontrar este livro”**  

---

## 2. Card Resumido do Livro (contexto rápido)

- Miniatura da capa (à esquerda)  
- Título do livro (destaque principal)  
- Autor  
- Categoria ou gênero (secundário)  
- Status de disponibilidade (ex: 🟢 disponível)  

---

## 3. Seção Principal: Mapa Digital da Biblioteca (FOCO UX)

### Subtítulo:
**“Localização exata na biblioteca”**

### Elementos do mapa:
- Mapa esquemático simplificado da biblioteca  
- Estante do livro destacada (marcador/ponto iluminado)  
- Setor correspondente destacado por cor  
- Caminho sugerido até a estante (linha visual simplificada, opcional)  
- Indicador “📍 Você está aqui” (quando disponível)  

📌 Objetivo:
Permitir compreensão instantânea da localização sem necessidade de interação complexa.

---

## 4. Instruções de Navegação (Texto + Voz)

### Subtítulo:
**“Como chegar até o livro”**

### Instruções em texto (passo a passo):
- “Siga até o corredor C”  
- “Vire à direita no setor de literatura”  
- “Procure a estante H3”  

### Controles:
- Botão: **“Ouvir instruções em voz” 🎧**  
- Botão: **“Repetir instruções”**  

📌 Microcopy:
“Você pode seguir pelo mapa ou pelas instruções guiadas”

---

## 5. Informações de Localização Detalhada

Box destacado:

- **Andar:** 2º andar  
- **Setor:** Literatura Contemporânea  
- **Corredor:** C  
- **Estante:** H3  

---

## 6. Ação Principal (CTA)

Botão grande e fixo na base da tela:

**“Iniciar rota até o livro”**

### Ação secundária:
- “Ver novamente os detalhes do livro”  

---

## 7. Feedback Visual

- Animação leve indicando direção no mapa  
- Estante alvo com destaque pulsante  
- Atualização visual conforme progresso do usuário (opcional em tempo real)  

---

## 3. Critérios de Aceitação (BDD — Behavior Driven Development)

---

## Cenário 1: Acesso ao mapa de localização

- **Dado que** Lucas selecionou um livro na lista de resultados ou nos detalhes do livro  
- **Quando** ele clica na opção “Ver no mapa” ou equivalente  
- **Então** o sistema deve exibir um mapa digital da biblioteca com a localização exata da estante destacada  
- **E** apresentar claramente o setor e a estante correspondente ao livro selecionado  
- **E** permitir visualização sem necessidade de zoom ou interação complexa inicial  

---

## Cenário 2: Orientação guiada por instruções

- **Dado que** Lucas está visualizando o mapa digital da biblioteca  
- **Quando** ele acessa a seção de instruções de navegação  
- **Então** o sistema deve exibir instruções em texto simples e escaneável  
- **E** permitir reprodução das instruções por áudio com um único toque  
- **E** garantir que as instruções correspondam ao caminho até a estante do livro  

---

## Cenário 3: Ação de navegação até o livro

- **Dado que** Lucas compreendeu a localização do livro no mapa  
- **Quando** ele toca no botão “Iniciar rota até o livro”  
- **Então** o sistema deve destacar novamente o caminho visual no mapa  
- **E** manter a estante como ponto final claramente identificado  
- **E** reforçar a orientação até o destino sem ambiguidade  

---

## Cenário 4: Clareza e redução de fricção

- **Dado que** Lucas utiliza o mapa pela primeira vez  
- **Quando** ele analisa a tela de localização  
- **Então** ele deve conseguir identificar a estante correta em menos de 5 segundos  
- **E** compreender o caminho sem necessidade de ajuda externa  
- **E** sentir segurança para se deslocar de forma independente dentro da biblioteca  

---

## Resultado Esperado

Lucas sai da etapa de descoberta digital e chega ao espaço físico da biblioteca com:

- orientação clara  
- mínima carga cognitiva  
- confiança de navegação  
- ausência de frustração  

A experiência fecha o ciclo completo:

**Busca → Descoberta → Decisão → Localização física do livro**
