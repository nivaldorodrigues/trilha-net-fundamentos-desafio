# Sistema de Estacionamento - Trilha .NET Fundamentos

Este projeto é um sistema simples de estacionamento desenvolvido como desafio da trilha de Fundamentos do .NET. O objetivo é praticar conceitos básicos de C#, como classes, métodos, listas, entrada e saída de dados, além de lógica de programação.

## Funcionalidades

- Cadastro de veículos (placa)
- Remoção de veículos com cálculo de valor a pagar
- Listagem de veículos estacionados
- Menu interativo no console

## Alterações Recentes

- Implementação completa dos métodos `AdicionarVeiculo`, `RemoverVeiculo` e `ListarVeiculos` na classe `Estacionamento`.
- Correção do fluxo de entrada de dados para evitar erros e melhorar a experiência do usuário.
- Tratamento de exceções e validações para evitar falhas na execução.
- Comentário da linha `Console.Clear()` no menu principal para evitar exceções em ambientes sem console.

## Como Executar

1. Clone este repositório:
   ```
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Acesse a pasta do projeto:
   ```
   cd trilha-net-fundamentos-desafio/DesafioFundamentos
   ```
3. Compile e execute:
   ```
   dotnet run
   ```

## Observações
- O projeto foi desenvolvido para rodar no terminal/console.
- Caso execute em ambientes como VS Code, a tela não será limpa devido à limitação do ambiente.
- O código está comentado para facilitar o entendimento.

---

Desafio prático da trilha .NET da DIO.
