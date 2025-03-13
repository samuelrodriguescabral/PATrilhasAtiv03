# PATrilhasAtiv03

A) using System;
 
 namespace ALEM_DE_PRETO_E_SURDO
 {
 	class Program
 	{
 		public static void Main(string[] args)
 		{
 			Console.WriteLine("Escreva um número inteiro:");
 			int num1 = int.Parse(Console.ReadLine());
 			Console.WriteLine("Escreva um número inteiro:");
 			int num2 = int.Parse(Console.ReadLine());
 			
 			
 			if (num1 > num2 ) {
 				Console.WriteLine("O " +num1+ " e maior que o " + num2);
 			} else {
 				Console.WriteLine("O " +num2+ " e menor  que o " +num1);
 			}
 			
 			
 			
 			
 			Console.Write("PRESSIONE ALGO PARA FECHAR . . . ");
 			Console.ReadKey(true);
 		}
 	}
 }





B) using System;
 
 namespace ALEM_DE_PRETO_E_SURDO
 {
 	class Program
 	{
 		public static void Main(string[] args)
 		{
 			Console.WriteLine("Escreva um número:");
 			double num1 = double.Parse(Console.ReadLine());
 			Console.WriteLine("Escreva um segundo número:");
 			double num2 = double.Parse(Console.ReadLine());
 		
 			
 			
 			if (num1 <= num2) {
 				Console.WriteLine("O número " +num1+ " e menor ou igual a: "+num2);
 			}
 			
 			
 			
 			
 			
 			
 			Console.Write("PRESSIONE ALGO PARA FECHAR . . . ");
 			Console.ReadKey(true);
 		}
 	}
 }








C) using System;
 
 namespace ALEM_DE_PRETO_E_SURDO
 {
 	class Program
 	{
 		public static void Main(string[] args)
 		{
 			Console.WriteLine("Escreva um número:");
 			double num1 = double.Parse(Console.ReadLine());
 			Console.WriteLine("Escreva um número:");
 			double num2 = double.Parse(Console.ReadLine());
 		
 			
 			
 			if (num1 >= num2 ) {
 				Console.WriteLine("O " +num1+ " e maior ou igual a  " + num2);
 			} 
 			
 			
 			
 			
 			
 			Console.Write("PRESSIONE ALGO PARA FECHAR . . . ");
 			Console.ReadKey(true);
 		}
 	}
 }





(D) using System;
 
 namespace ALEM_DE_PRETO_E_SURDO
 {
 	class Program
 	{
 		public static void Main(string[] args)
 		{
 			Console.WriteLine("Escreva um número inteiro:");
 			int num1 = int.Parse(Console.ReadLine());
 			Console.WriteLine("Escreva um número inteiro:");
 			int num2 = int.Parse(Console.ReadLine());
 			Console.WriteLine("Escreva um número inteiro:");
 			int num3 = int.Parse(Console.ReadLine());
 			
 			
 			if (num1 < num2 ) {
 				Console.WriteLine("O " +num1+ " e menor que " + num2);
 			} else {
 				Console.WriteLine("O " +num2+ " tem  que ser maior  que " +num1);
 			}
 			if (num1 > num3) {
 				Console.WriteLine("O " +num1+ " e maior que " + num3);
 			}else{
 				Console.WriteLine("O " +num1+ " tem  que ser maior  que " +num3);
 			
 			}
 			
 			
 			
 			
 			Console.Write("PRESSIONE ALGO PARA FECHAR . . . ");
 			Console.ReadKey(true);
 		}
 	}






E)  using System;
 
 namespace ALEM_DE_PRETO_E_SURDO
 {
 	class Program
 	{
 		public static void Main(string[] args)
 		{
 			Console.WriteLine("Escreva um número:");
 			double num1 = double.Parse(Console.ReadLine());
 			Console.WriteLine("Escreva um número:");
 			double num2 = double.Parse(Console.ReadLine());
 		
 			
 			
 			if (num1 >= num2 ) {
 				Console.WriteLine("O " +num1+ " e maior ou igual a  " + num2);
 			} 
 			
 			
 			
 			
 			
 			Console.Write("PRESSIONE ALGO PARA FECHAR . . . ");
 			Console.ReadKey(true);
 		}
 	}
 }




F) using System;
 
 namespace ALEM_DE_PRETO_E_SURDO
 {
 	class Program
 	{
 		public static void Main(string[] args)
 		{
 			Console.WriteLine("Escreva um número:");
 			double num1 = double.Parse(Console.ReadLine());
 			
 		
 			
 			
 			if (num1 % 2 ==0) {
 				Console.WriteLine("O número " +num1+ " e par.");
 			}else{
 				Console.WriteLine("O nùmero "+num1+ " e impar.");
 			}
 			
 			
 			
 			
 			
 			Console.Write("PRESSIONE ALGO PARA FECHAR . . . ");
 			Console.ReadKey(true);
 		}
 	}
 }


G) using System;
 
 namespace ALEM_DE_PRETO_E_SURDO
 {
 	class Program
 	{
 		public static void Main(string[] args)
 		{
 			Console.WriteLine("Escreva um número:");
 			int num1 = int.Parse(Console.ReadLine());
 			Console.WriteLine("Escreva um número:");
 			int num2 = int.Parse(Console.ReadLine());
 		
 			int diferenca = Math.Abs(num1 - num2);
 			
 			if (diferenca <= 10) {
 				Console.WriteLine("A diferença entre " +num1+ " e " +num2+ " é de: " +diferenca+ " sendo menor ou igual a 10.");
 			}else {
 				Console.WriteLine("A diferença entre " +num1+ " e " +num2+ " é de: " +diferenca+ " sendo maior a 10.");
 			}
 			
 			Console.Write("PRESSIONE ALGO PARA FECHAR . . . ");
 			Console.ReadKey(true);
 		}
 	}
 }



H) using System;
 
 namespace ALEM_DE_PRETO_E_SURDO
 {
 	class Program
 	{
 		public static void Main(string[] args)
 		{
 			Console.WriteLine("Escreva um número:");
 			double num1 = double.Parse(Console.ReadLine());
 		
 		
 			
 			
 			if (num1 > 0) {
 				Console.WriteLine("O número digitado e positivo.");
 			}else if (num1 < 0) {
 				Console.WriteLine("O número digitado e negativo.");
 			}else {
 				Console.WriteLine("O número e igual a zero.");
 			}
 			
 			
 			
 			
 			
 			
 			Console.Write("PRESSIONE ALGO PARA FECHAR . . . ");
 			Console.ReadKey(true);
 		}
 	}
 }


























 J) using System;
 
 namespace ALEM_DE_PRETO_E_SURDO
 {
 	class Program
 	{
 		public static void Main(string[] args)
 		{
 			Console.WriteLine("Escreva um número:");
 			double num1 = double.Parse(Console.ReadLine());
 			
 		
 		    if (num1 == 0) {
 				Console.WriteLine("O número e igual a 0");
 			}else{ 
 				Console.WriteLine("O número não igual a 0");
 			}
 			
 			Console.Write("PRESSIONE ALGO PARA FECHAR . . . ");
 			Console.ReadKey(true);
 		}
 	}
 }
