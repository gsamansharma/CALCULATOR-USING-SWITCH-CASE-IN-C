# CALCULATOR-USING-SWITCH-CASE-IN-C
This is a very basic calculator made using only switch case for two numbers
```c
#include <stdio.h>
#include<math.h>
int main()
{
    int c;
    unsigned a,b ;
    printf("\t\t\t\t\t\tWELCOME TO THE CALCULATOR\n\n\n");
    printf("\t\t\t\t\t\t1(+)   2(-)   3(*)\n\n\n\t\t\t\t\t\t4(/)   5 (%%)   6 Square   7(squareroot)\n\n\n\n");
    printf("Please select a number as per the following operator : ");
    scanf("%d",&c);
    printf("Enter the first Number:");
    scanf("%d",&a);
    printf("Enter the Second Number : ");
    scanf("%d",&b);
    switch(c){
        case 1:printf("%d",a+b);
            break;
        case 2:printf("%d",a-b);
            break;
        case 3:printf("%d",a*b);
            break;
        case 4:printf("%f",(float)a/b);
            break;
        case 5:printf("%d",a%b);
            break;
        case 6:printf("%d and %d",a*a,b*b);
            break;
        case 7:printf("%f and %f",(float)sqrt(a),(float)sqrt(b));
            break;
        default:printf("please enter a value from the calculator when asked for the operator");
            break;
    }
    printf("\nRun again?\n Enter 1 for yes and 0 for no: ");
    int d;
    scanf("%d",&d);
    if(d==1)
    main();
    else
    return 0;
}
```
