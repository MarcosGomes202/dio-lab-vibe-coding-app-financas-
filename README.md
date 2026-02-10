#  App de Organização de Finanças Pessoais com Vibe Coding

PRD no Copilot WEb:

```markdown
PRD – App de Organização de Finanças Pessoais

Contexto
Criar um aplicativo de organização financeira pessoal baseado em conversas em linguagem natural.
O objetivo é simplificar o controle de gastos sem depender de formulários extensos ou planilhas complexas.

Problema
Usuários abandonam apps de finanças porque:
- Exigem muita entrada manual.
- Pouca personalização na experiência.

Solução proposta
Interação por chat, com recomendações automáticas de economia e relatórios simples.

Público-Alvo
- Pessoas que desejam começar a organizar suas finanças de forma prática.
- Principalmente iniciantes que não têm familiaridade com planilhas ou apps complexos.
- Inclusão: garantir que o app siga princípios de Design Universal, oferecendo boa experiência para o máximo de usuários possíveis, independentemente de idade, nível de habilidade digital ou necessidades específicas de acessibilidade.

Funcionalidades-Chave
1. Registro de gastos via chat em linguagem natural.
2. Classificação automática das transações (ex.: alimentação, transporte).
3. Metas financeiras: definir e acompanhar objetivos (ex.: poupar R$500/mês).
4. Agente Financeiro: dicas de economia personalizadas.
5. Relatórios simples e visuais: visão clara de gastos e progresso.
6. Design Universal: interface acessível, com suporte a diferentes perfis de usuários (ex.: contraste adequado, navegação intuitiva, compatibilidade com leitores de tela).
7. Investimentos interativos: seção dedicada a possíveis investimentos, explicados de forma clara e acessível, com simulações simples para qualquer usuário entender e usar.
8. Tela inicial estilo banco digital: mostrar saldo atual, atalhos para funcionalidades importantes e um chat interativo para dúvidas rápidas.

Entregável da IA
- Plano de MVP com:
  - Principais telas (chat, metas, relatórios, investimentos, tela inicial estilo banco).
  - Recursos necessários (NLP para chat, categorização automática, motor de recomendações, módulo de simulação de investimentos).
  - Esboço de validação inicial (testes com grupo piloto de usuários iniciantes e diversidade de perfis).
- Linguagem acessível e educativa em português.


```

Interações com o Lovable:

> Crie um App de Finanças Pessoais com base no seguinte PRD: {PRD}
> Adicione uma página de login/cadastro.
> Adicione ao aplicativo a funcionalidade de mudar o tema da interface:  
- Deve existir uma opção de escolha entre três modos: escuro, claro e automático.  
- O modo automático deve seguir o tema configurado no sistema operacional do dispositivo.  
- A seleção de tema deve estar disponível nas configurações do app e ser fácil de alterar a qualquer momento.  
- Garanta que todos os elementos visuais (telas, botões, ícones, textos) se adaptem corretamente ao tema escolhido.

> Corrija o erro no cadastro inicial do aplicativo.  
- Atualmente, ao criar uma nova conta, o sistema já mostra um saldo de mais de R$4000 sem que o usuário tenha registrado nada.  
- O comportamento correto deve ser: ao cadastrar uma nova conta, o saldo inicial deve ser sempre R$0,00.  
- Além disso, todas as demais informações também devem estar zeradas. Nenhuma meta financeira ou configuração deve ser adicionada automaticamente.  
- Apenas após o usuário registrar transações, adicionar valores ou definir metas é que o saldo e as metas devem ser atualizados.  
- Garanta que não haja valores pré-preenchidos, metas automáticas ou dados fictícios em uma nova conta.

> Corrija o comportamento do aplicativo em relação ao armazenamento e sincronização de dados:

1. Saldo

- Quando o usuário informa ao chat uma receita (ex.: "Recebi R$2000 de salário"), o valor deve ser registrado e sincronizado automaticamente com o saldo do aplicativo.  

- O saldo deve permanecer salvo mesmo após atualizar a página ou sair e entrar novamente no app.  

- Não pode zerar ou perder informações já registradas.

2. Metas

- Quando o usuário informa ao chat uma meta (ex.: "Quero juntar R$3000 em 6 meses"), essa meta deve ser criada automaticamente na seção de metas do aplicativo.  

- O sistema deve registrar valor, prazo e categoria da meta sem necessidade de preenchimento manual.  

- As metas devem permanecer salvas e sincronizadas com o app, mesmo após atualização ou logout.

3. Integração geral

- Todas as funções do app (saldo, metas, gastos, receitas, relatórios) devem estar conectadas com a IA.  

- O chatbot deve ser capaz de registrar e atualizar informações em tempo real, refletindo imediatamente nas telas correspondentes.  

- Nenhum dado informado pelo usuário deve ser perdido ou apagado automaticamente.

Objetivo:

Garantir que o aplicativo guarde e sincronize todas as informações passadas pelo usuário via chat, mantendo consistência entre o chatbot e as funcionalidades principais (saldo, metas, relatórios).

> Conecte o chatbot à API de IA do Lovable para respostas mais inteligentes e personalizadas, substituindo o parser baseado em regex

Resultado final no Lovable: https://dvnsfinancas.lovable.app/auth

<img width="485" height="938" alt="image" src="https://github.com/user-attachments/assets/89959b90-6571-419a-adbf-3e90476d9322" />


📱 Resumo do Aplicativo de Finanças Pessoais

O aplicativo é um organizador financeiro inteligente, integrado com um chatbot de IA, que ajuda o usuário a controlar e planejar sua vida financeira de forma simples e acessível.

Principais funcionalidades:
- Registro de receitas e despesas: o usuário informa valores pelo chat (ex.: “Recebi R$2000” ou “Gastei R$100 em restaurante”) e o app atualiza automaticamente o saldo.
- Controle de faturas: permite acompanhar gastos parcelados e organizar pagamentos em diferentes cartões.
- Metas financeiras automáticas: ao informar uma meta pelo chat (ex.: “Quero juntar R$3000 em 6 meses”), o app cria e sincroniza essa meta na seção de metas.
- Relatórios e limites de gastos: apresenta tetos por categoria (alimentação, transporte, saúde, etc.) e mostra relatórios claros para manter o usuário dentro das metas.
- Reserva de emergência e investimentos: ajuda a planejar aportes mensais e acompanhar o progresso da reserva.
- Histórico de conversas persistente: todas as interações com o chatbot ficam salvas e sincronizadas com as funções do app.
- Integração total: saldo, metas, relatórios e histórico estão conectados, garantindo consistência entre o que é informado no chat e o que aparece nas telas do app.
- Acessibilidade e design universal: interface simples, moderna e inclusiva, com suporte a tema claro, escuro e automático.
 
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?
      Toda a interface gráfica, algumas interações do chat bot com algumas funções. Mas muito a ser ajustado. 
  - O que não funcionou como o esperado?
      Algumas faltas de conexões de algumas fuções do app com o chat.  
  - O que aprendeu sobre conversar com IAs?
      Quanto mais completas as infromações melhor vai ser a interação, igual a conversar com um ser humano. É necessário dar informações completas para a IA entregar oque você espera. 


