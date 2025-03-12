#include <stdio.h>
int main ()
{
	const float PAGO =100;
	const float ISR = 0.1 ;
	int horas;
	float sbruto,sneto,desc;
	printf("Horas laboradas ");
	scanf( "%d",& horas );
	sbruto=horas*PAGO;
	desc=sbruto* ISR ;
	sneto= sbruto*desc ; 
	printf( "salario bruto: %f",sbruto);
	printf( "Descuento (10%): %f",desc);
	printf( "Salario neto : %f ",sneto); 
	return 0; 
	
}