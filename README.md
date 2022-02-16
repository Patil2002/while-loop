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
        	Console.WriteLine("Enter Number");
			a= Convert.ToInt32(Console.ReadLine());
			Console.WriteLine("The table of given number is:- ");
			i=1;
			while(i<=10)
	
				{
					Console.WriteLine(a*i);
				 i++;
					
				}
        	
			
        }
    }
} 
Output:-Enter Number
5
The table of given number is:- 
5
10
15
20
25
30
35
40
45
50
