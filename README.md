= PROJETO: CALCULADORA SIMPLES             =
= DESENVOLVEDOR: FERNANDO AUGUSTO DA SILVA =

= DESCRIÇÃO =
= Este projeto é uma calculadora simples desenvolvida em C++, com o objetivo de praticar conceitos
  básicos da linguagem, como:
- Entrada e saída de dados (cin, cout);
- Estruturas condicionais (if, switch);
- Laços de repetição;
- Organização do código em funções.

= O programa permite realizar as quatro operações básicas (adição, subtração, multiplicação e divisão)
  e oferece um menu interativo no console.

= FUNCIONALIDADES =
- Somar dois números
- Subtrair dois números
- Multiplicar dois números
- Dividir dois números (com verificação de divisão por zero)
- Repetir operações até o usuário escolher sair

= CONCEITOS APLICADOS =
- Estruturas de repetição (while)
- Estruturas condicionais (switch)
- Entrada e saída de dados (cin, cout)
- Organização modular com funções

= ESTRUTURA DO PROJETO =
= O programa utiliza estruturas de repetição e controle de fluxo para permitir múltiplos cálculos
  até que o usuário decida encerrar o programa.

= ORGANIZAÇÃO =
- Função main(): Controla o fluxo principal do programa.
- Função cin(): Recebe os dados digitados pelo usuário.
- Função cout(): Exibe no terminal as mensagens.
- Estrutura while(opcao != 5): Mantém o programa rodando até o usuário escolher sair.
- Estrutura switch(): Decide qual operação matemática será executada.

= COMO USAR? =
= Se você for executar no terminal CMD no Windows, aqui vai um passo a passo:
- Você deve estar na pasta onde criou o arquivo "nomedoarquivo.cpp" para conseguir rodar o programa.
  Caso não saiba mexer no CMD, use o comando "cd" para acessar a pasta desejada e o comando "dir" para
  listar as pastas dentro do diretório atual.
- Após seguir os passos anteriores, compile o programa com:
  "g++ nomedoarquivo.cpp -o calculadora"
- Em seguida, execute com:
  "./calculadora"

= Se você for executar o programa no VS Code ou em qualquer outra IDE, crie um projeto com qualquer nome,
  mas com a extensão ".cpp", copie e cole o código e então rode o programa.
