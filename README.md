Projeto Blazor Counter

Projeto básico em Blazor Server que demonstra um componente de contador com valor de incremento configurável.

Funcionalidade
Página inicial chama o componente Counter
O contador incrementa com base em um parâmetro
Valor padrão de incremento: 100
Exemplo usando incremento de 250 na página inicial
Exemplo

Uso do componente:

<Counter IncrementarQuantia="250" />

Parâmetro no componente:

[Parameter]
public int IncrementarQuantia { get; set; } = 100;
Como executar
Instale o .NET SDK
No terminal, execute:
dotnet run
Acesse no navegador:
https://localhost:5001
Tecnologias
Blazor Server
.NET
