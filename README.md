# 💸 App de Organização de Finanças Pessoais do hinacio com Vibe Coding

PRD Refinado no copilot web:

****markdown
# PRD - Finanças em Conversa

## Visão Geral

Finanças em Conversa é um aplicativo de organização financeira pessoal baseado em linguagem natural. O objetivo é permitir que usuários registrem receitas, despesas e metas financeiras simplesmente conversando com um assistente inteligente, eliminando a necessidade de planilhas complexas ou formulários extensos.

O produto deve transformar informações fornecidas em linguagem cotidiana em dados financeiros estruturados e gerar insights personalizados para ajudar o usuário a tomar melhores decisões financeiras.

---

# Problema

Muitas pessoas abandonam o controle financeiro porque os aplicativos existentes exigem entrada manual excessiva, categorização constante de transações e conhecimento prévio sobre finanças.

Além disso, usuários iniciantes frequentemente têm dificuldade para compreender relatórios financeiros tradicionais e identificar oportunidades de economia.

O produto busca simplificar a gestão financeira por meio de uma experiência conversacional intuitiva e personalizada.

---

# Objetivo do MVP

Validar se usuários conseguem gerenciar suas finanças de forma mais simples utilizando linguagem natural em vez de interfaces tradicionais baseadas em formulários.

O MVP deve permitir:

- Registrar receitas e despesas via chat.
- Classificar transações automaticamente.
- Acompanhar gastos por categoria.
- Criar e acompanhar metas financeiras.
- Receber recomendações automáticas de economia.
- Visualizar um resumo financeiro simples.

---

# Público-Alvo

## Público Principal

- Adultos entre 18 e 45 anos.
- Pessoas com pouco conhecimento sobre educação financeira.
- Usuários que não utilizam aplicativos financeiros atualmente.
- Pessoas que desejam organizar suas finanças de forma simples.

## Público Secundário

- Usuários que abandonaram aplicativos financeiros tradicionais.
- Pessoas que procuram uma alternativa mais prática para registrar gastos.

---

# Proposta de Valor

"Controle suas finanças conversando naturalmente com um assistente financeiro inteligente."

---

# Funcionalidades Principais

## 1. Registro de Transações em Linguagem Natural

O usuário poderá registrar receitas e despesas através de mensagens simples.

### Exemplos

Entrada:
"Gastei R$ 48 no almoço."

Saída esperada:
- Tipo: Despesa
- Valor: R$ 48
- Categoria: Alimentação
- Data: Hoje

Entrada:
"Recebi R$ 3.000 de salário."

Saída esperada:
- Tipo: Receita
- Valor: R$ 3.000
- Categoria: Salário

---

## 2. Classificação Automática

O sistema deverá sugerir automaticamente uma categoria para cada transação.

Categorias iniciais:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Investimentos
- Salário
- Outros

O usuário poderá editar a categoria sugerida.

---

## 3. Metas Financeiras

O usuário poderá criar objetivos financeiros.

Exemplos:

- Guardar R$ 5.000 para uma viagem.
- Economizar R$ 500 por mês.
- Criar uma reserva de emergência.

Acompanhamentos exibidos:

- Valor acumulado.
- Valor alvo.
- Percentual concluído.
- Previsão de atingimento.

---

## 4. Agente Financeiro

Assistente responsável por gerar recomendações simples e personalizadas.

Exemplos:

- "Você gastou 25% mais com alimentação neste mês."
- "Se reduzir R$ 100 em delivery por mês poderá atingir sua meta duas semanas antes."
- "Transporte é sua categoria de maior gasto atualmente."

Importante:

O agente deve fornecer conteúdo educativo e não realizar aconselhamento financeiro profissional.

---

## 5. Dashboard Financeiro

Apresentar informações de forma simples e visual.

Indicadores principais:

- Saldo atual.
- Total de receitas.
- Total de despesas.
- Gastos por categoria.
- Evolução mensal.
- Progresso das metas.

---

# Principais Telas do MVP

## Tela 1 - Onboarding

Objetivos:

- Apresentar a proposta do produto.
- Capturar nome do usuário.
- Configurar objetivo financeiro inicial.

---

## Tela 2 - Chat Principal

Objetivos:

- Registrar receitas e despesas.
- Conversar com o Agente Financeiro.
- Fazer perguntas sobre a situação financeira.

Exemplos de perguntas:

- "Quanto gastei com alimentação este mês?"
- "Qual foi meu maior gasto?"
- "Como está minha meta de viagem?"

---

## Tela 3 - Dashboard

Objetivos:

- Exibir indicadores financeiros.
- Apresentar gráficos simples.
- Mostrar resumo das movimentações.

---

## Tela 4 - Metas

Objetivos:

- Criar metas.
- Editar metas.
- Acompanhar progresso.

---

## Tela 5 - Perfil e Configurações

Objetivos:

- Editar dados do usuário.
- Gerenciar categorias.
- Configurar notificações.

---

# Fluxo Principal do Usuário

1. Usuário realiza cadastro.
2. Define uma meta financeira inicial.
3. Envia uma mensagem registrando um gasto ou receita.
4. O sistema interpreta a mensagem.
5. A transação é salva automaticamente.
6. O dashboard é atualizado.
7. O Agente Financeiro gera insights relevantes.
8. O usuário acompanha sua evolução financeira.

---

# Requisitos Funcionais

RF01 - Registrar receitas utilizando linguagem natural.

RF02 - Registrar despesas utilizando linguagem natural.

RF03 - Classificar transações automaticamente.

RF04 - Permitir edição de transações registradas.

RF05 - Criar e acompanhar metas financeiras.

RF06 - Gerar relatórios financeiros simplificados.

RF07 - Fornecer recomendações automáticas.

RF08 - Permitir consultas financeiras através do chat.

RF09 - Exibir histórico de movimentações.

RF10 - Armazenar dados financeiros do usuário.

---

# Requisitos Não Funcionais

RNF01 - Interface intuitiva para iniciantes.

RNF02 - Tempo médio de resposta inferior a 3 segundos.

RNF03 - Design responsivo para dispositivos móveis.

RNF04 - Armazenamento seguro dos dados.

RNF05 - Linguagem simples e acessível.

RNF06 - Experiência otimizada para uso frequente e rápido.

---

# Métricas de Sucesso

- 70% dos usuários registram o primeiro gasto em menos de 2 minutos.
- 50% dos usuários retornam após 7 dias.
- Média mínima de 5 registros por usuário na primeira semana.
- NPS superior a 30.
- 60% dos registros financeiros realizados através do chat.

---

# Hipóteses a Validar

H1 - Usuários preferem registrar transações por conversa em vez de formulários.

H2 - A classificação automática reduz o atrito de uso.

H3 - Recomendações personalizadas aumentam o engajamento.

H4 - Usuários iniciantes conseguem interpretar os relatórios sem treinamento.

---

# Plano de Validação Inicial

## Fase 1

Construir MVP funcional utilizando Lovable.

## Fase 2

Realizar testes com 5 a 10 usuários.

## Fase 3

Observar:

- Facilidade de registrar gastos.
- Clareza dos relatórios.
- Utilidade dos insights.

## Fase 4

Coletar feedback por entrevistas curtas.

## Fase 5

Priorizar melhorias para evolução do produto.

---

# Diretrizes para a IA do Produto

O assistente financeiro deve:

- Utilizar linguagem simples e amigável.
- Explicar conceitos financeiros quando necessário.
- Evitar termos excessivamente técnicos.
- Solicitar esclarecimentos quando uma transação estiver ambígua.
- Incentivar hábitos financeiros saudáveis.
- Nunca fornecer aconselhamento financeiro profissional.

Exemplo:

Usuário:
"Gastei um pouco no mercado."

Resposta:
"Posso registrar esse gasto para você. Qual foi o valor aproximado da compra?"

Interações com o lovable:

> crie um APP de Finanças Pessoais com base no seguinte PRD (Product Requirements Document): {PRD}

> Revisei o APP e corrigi o valores em reais e apresentação no celular 

Resultado Final no Lovable: https://chatty-money-compass.lovable.app

<img width="1341" height="602" alt="site 1" src="https://github.com/user-attachments/assets/506ecfba-d56b-4642-9d40-48112675c3c9" />
<img width="1335" height="600" alt="site 2" src="https://github.com/user-attachments/assets/bda9c60c-23ec-4c42-9fec-058e79ae53be" />
<img width="1311" height="601" alt="site 3" src="https://github.com/user-attachments/assets/0f70cbdf-fb78-439d-815d-e7dc7ed57e47" />
<img width="1325" height="601" alt="site 4" src="https://github.com/user-attachments/assets/b1249048-461e-4e23-bb95-a27b5597ed28" />

Finanças em Conversa
Aplicação de gestão financeira pessoal baseada em IA conversacional.

O sistema permite o registro de receitas e despesas utilizando linguagem natural, realizando a interpretação das mensagens, classificação automática das transações e geração de insights financeiros personalizados.

Objetivo
Reduzir a complexidade do controle financeiro pessoal por meio de uma interface conversacional capaz de transformar interações em linguagem natural em dados financeiros estruturados.

O produto foi concebido como um MVP para validar a hipótese de que usuários iniciantes possuem maior adesão ao controle financeiro quando utilizam uma experiência baseada em chat em vez de formulários tradicionais.

Arquitetura Funcional
┌─────────────────────┐
│     Usuário         │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Interface de Chat   │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Processamento NLP   │
│ (Linguagem Natural) │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Motor Financeiro    │
├─────────────────────┤
│ Receitas            │
│ Despesas            │
│ Categorias          │
│ Metas               │
└──────────┬──────────┘
           │
           ├────────────► Dashboard
           │
           ├────────────► Extrato
           │
           └────────────► Agente Financeiro
Funcionalidades
Registro Conversacional
Permite registrar movimentações financeiras através de mensagens em linguagem natural.

Exemplos
"Gastei R$ 45 no almoço."
Resultado:

{
  "tipo": "despesa",
  "valor": 45,
  "categoria": "alimentação",
  "data": "hoje"
}
"Recebi R$ 2.500 de salário."
Resultado:

{
  "tipo": "receita",
  "valor": 2500,
  "categoria": "salário",
  "data": "hoje"
}
Classificação Automática
O sistema categoriza automaticamente as transações utilizando regras de negócio e interpretação contextual.

Categorias suportadas:

Alimentação
Transporte
Moradia
Saúde
Educação
Lazer
Compras
Investimentos
Salário
Outros
Dashboard Financeiro
Painel consolidado com indicadores financeiros em tempo real.

Métricas
Saldo Atual
Receitas Mensais
Despesas Mensais
Gastos por Categoria
Evolução Financeira
Progresso de Metas
Visualizações
Cards de resumo
Gráfico de categorias
Evolução temporal
Indicadores de performance financeira
Agente Financeiro
Camada de inteligência responsável por analisar dados históricos e gerar recomendações contextualizadas.

Exemplos de Insights
Você gastou 20% mais com alimentação neste mês.
Sua meta de viagem poderá ser atingida 4 semanas antes caso economize R$100 adicionais por mês.
Educação representa sua maior categoria de despesas.
Módulo de Metas
Possibilita a criação e acompanhamento de objetivos financeiros.

Recursos
Criação de metas
Acompanhamento de progresso
Percentual de conclusão
Projeções de atingimento
Recomendações de economia
Casos de Uso
Reserva de emergência
Viagens
Aquisição de bens
Formação profissional
Extrato Financeiro
Histórico completo das transações registradas.

Informações Disponíveis
Campo	Descrição
Data	Data da movimentação
Descrição	Texto informado pelo usuário
Categoria	Categoria atribuída
Tipo	Receita ou Despesa
Valor	Valor financeiro
Casos de Uso
Registrar Despesa
Usuário → Chat
Chat → Interpretar movimentação
Sistema → Classificar categoria
Sistema → Persistir transação
Dashboard → Atualizar indicadores
Consultar Gastos
Usuário:
"Quanto gastei este mês?"
Sistema:
Calcula despesas do período e retorna resumo financeiro.
Acompanhar Meta
Usuário:
"Como está minha meta de viagem?"
Sistema:
Consulta valor acumulado
Calcula percentual concluído
Retorna previsão de conclusão
Requisitos Funcionais
ID	Requisito
RF01	Registrar receitas em linguagem natural
RF02	Registrar despesas em linguagem natural
RF03	Classificar transações automaticamente
RF04	Permitir edição de registros
RF05	Gerenciar metas financeiras
RF06	Gerar relatórios financeiros
RF07	Responder consultas via chat
RF08	Produzir recomendações personalizadas
RF09	Exibir histórico financeiro
RF10	Gerenciar dados do usuário
Requisitos Não Funcionais
ID	Requisito
RNF01	Interface responsiva
RNF02	Tempo de resposta inferior a 3 segundos
RNF03	Navegação intuitiva
RNF04	Persistência segura dos dados
RNF05	Compatibilidade mobile-first
RNF06	Linguagem acessível para iniciantes
MVP Scope
Incluído
Chat financeiro
Dashboard
Categorias automáticas
Metas financeiras
Extrato
Insights financeiros
Fora do Escopo
Open Finance
Integração bancária
Importação automática de extratos
Gestão de investimentos
Sincronização multiusuário
Roadmap
Fase 1
MVP Conversacional
Dashboard Financeiro
Gestão de Metas
Fase 2
Inteligência Financeira Avançada
Regras preditivas
Recomendações contextuais
Fase 3
Open Finance
Integrações bancárias
Importação automática de transações
Métricas de Produto
Adoção
Taxa de ativação
Tempo para primeiro registro
Retenção D7
Retenção D30
Engajamento
Quantidade de transações registradas
Mensagens enviadas ao chat
Metas criadas por usuário
Valor
Frequência de uso do dashboard
Utilização das recomendações
Evolução do saldo dos usuários
Tecnologias e Conceitos Aplicados
IA Conversacional
NLP (Natural Language Processing)
Product Discovery
Product Requirements Document (PRD)
UX Conversacional
Vibe Coding
Desenvolvimento Assistido por IA
Status
Projeto desenvolvido como estudo prático de Product Management, IA Conversacional e Vibe Coding utilizando Lovable.

## reflexão

## O que funcionou bem?  
O Refinamento do PRD previamente feito no copilot ajudou muito, pois os créditos do lovable acabaram em apenas 3 instruções.

### O que não funcionou como o esperado?  
Esperava poder interagir mais vezes gratuitamente com o lovable, mais a interações feita já foram de grande valia para aprender mais sobre vibe coding.
  
### O que aprendeu sobre conversar com IAs?
Aprendi que é basicamente igual a conversar com uma pessoa, quanto mais detalhe e clareza você dá, melhor é a interação.
  

