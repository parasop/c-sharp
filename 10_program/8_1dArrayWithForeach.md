# Code


```
using System;
     
class Program {
     
    // Main Function
    static void Main(string[] args)
    {

        int[] array = new int[5];


      for(int i =0;i<5;i++){

        Console.Write("Enter Number :");
        array[i] = int.Parse(Console.ReadLine());
      }

      foreach(int data in array){
        Console.Write(data);
      }

      
    }
}
```
