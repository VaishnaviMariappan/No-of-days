# EXP-3 Java program to fins the number of day in a month

## Aim:

To Write a Java program to find the number of days in a month.

## Algorithm:

1. Take input from the user for the month and store it in a variable.

2. Create a switch statement based on the month variable.

3. For each case, print the corresponding number of days and break out of the switch statement.

4. Handle the special case of February separately, considering leap years. If the month is February, check if it's a leap year. If it is, print 29 days, otherwise, print 28 days.

5. If the input month does not match any of the cases, display an error message indicating an invalid number.
Finally, print the number of days in the month.

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
                System.out.print("Enter the year: ");
                int year = a.nextInt();
                if ((year % 4 == 0 && year % 100 != 0) || year % 400 == 0) {
                    System.out.println("29 days");
                } else {
                    System.out.println("28 days");
                }
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
