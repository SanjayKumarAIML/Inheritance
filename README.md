# <p align="center">Inheritance</p>

## Aim:
To write a C# program to print some messages using hierarchical inheritance.

## Algorithm:
### Step 1: 
Create a base class.

### Step 2:
Create two child class.

### Step 3:
Create a constructor in the base class and print a message.

### Step 4:
Create constructor in child classes to print the message.


## Program:
Developed By: **Sanjay Kumar. S. S**

Register No.: **212221240048**
```c#
using System;

namespace exp8
{
    public class tyre
    {
        public tyre()
        {
            Console.Write("Tyre is attached to ");
        }
    }
    

    public class car : tyre
    {
        public car()
        {
            Console.WriteLine("Car");
        }
    }

    public class scooter : tyre
    {
        public scooter()
        {
            Console.WriteLine("Scooter");
        }
    }
    public class main
    {
        public static void Main(string[] args)
        {
            car newcar = new car();
            scooter newscooter = new scooter();
        }
    }
}
```
## Output:
![image](https://github.com/SanjayKumarAIML/Inheritance/assets/93427246/d961f5e4-f051-4c2f-9148-4cc849407532)

## Result
Thus, C# program to print some messages using hierarchical inheritance is implemented successfully.
