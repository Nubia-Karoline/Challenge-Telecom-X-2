<h1 align="center"> Challenge TelecomX-2 </h1>

# Análise Preditiva de Evasão de Clientes

Este repositório contém a solução para o desafio da Telecom X, focado na análise preditiva de evasão de clientes, utilizando técnicas de Machine Learning para identificar fatores que levam ao cancelamento dos serviços.


🎯 Objetivo
A Telecom X enfrenta um alto índice de cancelamentos e busca:

* Coletar, tratar e preparar os dados dos clientes.
* Analisar e explorar os dados para entender o comportamento dos clientes.
* Desenvolver modelos preditivos para identificar clientes com maior risco de evasão.
* Oferecer insights estratégicos para reduzir a evasão e melhorar a retenção.

🧹 Limpeza e Tratamento de Dados
Principais etapas realizadas:

* ✅ Importação e tratamento de dados, incluindo transformação de variáveis categóricas e numéricas.

* ✅ Remoção de valores ausentes e padronização dos dados.

* ✅ Análise de correlação para seleção e exclusão de variáveis redundantes.

* ✅ Preparação dos dados para modelagem preditiva.


🔍 Análise Exploratória e Modelagem Preditiva
* Proporção de evasão: cerca de 25,8% dos clientes cancelaram os serviços.
* Modelos testados: Regressão Logística, Random Forest e modelo Random.
* Melhor modelo: Regressão Logística, com acurácia de 79,96%, precisão de 65,44%, recall de 52,14% e F1-score de 58,04%.
* Variáveis mais relevantes para previsão:
* Tempo de Contrato (clientes com contratos mais curtos têm maior risco)
* Valor Mensal (valores mais altos correlacionam com evasão)
* Serviços adicionais como segurança online e backup também influenciam.

💡 Recomendações Estratégicas
* Desenvolver ações de retenção personalizadas para clientes com contratos curtos e valores mensais elevados.
* Oferecer pacotes promocionais e descontos progressivos para aumentar a fidelização.
* Utilizar o modelo de Regressão Logística para monitoramento contínuo, possibilitando intervenções proativas em clientes com maior risco de evasão.

📊 Análise de dados - Gráficos

<img width="1735" height="735" alt="image" src="https://github.com/user-attachments/assets/7017ac89-2ff8-475a-8c93-9025657f6838" />
<img width="1477" height="710" alt="image" src="https://github.com/user-attachments/assets/73b00820-7675-4bb4-8ec5-7e09e7736ca5" />
<img width="1236" height="732" alt="image" src="https://github.com/user-attachments/assets/fd64953d-703b-4dca-97bf-6bec0ff14603" />



🔧 Tecnologias e Ferramentas
* Python 3.10+
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Google Colab / VSCode

✍️ Autor
Projeto desenvolvido por Núbia Karoline como parte de um desafio de análise de dados no setor de telecomunicações.


📝 Licença

Para fins de prática e estudo, distribuído livremente sob a MIT License.
