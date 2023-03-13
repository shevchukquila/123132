# 123132
using System;

namespace efanov
{
    class Program
    {
        static void Main(string[] args)
        {
            //Заполнить одномерный массив с клавиатуры шестью целыми числами. Вывести одномерный массив в обратном порядке.
            int[] array = new int[6];
            for (int i = 0; i < 6; i++) //последовательный
            {
                Console.WriteLine($"array[{i}=", i);
                array[i] = int.Parse(Console.ReadLine());
            }
            for (int i = array.Length - 1; i >= 0; i--) //обратный порядок
            {
                Console.WriteLine($"array[{i}]={array[i]}");
            }
            Console.Read();




        }
    }
}
