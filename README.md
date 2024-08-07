using System;
					
public class Program
{
public static void Main()
{
    Random rnd = new Random();
    int i = 1;

    Console.WriteLine("1");
    Console.WriteLine("2");
    int menu = int.Parse(Console.ReadLine());
    while (i <= menu)
    {
        i++;
        int random = rnd.Next(1, 11);
        Console.Write(random + " ");
        if (random == 1) Console.WriteLine("A");
        else if (random == 2) Console.WriteLine("B");
        else if (random == 3) Console.WriteLine("C");
        else if (random == 4) Console.WriteLine("D");
        else if (random == 5) Console.WriteLine("E");
        else if (random == 6) Console.WriteLine("F");
        else if (random == 7) Console.WriteLine("G");
        else if (random == 8) Console.WriteLine("H");
        else if (random == 9) Console.WriteLine("I");
        else Console.WriteLine("J");
    }
  }
}

//
