### All java exercises during the Udemy Course:
"Java COMPLETO 2023 Programação Orientada a Objetos +Projetos"
Grupo 1 --> (Estrutura Sequêncial): 
#### Ex1
```java
import java.util.Scanner;
	public static void main(String[] args) {
		/*
		 * Faça um programa para ler dois valores 
		 * inteiros, e depois mostrar na tela a
		 * soma desses números com uma mensagem explicativa, 
		 * conforme exemplos.
		 */
		Scanner sc = new Scanner(System.in);
		int x, y;
		x = sc.nextInt();
		y = sc.nextInt();
		
		System.out.println("SOMA = " + (x+y));
		sc.close();
	}
```
#### Ex2
```java
	public static void main(String[] args) {
		/*
		Faça um programa para ler o valor do raio de um círculo, 
		e depois mostrar o valor da área deste círculo com quatro
		casas decimais conforme exemplos.
		Fórmula da área: area = π . raio2
		Considere o valor de π = 3.14159
		 */
		Locale.setDefault(Locale.US);
		
		Scanner sc = new Scanner(System.in);
		double pi=3.14159, raio = sc.nextDouble();;

		System.out.printf("A = %.4f",(pi*(Math.pow(raio, 2))));
		sc.close();	
	}
```
#### Ex3
```java
	public static void main(String[] args) {
		/*
		Fazer um programa para ler quatro valores inteiros A, B, C e D. 
		A seguir, calcule e mostre a diferença do produto
		de A e B pelo produto de C e D segundo a fórmula: 
		DIFERENCA = (A * B - C * D).
		*/
		int A, B, C, D;
	
		Scanner sc = new Scanner(System.in);
		A = sc.nextInt();
		B = sc.nextInt();
		C = sc.nextInt();
		D = sc.nextInt();
		
		System.out.printf("DIFERENCA = " + (A * B - C * D));
		sc.close();	
	}
```
#### Ex4
```java
	public static void main(String[] args) {
		/*
		Fazer um programa que leia o número de um funcionário, 
		seu número de horas trabalhadas, o valor que recebe por
		hora e calcula o salário desse funcionário. A seguir, 
		mostre o número e o salário do funcionário, com duas casas
		decimais.
		*/
		int number; 
		double hours, work_hours;
		Locale.setDefault(Locale.US);

		Scanner sc = new Scanner(System.in);
		number = sc.nextInt();
		hours = sc.nextDouble();
		work_hours = sc.nextDouble();
		
		System.out.println("NUMBER = " + number);
		System.out.printf("SALARY = U$ %.2f", (hours*work_hours) );
		sc.close();	
	}
```
#### Ex5
```java
	public static void main(String[] args) {
		/*
		 * Fazer um programa para ler o código de uma peça 1, o número de peças 1, o
		 * valor unitário de cada peça 1, o código de uma peça 2, o número de peças 2 e
		 * o valor unitário de cada peça 2. Calcule e mostre o valor a ser pago.
		 */
		Locale.setDefault(Locale.US);
		Scanner sc = new Scanner(System.in);
		int cod1 = sc.nextInt();
		int num_pecas_1 = sc.nextInt();
		float val_unt_1 = sc.nextFloat();
		int cod2 = sc.nextInt();
		int num_pecas_2 = sc.nextInt();
		float val_unt_2 = sc.nextFloat();
		
		System.out.printf("VALOR A PAGAR: R$ %.2f", ((num_pecas_2 * val_unt_2) + (num_pecas_1 * val_unt_1)));

		sc.close();
	}
```
#### Ex6
```java
	public static void main(String[] args) {
		/*
	Fazer um programa que leia três valores com ponto flutuante 
	de dupla precisão: A, B e C. Em seguida, calcule e mostre:
	a) a área do triângulo retângulo que tem A por base e C por altura.
	b) a área do círculo de raio C. (pi = 3.14159)
	c) a área do trapézio que tem A e B por bases e C por altura.
	d) a área do quadrado que tem lado B.
	e) a área do retângulo que tem lados A e B.
	    */
		Locale.setDefault(Locale.US);
		Scanner sc = new Scanner(System.in);
		
		double A , B, C;
		double pi = 3.14159;
		A = sc.nextDouble();
		B = sc.nextDouble();
		C = sc.nextDouble();
		
		System.out.printf("TRIANGULO : %.3f \n",((A*C)/2));
		System.out.printf("CIRCULO : %.3f \n",(pi*(Math.pow(C, 2))));
		System.out.printf("TRAPEZIO : %.3f \n",(((A+B)*C)/2));
		System.out.printf("QUADRADO : %.3f \n",(B*B));
		System.out.printf("RETANGULO : %.3f \n",(A*B));
		sc.close();
	}
```
