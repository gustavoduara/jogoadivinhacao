# jogo adivinhação

![](https://i.imgur.com/AWlzjd5.gif)

## Descrição

O **jogo de adivinhação** é um simples jogo, que simula um jogo de adivinhação a partir 
de um número gerado aleatoriamente. O jogo poossui diferntes níveis de dificuldade


## Funcionalidades


### Niveis de dificuldade

- 1-Facíl - 10 tentativas
- 2-Médio - 5 tentativas
- 3-Difícil - 3 tentativas

### Regras

- O jogador deve adivinhar um número entre 1 e 20, em caso de erro, o sistema informa se o número é maior ou menor que o número sorteado

### Validar entrada

- Garante que o jogador informe um número válido

 ## Como ultilizar

 1. Clone o repositório ou baixe o código-fonte.
 2. Abra o terminal ou prompt de comando e navegue até a pasta raiz do projeto.
 3. Utilize o comando abaixo para restaurar as dependências do projeto:
 
 ```
 dotnet restore
 ```
 
4. Em seguida, compile a solução o comando:

 ```

 dotnet build --configuration Release

 ```

 5. Para executar o projeto compilando em tempo real

 ```

 dotnet run --project JogoDeAdivinhacao.ConsoleApp

 ```

 6. Para executar o arquivo compilado, navegue até a pasta 

 ```

 JogoDeAdivinhacaoConsoleApp.exe

 ```

 
 ## Requisitos
 
 - .NET SDK (recomendado .NET 8.0 ou superior) para compilação e execução do projeto.
 
