# 🍱 Menuzito

Menuzito é um app pessoal para organizar cardápios semanais de marmitas e refeições.  
A ideia nasceu da necessidade de planejar de forma prática o que cozinhar para a semana, economizando tempo e evitando repetição.

---

## 🎯 Objetivo

- Organizar refeições da semana (café da manhã, almoço, lanche, jantar etc.)
- Planejar cardápios de forma simples e visual
- Facilitar o preparo de marmitas
- Evoluir para ter sugestões inteligentes (IA)

---

## 🛠️ Roadmap do Projeto

### 🔹 MVP (Funcionalidades Básicas)
- [ ] Cadastro de refeições da semana
- [ ] Visualização em calendário/agenda
- [ ] Categorias de refeição: Café da manhã, Almoço, Lanche da tarde, Janta
- [ ] Opção de repetir refeição para a semana toda

### 🔸 Funcionalidades Intermediárias
- [ ] Salvar receitas (ingredientes + modo de preparo)
- [ ] Vincular receitas ao calendário

### 🔹 Funcionalidades Avançadas
- [ ] Integração com IA:
  - Usuário digita: “Essa semana no almoço quero comer strogonoff de frango com arroz e batata palha”
  - App preenche automaticamente o calendário
- [ ] Evoluções possíveis:
  - Recomendações para variar cardápio

---

## 📱 Wireframes

### Tela 1 – Home (Cardápio Semanal)
- Grade semanal (segunda a domingo)
- Slots: Café da manhã, Almoço, Lanche, Janta
- Cada célula mostra prato/receita
- Botão “+” para adicionar refeição

### Tela 2 – Adicionar Refeição
- Seleção de refeição
- Nome do prato
- Ingredientes (multi-input ou checklist)
- Foto/ícone opcional
- Botão salvar

### Tela 3 – Receitas Salvas
- Lista de receitas cadastradas
- Card: foto + nome + ingredientes
- Botão: “Adicionar ao cardápio”
- Botão flutuante ➕ para criar nova receita

### Tela 5 – Configurações
- Gerenciar categorias de refeição
- Ativar/desativar notificações
- Escolher tema (claro/escuro)

---

## 🚀 Tecnologias

- **Frontend**: React / TypeScript
- **UI**: styled-components
- **Armazenamento**: PostgreSQL
- **Backend**: Ruby on Rails
- **Autenticação**: JWT
- **App**: PWA
- **IA**: integração futura com OpenAI API

---