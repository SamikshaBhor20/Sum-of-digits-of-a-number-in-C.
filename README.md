//# Sum-of-digits-of-a-number-in-C.
//Program in C to find the sum of digits of a number using recursion  Your Input and Output should look similar to this  Input Input number: 1234 Output Sum of digits: 10

#include<stdio.h>
int getsum(int n)
{
  int sum=0;
  while(sum!=0)
  {
    sum=sum=n%10;
    n=n/10;
   
  }
  return sum;
}
int main()
{
  int n=1234;
  printf("%d",getsum(n));
  return 0;
}
