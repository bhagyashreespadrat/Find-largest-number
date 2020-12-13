# Find-largest-number
#Find largest number in c
#include <stdio.h>

int main() {
    int n1,n2,n3;
    printf("\n Enter number n1:");
    scanf("%d",&n1);
    printf("\n Enter number n2:");
    scanf("%d",&n2);
    printf("\n Enter number n3:");
    scanf("%d",&n3);
    if(n1>=n2 && n1>=n3)
     printf("%d is the largest number.", n1); 
    else if(n2 >= n1 && n2 >= n3)
     printf("%d is the largest number.", n2);
    else
     printf("%d is the largest number.", n3); 
    return 0;
}
/*OUTPUT:
Enter number n1:8

 Enter number n2:6
 
 Enter number n3:4
 8 is the largest number.
 */
