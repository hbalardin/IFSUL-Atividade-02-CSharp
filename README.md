

Aluno: Henrique Balardin
Turma: 4INF
Ano: 2022

# IFSUL-Atividade-02-CSharp
Atividade de Linguagem de Programação III.

## 1) Elabore um algoritmo que calcule a idade média de 5 alunos.
```C#
using System;

namespace Grades{
	public class Program
	{
		public static void Main()
		{
			Selector();
		}
		
		public static void Selector(){
			Console.WriteLine("===== Calculadora da média de idade dos alunos =====");
			
			Console.WriteLine("Qual a idade do 1º aluno?");
			int n1 = int.Parse(Console.ReadLine());
			
			Console.WriteLine("Qual a idade do 2º aluno?");
			int n2 = int.Parse(Console.ReadLine());
			
			Console.WriteLine("Qual a idade do 3º aluno?");
			int n3 = int.Parse(Console.ReadLine());
			
			Console.WriteLine("Qual a idade do 4º aluno?");
			int n4 = int.Parse(Console.ReadLine());
			
			Console.WriteLine("Qual a idade do 5º aluno?");
			int n5 = int.Parse(Console.ReadLine());
			
			double result = Sum(n1, n2, n3, n4, n5);
			result = Divide(result, 5);
			
			Console.WriteLine();
			Console.WriteLine("A média das idades é " + result);
			
			Console.WriteLine();
			Console.WriteLine("Obrigado pela preferência! ;)");
			Console.WriteLine("====================================================");
		}
		
		public static double Sum(int n1, int n2, int n3, int n4, int n5){
			double result = n1 + n2 + n3 + n4 + n5;
			return result;
		}
		public static double Divide(double n1, double n2){
			double result = n1 / n2;
			return result;
		}
	}
}

```

## 2) Elabore um algoritmo que calcule a idade média de 5 alunos.
```C#
using System;

namespace OddOrEven{
	public class Program
	{
		public static void Main()
		{
			Selector();
		}
		
		public static void Selector(){
			Console.WriteLine("===== Descubra se seu número é par ou impar! =====");
			
			Console.WriteLine("Digite um número inteiro: ");
			int n1 = int.Parse(Console.ReadLine());
			
			bool isEven = IsEven(n1);
			
			if (isEven){
				Console.WriteLine();
				Console.WriteLine("Seu número é par! :p");
			} else {
				Console.WriteLine();
				Console.WriteLine("Seu número é impar! :D");
			}
			
			Console.WriteLine();
			Console.WriteLine("Obrigado pela preferência! ;)");
			Console.WriteLine("====================================================");
		}
		
		public static bool IsEven(int n){
			return n % 2 == 0;
		}
	}
}

```

##3) Pesquise sobre conversões de variáveis em C# e descreva os temas abaixo:
###a. Conversão implícita
###b. Conversão explícita

