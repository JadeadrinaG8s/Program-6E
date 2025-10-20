# Program-6E
C module 6
EX NO-6)E)a C program to find character 'R' is vowel or consonant using pointer.
DATE:20/10/25
NAME:JADE ADRINA J
REF NO:25017000
AIM:TO Write a C program to find character 'R' is vowel or consonant using pointer.
ALGORITHM:
1)Declare a character variable and assign it the value 'R'.2)Declare a pointer and point it to the character variable.3)Check if the character pointed by the pointer is a vowel:4)If it's a vowel, print "Vowel".
PROGRAM:
```
#include<stdio.h>
int main()
{
    char ch;
    scanf("%c",&ch);
    char *p1=&ch;
    if(*p1=='A'||*p1=='a'||*p1=='E'||*p1=='e'||*p1=='i'||*p1=='I'||*p1=='o'||*p1=='O'||*p1=='U'||*p1=='u')
    printf("%c is vowel.",*p1);
    else 
    printf("%c is consonant.",*p1);
}
```
OUTPUT:
<img width="559" height="230" alt="Screenshot 2025-10-20 093302" src="https://github.com/user-attachments/assets/183e8610-eb33-4acc-9cd6-65cd9ba8eaac" />
RESULT:
Thus, a C program to find character 'R' is vowel or consonant using pointer has been executed successfully.
