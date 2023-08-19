# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:
Start the program and declare the variables required.

Obtain the input from the user and read the values.

Calculate the total marks and check for the conditions.

Print the required output.

End the program.
## Program:
```
Name:Varsha Ajith
Register number: 212221230118
```
```
using System;
namespace Hello
{
    public class program
    {
        public static void Main()
        {
            int phy,chem,maths;
            Console.WriteLine("Enter the physics mark");
            phy = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter the chemistry mark");
            chem =Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter the maths mark");
            maths = Convert.ToInt32(Console.ReadLine());
            if (maths >= 65 && phy >= 55 && chem >= 50)
            {
                if ((maths + phy + chem) >= 180 || (maths + phy) >= 140)
                    Console.WriteLine("Student is eligible");
                else
                    Console.WriteLine("Student is not eligible");
            }
            else
                Console.WriteLine("student is not eligible");
        }
    }

}


```


## Output:

<img width="960" alt="Screenshot 2023-08-19 185622" src="https://github.com/VarshaAjith1110/Eligibility-for-Admission/assets/94222288/75228584-314d-480f-a44e-51dc6bf34bcf">


## Result:
Thus,the program to find the eligibility for admission is executed successfully.
