# Machine Learning Automatizado no Azure Machine Learning

## Instruções

1 - Entre no portal do Azure usando https://portal.azure.com e acesse com suas credenciais da Microsoft.

2 - Em "All Services" pesquise o serviço "Azure Machine Learning".

![image](https://github.com/user-attachments/assets/75dc768b-e48b-4bfc-b4f2-9e6e28b3e0fe)

 
3 - Crie um Workspace e preencha as informações necessárias, após clique em "Review + Create" (esse passo pode demorar alguns minutos, aguarde a mensagem de sucesso).

Obs.: Caso ainda não possua um Resource Group, basta clicar em "Create New" e criar um com título desejado.

![image](https://github.com/user-attachments/assets/15c663b3-a976-4d6c-98d7-269266c6ded6)


4 - Selecione "Launch Studio" (uma nova guia do navegador será aberta). 
Ou navegue para https://ml.azure.com e entre no Azure Machine Learning Studio usando sua conta da Microsoft. Feche todas as mensagens exibidas.

![image](https://github.com/user-attachments/assets/077b5744-d1f2-47ee-ae7d-ee621fb643ad)


### Use aprendizado de máquina automatizado para treinar um modelo.

5 - No Azure Machine Learning Studio , vá para ML Automatizado.

![image](https://github.com/user-attachments/assets/f86c8fea-19cf-46b7-9f5d-e8db08a46c15)


6 - Crie um novo trabalho de ML automatizado preenchendo as configurações, usando Next conforme necessário para avançar pela interface do usuário.

Etapas de preenchimento:
![image](https://github.com/user-attachments/assets/2c2482cb-9b29-4bd9-a86e-0e2db6225056)


7 -  Após preencher as configurações necessárias, selecionar o tipo de tarefa e informar o conjunto de dados, na etapa "Examinar" sigo com "Enviar trabalho de treinamento" para o treinamento e seleção do melhor modelo após resultados.

8 - Nos menus lateral esquerdo vai em "Tarefas (Jobs)", selecione o teste que foi realizado e clique no "MELHOR" modelo.

![image](https://github.com/user-attachments/assets/a66f9057-3311-4686-afef-766265350ff0)


9 - Dentro do Melhor Modelo, clique em "Implantar" e selecione "Serviços da Web". Preencha as configurações conforme necessário. Aguarde até que o status fique "Concluído". (Esse passo pode demorar alguns minutos).

![image](https://github.com/user-attachments/assets/e2a409cc-f4bf-49b5-aa3e-8bda5c369620)


### Teste o modelo implantado.

10 - Após modelo implantado com Sucesso, vá até o menu lateral esquerdo e selecione "Pontos de extremidades".
Selecione o nome criado no passo 9.

11 - Vá para aba "Testar" e preencha os parametros para teste e clique em testar.

![image](https://github.com/user-attachments/assets/ac8f85cc-59f8-4d1b-a433-f49f7bb3440d)


## Doc de Referência - Lab Microsoft

https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html



