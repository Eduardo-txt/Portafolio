# Portafolio
## portafolio
### Proyectos destacados
~~~
#include<stdio.h>
int main()
{
    int num, cont, x;
    printf("\n_____________SECUENCIA DE COLLATZ_______________\n");
    //printf("\n Escribe un numero para imprimir las secuencias:");
    //scanf("%d", &x);
    cont=0;
    for(x=1;x<10;x++)
    {
    num = x; 
    while (num>1)
    {
    if(num%2==0)
    {
       num=num/2;
       printf(" %d,", num);
       cont++;
    }
    else
    {
        num=num*3+1;
        printf(" %d,", num);
        cont++;
    }
    if(num==1)
    {
        printf("\n");
    }    
    }
    }
    return 0;   
}
~~~
### METAS PROFESIONALES
-Aprender mas lenguajes de programcion interesantes
-Ser cada vez mas rapido y eficaz al programar
### Tecnologias favoritas
-Realidad virtual
-Inteligencia artificial
### Informacion adicional
-me gustan los gatos
-me gusta el basquetbol
