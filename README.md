using System;

namespace TimeLoop1
{
    class Program
    {
        static void Main(string[] args)
        {
            string val;
            int num;

            val = Console.ReadLine();

            num = Convert.ToInt32(val);
            for (int i = 1; i <= num; i++)
            {
                Console.WriteLine(i + " Abracadabra");
            }
        }
    }
}
