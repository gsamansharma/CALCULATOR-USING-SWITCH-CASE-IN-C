# CALCULATOR-USING-SWITCH-CASE-IN-C
This is a very basic calculator made using only switch case for two numbers
```c
#include <stdio.h>
#include<math.h>
float main()
{
    int c;
    unsigned a,b ;
    printf("\t\t\t\t\t\tWELCOME TO THE CALCULATOR\n\n\n");
    printf("\t\t\t\t\t\t1(+)   2(-)   3(*)\n\n\n\t\t\t\t\t\t4(/)   5'%' 6 Square   7(squareroot)\n\n\n\n");
    printf("Please select a number as per the following operator : ");
    scanf("%d",&c);
    printf("Enter the first Number:");
    scanf("%d",&a);
    printf("Enter the Second Number : ");
    scanf("%d",&b);
    switch(c){
        case 1:printf("%f\n",a+b);
            break;
        case 2:printf("%f\n",a-b);
            break;
        case 3:printf("%f\n",a*b);
            break;
        case 4:printf("%f\n",a/b);
            break;
        case 5:printf("%d\n",a%b);
            break;
        case 6:printf("%f and %f\n",a*a,b*b);
            break;
        case 7:printf("%f and %f",sqrt(a),sqrt(b));
            break;
        default:printf("please enter a value from the calculator when asked for the operator");
            break;
    }
    return 0;
}
```
