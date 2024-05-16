# att10.04

#include <stdio.h>
#include <stdlib.h>

int main() {
	float num1;
	float num2;
	
	printf("Digite um numero aleatorio: ");
	scanf("%f", &num1);
	printf("Digite outro numero aleatorio: ");
	scanf("%f", &num2);
	
	float diferenca = num1 - num2;
	
	printf("A diferença entre os dois numeros digitados e de: %f", diferenca);
	
return 0;
}
