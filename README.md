# grade-point-finder
write a program in c that finds grade point
#include<stdio.h>
int main()
{
    float mark;
    printf("Enter your mark : ");
    scanf("%f",&mark);

    if (mark>=80)
        printf("the grade is A+");
    else if(mark>=70)
        printf("the grade is A");
    else if(mark>=60)
        printf("the grade is A-");
    else if(mark>=50)
        printf("the grade is B");
    else if(mark>= 40)
        printf("the grade is C ");
    else if(mark>=33)
        printf("the grade is D");
    else
        printf("the Grade is FAIL");
}
