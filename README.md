# Pipeline de Dados: Telegram para AWS com Análise Exploratória
![Texto alternativo para a imagem](https://wellingtonfly.site/pipelinededados.3aef0c3d.png)

Este projeto demonstra a extração de dados do Telegram, sua transferência para um Datalake na AWS, processamento em lote na nuvem e análise dos dados tratados. 

## Conteúdo

* **Introdução**
    * Objetivo
    * O que é Pipeline?
    * Pipeline do projeto
* **Sistema Transacional**
    * Ingestão de dados
    * O que é uma API?
    * Telegram Botfather
    * AWS API Gateway
    * Webhook
* **Sistema Analítico**
    * O que é ETL?
    * Extração
    * Transformação
    * Carregamento
* **Apresentação**
    * AWS Athena
    * Análise de Dados
* **Conclusão**

## Como usar

1. **Configurar ambiente AWS:**
    * Criar um bucket S3 para dados brutos e outro para dados enriquecidos
    * Configurar funções Lambda para extração e transformação
    * Configurar um Event Bridge para acionar a transformação diária
    * Criar uma tabela no Athena para consultar os dados

2. **Configurar o Telegram:**
    * Criar um bot usando o BotFather
    * Adicionar o bot a um grupo
    * Configurar um webhook para enviar mensagens para a API Gateway

3. **Executar o projeto:**
    * As mensagens do Telegram serão enviadas para o S3
    * A função Lambda de transformação será executada diariamente
    * Os dados transformados serão armazenados no S3
    * Consultar e analisar os dados usando o Athena

## Tecnologias Utilizadas

* **AWS:**
    * API Gateway
    * Lambda
    * S3
    * Athena
    * Event Bridge
* **Telegram:**
    * BotFather
    * Webhooks
* **Outras:**
    * Python
    * PyArrow
    * SQL

## Análises Realizadas

* Quantidade de mensagens por dia
* Quantidade de mensagens por usuário por dia
* Média do tamanho das mensagens por usuário por dia
* Quantidade de mensagens por hora por dia da semana por número da semana

## Conclusão

Este projeto demonstra como integrar o Telegram com a AWS para análise de dados, otimizando operações e oferecendo suporte à tomada de decisões. A análise de dados impulsionada por pipelines na nuvem permite extrair insights valiosos das interações dos usuários.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

## Observações

* Certifique-se de ter as credenciais da AWS configuradas corretamente.
* Adapte o código Python às suas necessidades específicas.
* Explore outras análises e visualizações com os dados coletados.

## Contato

Em caso de dúvidas ou sugestões, entre em contato.
