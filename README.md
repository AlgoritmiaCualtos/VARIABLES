# VARIABLES

//Variables

#include <stdio.h>
#include <stdlib.h>

int main () {
    int x; //Entero: 8, -9, 10 16bits -32768 hasta 32767 2^16
    float y;//Flotante: 9, 58, 10, 69, 5 32bits 2^32
    double y2;//Flotante: 64bits 2^64

    x=5;
    y=10.5;
    y2=20.9;

    printf ("Valor de x: %i.\n",x);
    printf ("Valor de y: %f.\n",y);
    printf ("Valor de y2: %f.\n",y2);

    system ("pause");
    return 0;
}