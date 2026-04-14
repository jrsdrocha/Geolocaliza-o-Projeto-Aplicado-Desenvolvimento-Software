## História de Usuário — Tela Inicial (Descoberta e Busca)

Visualiza a tela inicial com busca e sugestões de livros → sente curiosidade e percebe que pode explorar opções facilmente.  
( Touchpoint — tela inicial )

---

### • História de Usuário (Narrativa)  
• Como Lucas, o leitor indeciso, que usa o celular constantemente e se sente perdido em ambientes grandes.  
• Eu quero ao abrir o aplicativo visualizar uma tela inicial simples, com busca destacada e sugestões de livros relevantes.  
• Para conseguir descobrir rapidamente opções interessantes sem precisar pensar muito ou pedir ajuda.

---

### • Detalhes da Tela (Informações na tela e Protótipo Conceitual)  

• Esta tela deve priorizar **descoberta rápida + baixa fricção cognitiva**, com foco em guiar o usuário indeciso sem exigir esforço.

#### Estrutura Visual Otimizada para Mobile (Top-Down):

• **Header/Branding:**  
Logo simples da biblioteca + ícone de localização (indicando que ele está dentro do espaço físico).

• **Barra de Busca (Elemento Principal - Above the Fold):**  
Campo grande e central com placeholder inteligente.  
Texto: *“Buscar livros, autores ou temas…”*  
Ícone de lupa + sugestão de autocomplete.

• **Sugestões Rápidas (Chips clicáveis):**  
Tags como:  
• “Ficção”  
• “Romance”  
• “Tecnologia”  
• “Autoajuda”  

→ Reduz esforço de decisão.

• **Seção: “Mais populares”**  
Carrossel horizontal com capas grandes.  
Exibe: capa + título curto.

• **Seção: “Novidades”**  
Lista ou carrossel com destaque visual (badge “Novo”).

• **Seção: “Recomendados para você” (MVP simples baseado em popularidade)**  
Sugestões genéricas inteligentes.

• **CTA Secundário Sutil:**  
Botão ou ícone: “Explorar no mapa”.

• **Feedback Visual:**  
Animações leves ao carregar conteúdos (skeleton loading).

• **Acessibilidade:**  
• Alto contraste  
• Fontes legíveis  
• Áreas de toque grandes  

---

### • Critérios de Aceitação (BDD — Behavior Driven Development)  

#### • Cenário 1: Primeira visualização da tela inicial  
• Dado que sou Lucas acessando o sistema dentro da biblioteca  
• Quando a tela inicial carregar  
• Então devo visualizar imediatamente a barra de busca sem precisar rolar a tela  
• E devo ver pelo menos uma seção de sugestões (ex: “Mais populares”) visível  

---

#### • Cenário 2: Exploração sem digitar (comportamento indeciso)  
• Dado que não sei exatamente o que procurar  
• Quando visualizo as sugestões de categorias ou livros  
• Então devo conseguir clicar em qualquer sugestão com apenas um toque  
• E devo ser direcionado para uma lista de livros relacionados  

---

#### • Cenário 3: Clareza e redução de fricção  
• Dado que estou me sentindo perdido na biblioteca  
• Quando olho para a tela inicial  
• Então devo entender em menos de 3 segundos como começar (buscar ou explorar)  
• E não devo encontrar menus complexos ou excesso de informações  

---

#### • Cenário 4: Performance e feedback  
• Dado que estou usando o app em ambiente físico (possível internet instável)  
• Quando a tela inicial carrega  
• Então os elementos devem aparecer progressivamente (skeleton/loading)  
• E o tempo de carregamento inicial deve ser ≤ 2 segundos  

---

#### • Cenário 5: Engajamento com conteúdo  
• Dado que estou explorando livros sugeridos  
• Quando deslizo os carrosséis  
• Então a navegação deve ser fluida e responsiva  
• E devo conseguir identificar facilmente capas e títulos  

---

#### • Cenário 6: Continuidade da jornada  
• Dado que encontrei um livro interessante  
• Quando clico em um item  
• Então devo ser direcionado para a tela de detalhes do livro  
• E manter contexto visual (animação/transição suave)  

---
