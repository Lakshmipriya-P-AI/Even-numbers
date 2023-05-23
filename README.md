# Even-numbers
## Experiment 4: Even Numbers
### AIM:
To Write a Java program to print the even numbers from 1 to 20.

### ALGORITHM:
Step 1:
Create the class and declare the main method so that the JVM will identify the main program to run.

Step 2:
reate a for loop and initiate the variable with 0 as intital value, condition as variable less that 21 and incrementing the variable.

Step 3:
Inside for loop declare an if condition to check whether the given number is even or not.

Step 4:
Print the result using 'System.out.print'.

Step 5:
The iteration will be haulted once the conditions is turned false.

Step 6:
The program will be executed after the compilation.

### PROGRAM:
```
public class even
{
    public static void main(String args[])
    {
        int i;
        System.out.println("Even numbers in the range 1 - 20 are:");
        for(i=1;i<=20;i++)
        {
            if(i%2 == 0)
            {
                System.out.print(i+" ");
            }
        }
    }
}
```
### OUTPUT:
![image](https://github.com/Lakshmipriya-P-AI/Even-numbers/assets/93427923/aefe3156-c650-4e9e-9ba4-d2689dc6c4f9)


### RESULT:
Thus, a java program is created to print the even numbers from 1 to 20.
