# hello-world
try/catch repository


import java.util.Scanner;

public class EjemploTry
{
  public static void main(String[] args)
  {
      try
    {
        Scanner teclado = new Scanner(System.in);
        System.out.println("Por favor ingresa un numero del 1 al 9");
        int numero = teclado.nextInt();
        System.out.println("El numero fue:"+numero);
    }
       catch(Exception exc)
    {
      System.out.println("Te equivocaste, intenta de nuevo. Recuerda que es de 1 a 9");
    }
  }
}
