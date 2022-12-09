# Code

```
using System;
     
class Program {
     
    // Main Function
    static void Main(string[] args)
    {

        int[,] array = new int[2,2];


      for(int i =0;i<2;i++){

          for(int j =0;j<2;j++){
        Console.Write("Enter Number :");
        array[i,j] = int.Parse(Console.ReadLine());
          }
      }

      foreach(int data in array){
        Console.Write(data);
      }

      
    }
}

```
