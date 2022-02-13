# while-loop
using System;
using System.IO;
using System.Linq;
using System.Collections.Generic;

namespace CSharp_Shell
{

    public class Program 
    {
        public static void Main()
        {
			int i,a;
			Console.WriteLine("Enter any number");
			a=Convert.ToInt32(Console.ReadLine());
			Console.WriteLine("The table of given number is:");
			i=1;
			while(i<=10)
			{
				Console.WriteLine(a*i);
				i++;
			}
        }
    }
}
