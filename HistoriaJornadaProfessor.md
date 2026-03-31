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
