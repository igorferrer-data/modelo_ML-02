# Machine Learning Automatizado no Azure Machine Learning

## Objetivo 

Entrega do desafio DIO - Trabalhando com Machine Leraning na Prática no Azure ML

## Instruções (PT-BR)

1- Entre no portal do Azure usando https://portal.azure.com e acesse com suas credenciais da Microsoft.

2- Em "All Services" pesquise o serviço "Azure Machine Learning"

![image](https://github.com/igorferrer-data/modelo_ML-02/assets/155840444/94a4a97e-59eb-4d26-bdfb-a61fe606dbca)
 
3- Crie um Workspace e preencha as informações necessárias, após clique em "Review + Create" (esse passo pode demorar alguns minutos, aguarde a mensagem de sucesso)

Obs.: Caso ainda não possua um Resource Group, basta clicar em "Create New" e criar um com título desejado

![image](https://github.com/igorferrer-data/modelo_ML-02/assets/155840444/29e93e7b-1597-49f7-a4d2-472a0258ccbf)

4- Selecione "Launch Studio" (uma nova guia do navegador será aberta). 
Ou navegue para https://ml.azure.com e entre no Azure Machine Learning Studio usando sua conta da Microsoft. Feche todas as mensagens exibidas.

![image](https://github.com/igorferrer-data/modelo_ML-02/assets/155840444/6611d592-c74f-48de-8102-ff90ee4a905f)

### Use aprendizado de máquina automatizado para treinar um modelo

5- No Azure Machine Learning Studio , vá para ML Automatizado.

![image](https://github.com/igorferrer-data/modelo_ML-02/assets/155840444/97f33ef4-0e13-421b-b98e-2861075f42c0)

6 - Crie um novo trabalho de ML automatizado preenchendo as configurações, usando Next conforme necessário para avançar pela interface do usuário.

- Etapas de preenchimento:
![image](https://github.com/igorferrer-data/modelo_ML-02/assets/155840444/2be32039-9478-45d4-9295-a8e4e2cff8f9)

7 -  Após preencher as configurações necessárias, selecionar o tipo de tarefa e informar o conjunto de dados, na etapa "Examinar" sigo com "Enviar trabalho de treinamento" para o treinamento e seleção do melhor modelo após resultados.

8- Nos menus lateral esquerdo vai em "Tarefas (Jobs)", selecione o teste que foi realizado e clique no "MELHOR" modelo

![image](https://github.com/igorferrer-data/modelo_ML-02/assets/155840444/ace0aae4-ed72-4d85-8136-0d5f947dd6dc)

9 - Dentro do Melhor Modelo, clique em "Implantar" e selecione "Serviços da Web". Preencha as configurações conforme necessário. Aguarde até que o status fique "Concluído". (Esse passo pode demorar alguns minutos)

![image](https://github.com/igorferrer-data/modelo_ML-02/assets/155840444/43870d6e-806d-4809-830e-d52361775e8a)

### Teste o modelo implantado

10 - Após modelo implantado com Sucesso, vá até o menu lateral esquerdo e selecione "Pontos de extremidades".
Selecione o nome criado no passo 9.

11- Vá para aba "Testar" e preencha os parametros para teste e clique em testar

![image](https://github.com/igorferrer-data/modelo_ML-02/assets/155840444/62c71041-6805-4539-a767-452532fcea75)

# Doc de Referência - Lab Microsoft

https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html



