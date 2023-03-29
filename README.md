# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:

## Step1: 
Start by creating a new class.

## Step2: 
Initiate the integer variables to assign the marks of Maths, Physics and Chemistry and a string variable to assign the name of the student; read the input from the user.

## Step3: 
Calculate the first total that sums all the 3 subject marks; and the second total that sums maths and physics marks.

## Step4: 
Based on the condition given, check whether the student is eligible for the engineering admission.

## vStep5: 
Display the output for the input read from the user.

## Step6: 
Stop the execution.
## Program:
DEVELOPED BY:DHANASHREE M
REGISTER NO:212221230018
```
using System;
public class Exercise10
{
    public static void Main()
    {
        int p, c, m;
        string name;
        Console.WriteLine("Enter the student name:");
        name = Console.ReadLine();
        Console.Write("Marks obtained in Maths :");
        m = Convert.ToInt32(Console.ReadLine());
        Console.Write("Marks obtained in Chemistry :");
        c = Convert.ToInt32(Console.ReadLine());
        Console.Write("Marks obtained in Physics :");
        p = Convert.ToInt32(Console.ReadLine());
        int total1 = m + p + c;
        int total2 = m + p;

        if (m >= 65 && p >= 55 && c >= 50)
        {
            if((total1>=100) || total2>=140)
            {
                Console.WriteLine(name+"is eligible for engineering addmission");
            }
            else
            {
                Console.Write(name+" is not eligible.\n\n");
            }
        }
        else
        {
            Console.Write(name+" is not eligible.\n\n");
        }
    }
}

```


## Output:

![Screenshot 2023-03-13 204632](https://user-images.githubusercontent.com/94165415/228582022-90c7becc-1887-40a5-b04e-04634c45b216.png)


## Result:
Thus, a C# program to check the eligibility of a student on engineering admission has been executed successfully.
