# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.

## Algorithm:
Step1:

Start

Step2:

Create a class and declare variable with string datatype

Step3:

Converts the given string into lowercase

Step4:

Iterate the string forward and backward, compare one character at a time

Step5:

till middle of the string is reached

Step6:

stop



## Program:
```c#
using System;  
                      
public class Palindrome  
{  
    public static void Main()  
    {  
        string s;
        s=Console.ReadLine();
        Boolean flag = true;  
          
        
        s = s.ToLower();  
          
    
        for(int i = 0; i < s.Length/2; i++){  
            if(s[i] != s[s.Length-i-1]){  
                flag = false;  
                break;  
            }  
        }  
        if(flag)  
            Console.WriteLine("Given string is palindrome");  
        else  
            Console.WriteLine("Given string is not a palindrome");  
    }  
} 
```

## Output:

![image](PALINDROME.PNG)


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
