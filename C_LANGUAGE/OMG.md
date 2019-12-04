````c

#define _CRT_SECURE_NO_WARNINGS
#include <string.h>
#include <stdio.h>

int main(void)
{


  char string[80];
  
  
  strcpy(string, "Hello my lovely World from");
  strcat(string, "strcpy");
  strcat(string, "and");
  strcat(string, "strcat");
  printf("string=%s\n",string);
  return 0;
 }


  
