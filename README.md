# 💸 Projeto FinanChat - App de Organização de Finanças Pessoais com Vibe Coding

## PRD Feito no Copilot Web + Alguns Ajustes Pessoais:
```markdown
# PRD – Aplicativo de Organização de Finanças Pessoais Conversacional

## 1. Contexto
O objetivo é criar um aplicativo de organização de finanças pessoais que funcione por meio de conversas em linguagem natural.
A proposta é simplificar o controle financeiro, eliminando a necessidade de formulários manuais ou planilhas complexas, tornando a experiência mais intuitiva e próxima de uma conversa com um assistente pessoal.

## 2. Problema
### Atualmente, muitos usuários desistem de controlar seus gastos porque:
- Os aplicativos exigem entrada manual excessiva.
- Há pouca personalização na experiência.
- O processo é visto como burocrático e pouco amigável.

### O aplicativo busca resolver isso oferecendo:
- Uma experiência conversacional fluida.
- Recomendações automáticas de economia adaptadas ao perfil do usuário.
- Um ambiente simples e motivador para iniciantes.

## 3. Público-Alvo
- Pessoas que desejam começar a organizar suas finanças de forma prática e sem complicação.
- Usuários iniciantes em controle financeiro, que não têm familiaridade com planilhas ou apps complexos.
- Jovens adultos e profissionais que buscam simplicidade e orientação personalizada.
- Diversidade de perfis: independente de idade, escolaridade ou nível de familiaridade com tecnologia.

## 4. Funcionalidades-Chave
1- Registrar gastos via chat em linguagem natural.
   Exemplo: “Gastei 50 reais no supermercado ontem.”
2- Classificação automática de transações.
   Categorias como alimentação, transporte, lazer, etc.
3- Definição e acompanhamento de metas financeiras.
   Exemplo: “Quero economizar 500 reais este mês.”
4- Agente Financeiro com dicas de economia.
   Recomendações personalizadas com base nos hábitos do usuário.
5- Relatórios simples e personalizados.
   Gráficos e resumos acessíveis, sem sobrecarga de informação.

## 5. Considerações Importantes
- Todos os dados iniciam em zero, e devem ser atualizados pelo usuário através do chat.
- O chat deve agir como um agente financeiro, solicitando informações e dando dicas.
- Sempre confirmar nas respostas do chat o que foi alterado.
- Salvar toda conversa com o agente para facilitar a retomada de assunto.
- Nenhum dado deve ser inserido sem solicitação do usuário.

## 6. Entregável da IA (MVP)
O MVP deve incluir:

### Principais Telas
- Tela de Login: como primeiro contato com a plataforma.
- Tela de Conversa: interface central para registrar gastos e interagir com o agente financeiro.
- Tela de Metas: definição e acompanhamento de objetivos financeiros.
- Tela de Relatórios: visão geral dos gastos, categorias e progresso das metas.

### Recursos Necessários
- Motor de processamento de linguagem natural (NLP) para interpretar mensagens.
- Sistema de classificação automática de transações.
- Banco de dados simples para armazenar gastos e metas.
- Módulo de recomendações financeiras.
- Visualizações básicas (gráficos e tabelas).

### Esboço de Validação Inicial
- Teste com usuários iniciantes para avaliar clareza da conversa.
- Medição de engajamento: quantos gastos são registrados via chat.
- Feedback qualitativo: percepção de simplicidade e utilidade.
- Iterações rápidas para ajustar linguagem e recomendações.

## 7. Design Universal
O aplicativo deve adotar um design inclusivo e acessível, garantindo que qualquer pessoa consiga utilizá-lo, independentemente de idade, escolaridade ou experiência digital.
Princípios fundamentais:
- Interface simples e intuitiva: poucos elementos visuais, foco na conversa mas com valor do saldo, despesa e meta sempre em tela.
- Linguagem clara e acessível: evitar jargões técnicos.
- Contraste e legibilidade: cores e tipografia que favoreçam leitura fácil.
- Navegação mínima: reduzir cliques e menus complexos.
- Acessibilidade: compatibilidade com leitores de tela e boas práticas de UX universal.

## 8. Tom e Linguagem
- Educativo e acessível, evitando termos técnicos complexos.
- Conversa natural, próxima ao estilo de mensagens instantâneas.
- Foco em motivação e simplicidade, para reduzir barreiras de uso.
```
## Principais Interações  com Lovable

> Crie um app de assitente financeiro seguindo este PRD(Product Requirements Document):{PRD}

> Bug detectado, campo de texto do chat sumiu e não consigo conversar mais. pode resolver?

> a tela de relatorios está sem rolagem e não consigo ver todos os dados, poderia adicionar pra mim?

> adicione um botão discreto para mudar o app para modo dark.
#
### App Final no Lovable: https://id-preview--375f42eb-e5cf-4198-a225-0d7540961f8e.lovable.app/auth
### OVERVIEW: https://youtu.be/XDqKX3Z7XE4

<img width="1918" height="872" alt="FinanChat" src="https://github.com/user-attachments/assets/739d1ffa-c1cd-4e2f-90ae-9bddbbd0d4fe" />

## Funcionalidades do Aplicativo

### 1. Interface Conversacional
- Interação por mensagens em linguagem natural.
- O agente financeiro responde com orientações, sugestões e confirmações.
- Exemplo: sugestões de economia mensal para metas específicas.

### 2. Registro de Transações via Chat
- O usuário informa gastos ou ganhos diretamente na conversa.
- Exemplo: "Ganhei 500 reais no tigrinho" é reconhecido como entrada de receita.

### 3. Painel de Indicadores Financeiros
- Exibição em tempo real dos principais dados:
  - **Saldo**: valor disponível.
  - **Despesas**: total gasto.
  - **Metas**: número de objetivos ativos.

### 4. Gestão de Metas
- Criação de metas financeiras com base em objetivos pessoais.
- Estratégias sugeridas para alcançar metas com economia mensal.
- Visualização de metas ativas e progresso.

### 5. Relatórios Personalizados
- Aba dedicada a relatórios simples e visuais.
- Gráficos e resumos para facilitar o entendimento dos hábitos financeiros.

### 6. Design Universal e Acessível
- Interface limpa e intuitiva com foco na conversa.
- Informações essenciais sempre visíveis (saldo, despesas, metas).
- Navegação simples com botões claros: Chat, Metas, Relatórios, Tema, Sair.

### 7. Confirmação e Histórico
- O agente confirma cada ação registrada.
- Toda conversa é salva para facilitar acompanhamento e retomada de assuntos.
  
## Reflexão
  ### O que funcionou bem?
   A criação do app foi rápida e a adição de funcionalidades foi simples de implementar apesar da limitação de creditos do Lovable.
  ### O que não funcionou como o esperado?  
   O chat estava bugado em segundo plano mas foi resolvido com alguns prompts e o chatbot apresentou alguns problemas com criação de metas,
   o processo demorou mais que o esperado pois tive apenas de 3 a 5 correções por dia.
  ### O que aprendeu sobre conversar com IAs?
   A maior barreira é o prompt, já que sem conhecimento de programação ficou mais difícil especificar os problemas encontrados.
#
> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
