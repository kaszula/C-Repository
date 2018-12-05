# C-Repository

6. Write a C# Sharp program to print the output of multiplication of three numbers which will be entered by the user. 
.
.
.
.
.
.
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
using System;

public class Exercise1
{
    public static void Main( )
    {
         int numer1, numer2;
         Console.Write("Podaj pierwsza liczbe: ");
         numer1 = Convert.ToInt32(Console.ReadLine());
         
         Console.Write("Podaj druga liczbe: ");
         numer2 = Convert.ToInt32(Console.ReadLine());
         int result = numer1*numer2;
         Console.WriteLine("Output: {0} x {1} = {2}", numer1, numer2, result);
    }
}

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
