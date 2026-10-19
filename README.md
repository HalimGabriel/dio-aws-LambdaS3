Executando Tarefas Automatizadas com AWS Lambda e Amazon S3

📌 Sobre o Projeto

Este repositório reúne anotações e conceitos aprendidos durante o laboratório da DIO sobre automação de tarefas utilizando AWS Lambda e Amazon S3.

O objetivo é compreender como integrar serviços da AWS para executar funções automaticamente a partir de eventos, reduzindo a necessidade de intervenção manual e facilitando a construção de soluções escaláveis.

🎯 Objetivos de Aprendizagem

Compreender o funcionamento do AWS Lambda.

Entender o armazenamento de objetos utilizando Amazon S3.

Conhecer as possibilidades de integração entre Lambda e S3.

Explorar a automação de tarefas orientada a eventos.

Documentar os conhecimentos adquiridos utilizando Markdown e GitHub.

☁️ Serviços AWS

Amazon S3

Serviço de armazenamento de objetos que permite armazenar e recuperar arquivos em buckets. Pode ser utilizado para armazenar documentos, imagens, arquivos de dados e outros conteúdos.

AWS Lambda

Serviço de computação sem servidor (serverless) que permite executar código em resposta a eventos, sem precisar administrar diretamente servidores.

Integração entre Lambda e S3

O Amazon S3 pode gerar eventos, como o envio de um novo objeto para um bucket, que podem acionar uma função Lambda configurada para processar o conteúdo automaticamente.

Exemplos de aplicações:

Processamento de arquivos enviados para um bucket.

Redimensionamento automático de imagens.

Validação e transformação de arquivos.

Execução de rotinas automatizadas após o upload de objetos.
