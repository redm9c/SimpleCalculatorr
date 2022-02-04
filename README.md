# SimpleCalculatorr
#include <stdio.h>
#include <stdlib.h>
#include <conio.h>
#include <math.h>

void main()
{
    char opr;
    double n1,n2;
    double base,power,result;

    printf("A SIMPLE CALCULATOR! \n\n");
    printf("You are allowed to calculate only 2 numbers!!!\n\n");

    printf("Enter Operator (+, -, *, / ,^ ) : ");
    scanf("%c",&opr);

switch(opr)
        {
    case '+' :
            printf("Enter Numbers to Add : \n");
            scanf("%lf %lf",&n1,&n2);

            printf("%.2lf + %.2lf = %.2lf",n1,n2,n1+n2);
            break;

    case '-' :

      printf("Enter Numbers to Subtract: \n");
            scanf("%lf %lf",&n1,&n2);

            printf("%.2lf - %.2lf = %.2lf",n1,n2,n1-n2);
            break;

    case '*' :
        printf("Enter Numbers to MUltiply: \n");
            scanf("%lf %lf",&n1,&n2);

            printf("%.2lf * %.2lf = %.2lf",n1,n2,n1*n2);
            break;

    case '/' :
        printf("Enter Numbers to Divide: \n");
            scanf("%lf %lf",&n1,&n2);

            printf("%.2lf / %.2lf = %.2lf",n1,n2,n1/n2);
            break;

    case '^' :

        printf("Enter Base : ");
        scanf("%lf",&base);
     printf("Enter power : ");
     scanf("%lf",&power);

      result=pow(base,power);

         printf(" %.2lf ^ %.2lf = %.2lf",base,power,result);
         break;
        }
        }




