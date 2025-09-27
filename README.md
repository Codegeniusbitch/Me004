#include<stdio.h>
int main(){
float num1, num2;
int choice;
printf("Enter num1: ");
scanf("%f", &num1);
printf("Enter num2: ");
scanf("%f", &num2);
printf("1-Add\n2-Suntract\n3-Multiply\n4-Divide\n");
printf("Enter choice: ");
scanf("%d", choice);
switch(choice){
case 1:
printf("Answer:%.2f", num1+num2);
break;
case 2:
printf("Answer:%.2f",num1-num2);
break;
case 3:
printf("Answer:%.2f", num1*num2);
break;
case 4:
printf("Answer:%.2f", num1/num2);
break;
default:
printf("Incorrect input!");
}
return 0;
}
