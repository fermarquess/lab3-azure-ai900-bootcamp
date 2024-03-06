# Desafio de projeto

## Análise de Sentimentos com Language Studio no Azure AI

Projeto desenvolvido no Bootcamp Microsoft Azure AI Fundamentals - oferecido pela **[Digital Innovation One](https://www.dio.me/)**.

Para a prática deste laboratório é necessário ter uma conta na Microsoft e acessar o portal [Azure](https://portal.azure.com/).

## Passos

1. Realizar o login no portal [Azure](https://portal.azure.com/).

2. Clicar em **Create Resource**

   ![image](https://github.com/fermarquess/lab2-azure-ai900-bootcamp/assets/100250814/f8e55bf3-a8b9-4f45-aaf5-a0dbf81d4363)
   
3. Clicar em **AI + Machine Learning**, localizar **Language service** e clicar em **Create**

   ![image](https://github.com/fermarquess/lab3-azure-ai900-bootcamp/assets/100250814/67b9c431-ded9-4d74-bfef-f2a85f0b8c1a)

4. Clicar em **Continue to create resource**

   ![image](https://github.com/fermarquess/lab3-azure-ai900-bootcamp/assets/100250814/1dbdc29f-3b78-4c15-b85e-cb7e7359029a)

5. Então basta inserir o nome da Resource, o nome da instância e o price tier. No meu primeiro teste apareceu a opção F0, porém, por algum motivo, refazendo o processo ele não está mais disponível. Dessa forma, selecionei a outra opção disponível.

   ![image](https://github.com/fermarquess/lab3-azure-ai900-bootcamp/assets/100250814/94b8acaa-2427-4250-9642-ec52e02236a4)

   Por fim, clicar em **Review + Create** e em seguida em **Create**. Assim que o deploy for concluído com sucesso, clicar em **Go to Resource group**

6. Ao verificar que o deploy teve sucesso. Agora é o momento de acessar o [Language Studio](https://language.cognitive.azure.com/home)

7. Aí basta selecionar o diretório padrão, a Azure subscription, o resource type **Language** e o resource name que foi criado anteriormente. Clicar em **Done**.

   ![image](https://github.com/fermarquess/lab3-azure-ai900-bootcamp/assets/100250814/e969423b-09f9-46c2-ac00-5d955668af35)

8. Na tela seguinte devemos selecionar **Analyze sentiment and mine opinion**

   ![image](https://github.com/fermarquess/lab3-azure-ai900-bootcamp/assets/100250814/07f9815b-67a5-435f-b9c2-d599947114c5)

9. Então é possível realizar testes com os textos disponíveis no próprio portal ou subir algum texto para análise.

    ![image](https://github.com/fermarquess/lab3-azure-ai900-bootcamp/assets/100250814/f3645063-4591-47c1-8a9d-582539c4eaa7)

10. Ao inserir um texto é necessário selecionar que está ciente sobre um possível custo do serviço e clicar em **Run** e observar o resultado da frase após a análise.

    ![image](https://github.com/fermarquess/lab3-azure-ai900-bootcamp/assets/100250814/9a16afaa-1c56-4a7f-b241-a08db2270ca9)

    No exemplo acima podemos verificar que a análise foi de 50% positive e 50% negative justamente porque a frase diz coisas boas e ruins sobre a cidade de São Paulo.

    E como a análise da frase é quebrada, podemos verificar aqui os detalhes de cada parte:

    ![image](https://github.com/fermarquess/lab3-azure-ai900-bootcamp/assets/100250814/ab03ef0e-2739-409a-bfa8-dc1cff6b2a48)

## Demo

Neste repositório criei a pasta **Inputs** com sentenças que utilizei nos teste abaixo.
Segue os screenshots dos resultados das análises:

Sentença 2
![image](https://github.com/fermarquess/lab3-azure-ai900-bootcamp/assets/100250814/3d113a23-7510-4fde-8fda-0f901fafd96f)

Sentença 3
![image](https://github.com/fermarquess/lab3-azure-ai900-bootcamp/assets/100250814/17d4c0dd-13b1-44e5-8108-10236c30227a)

Sentença 4
![image](https://github.com/fermarquess/lab3-azure-ai900-bootcamp/assets/100250814/62aceea3-6d27-48f8-a4c5-c3fb4bee6485)
![image](https://github.com/fermarquess/lab3-azure-ai900-bootcamp/assets/100250814/ab406545-8fc8-4742-b5e8-00ad0acd922c)



## Principais insights

- Agilidade na análise de sensações por meio de texto;
- Facilidade para análise de grandes quantidades de texto;   

