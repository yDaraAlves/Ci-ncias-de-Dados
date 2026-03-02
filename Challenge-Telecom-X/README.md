📊 Projeto de Análise Exploratória de Dados (EDA) — Telecom X

Tecnologias: Python · Pandas · Requests · Matplotlib
Licença: MIT

💡 Identificação dos principais fatores de evasão de clientes (Churn) para apoiar decisões estratégicas de retenção.


🧠 Objetivo do Projeto

A Telecom X enfrenta um alto índice de cancelamento de clientes, impactando diretamente sua receita e sustentabilidade.
Este projeto tem como objetivo realizar uma Análise Exploratória de Dados (EDA) para identificar os principais fatores associados ao churn, fornecendo insights que apoiem estratégias de retenção.

Telecom x - parte 2

Principais Fatores que Influenciam a Evasão
A análise dos coeficientes (Regressão Logística), importância das variáveis (Random Forest) e influência na separação das classes (SVM e KNN) revelou convergência nos mesmos fatores críticos.

🔥 Fatores que AUMENTAM a evasão

📄 1. Contrato Mensal (Month-to-month)

Maior coeficiente positivo na Regressão Logística

Alta importância no Random Forest

Principal divisor na Árvore

👉 Clientes sem fidelização formal são mais propensos a sair.

📅 2. Baixo Tempo como Cliente (Meses_Cliente)

Variável mais importante no Random Forest

Forte peso na separação do SVM

Dominante na distância do KNN

👉 Os primeiros meses são críticos para retenção.

💰 3. Cobrança Mensal Elevada

Impacto positivo nos coeficientes

Alta relevância nas árvores

👉 Sensibilidade ao preço influencia decisão de cancelamento.

🌐 4. Internet Fibra Óptica

Associada a maior churn

Pode indicar problemas de qualidade ou expectativa

💳 5. Método de Pagamento — Electronic Check

Forte correlação com evasão

Pode indicar perfil menos fidelizado

🛡️ Fatores que REDUZEM evasão

📄 Contratos de 1 e 2 anos

📅 Maior tempo como cliente

🛠️ Serviços adicionais (suporte técnico, segurança online)

💵 Maior cobrança total acumulada
