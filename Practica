#include <iostream>
#include <cstdlib>
#include <math.h>
#include <string.h>

/*
Problema 15. La computadora generará parejas de enteros y
encontrará el máximo común divisor
*/

//@Autor: Grecia Cortes (@Nyoseka)
//@Fecha: 16 Septiembre 2021

using namespace std;

int MaxCD(int a,int b)
{
    int temp;
    while(b!=0)
    {
        temp=b;
        b=a%b;
        a=temp;
    }
    return a;
}

int main() {
    int a=rand()%50;
    int b=rand()%50;

    cout<<"Números generados: "<<"\n";
    cout<<"a="<<a<<" b="<<b;
    cout<<"\n"<<"Máximo Comun Divisor: "<<MaxCD(a,b);
    return 0;
}
