# Ashutosh.Nayak.Day3.Exercise3
Linking DLL that contains method with parameter to a Console Application to perform as a Caluculator using Switch Case
code for the DLL class
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Ashutosh.Nayak.Day3.Exercise3
{
    public class ArthimaticOperation
    {
        
        public double Add(double a,double b)
        {
           return a + b;
        }
        public double Subtract(double a, double b)
        {
            return a - b;
        }
        public double Multiply(double a, double b) 
        {
            return a * b;
        }
        public double Divide(double a, double b) 
        {
            return a / b;
        }
        public double Modulus(double a, double b) 
        {
            return a % b;
        }
    }
}

Link the DLL File in the console application by clicking the refences and add the DLL File
when we pass the pararmeter in calculator then its been readable by DLL file and returns the operation
