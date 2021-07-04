# SSLTP1
César Matías Sagardía

//int argc: contiene el número de argumentos que tiene *argv[]. 
//Por defecto C tiene 1 argumento, es el path de la ubicación del archivo
//char *argv[]: es un puntero a un vector de cadenas, separa las cadenas mediante un espacio entre las mismas.

#include <stdio.h>

int main(int argc, char *argv[])
{
	printf("Número de argumentos: %i \n",argc);

	int i;
	for(i=0;i<argc;i++)
	{
		printf("%s\n", argv[i]);		
	}

	return 0;
}
