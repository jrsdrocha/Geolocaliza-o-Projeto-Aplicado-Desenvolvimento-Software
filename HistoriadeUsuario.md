```md id="kq3lx"
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
```
