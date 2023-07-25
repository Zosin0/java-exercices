### All java exercises during the Udemy Course:
"Java COMPLETO 2023 Programação Orientada a Objetos +Projetos"
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
