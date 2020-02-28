using System;

namespace algoritmos
{
    class Program
    {
        static void Main(string[] args)
        {
            int edad1, edad2, dif1, dif2;
            Console.WriteLine("Digite la primera edad:");
            edad1 = Convert.ToInt32(Console.ReadLine());

            Console.WriteLine("Digite la segundad edad:");
            edad2 = Convert.ToInt32(Console.ReadLine());

            

            if (edad1 > edad2)
            {
                dif1 = edad1 - edad2;
                Console.WriteLine("La edad del mayor es: " + edad1);
                Console.WriteLine("La edad del menor es: " + edad2);
                Console.WriteLine("La diferencia entre edades es: " + dif1);

            }
            else
            {
                dif2 = edad2 - edad1;
                Console.WriteLine("La edad del mayor es: " + edad2);
                Console.WriteLine("La edad del menor es: " + edad1);
                Console.WriteLine("La diferencia entre edades es: " + dif2);
            }
        }
    }
}
