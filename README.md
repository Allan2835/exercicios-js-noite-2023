# exercicios-js-noite-2023

1. Faça um script que uma variável receba um número (de 1 a 12) e retorne o mês correspondente como uma string no console. Por exemplo, se a entrada for 2, deverá retornar “fevereiro”, pois este é o 2° mês.

2. Faça um script que verifique se um número inteiro é divisível por 3. Mostrar no console a mensagem se é divisível ou não.

3. Faça um script que receba a hora e retorne no console a mensagem entre 00h e 12h "Bom dia!", entre 12h e 18h "Boa tarde!", e entre 18h e 00h "Boa noite!".

4. Faça um script capaz de encontrar o menor dentre 3 números inteiros quaisquer dados pelo teclado e retorne a resposta no console.

5. Faça um script que verifique se uma letra armazenada numa variável é vogal ou consoante e retorne a resposta no console.

6. Faça um script que pede duas notas de um aluno. Em seguida ele deve calcular a média do aluno e dar o seguinte resultado:
    A mensagem "Aprovado", se a média alcançada for maior ou igual a sete;
    A mensagem "Reprovado", se a média for menor do que sete;
    A mensagem "Aprovado com Distinção", se a média for igual a dez.

7. Fazer um script que receba o valor do salário mínimo e o valor do salário de uma pessoa. Calcular e imprimir quantos salários mínimos ela ganha. Se a pessoa ganhar menos de 1 salário mínimo, retornar na tela "baixa renda". Se a pessoa ganhar entre 1 salário mínimo e 5 salários mínimos, retornar na tela "classe média". Se a pessoa ganhar mais de 5 salários mínimos, retornar na tela "classe alta". Base salário mínimo 1212. Salário da pessoa irá ser dada pela variável.

8. Em uma loja e CDs existem apenas quatro tipos de preços que estão associados a cores. Assim os CDs que ficam na loja não são marcados por preços e sim por cores. Desenvolva o script que a partir da entrada da cor, mostre o preço no console. A loja está atualmente com a seguinte tabela de preços:
    Preços
    verde = 10;
    amarelo = 20;
    vermelho = 30;
    azul = 40;

__________________________________________________________________________________________________________________________________________________________________________________________________________________________

Exercícios dia 27-07-2023

1- Obtenha uma entrada com o nome de um mês e mostre na tela a estação do ano relacionada ao mês.

  E apresente no console um texto referente ao que vai ser mostrado e a variável em questão.
  
  	-console.log(“o texto digitado” + variavel);
  
  -Março, Abril, Maio - Outono
  
  -Junho, Julho, agosto - Inverno
  
  -Setembro, Outubro, Novembro - Primavera
  
  -Dezembro, Janeiro, Fevereiro - Verão

2- Desenvolva uma calculadora com as 4 operações básicas (soma, subtração, divisão e multiplicação). Receba 2 valores e qual operação a ser realizada, e apresente o cálculo e qual operação na tela

console.log(“texto” + variavel);

3- Em uma empresa o salário base é de 2000 reais, se o colaborador tiver o cargo de gerente tem uma acréscimo de 10% no salário, caso o colaborador for supervisor, tem um acréscimo de 50% no salário, e caso for outro cargo o salário é o base.
	Receba uma entrada com o cargo do colaborador, e apresente na tela o cargo e o salário.

console.log(“texto” + variavel);

4- Escreva um script que receba o peso em kg e uma altura em m e a partir desses valores calcule o índice de massa corpórea do utilizador.

imc = peso / (altura * altura)

![image](https://github.com/EdsonTiepermann/exercicio-js-turma-tarde-2023/assets/33090891/802fee87-849d-4297-8c4b-666ff4839526)

E mostre na tela em qual grau o usuário se enquadra.

console.log(“texto” + variavel);

if …else

5- Compras, crie um script com a seguinte situação. Uma variável com valor total da compra.
        tipos de pagamentos (pix, débito, crédito, parcelado no cartão, parcelado no carnê).
        se for pix, aplica-se um desconto de 10%;
        se for no débito, valor original;
        se for crédito em 1x, acréscimo de 5%;
        se for parcelado no cartão, acréscimo de 10% por parcela;
        se for parcelado no carnê, acréscimo de 20% por parcela;

        se a compra for feita em cartão, tanto em crédito ou em débito, 
        verificar se tem o valor disponível no cartão;
        o valor do cartão será dada por uma variável

        variaveis: formaPagamento; valorTotal; 

        aparecer a forma de pagamento, em quantas vezes foi escolhido, 
        se for parcelado aparecer o valor total e valor de cada parcela.

__________________________________________________________________________________________________________________________________________________________________________________________________________________________

Exercícios dia 03-08-2023

01 - Escrever um algoritmo para mostrar os números ímpares entre 100 e 200

02 - Escrever um algoritmo que leia um valor para uma variável N de 1 a 10 e calcule a tabuada de
N. Mostre a tabuada na forma: 0 x N = 0, 1 x N = 1N, 2 x N = 2N, ..., 10 x N = 10N

03 - Desenvolver um algoritmo que efetue a soma de todos os números ímpares que são múltiplos de três e que se encontram no conjunto dos números de 1 até 500

04 - Escrever um script que leia número de 0 a 999. Desses, fazer a soma apenas dos ímpares e mostrar na tela. Mostrar também o total de números ímpares e pares. E por fim, fazer a média aritmética da soma dos números divisíveis por 3
