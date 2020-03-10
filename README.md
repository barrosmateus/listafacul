# listafacul
#include <stdio.h>

main(){
	
//EXERCICIO-1
/*	
		int numero;
		
		printf("Digite um numero inteiro:");
		scanf("%i", &numero);
		printf("voce digitou %i", numero);
*/


//EXERCICIO-2
/*	
		int	numero1, numero2, soma;
		
		printf("Digite um numero inteiro:");
		scanf("%i", &numero1);
		
		printf("Digite outro numero:");
		scanf("%i", &numero2);
		
		soma = numero1 + numero2;
		
		printf("A soma entre %i e %i e igual a %i.", numero1, numero2, soma);
*/


//EXERCICIO-3
/*
	float numero1, numero2, diferenca;
		
		printf("Digite um numero inteiro:");
		scanf("%f", &numero1);
		
		printf("Digite outro numero:");
		scanf("%f", &numero2);
		
		diferenca = numero1 - numero2;
		
		printf("A diferença entre %f e %f e igual a %f.", numero1, numero2, diferenca);
*/


//EXERCICIO-4
/*
		int	numero1, numero2, numero3, soma;
		
		printf("Digite um numero inteiro:");
		scanf("%i", &numero1);
		
		printf("Digite outro numero:");
		scanf("%i", &numero2);
		
		printf("Digite mais um numero inteiro:");
		scanf("%i", &numero3);
		
		soma = numero1 + numero2 + numero3;
		
		printf("A soma entre %i, %i e %i e igual a %i.", numero1, numero2, numero3, soma);
*/		

//EXERCICIO-5
/*
		int	numero1, numero2, numero3, resultado;
		
		printf("Digite um numero inteiro:");
		scanf("%i", &numero1);
		
		printf("Digite outro numero:");
		scanf("%i", &numero2);
		
		printf("Digite mais um numero inteiro:");
		scanf("%i", &numero3);
		
		resultado = (numero1 - numero2) + numero3;
		
		printf("O resultado da expressao %i - %i + %i e igual a %i.", numero1, numero2, numero3, resultado);
*/


//EXERCICIO-6
/*
		float	numero1, numero2, numero3, numero4, resultado;
		
		printf("Digite um numero inteiro:");
		scanf("%f", &numero1);
		
		printf("Digite outro numero:");
		scanf("%f", &numero2);
		
		printf("Digite outro numero:");
		scanf("%f", &numero3);
		
		printf("Digite mais um numero inteiro:");
		scanf("%f", &numero4);
	
		resultado = (numero1 + numero2 + numero3 + numero4) / 4;
		
		printf("a media aritimetica entre %f, %f, %f e %f e igual a %f.",numero1, numero2, numero3, numero4, resultado);
*/


//EXERCICIO-7
/*
		float	numero1, numero2, resultado;
		
		printf("Digite um numero:");
		scanf("%f", &numero1);
		
		printf("Digite outro numero diferente de zero:");
		scanf("%f", &numero2);
		
		resultado = numero2 / numero1;
		
		printf("A divisao entre %f e %f e igual a %f", numero1, numero2, resultado );
*/


//EXERCICIO-8
/*		
		int num1, num2, num3, num4, resultado;
		
		printf("Digite um numero inteiro:");
		scanf("%i", &num1);
		
		printf("Digite outro numero:");
		scanf("%i", &num2);
		
		printf("Digite outro numero:");
		scanf("%i", &num3);
		
		printf("Digite mais um numero inteiro:");
		scanf("%i", &num4);
		
		resultado = num1 + num2 + num3 + num4;

		printf("a soma aritimetica entre %i, %i, %i e %i e igual a %i."
		,num1, num2, num3, num4, resultado);
*/


//EXERCICIO-9

/*
		float nota1, nota2,resultado;
		
		printf("Digite a nota do trabalho:");
		scanf("%f", &nota1);
		
		printf("Digite a nota da prova:");
		scanf("%f", &nota2);
		
		resultado = (nota1 * 4 + nota2 * 6) / (4 + 6);
		
		printf("a media desse aluno e: %f", resultado);
*/


//EXERCICIO-10
/*
		float nota1, nota2, peso1, peso2, resultado;
		
		printf("Digite a nota do trabalho:");
		scanf("%f", &nota1);	
		
		printf("Digite o peso da nota do trabalho:");
		scanf("%f", &peso1);
		
		printf("Digite a nota da prova:");
		scanf("%f", &nota2);
		
		printf("Digite o peso da nota da prova:");
		scanf("%f", &peso2);
		
		resultado = (nota1 * peso1 + nota2 * peso2) / (peso1 + peso2);
		
		printf("a media desse aluno e: %f", resultado);
			
*/



//EXERCICIO-11
/*
		int	numero1, numero2, soma, subtracao12, subtracao21, produto;
		
		printf("Digite um numero inteiro:");
		scanf("%i", &numero1);
		
		printf("Digite outro numero:");
		scanf("%i", &numero2);
		
		soma = numero1 + numero2;
		subtracao12 = numero1 - numero2;
		subtracao21 = numero2 - numero1;
		produto = numero1 * numero2;
		
		printf("A soma entre %i e %i e igual a %i.\n", numero1, numero2, soma);
		printf("A diferenca entre %i e %i e igual a %i.\n", numero1, numero2, subtracao12);
		printf("A diferenca entre %i e %i e igual a %i.\n", numero2, numero1, subtracao21);
		printf("E o produto entre %i e %i e igual a %i.\n", numero1, numero2, produto);
	
*/


//EXERCICIO-12
/*
		float	numero1, numero2, numero3, resultado;
		
		printf("Digite a primeira nota:");
		scanf("%f", &numero1);
		
		printf("Digite outra nota:");
		scanf("%f", &numero2);
		
		printf("Digite a ultima nota:");
		scanf("%f", &numero3);
		
		resultado = (numero1 + numero2 + numero3) / 3;
		
		printf("A media  entre as notas %f, %f e %f e igual a %f.", numero1, numero2, numero3, resultado);		
*/


//EXERCICIO-13
/*
	float	numero1, numero2, resultado;
		
		printf("Digite a altura do triangulo:");
		scanf("%f", &numero1);
		
		printf("Digite a base do triangulo:");
		scanf("%f", &numero2);
				
		resultado = (numero1 * numero2) / 2;
		
		printf("A area desse triangulo e %f.", resultado);
	
*/

//EXERCICIO-14
/*
		float salario1, salario2;
		
		printf("Qual o valor do salario; R$:");
		scanf("%f", &salario1);
		
		salario2 = (salario1 * 125) / 100;
		
		printf("O salario com acéscimo de 25 por cento e : %f", salario2);
*/	
	
	
//EXERCICIO-15

/*
		float salario1, salario2, aumento;
		
		printf("Qual o valor do salario; R$:");
		scanf("%f", &salario1);
		printf("Qual o valor do acrescimo; porcento:");
		scanf("%f", &aumento);
		
		aumento = aumento + 100;
		
		salario2 = (salario1 * aumento) / 100;
		
		aumento = aumento - 100;
				
		printf("O salario final com o almento de %f  por cento e : %f", aumento,  salario2);	
*/

//EXERCICIO-16	
/*
		float salario1, salario2, aumento,acrescimo, decrescimo;
		
		printf("Qual o valor do salario; R$:");
		scanf("%f", &salario1);
	
		acrescimo = salario1 * 0,05;
		decrescimo = salario1 * 0.07;
		salario2 = salario1 + acrescimo - decrescimo;
		
		
				
		printf("O salario final  e : %f",salario2);

*/

//EXERCICIO-17

/*
		float salario, quantidadekh, valorkh, desconto, contadeenergia;
					
		printf("Qual o valor do salario; R$:");
		scanf("%f", &salario);
		
		printf("quantos quilowatts essa casa consumiu? ");
		scanf("%f", &quantidadekh);
		
		valorkh = salario / 5;
		contadeenergia = valorkh * quantidadekh;
		desconto = contadeenergia - ((contadeenergia * 15) / 100);
	
		printf("valor de cada quilowatt : %f\n", valorkh);
		printf("O valor a ser pago por essa residencia e: %f\n",contadeenergia);
		printf("o preco a ser pago com um desconto de 15 por cento e %f\n", desconto);
*/


//EXERCICIO-18

/*
	float raio, area;

	printf("digite o raio do circulo: ");	
	scanf("%f", &raio);
	
	area = 3.14 * (raio * raio);
	
	printf("a area desse circulo e :%f", area);

*/

//EXERCICIO-19
/*
		float gasolina, etanol;
		
		printf("qual o valor da gasolina?");
		scanf("%f", &gasolina);
		
		etanol = (70 * gasolina ) / 100;
	
		printf("para a gasolina custando R$ %f, o etanol deve estar custando ate R$ %f.", gasolina, etanol);
*/

//EXERCICIO-20

/*			
		float compra, desconto, valorfinal;
		
		printf("qual o valor da da compra?");
		scanf("%f", &compra);
		
		desconto = (compra * 20) / 100;
		valorfinal = compra - desconto;
			
		printf("Com um desconto de R$ %f a compra de R$ %f passsa a custar R$ %f.", desconto, compra, valorfinal);
*/
	
	
	
}

