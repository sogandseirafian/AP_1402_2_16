# AP_1402_2_16
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;


namespace AP_1402_2_14.CS
{
    internal class Program
    {
        static void Main(string[] args)
        {
            //برنامه ای بنویسید که دترمینال یک ماتریس 3*3 را محاسبه کند
          
            int[,] matrix= new int[3, 3];
            for (int i = 0; i < 3; i++)
            {
                for (int j = 0; j < 3; j++)
                {
                    matrix[i, j] = Convert.ToInt32(Console.ReadLine());
                }

            }
            Console.WriteLine("Matrix is:");
            for(int i=0;i<3;i++)
            {
                for(int j=0;j<3;j++)
                {
                    Console.WriteLine(matrix[i, j] + "\t");
                }
                Console.WriteLine();
            }

   
        }
    }
}

