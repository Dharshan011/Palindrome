# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
## Step 1:
Create a new Class.

## Step 2:
Get input from the user and store it.

## Step 3:
Loop over the entire string and reverse it.

## Step 4:
Use if condition to check whether the string and the reversed string is equal or not.

## Step 5:
print palindrome if it's equal else print not a palindrome.

## Program:
```
using System;  
    namespace palindrome  
    {  
        class Program  
        {  
            static void Main(string[] args)  
            {  
                string s,revs="";  
                Console.WriteLine(" Enter string");  
                s = Console.ReadLine();  
                for (int i = s.Length-1; i >=0; i--) //String Reverse  
                {  
                    revs += s[i].ToString();  
                }  
                if (revs == s) // Checking whether string is palindrome or not  
                {  
                    Console.WriteLine("String is Palindrome \n Entered String Was {0} and reverse string is {1}", s, revs);  
                }  
                else  
                {  
                    Console.WriteLine("String is not Palindrome \n Entered String Was {0} and reverse string is {1}", s, revs);  
                }  
                Console.ReadKey();  
            }  
        }  
    }
```

## Output:
![Screenshot 2023-08-18 212322](https://github.com/Dharshan011/Palindrome/assets/113497491/fdd608f0-83c8-4004-9441-e328cd1310b7)


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
