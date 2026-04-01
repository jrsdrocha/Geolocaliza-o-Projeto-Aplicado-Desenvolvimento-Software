# 📘 User Story — Assistente de Localização (Modo Funcionário)

---

## 1. 🧾 História de Usuário (Narrativa)

- **Como:** Jonas Lima (Funcionário Otimizador de Fluxo)  
- **Eu quero:** uma interface de consulta rápida com geração de QR Code de rota compartilhável  
- **Para:** direcionar usuários para o autoatendimento em demandas de localização de obras raras, eliminando a necessidade de acompanhá-los fisicamente até as estantes  

---

## 2. 🖥️ Detalhes da Tela

### 🏷️ Título da Tela
**Assistente de Localização (Modo Funcionário)**

### 📝 Subtítulo
> "Busque a obra para gerar a rota de autonomia do usuário."

---

### 🔍 Campo de Entrada (Busca)
- Input de texto com ícone de lupa  
- Permite busca por:
  - Título  
  - Autor  
  - Código de Chamada  

---

### 📚 Card de Resultado da Obra
- **Título da Obra** em destaque  
- **Badge de Status:** "Disponível - Acervo de Obras Raras"  
- **Informação Geográfica:**  
  - Piso 2  
  - Setor B  
  - Estante 14  

---

### 🎯 Componente de Saída Principal (Call to Action)
- **Botão:** "Gerar QR Code de Rota"  
- **Ação:**  
  - Ao clicar, abre-se um **modal** com um QR Code dinâmico  
  - O usuário pode escanear o código para abrir o mapa no próprio celular  

---

### 🎨 Estrutura Visual
- Layout limpo (**Clean UI**)  
- Alto contraste para leitura rápida em ambientes de balcão  
- Botões grandes (facilitam o toque e agilizam o atendimento)  

---

## 3. ✅ Critérios de Aceitação (BDD — Behavior Driven Development)

### 🎬 Cenário: Direcionamento bem-sucedido de usuário para obra rara

- **Dado que:**  
  Eu (Jonas) estou autenticado no sistema de gestão da biblioteca e acessei a aba **"Assistente de Rota"**  

- **Quando:**  
  Preencho o nome da obra rara solicitada pelo usuário no campo de busca  

- **E:**  
  Seleciono a obra correta na lista de resultados e clico em **"Gerar QR Code"**  

- **Então:**  
  O sistema deve exibir um QR Code na tela do meu dispositivo  

- **E:**  
  Ao ser lido pelo usuário, o QR Code deve abrir automaticamente o mapa interativo com a rota traçada do balcão até a estante 14  

- **E:**  
  O sistema deve registrar que o atendimento foi convertido em **"Autoatendimento Autônomo"** para fins de métricas de produtividade  

---

# 🎯 Documentação UX/UI — Jornadas de Jonas Lima

Como um UX/UI Designer sênior, apresento a documentação detalhada para os touchpoints das jornadas de Jonas Lima, focando em eficiência operacional e redução de fricção no atendimento.

---

## 🔎 Jornada 2: Consultar

### 1. 🧾 História de Usuário (Narrativa)

- **Como:** Jonas Lima (Funcionário Otimizador de Fluxo)  
- **Eu quero:** visualizar o status de disponibilidade e a localização exata da obra em uma única tela de consulta  
- **Para:** validar rapidamente se o livro está na estante antes de iniciar qualquer procedimento de orientação, garantindo agilidade no balcão  

---

### 2. 🖥️ Detalhes da Tela

- **Título da Tela:** Detalhes do Acervo  
- **Header:** Barra de busca persistente no topo para correções rápidas  

#### 📊 Indicador de Status
- Badge de alto contraste:
  - Verde: "Disponível"  
  - Vermelho: "Emprestado"  

#### 📚 Dados da Obra
- Título em negrito  
- Autor  
- Edição  
- Número de Chamada em destaque  

#### 📍 Painel de Localização
- Card contendo:
  - Piso  
  - Setor  
  - Corredor  
- Ícone de pin de mapa  

---

### 3. ✅ Critérios de Aceitação (BDD)

- **Dado que:**  
  Realizei a busca por uma obra específica no catálogo integrado  

- **Quando:**  
  Acesso a tela de detalhes da obra  

- **E:**  
  Observo o indicador de status como disponível  

- **Então:**  
  O sistema deve exibir imediatamente o botão **"Ver no Mapa"**  

- **E:**  
  Deve apresentar as coordenadas físicas da estante para prosseguimento do atendimento  

---

## 🗺️ Jornada 3: Apresentar

### 1. 🧾 História de Usuário (Narrativa)

- **Como:** Jonas Lima (Funcionário Otimizador de Fluxo)  
- **Eu quero:** alternar a visualização para um mapa interativo simplificado do andar  
- **Para:** mostrar visualmente ao usuário onde ele se encontra e para onde deve ir, reduzindo a carga cognitiva de interpretar códigos de estante  

---

### 2. 🖥️ Detalhes da Tela

- **Título da Tela:** Mapa do Pavimento  

#### 🗺️ Visualização
- Planta baixa 2D/3D simplificada da biblioteca  
- Estilo semelhante a mapas internos (ex: Google Maps indoor)  

#### 🎯 Elementos Visuais
- Ícone **"Você está aqui"** (Balcão de Atendimento)  
- Ponto de destino (Estante) destacado com cor vibrante ou animação  
- Subtítulo dinâmico:  
  > "A obra está no 2º Andar, Setor de História, Corredor 4"  

#### 🔗 Ação de Saída
- Botão: **"Compartilhar Rota via QR Code/Link"**

---

### 3. ✅ Critérios de Aceitação (BDD)

- **Dado que:**  
  Confirmei a disponibilidade da obra na tela anterior  

- **Quando:**  
  Clico no componente de localização ou no mapa  

- **E:**  
  Viro o dispositivo (ou monitor) para o usuário  

- **Então:**  
  O mapa deve carregar com zoom automático no setor da obra  

- **E:**  
  Deve destacar o caminho inicial a partir do balcão  

---

## 🧭 Jornada 4: Orientar

### 1. 🧾 História de Usuário (Narrativa)

- **Como:** Jonas Lima (Funcionário Otimizador de Fluxo)  
- **Eu quero:** disparar a rota guiada passo a passo para o dispositivo do usuário  
- **Para:** finalizar o atendimento presencial com a certeza de que o usuário possui as instruções necessárias para chegar à estante de forma autônoma  

---

### 2. 🖥️ Detalhes da Tela

- **Título da Tela:** Rota Finalizada / Compartilhamento  

#### 📱 Interface Principal
- QR Code centralizado de leitura fácil  

#### 📝 Instruções de Suporte
> "Aponte a câmera para levar o mapa com você"

#### 🗺️ Visualização de Rota (Preview)
- Miniatura do mapa com o traçado do caminho (linha pontilhada) do ponto A ao ponto B  

#### ✅ Feedback de Jonas
- Botão: **"Atendimento Concluído"**  
- Ação: limpa a tela para a próxima tarefa  

---

### 3. ✅ Critérios de Aceitação (BDD)

- **Dado que:**  
  O usuário deseja levar a rota em seu próprio smartphone  

- **Quando:**  
  Seleciono a opção de gerar rota direta para estante  

- **E:**  
  O usuário escaneia o código exibido  

- **Então:**  
  O sistema deve confirmar a conexão  

- **E:**  
  Deve permitir encerrar a sessão de consulta  

- **E:**  
  O dashboard deve retornar ao status de **"Disponível para Atividades Técnicas"**  

---
