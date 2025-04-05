# Criando_um_Chatbot_Baseado_em_Conte-do_de_PDFs
Este projeto consiste em desenvolver um sistema de chatbot capaz de responder perguntas com base em informações extraídas de documentos PDF. O processo envolve a utilização de técnicas de Processamento de Linguagem Natural (NLP) para analisar e compreender o conteúdo dos PDFs. Um modelo de Machine Learning é treinado para interpretar perguntas e encontrar as respostas mais relevantes no texto. O chatbot pode ser implantado como um serviço web, permitindo interações em tempo real. Tecnologias como APIs de NLP, serviços de armazenamento em nuvem e frameworks de Machine Learning são utilizadas para construir e escalar a solução.


## 🔗 Links
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/monica-riegel/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MonicaRiegel)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/5551998152447)
[![E-mail](https://img.shields.io/badge/-Email-000?style=for-the-badge&logo=microsoft-outlook&logoColor=007BFF)](mailto:monicariegel@hotmail.com)


## Entendendo o Desafio - Criando um Chatbot Baseado em Conteúdo de PDFs 🍦📊 
Agora é a sua hora de brilhar e construir um perfil de destaque na DIO! Explore todos os conceitos explorados até aqui e replique (ou melhore, porque não?) este projeto prático. Para isso, crie seu próprio repositório e aumente ainda mais seu portfólio de projetos no GitHub, o qual pode fazer toda diferença em suas entrevistas técnicas 😎

## Visão Geral do Desafio
Neste desafio, você desenvolverá um chat interativo que responderá com base no conteúdo dos seus arquivos PDF. Para isso, utilizaremos conceitos de IA generativa, embeddings e buscas vetorizadas para estruturar um sistema capaz de entender, processar e responder perguntas a partir de documentos específicos. Essa abordagem permitirá que você crie um modelo personalizado de assistência virtual focado em um conjunto de informações proprietárias, sem depender unicamente do conhecimento geral de modelos pré-treinados.

## Cenário
Imagine que você é um estudante de Engenharia de Software, prestes a escrever seu Trabalho de Conclusão de Curso (TCC). Para isso, você precisa revisar e correlacionar diversos artigos científicos. Entretanto, à medida que acumula mais documentos, torna-se cada vez mais difícil extrair informações relevantes e conectar ideias entre diferentes textos.

Diante desse desafio, você decide utilizar inteligência artificial para facilitar esse processo, criando um sistema de busca inteligente capaz de interpretar os PDFs, organizar informações e gerar respostas relevantes com base no conteúdo carregado.

 

## Objetivo
O objetivo deste projeto é permitir que você:

✅ Carregue arquivos PDF contendo informações relevantes para seu estudo ou projeto.
✅ Implemente um sistema de busca vetorial para indexar e recuperar informações dos PDFs.
✅ Utilize inteligência artificial para gerar respostas baseadas no conteúdo dos documentos carregados.
✅ Desenvolva um chat interativo onde seja possível realizar perguntas e obter respostas contextuais fundamentadas nos arquivos.

 

## Entrega
Para iniciar esse projeto foi preparado o ambiente no Azure AI Foundry, e iniciado um novo projeto
![3-Criando novo projeto](https://github.com/user-attachments/assets/a1d5f2af-93e6-4816-b3b4-e418bd310bb7)


![4-Projeto criado](https://github.com/user-attachments/assets/f8349c98-cee8-4acb-b1bb-454c97f53396)


Em seguida foi sugerido a implantação do modelo GPT-4o,  
![5-Erro ao implantar o modelo GPT-4o](https://github.com/user-attachments/assets/a5f92ace-1414-4804-855d-b7afe6ebdfd4)


mas como uso a assinatura de estudante não tive cotas suficientes para utilizar esse modelo, recorrendo ao uso do GPT-35-turbo
![6-Implantação gpt-35-turbo](https://github.com/user-attachments/assets/d81bc024-6399-41db-b76a-d636bbdc1ce9)

E por fim implantamos o modelo text-embedding-large, para converter textos em vetores
![7-Implantação text-embedding-3-large](https://github.com/user-attachments/assets/16ca83bf-a524-4b29-be29-84d6b9e09cb4)

Após essas configurações podemos entrar no Playground de chat e iniciar os testes
![8-Playground de chat](https://github.com/user-attachments/assets/b163ac6a-e60c-4e6d-94db-2f202051f306)

Com tudo funcionado é a hora de carregar nossos arquivos PDF, para meu experimento utilizei os mesmos artigos utilizados durante o treinamento, com exceção de um que não estava disponível.

Após criar os índices com os vetores já é possível interagir com o chat e obter respostar referentes aos arquivos PDF.







