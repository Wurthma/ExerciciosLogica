### Lista de exercícios para praticar algoritmos e lógica de programação

Este repositório possui uma lista de exercícios para serem desenvolvidos na linguagem de sua preferência ou pseudocógido.
Costumo utilizar esse exercícios em minhas tutorias, mas fique a vontade para utiliza-los.

### Objetivo

Nesse repositório você não terá um material detalhado para o estudo da lógica de programação e algoritmos, mas terá uma lista de exercícios para ajudar na jornada de estudos.
Um exercício não é dependente do outro e você pode fazer na ordem que preferir, mas tentei deixa-los em uma ordem que ajude a estudar os tópicos de lógica de programação e algoritmos de uma forma fluída.

## Requisitos básicos para fazer os exercícios

Sugiro que você já conheça de forma básica:

- Estudo da lógica de programação e algoritmos;

# Lista de exercícios:

1. Escreva um algoritmo que imprima a frase "Olá, mundo!" para o usuário.

------------
2. Escreva um algoritmo que armazene o valor 10 em uma variável A e o valor 20 em uma variável B. A seguir (utilizando apenas atribuições entre variáveis) troque os seus conteúdos fazendo com que o valor que está em A passe para B e vice-versa. Ao final, escrever os valores que ficaram armazenados nas variáveis.

------------
3. Solicite um valor para o usuário, identifique se esse número é **par** ou **impar** e escreva o resultado na tela.

------------
4. Solicite para o usuário 4 notas entre 0 e 10, tire a média entre as 4 notas e escreva o resultado em tela.

------------
5. Crie uma calculadora com as operações básica de soma, subtração, multiplicação e divisão.
- Regras:
    - Ao entrar na calculadora o usuário deverá ter um menu com as opções 1, 2, 3, 4 e 0. Sendo elas:
        > 1 - Somar
        > 2 - Subtrair
        > 3 - Multiplicar
        > 4 - Dividir
    - Todas as operações devem solicitar que o usuário entre com dois valores e então estes valores devem ser utilizados para realizar a operação escolhida.

------------
6.	Faça um algoritmo capaz de ler as dimensões de um retângulo (base e altura), calcular e escrever a sua área. A área de um retângulo é calculado multiplicando a **base x altura**.

------------
7.	Escreva um algoritmo para ler o salário mensal atual de um funcionário e o percentual de reajuste. Calcular e escrever o valor do novo salário.

------------
8. Escreva um algoritmo que colete a nota e quantidade de faltas de um aluno e identifique se o mesmo foi aprovado ou reprovado na matéria. As regras para verificar se um aluno está aprovado, de recuperação ou reprovado, são: 
    - Se sua nota estiver entre 7 e 10 ele é aprovado;
    - Se sua nota for maior ou igual a 5 e menor que 7, o aluno irá para recuperação;
    - Se a nota estiver abaixo de 5, o aluno está reprovado;
    - Se o aluno tiver mais de 4 faltas ele será reprovado independente da nota tirada.

------------
9.	Solicite 5 números para o usuário, some os números e mostre o resultado em tela.

------------
10. Tendo uma lista com os dias uteis do mês atual, solicite o dia atual para o usuário e, baseado no dia atual informado, capture o próximo dia útil dessa lista, que não seja o dia atual e imprima o resultado na tela.
    - Exemplo de lista de dias uteis: `{1, 2, 3, 4, 5, 8, 9, 10, 11, 12, 15, 16, 18, 19, 22, 25, 26, 29, 30}`
- Regras adicionais:
    - O dia atual informado pelo usuário deve estar entre 1 e 31;
    - Se o próximo dia util não existir na lista, retorne a mensagem **"Não foi possível localizar o próximo dia útil"**.

------------
11. O custo de um carro novo ao consumidor é a soma do custo de fábrica com a porcentagem do distribuidor e dos impostos (aplicados ao custo de fábrica). Supondo que o percentual do distribuidor seja de 28% e os impostos de 45%, escrever um algoritmo para ler o custo de fábrica de um carro, calcular e escrever o custo final ao consumidor.

------------
12. Uma revendedora de carros usados paga a seus funcionários vendedores um salário fixo por mês, mais uma comissão também fixa para cada carro vendido e mais 5% do valor das vendas por ele efetuadas. Escrever um algoritmo que leia o número de carros por ele vendidos, o valor total de suas vendas, o salário fixo e o valor que ele recebe por carro vendido. Calcule e escreva o salário final do vendedor.

------------
13. Faça um algoritmo que leia a idade de uma pessoa expressa em anos, meses e dias e escreva a idade dessa pessoa expressa apenas em dias. Considerar o ano com 365 dias.

------------
14. *(Recursão)* O fatorial de um número qualquer **N** consiste em multiplicações sucessivas até que **N** seja igual ao valor unitário, ou seja, **5!=5×4×3×2×1**, que resulta em **120**. Faça um algoritmo para calcular o número fatorial do número informado pelo usuário.

------------
15. *(Recursão)* Os números de Fibonacci compõem a seguinte sequência: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34,... Ou seja, a composição é formada por números que são o resultado da soma dos dois anteriores. Faça um programa que imprima em tela os próximos N número da sequência de Fibonacci, onde N é um número informado pelo usuário de 1 à 30.

------------
16. Palíndromos são frases ou palavras que podem ser lidas, indiferentemente, da esquerda para a direita, conforme o sentido habitual da leitura, ou da direita para a esquerda, sem que haja mudança da sua significação. Exemplos: arara, ana, ama, mirim, oco, ovo, osso, ralar, rapar, reter, reviver, rodador, salas, socos, etc.
Escreva um algoritmo que recebe uma palavra, indentifique se a palavra é um palíndromo e, se palíndromo, retorne para o usuário "É palíndromo" e se não for retornar "Não é palíndromo".

------------
17. Crie um algoritmo que simule um dado de 6 lados. Ou seja, ao abrir o programa o usuário irá tirar aleatóriamente um número entre 1 e 6.

------------
18. (Busca sequencial) A busca linear ou busca sequencial é a forma mais simples de se buscar um resultado em uma lista de dados. O vetor é percorrido comparando cada dado do vetor até encontrar o resultado desejado e retornando o índice do valor encontrado. O dado a ser encontrado é passado como parâmetro para função. O melhor caso nessa situação é se o dado que está sendo procurando é a primeira opção do vetor, e o pior resultado ocorre se este for o ultimo dado do vetor. A complexidade da busca linear é O(n).
Crie um algoritmo que contém uma lista de números entre 0 e 10, então, solicite um número para o usuário entre 0 e 10 e verifique se o número existe na lista. Se o número existir, imprima "Número encontrado", se não existir imprima "Número não encontrado".
    - Exemplo de lista de números: `{9,7,5,2,4,6,10,1,8}`.

------------
19. (Busca binária) A busca binária tem o mesmo objetivo da busca linear, seu tempo de busca é muito mais otimizado que o da busca linear, no entanto, para seu funcionamento, o vetor deve estar ordenado.
Exemplo de vetor ordenado: `vetor[10] = {0,1,2,3,4,5,6,7,8,9};`
A busca binária localiza o meio do vetor com a fórmula (Inicio + Fim) / 2, sendo Inicio a primeira posição do vetor e Fim a ultima posição do vetor. Levando em consideração o exemplo vetor[10] teríamos: (1+10) /2 = 5,5. Em C este valor seria passado para 5, pois ao armazena-lo como inteiro (int) as casas decimais são ignoradas.
Tendo em mãos o meio (5) do vetor ordenado o algoritmo verifica se o valor procurando é ele, se não for ele verificará se é maior ou menor que ele. Sendo maior, a busca será feita apenas na parte direita da metade, se menor, a busca será realizada na parte da esquerda:
![Busca binária](/imgs/BuscaBinaria_exemplo.jpg "Busca binária")