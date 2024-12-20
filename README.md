# AzorHostexApi
Api para integração com a Hostex (aplicativos de hospedagem como (AirBnb, Booking.com)

# Hostex

Responsável pela integração com as aplicações de hospedagem como AirBnb, Booking.com entre outras apliciações.

Documentação do Hostex disponível no link [Documentação](https://hostex-openapi.readme.io/reference)

Preciso criar novas apis para integrar com Expedia? 
*Não, basta apenas acessar o portal do Hostex no link "https://hostex.io/app/connected-accounts/list" para conectar com a sua conta.

```python
Documentação da API
https://hostex-openapi.readme.io/reference/overview


```python
# Como Utilizar o pacote no projeto?

Instale o pacote pelos comandos

# .Net core
dotnet add package AzorHostexApi --version x.x.x
ou
Install-Package AzorHostexApi -Version x.x.x 

Dentro do program.cs do seu projeto, instancia a api no services:
builder.Services.AddAzorHostexApi(hostexAccessToken);

Sendo o hostexAccessToken o token que você cria junto a conta diretamente no cadastro com a Hostex
