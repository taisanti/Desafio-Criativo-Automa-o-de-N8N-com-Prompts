# **🎯 Desafio Criativo: Planejando Automações com N8N Usando Apenas Bons Prompts**

Desafio Criativo desenvolvido para o Bootcamp de N8N da DIO.  
Nesta atividade, foram seguidas algumas etapas simples para **planejar uma automação em N8N a partir de um prompt claro e estruturado**.

## **💡**Passo 1: Defina a automação desejada

Nesta etapa, foi **descrito qual processo eu desejo automatizar e quem será beneficiado por ele**.

Quero criar uma automação no N8N para registrar automaticamente meus gastos com cartão de crédito.

**Público ou responsável:**  
Uso pessoal

**Resultado esperado:**  
Receber os dados dos meus gastos e salvar em uma planilha e enviar resumo por e-mail a cada 4 dias.

## 🧩 Passo 2: Adicione contexto e regras

**Informar os sistemas envolvidos, as etapas do fluxo e as restrições importantes**. 

**Ferramentas envolvidas:**  
Telegram, google sheets e gmail.

**Fluxo desejado:**  
1\. Receber dados de canal no Telegram  
2\. Registrar dados em uma planilha financeira  
3\. Enviar resumo de gastos por e-mail a cada 4 dias.

**Regras importantes:**

* No início de mês, será definida uma meta de gastos considerando o gasto total de todos os cartões e seu vencimento;  
* Na entrada de dados, pelo Telegram, será possível adicionar os gastos por categoria (lazer, estudos, saúde, trabalho, casa, alimentação, delivery, transporte);  
* Na entrada de dados, será possível adicionar compras parceladas, considerando mês de início e mês de término;  
* Na entrada de dados, será perguntado o titular do cartão para registro na planilha;  
* O e-mail terá um resumo total de gastos, quanto falta para bater a meta do mês e um lembrete para dar entrada nos novos gastos.

## 🚀 Passo 3: Monte o prompt final

**Unir todas as peças construídas anteriormente em um único prompt completo**. 

**Atue como um especialista em N8N.**

Crie uma automação para registrar automaticamente meus gastos com cartão de crédito.

**Público:**  
Uso pessoal

**Ferramentas envolvidas:**  
Telegram, google sheets e gmail.

**Fluxo:**  
1\. Receber dados de canal no Telegram  
2\. Registrar dados em uma planilha financeira  
3\. Enviar resumo de gastos por e-mail a cada 4 dias.

**Regras:**

* No início de mês, será definida uma meta de gastos considerando o gasto total de todos os cartões e seu vencimento;  
* Na entrada de dados, pelo Telegram, será possível adicionar os gastos por categoria (lazer, estudos, saúde, trabalho, casa, alimentação, delivery, transporte);  
* Na entrada de dados, será possível adicionar compras parceladas, considerando mês de início e mês de término;  
* Na entrada de dados, será perguntado o titular do cartão para registro na planilha;  
* O e-mail terá um resumo total de gastos, quanto falta para bater a meta do mês e um lembrete para dar entrada nos novos gastos.  
    
  **Explique quais nós do N8N devem ser utilizados e a lógica de funcionamento do workflow.**

