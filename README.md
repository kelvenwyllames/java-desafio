# Desafio de Controle de Fluxo

Este projeto representa um desafio de controle de fluxo, onde são recebidos dois parâmetros via terminal e é realizada a impressão dos números incrementados de acordo com os parâmetros.

## Funcionalidades

O projeto possui as seguintes funcionalidades:

1. **Contador**: Recebe dois parâmetros via terminal e imprime números incrementados com base nesses parâmetros.

2. **Exceção ParametrosInvalidosException**: Define uma exceção personalizada para tratar o caso em que o segundo parâmetro é menor ou igual ao primeiro.

## Estrutura do Código

O código está organizado da seguinte maneira:

-   **`DesafioControleFluxo`**: Pacote que contém as classes relacionadas ao desafio de controle de fluxo.

    -   **`Contador`**: Classe principal que contém o método `main` para iniciar o contador.

    -   **`ParametrosInvalidosException`**: Classe que representa a exceção de parâmetros inválidos.

## Utilização

Para executar o programa, é necessário compilar as classes e executar a classe `Contador`. Os números devem ser inseridos como parâmetros via terminal.

```bash
javac Contador.java ParametrosInvalidosException.java
java DesafioControleFluxo.Contador
```
