#  API de Vendas - FastAPI

Este projeto é uma API simples construída com [FastAPI](https://fastapi.tiangolo.com/) para simular um sistema de vendas.

##  Tecnologias
- Python 3.9+ 
- FastAPI
- Uvicorn (para rodar o servidor)

##  Funcionalidades
- **`GET /`** → retorna o total de vendas registradas.
- **`GET /vendas/{id_venda}`** → retorna os detalhes de uma venda pelo seu ID.

### Exemplo de retorno da rota `/`:
```json
{
  "Vendas": 4
}
