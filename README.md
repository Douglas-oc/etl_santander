# Explorando IA Generativa em um Pipeline de ETL com Python

Este é um dos vários desafios de projetos do Bootcamp Santander com Python da DIO. Com o intuito de criar mensagens personalizadas para clientes de um banco falando sobre a importância de investir. Tudo isso utilizando IA Generativa, para gerar as mensagens, e Python, como linguagem principal. 



## Algumas das mensagens que foram geradas

```javascript
"Jesse, investir é o caminho para construir seu futuro financeiro. Vamos começar hoje?"

"Pam, não perca a chance de alcançar seus objetivos financeiros. Comece a investir agora!"

"Jim, o investimento é a chave para a segurança financeira. Vamos criar um plano juntos?"
```


## Passo a passo

- 1-Extract: A extração de dados dos clientes foi feita através de uma API do "Santander Dev Week 2023";
- 2-Transform: Com a API do GPT, as mensagens são geradas e enviadas para os clientes;
- 3-Load: Os dados dos clientes, agora com a mensagem, são atualizados na API.

## Imports



`pandas` 

`requests`

`json`

`openai`



