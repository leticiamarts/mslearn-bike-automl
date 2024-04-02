# mslearn-bike-automl

## Explicando o Projeto
 O projeto foi estruturado conforme o arquivo de referência [mslearn-bike-automl](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html).

## Passos
- Login na plataforma Azure Machine Learning
- Trial gratuíto de 30 dias
- Configuração de Workspace
- Uso de Automated ML conforme dados da referência da Azure
- Criação do modelo de previsão com seus devidos pontos de extremidade (endpoints) configurados
- Execução do modelo
- Revisão do melhor modelo
- Análise de métricas
- Deploy e teste do modelo
- Endpoints salvos e armazenados no projeto

## Teste

Validação foi feita através da inserção de dados para teste de ponto de extremidade
Os dados inseridos foram utilizados conforme orientação da documentação consultada e está disponibilizado abaixo:

```json
 {
   "Inputs": { 
     "data": [
       {
         "day": 1,
         "mnth": 1,   
         "year": 2022,
         "season": 2,
         "holiday": 0,
         "weekday": 1,
         "workingday": 1,
         "weathersit": 2, 
         "temp": 0.3, 
         "atemp": 0.3,
         "hum": 0.3,
         "windspeed": 0.3 
       }
     ]    
   },   
   "GlobalParameters": 1.0
 }

 ````
