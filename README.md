
#include <stdlib.h>
#include <stdio.h>
#include <iostream>

void main ()
{
  int num1, num2, num3, num4, num5;
  int max, min, sum = 0;
  printf ("please enter 5 numbers\n");
  scanf ("%d %d %d %d %d", num1, num2, num3, num4, num5);


  //finding the max number
  if ((num1 >= num2) && (num1 >= num3) && (num1 >= num4) && (num1 >= num5))
    max = num1;
  if ((num2 >= num1) && (num2 >= num3) && (num2 >= num4) && (num2 >= num5))
    max = num2;
  if ((num3 >= num2) && (num3 >= num1) && (num3 >= num4) && (num3 >= num5))
    max = num3;
  if ((num4 >= num2) && (num4 >= num3) && (num4 >= num1) && (num4 >= num5))
    max = num4;
  if ((num5 >= num2) && (num5 >= num3) && (num5 >= num4) && (num5 >= num1))
    max = num5;


  //finding the min number
  if ((num1 <= num2) && (num1 <= num3) && (num1 <= num4) && (num1 <= num5))
    min = num1;
  if ((num2 <= num1) && (num2 <= num3) && (num2 >= num4) && (num2 <= num5))
    min = num2;
  if ((num3 <= num2) && (num3 <= num1) && (num3 >= num4) && (num3 <= num5))
    min = num3;
  if ((num4 <= num2) && (num4 <= num3) && (num4 >= num1) && (num4 <= num5))
    min = num4;
  if ((num5 <= num2) && (num5 <= num3) && (num5 >= num4) && (num5 <= num1))
    min = num5;


  sum = num1 + num2 + num3 + num4 + num5 / 5;
  printf ("the min and the max numbers toghther are %d\n", max + min);
  printf ("the min number is %d\n", min);
  printf ("the sum of the numbers is %d\n", sum);
  printf ("%d is the largest number\n", max);
  system.("pause");

}
