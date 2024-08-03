# ChatBot Maritaca

## Conteúdo
- [Introdução](#introdução)
- [Como utilizar](#como-utilizar)
- [Parametros](#parametros)

# Introdução
Esse projeto é um exemplo simples de como utilizar a lib [OpenAI](https://github.com/openai/openai-dotnet) para `.NET` para criar um chatbot utilizando a API [Maritaca AI](https://github.com/maritaca-ai). 
O modelo utilizado é o `sabia-3` que é capaz de responder perguntas em portugûes.

## Como utilizar
É necessário ter uma conta na Maritaca AI para obter uma chave de API.

## Parametros

- `key`: Chave de API da Maritaca AI.
- `model`: Modelo de linguagem a ser utilizado. No exemplo está sendo utilizado `sabia-3`.
- `url`: URL da Maritaca AI api https://chat.maritaca.ai/api.
- `nameProject` : Nome do seu projeto ou aplicação.
- `maxTokens`: Número máximo de tokens a serem gerados na resposta.
- `temperature`: Controla a aleatoriedade das respostas. Quanto maior o valor, mais aleatórias as respostas serão.
