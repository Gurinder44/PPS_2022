## Programs 5: Write a program to show use of if statements
```c
#include<stdio.h>

//programm to use if statements 
int main()
{
int x;
printf("Enter a number:");
scanf("%d", &x);
if(x%2==0)printf("%d is even\n",x);
else printf("%d is odd\n",x);

return 0;
}
```

**Output**:
``` 
Enter a number:44
44 is even
```
