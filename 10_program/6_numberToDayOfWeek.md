# Code

```
using System;

class Program {
  public static void Main (string[] args) {

string[] days = { "Monday", "Tuesday", "Wednesday", 
                            "Thursday", "Friday", "Saturday", 
                            "Sunday"};
        int day;

    Console.Write("Enter number :");
    day = int.Parse(Console.ReadLine()); 
   
    if(day > 0 && day < 8)
    {
         Console.Write(days[day-1]);
    }
    else
    {
       Console.Write("Invalid input! Please enter week number between 1-7.");
    }


    
    
    
  }
}```
