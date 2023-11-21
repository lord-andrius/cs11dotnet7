# 1) É o Visual Studio 2022 melhor que o Visual Studio Code?
## R = Depende se estamamos falando de desenvolvimento desktop sim, se falamos de desenvolvimento web não.
# 2) É .NET 5 e posteriores melhores que o .NET Framework?
## R = Sim pois estes são multiplataforma e desempenham muito melhor.
# 3) O que é .NET Standard e por que ainda é relevante?
## R = O .NET Standard foi um padrão usado na transição do .NET Framework para o .NET que permitia a interoperabilidade entre diferentes runtimes .NET. Ainda se mantêm relevante pois ainda a bases de código legadas que foram escritas em .NET Framework e estas precisam ainda serem mantidas.
# 4) Por que programadores podem usar diferentes linguagens de programação, por exemplo, C# e F#, para escrever aplicações que rodam em .NET?
## R = Porque qualquer linguagem que compile para IL(intermidiate language) pode ser usada para escrever programas para a plataforma .NET uma vez que ela é basicamente um interpretador de IL.
# 5) O que são os programas 'Top-level' e o como você pode acessar os argumentos neles?
## R =  São programas em que podemos simplesmente começar a digitar os comando(statements) sem a necessidade de uma declaração de um método main.Acessamos os argumentos de um programa 'Top-level' atravez da variável 'args'.
# 6) Qual o nome do método que é o ponto de entrada para os aplicativos de console .NET e como declara-los se não estamos em um programa 'Top-level'?
## R = O método que é a ponta de entrada se chama 'Main'. Podemos declarar o método 'Main' das seguintes formas:
```
public static void Main(string[] args){}
``` 
ou 
```
public static void Main(){}
```
# 7) Qual linha de comando você usa para compilar e executar um projeto em c#?
## R = Para compilar e executar deve-se usar o seguinte comando: `dotnet run`
# 8) Quais são os benefícios de usar o 'Polyglot Notebook' para escrever código C#?
## R =  Estes são os benefícios:
- Você pode por notas ao lado dos códigos
- Pode-se executar os cadernos sem instalar nada
# 9) Onde se pode achar ajuda com uma palavra reservado do C#?
## R = Podemos pesquisar no Google, stackoverflow e ainda na documentação oficial da Microsoft.
# 10) Onde você olharia para problemas comuns na codificação?
## R = No Stackoverflow
