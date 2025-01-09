# Consultando sua CriptoMoeda em Java com a API CoinGecko

Este é um programa em Java que permite consultar a cotação atual de criptomoedas em relação ao dólar (USD) utilizando a API pública do CoinGecko.

## Funcionalidades

- Solicita ao usuário o nome de uma criptomoeda.
- Faz uma requisição HTTP para obter a cotação atual da criptomoeda informada.
- Exibe a resposta da API com o preço da criptomoeda em dólar (USD).

## Requisitos

- **Java 11 ou superior**: O programa utiliza a classe `HttpClient`, introduzida no Java 11.
- **Conexão com a Internet**: Necessária para realizar a requisição à API do CoinGecko.

## Como executar

1. Certifique-se de ter o Java 11 ou superior instalado.
2. Compile o programa com o seguinte comando:
   ```bash
   javac ConsultaCotacaoCripto.java
