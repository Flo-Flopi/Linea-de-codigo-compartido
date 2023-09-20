#include "pch.h"
#include <iostream>
#include <ctime>
#include <cstdlib>

using namespace System;
using namespace std;

int leerCantidadFiguras();
void dibujarFigura();

int main()
{
    return 0;
}

//donde el usuario indica el numero de figuras entre 5 a 10 figuras
int leerCantidadFiguras() {
    int cantidadFiguras;
    do
    {
        cout << "Ingrese cantidad de figuras" << endl;
        cin >> cantidadFiguras;
    } while (cantidadFiguras < 5 || cantidadFiguras > 10);
    return cantidadFiguras;
}

//que el programa genere aleatoriamente entre 5 a 10 figuras
int generarCantidadFiguras(int minValor, int maxValor) {
    return   rand()%(maxValor - minValor) + minValor;
}

void dibujarFigura() {

}

