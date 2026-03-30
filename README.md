#  App de Organização de Finanças Pessoais com Vibe Coding

PRD no Copilot WEb:

```markdown
# 📱 MeuBolso – App de Organização de Finanças Pessoais com Vibe Coding

Este projeto apresenta o desenvolvimento do **MeuBolso**, um aplicativo de finanças pessoais inteligente, integrado com chatbot de IA, que ajuda o usuário a controlar e planejar sua vida financeira de forma simples e acessível.

---

## 📌 PRD – MeuBolso

### Contexto
Criar o **MeuBolso**, um aplicativo de organização financeira pessoal baseado em conversas em linguagem natural.  
O objetivo é simplificar o controle de gastos sem depender de formulários extensos ou planilhas complexas.

### Problema
Usuários abandonam apps de finanças porque:  
- Exigem muita entrada manual.  
- Pouca personalização na experiência.  

### Solução proposta
Interação por chat, com recomendações automáticas de economia e relatórios simples.

### Público-Alvo
- Pessoas que desejam começar a organizar suas finanças de forma prática.  
- Principalmente iniciantes que não têm familiaridade com planilhas ou apps complexos.  
- Inclusão: garantir que o **MeuBolso** siga princípios de **Design Universal**, oferecendo boa experiência para o máximo de usuários possíveis, independentemente de idade, nível de habilidade digital ou necessidades específicas de acessibilidade.  

---

## ⚙️ Funcionalidades-Chave
1. **Tela de Login/Cadastro**  
   - Campos para **Nome de Usuário** e **Senha**.  
   - Botões: **Entrar** e **Cadastrar**.  
   - Opções de login social: **Google** e **Apple**.  
   - Recuperação de senha via **PIN** ou **Pergunta Secreta**.  

2. **Registro de gastos via chat** em linguagem natural.  
3. **Classificação automática** das transações (ex.: alimentação, transporte).  
4. **Metas financeiras**: definir e acompanhar objetivos (ex.: poupar R$500/mês).  
5. **Agente Financeiro**: dicas de economia personalizadas.  
6. **Relatórios simples e visuais**: visão clara de gastos e progresso.  
7. **Gráficos interativos**:  
   - Gráficos de pizza para categorias de gastos.  
   - Gráficos de linha para evolução do saldo.  
   - Barras comparativas para metas atingidas vs. planejadas.  
8. **Design Universal**: interface acessível, com contraste adequado, navegação intuitiva e compatibilidade com leitores de tela.  
9. **Investimentos interativos**: seção dedicada a possíveis investimentos, explicados de forma clara e acessível, com simulações simples.  
10. **Tela inicial estilo banco digital**: mostrar saldo atual, atalhos para funcionalidades importantes e um chat interativo para dúvidas rápidas.  

---

## 📱 Entregável da IA (MVP)
- Principais telas:  
  - Login/Cadastro  
  - Chat  
  - Metas  
  - Relatórios  
  - Gráficos  
  - Investimentos  
  - Tela inicial estilo banco digital  

- Recursos necessários:  
  - NLP para chat  
  - Categorização automática  
  - Motor de recomendações  
  - Módulo de simulação de investimentos  
  - Biblioteca de gráficos (ex.: Chart.js, D3.js ou Flutter Charts)  

- Esboço de validação inicial:  
  - Testes com grupo piloto de usuários iniciantes  
  - Diversidade de perfis para garantir acessibilidade  

---

## 🔧 Interações com o Lovable
- Criação do **MeuBolso** com base no PRD.  
- Adição da página de login/cadastro.  
- Implementação da funcionalidade de **mudança de tema** (claro, escuro e automático).  
- Correção do erro no cadastro inicial (saldo inicial deve ser sempre R$0,00).  
- Ajustes no armazenamento e sincronização de dados.  
- Conexão do chatbot à **API de IA do Lovable**, substituindo parser baseado em regex.  

---

## ✅ Resultado Final
Aplicativo disponível em:  
[https://chatfinancas.lovable.app/)

### Print de Tela

### Tela de Login cadastro
<img width="819" height="558" alt="image" src="https://github.com/user-attachments/assets/d0834bd7-5e04-4df1-a5f5-498e343d0488" />


### Tela de Inicio
<img width="868" height="562" alt="image" src="https://github.com/user-attachments/assets/0081af5b-4816-424d-9655-e01456c7d8b8" />

### Tela de Chat
<img width="811" height="554" alt="image" src="https://github.com/user-attachments/assets/2d520bf6-ae18-4a8d-8b65-56f4742a5984" />

### Tela de Metas
<img width="830" height="565" alt="image" src="https://github.com/user-attachments/assets/2ac0ff6a-babb-4277-8330-ca934ddb040d" />

### Tela de Relatórios
<img width="830" height="566" alt="image" src="https://github.com/user-attachments/assets/9f76416a-81d0-46f7-8a6e-f503a074b3d9" />

---

## 📱 Resumo do MeuBolso
O **MeuBolso** é um organizador financeiro inteligente, integrado com um chatbot de IA, que ajuda o usuário a controlar e planejar sua vida financeira de forma simples e acessível.

**Principais funcionalidades:**
- Registro de receitas e despesas via chat.  
- Controle de faturas e gastos parcelados.  
- Metas financeiras automáticas criadas pelo chat.  
- Relatórios claros e limites de gastos por categoria.  
- Gráficos interativos para acompanhar saldo e metas.  
- Planejamento de reserva de emergência e investimentos.  
- Histórico de conversas persistente e sincronizado.  
- Integração total entre saldo, metas, relatórios e histórico.  
- Interface inclusiva com suporte a tema claro, escuro e automático.  

---

## 📖 Reflexão sobre o processo
- **O que funcionou bem?**  
  Interface gráfica, relatórios e algumas interações do chatbot com funções principais.  

- **O que não funcionou como esperado?**  
  Algumas conexões entre funções do app e o chat ainda precisam de ajustes.  

- **O que aprendi sobre conversar com IAs?**  
  Quanto mais completas forem as informações, melhor será a interação. É como conversar com um ser humano: é necessário dar contexto e detalhes para que a IA entregue exatamente o que você espera.  

---
