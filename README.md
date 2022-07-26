# Numeros-inteiros-e-soma-dos-pares-codigo-em-Java

Complete o programa abaixo, arrastando e soltando os trechos de código nos espaços vazios, de forma que receba dez números inteiros e mostre a soma dos números pares dentre eles.



public class SomaPares {
	public static void main(String[] args) {
		[int soma = 0;]
		
		[for(int cont = 1; cont <= 10; cont++)] {
			[System.out.printf("Informe o %do numero: ", cont);]
			[int numero = Integer.parseInt(System.console().readLine());]
			
			[if(numero % 2 == 0)]
				[soma += numero;]
		}
		
		System.out.printf("\nSOMA DOS NUMEROS PARES = %d\n", soma);
	}
}
