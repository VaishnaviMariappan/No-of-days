# EXP -3 Java program to fins the number of day in a month

## Aim:

To Write a Java program to find the number of days in a month.

## Algorithm:


## Program:
``` java
import java.util.Scanner;
public class days_month
{
    public static void main(String[] args)
    {
        Scanner a=new Scanner(System.in);
        System.out.println("Enter a month number");
        Integer month=a.nextInt();
        switch(month)
        {
            case 1:
                System.out.println("31 days");
                break;
            case 2:
                System.out.println("28 days");
                break;
            case 3:
                System.out.println("31 days");
                break;
            case 4:
                System.out.println("30 days");
                break;
            case 5:
                System.out.println("31 days");
                break;
            case 6:
                System.out.println("30 days");
                break;
            case 7:
                System.out.println("31 days");
                break;
            case 8:
                System.out.println("31 days");
                break;
            case 9:
                System.out.println("30 days");
                break;
            case 10:
                System.out.println("31 days");
                break;
            case 11:
                System.out.println("30 days");
                break;
            case 12:
                System.out.println("31 days");
                break;
            default:
                System.out.println("Invalid Number");
                break;
        }
    }
}
```
## Output:
![image](https://github.com/VaishnaviMariappan/No-of-days/assets/94169913/745616e5-87d5-48b1-a817-0a7c8497f9f7)

## Result:

Thus a java program is written to find the number of days in a month.
