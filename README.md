# 📊 Análise de Churn de Clientes 
![Logo do Projeto](Imagens/incentive-no-churn.png)

Este projeto tem como objetivo analisar a taxa de churn (cancelamento de clientes)
em um banco, identificar os principais motivos que levam os clientes
a cancelarem seus serviços e propor soluções para reduzir essa taxa.
</br>
</br>
## 🏆 Objetivos
Identificar quantos clientes cancelaram suas assinaturas.
Descobrir os principais fatores que influenciam o churn.
Propor estratégias para reduzir a evasão de clientes.
Simular um cenário otimizado para demonstrar o impacto das soluções sugeridas.
</br>
</br>
## 🛠 Tecnologias Utilizadas
Linguagem: Python </br>
Bibliotecas: Pandas, plotly
</br>
</br>
## Principais inshgts
**A taxa de churn é cerca de 57%.**
![Logo do Projeto](Imagens/ChurnCancelou.png)
A taxa está desequilibrada, 56,7% dos clientes cancelaram o serviço. Assim farei uma análise para descobrir suas motivações, posteriormente, descobrir soluções e qual será a taxa de churn da empresa após correção dos problemas. Para isso, visualizarei como todas as colunas impactam no cancelamento:
</br>
</br>
**Taxa de churn sobre a idade:**
![Logo do Projeto](Imagens/Idade.png)
**Taxa de churn sobre o atraso de pagamento:**
![Logo do Projeto](Imagens/Dias_atraso.png)
**Taxa de churn sobre as ligações ao CallCenter:**
![Logo do Projeto](Imagens/Ligacoes_callcenter.png)
**Taxa de churn sobre a assinatura:**
![Logo do Projeto](Imagens/Assinatura.png)
</br>
## Percepções
- Todos os clientes acima de 50 anos cancelaram o serviço. Isso significa que o serviço oferecido não é interessante para esse público. Deve-se evitar investir nesse público.
- É possível notar que todos os clientes com mais de 5 ligações ao callcenter cancelam o serviço. Criar um alerta para quando um cliente bater 3 ligações. Dar prioridade ao seu problema.
- Pós 20 dias de atraso no pagamento todos os clientes cancelaram. Criar um alerta e entrar em contato com o cliente pós 15 dias de atrasso no pagamento.
- Contratos mensais sempre cancelam. Evitar contratos mensais e incetiver anuais e quartenários.
- Clientes com menos de 500 reais gastos sempre cancelam. Incentivar o gasto maior com benefícios.
</br>
</br>

# Dados depois da melhoria
**Pós incentivo de planos quartenários e anuais a taxa de churn caiu cerca de 10%, um percentual que representa mais de 170 mil clientes. Uma melhoria significativa.**
<img src="Imagens/Cancelou - Retirada de Planos Mensais.png">

**Pós problema com CallCenter solucionado se destaca uma diminuição de 20%, cerca de 190 mil clientes, do churn em comparação ao valor anterior.**
<img src="Imagens/Cancelou - Correção do CallCenter.png">

**Pós solução do atraso de pagamento a taxa de cancelamento caiu 8%, 51 mil clientes.**
<img src="Imagens/Cancelou - Atraso do Pagamento.png">

**Pós focar e investir nos clientes mais jovens, percebemos uma diminuição de cerca de 6% no churn dos clientes, mais de 30 mil.**
<img src="Imagens/Cancelou - Idade.png">

## Conclução
- Iniciamos a análise com uma taxa de cancelamento de 56,7%, o que indicava um alto nível de churn entre os clientes. Após um primeiro tratamento nos dados, conseguimos reduzir esse valor para 46,1%, já demonstrando uma melhoria significativa.

- Com o apoio da análise exploratória e dos gráficos, ajustamos ainda mais a base de dados, refinando os critérios e identificando padrões mais precisos. Como resultado, conseguimos reduzir a taxa de cancelamento para 12,1%, evidenciando a importância da limpeza e organização dos dados na obtenção de insights mais confiáveis.

- Esses ajustes permitem que a empresa tenha uma visão mais clara do comportamento dos clientes e possa tomar decisões estratégicas mais assertivas para reduzir o churn no futuro. 


