### EX NO : 01
### DATE  : 30.03.2022
# <p align="center"> Largest-of-three-numbers </p>

## Aim:
To write a C# program to find the largest of three numbers

## Algorithm:
### Step1: 
Start
### Step2:
Create a class and declare three variable with integer datatype
### Step3:
Use if condition to check whether num1 is largest than num2 and num3
### Step4:
Use elif condition to check whether num2 is largest than num1 and num3
### Step5:
Use else condition to display that third variable is largest among all the variables
### Step6:
stop

<br/><br/><br/><br/><br/><br/><br/><br/>

## Program:
```c#
using System;
namespace fawzi
{
    class program
    {
        static void Main(string[] args)
        {
            int num1, num2, num3;
            Console.WriteLine("Enter Three Numbers: );
            num1 = Convert.ToInt32(Console.ReadLine());
            num2 = Convert.ToInt32(Console.ReadLine());
            num3 = Convert.ToInt32(Console.ReadLine());
            if ((num1 > num2) && (num1 > num3))
                Console.WriteLine(num1 + " is Greater");
            else if ((num2 > num1) && (num2 > num3))
                Console.WriteLine(num2 + " is Greater");
            else
                Console.WriteLine(num3 + " is Greater");
        }
    }
}
```
## Output:

![outttt](https://user-images.githubusercontent.com/75235022/175532590-5434132a-10f3-4557-8a9e-e9f4871d21dc.png)



## Result:
Thus the C# program to find the largest of three numbers is executed successfully
