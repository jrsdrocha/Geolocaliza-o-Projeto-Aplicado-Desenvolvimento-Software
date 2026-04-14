## História de Jornada da Gestão - Dashboarding, Vendas e Tomada de decisão

### Visualiza o painel inicial com indicadores básicos de estoque e acervo → sente alívio ao ter uma visão geral do cenário.  
( Touchpoint — dashboard principal )

---

### • História de Usuário (Narrativa)

• Como Marina, a gerente estratégica, que precisa tomar decisões rápidas e embasadas em dados confiáveis.  
• Eu quero visualizar um dashboard inicial com indicadores claros de estoque, acervo e uso da biblioteca.  
• Para entender rapidamente o desempenho da operação e identificar oportunidades de melhoria sem precisar consolidar dados manualmente.

---

### • Detalhes da Tela (Informações na tela e Protótipo Conceitual)

Esta tela deve ser orientada a **tomada de decisão rápida**, com foco em clareza, priorização de informação e leitura em poucos segundos (scanability). O design deve reduzir esforço cognitivo e destacar insights acionáveis.

#### Estrutura Visual Otimizada para Mobile (Top-Down):

---

• **Header (Contexto e Controle):**  
- Título: “Dashboard”  
- Saudação contextual: “Olá, Marina”  
- Filtro de período (Hoje / Semana / Mês)  
- Ícone de configurações  

---

• **Resumo de Indicadores (KPIs principais — acima da dobra):**  
Cards horizontais (scrollável ou grid 2x2):  
- Total de livros cadastrados  
- Livros disponíveis  
- Livros indisponíveis / emprestados  
- % de acervo organizado corretamente  

→ Cada card com: número grande + label + variação (↑↓)

---

• **Seção: Performance do Acervo**  
- Gráfico simples (barra ou linha)  
- “Livros mais buscados”  
- “Livros menos acessados”  

→ Ajuda a identificar demanda vs. ociosidade

---

• **Seção: Organização do Acervo**  
- Indicador: “Livros fora do lugar”  
- Indicador: “Correções recentes realizadas”  
- Alerta visual (ex: vermelho/amarelo)  

→ Foco em eficiência operacional

---

• **Seção: Uso do Sistema (Comportamento do Usuário)**  
- Nº de buscas realizadas  
- % de sucesso na busca (livro encontrado)  
- Tempo médio para encontrar um livro  

→ Conecta operação com experiência do usuário final

---

• **Insights Rápidos (Destaque Inteligente):**  
- “Alta demanda por livros de X categoria”  
- “Estante Y apresenta baixa organização”  

→ Frases curtas orientadas à ação

---

• **Ações Rápidas (CTA):**  
- “Gerenciar Acervo”  
- “Ver Relatórios Detalhados”  
- “Ajustar Localizações”  

→ Botões com destaque visual

---

• **Feedback de Estado:**  
- Loading com skeleton  
- Mensagem de “Sem dados suficientes ainda” (fase MVP)  

---

### • Critérios de Aceitação (BDD — Behavior Driven Development)

#### Cenário 1: Visualização inicial do dashboard
• Dado que estou logada no sistema administrativo  
• Quando acesso o dashboard principal  
• Então devo visualizar os principais indicadores de estoque e acervo sem precisar rolar a tela  
• E os dados devem estar organizados de forma clara e legível  

---

#### Cenário 2: Filtro de período
• Dado que estou no dashboard  
• Quando seleciono um período (ex: “Semana”)  
• E aguardo a atualização  
• Então todos os indicadores e gráficos devem refletir os dados do período selecionado  

---

#### Cenário 3: Identificação de problemas no acervo
• Dado que existem livros fora do lugar  
• Quando visualizo a seção de organização  
• Então devo ver um indicador claro com destaque visual (ex: alerta)  
• E entender rapidamente que existe um problema a ser resolvido  

---

#### Cenário 4: Leitura de performance
• Dado que existem dados de uso do sistema  
• Quando visualizo a seção de performance  
• Então devo identificar facilmente quais livros têm maior e menor demanda  
• E usar essa informação para decisões estratégicas  

---

#### Cenário 5: Insights automáticos
• Dado que o sistema possui dados suficientes  
• Quando acesso o dashboard  
• Então devo visualizar insights automáticos destacados  
• E esses insights devem ser escritos de forma clara e acionável  

---

#### Cenário 6: Ação a partir do dashboard
• Dado que identifiquei um problema ou oportunidade  
• Quando clico em uma ação rápida (ex: “Gerenciar Acervo”)  
• Então devo ser direcionada para a tela correspondente  
• Sem fricção ou necessidade de navegação complexa  

---

#### Cenário 7: Performance e carregamento
• Dado que acesso o dashboard  
• Quando os dados estão sendo carregados  
• Então devo visualizar um estado de loading (skeleton)  
• E os dados devem carregar em até 3 segundos  

---

#### Cenário 8: Consistência e confiabilidade dos dados
• Dado que o sistema está integrado ao estoque  
• Quando visualizo os indicadores  
• Então os dados exibidos devem refletir o estado real do acervo  
• E não devem apresentar inconsistências entre telas  

---

#### Cenário 9: Usabilidade mobile
• Dado que estou utilizando o sistema em dispositivo móvel  
• Quando navego pelo dashboard  
• Então todos os elementos devem ser responsivos, legíveis e fáceis de interagir  
• E não deve haver necessidade de zoom ou esforço visual excessivo  

---

#### Cenário 10: Evolução do MVP
• Dado que o sistema ainda está em fase inicial  
• Quando não houver dados suficientes  
• Então devo visualizar mensagens orientativas  
• E entender que os insights serão aprimorados com o uso contínuo  
