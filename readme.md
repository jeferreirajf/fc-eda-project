# Execução

Após executar o comando 
```
docker compose up -d --build
```
na raiz do projeto, a aplicação de ```balances``` estará disponível em http://localhost:3003 e as demais aplicações estarão disponíveis em http://localhost:8080.

Primeiro execute uma requisição para criar uma transação no arquivo ```./service-01/api/client.http```. Depois, execute uma requisição utilizando o arquivo ```./service-02/api/client.http``` para consultar os balanços.