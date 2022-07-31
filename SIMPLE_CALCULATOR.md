#include<stdio.h>
 int main()
{
    int choice,a,b,s;
    while(1)
    {
        printf("       BY masterDDA");
        printf("\n1.Addition");
        printf("\n2.Subtraction");
        printf("\n3.Multiplication");
        printf("\n4.Division");
        printf("\n5.Odd Even");
        printf("\n6.First n natural number");
        printf("\n7.Exit");
        printf("\n Enter your Choice");
        scanf("%d",&choice);
        switch(choice)
    {
    case 1:
    printf("\nenter a number");
    scanf("%d",&a);
    printf("\nenter second number");
    scanf("%d",&b);
            s=a+b;
    printf("\n addition of two numbers is %d.",s);
    break;
    case 2:
    printf("\nenter a number");
    scanf("%d",&a);
    printf("\nenter second number");
    scanf("%d",&b);
            s=a-b;
    printf("\n subtraction of two numbers is %d.",s);
    break;
    case 3:
    printf("\nenter a number");
    scanf("%d",&a);
    printf("\nenter second number");
    scanf("%d",&b);
            s=a*b;
    printf("\n multiplication of two numbers is %d.",s);
    break;
    case 4:
    printf("\nenter a number");
    scanf("%d",&a);
    printf("\nenter second number");
    scanf("%d",&b);
            s=a/b;
    printf("\n division of two numbers is %d.",s);
    break;
    case 5:
    printf("\nenter a number");
    scanf("%d",&a);
    if(a%2==0)
    printf("\n Input number is Even.");
    else
    printf("\n Input number is Odd.");
    break;
    case 6:
    printf("\n Enter a number");
    scanf("%d",&a);
    for(b=1;b<=a;b++)
    printf("%d",b);
        break;
    default:
    printf("\n Invalid choice");}
    getch();
        printf("THANK YOU");
    }
    return(1);

}
