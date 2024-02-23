# Introdução 
Modelo de Machine Learning criado no Azure durante o curso da DIO

# Objetivos
Recriar os passos do tutorial: [Link](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html)


# Passo 1 - Criar workspace em Azura Machine Learning
* Após entrar na sua conta, selecione criar um recurso (+ create a resource)
![image](https://github.com/Mihvieira/ml_bikes-rentals/assets/136247614/84d622b4-806f-4f80-b04a-e2db21415a79)
* Selecione Criar em Azure Machine Learning

![image](https://github.com/Mihvieira/ml_bikes-rentals/assets/136247614/9de98f25-cf93-4514-ab9c-718f60ae6764)

* Na tela seguinte preencha as configurações de acordo com as instruções do link
  *O campo subscrição se refere a sua assinatura do Azure;
  * No campo região. coloque a região mais próxima de onde estiver
  * Para o restante deixe como estiver definido, clique em "Consultar + criar"

# Passo 2 - Clique em "Iniciar o estúdio"

![image](https://github.com/Mihvieira/ml_bikes-rentals/assets/136247614/641811b8-dd6b-4126-bf37-02e3efbfde53)

# Passo 3 - Procure o botão "ML automatizado"

![image](https://github.com/Mihvieira/ml_bikes-rentals/assets/136247614/021f0986-e93f-4278-b538-27cd8653d483)
Em seguida clique em:

![image](https://github.com/Mihvieira/ml_bikes-rentals/assets/136247614/cfa61472-d5ae-45df-bae0-f092c116f927)

Preencha as informações básicas
![image](https://github.com/Mihvieira/ml_bikes-rentals/assets/136247614/d5e1155d-b875-40ab-a904-2e6a85e95aff)

Em tipo de dados coloque o nome dos dados, uma descrição e o tipo Tabular, em seguida clique no botão para arquivos da WEB (se o botão não aparecer é porque há algum erro, o ideal é iniciar novamente o cadastro)

Nas Configurações mude apenas o cabeçalho das colunas, marcando que a primeira linha é o cabeçalho

O tipo de tarefa de dados nesse caso será a Regressão e a coluna de destino é a Rentals

Após concluído o processo de criação vá até o nome do algoritmo
![image](https://github.com/Mihvieira/ml_bikes-rentals/assets/136247614/554a0bae-52bb-4f9e-a0b8-c5d46871beaa)

No campo métricas é possível visualizar gráficos e medidas
![image](https://github.com/Mihvieira/ml_bikes-rentals/assets/136247614/5b83b931-83a7-4aba-a448-d012980f9d86)

Clique em Implementar ![image](https://github.com/Mihvieira/ml_bikes-rentals/assets/136247614/d2d26abf-2583-4cf9-acbd-97da05f0ee1a)

Após em Serviço da Web, preencha os dados e clique em Implementar

![image](https://github.com/Mihvieira/ml_bikes-rentals/assets/136247614/85f8f553-6a9f-44bf-8ce5-3737f954cdcc)

Depois de concluída a implementação, vá até pontos de extremidade ou pontos finais (dependendo da versão do azure)

![image](https://github.com/Mihvieira/ml_bikes-rentals/assets/136247614/a44a5691-a3c9-4475-8a9d-19d2e322d8fc)

Clique em Testar e você poderá editar o arquivo json e verificar os resultados

# Final - Testando o modelo
![azure](https://github.com/Mihvieira/ml_bikes-rentals/assets/136247614/d362951d-100e-4575-b89f-bdb5ddd288b2)
