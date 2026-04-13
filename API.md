# Qatrol Coin API

Base URL: `https://qatrol.ru/api`

## GET /stats
Статистика сети.

Response:
{
  "blocks": 1688,
  "difficulty": 8,
  "hashrate": 1913340,
  "totalSupply": 1000000000,
  "circulatingSupply": 23576.32
}

## GET /chain
Последние блоки. Query: `?limit=10`

## GET /block/:hashOrIndex
Информация о блоке.

## GET /balance/:address
Баланс адреса.

## GET /pool/stats
Статистика майнинг-пула.
