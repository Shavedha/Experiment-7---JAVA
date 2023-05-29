# Experiment-7---JAVA
## AIM
To write a java program to insert an element into an array.
## ALGORITHM 
1. Create the class and declare the main method so that the JVM will identify the main program to run.
2. Declare an array and get the length of the array from the user.
3. Get the array elements from the user and store them in the array.
4. From the user get the input element which is to be added to the array
5. Print the array with the added element
6. End the program.
## PROGRAM
```
import java.util.Scanner;
class Main
{
    public static void main(String[] args)
    {
        int len, p,ele;
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter length of an array:");
        len = sc.nextInt();
        int arr[] = new int[len+1];
        System.out.println("Enter "+len+" elements:");
        for(int i = 0; i < len; i++)
        {
            arr[i] = sc.nextInt();
        }
        System.out.print("Enter the element which you want to insert:");
        ele = sc.nextInt();
        arr[len] = ele;
        System.out.print("After inserting : ");
        for(int i = 0; i <len; i++)
        {
            System.out.print(arr[i]+",");
        }
        System.out.print(arr[len]);

    }
}
```
## OUTPUT
<img width="452" alt="image" src="https://github.com/Shavedha/Experiment-7---JAVA/assets/93427376/bba260c8-489a-4f90-b8c9-4140084f5458">

## RESULT
Thus an element is inserted in an array using java programming language.
