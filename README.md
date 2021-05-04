# Bank-NET API
## Objetivo
Criar um console app que simula um sistema bancário simplificado, permitindo cadastrar, 
listar contas, sacar, transferir valores entre contas cadastradas.
## Tecnologia
Esta aplicação foi desenvolvida utilizando C#, .NET 5.0 e JetBrains Rider como IDE.
## Como testar
Para executar esta aplicação é preciso ter o .NET 5.0 instalado.
Clonar este repositório.
Utilizando sua IDE favorita, importar o projeto.
Após a importação, abrir o arquivo `Program.cs` e executá-lo.
Um menu de opções será apresentado no console:
Informe a opçao desejada:

    1- Listar contas
    2- Inserir nova conta
    3- Transferir
    4- Sacar
    5- Depositar
    C- Limpar Tela
    X- Sair

Basta digitar o número ou letra correspondente à opção escolhida, seguir as instruções da tela
e observar a execução do programa.
Após a finalização do programa, todos os dados utilizados para testes são perdidos, pois não são
persistidos em banco de dados. A cada nova execução será preciso fazer novamente o cadastramento
das contas para testes.

