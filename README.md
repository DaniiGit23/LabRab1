# NoviyRepazitory

ITS-b-o-22-1, 11.03.02, Kondratenko Daniil Vital’evich.

Programm:

#include <stdio.h>
#include <iostream>
#include <math.h>
#include <locale.h>

int main()
{
setlocale(LC_ALL, "Russian");

int i, j;
	printf("i:");
	scanf_s("%d", &i);
	printf("j:");
	scanf_s("%d", &j);
if (i < j) i++;

else
	{
		j = i - 3;
		i++;
	}
printf("i= %d\ j= %d", i, j);
	return 0;
}
