#include <stdio.h>
#include <math.h>

int main(void)
{
	enum tipler(byte,kbyte,mb);
	float mbvalue,sayi,cmb, mb;
	printf("Bir sayi giriniz: ");
	scanf("%f",&sayi);
	cmb = 8 * pow(1024,mb);
	mbvalue = sayi / cmb ;
	printf("mb value : %2f",mbvalue);
	
	return 0;
}
