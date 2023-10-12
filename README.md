# IF
Uso de if para ver si un numero es par o impar y si esta dentro de un rango numerico.
#include<iostream>
using namespace std;

int main (int argc, char *argv[]) {
	int numero;
	cout<<"Ingrese un numero cualquiera: "<<endl;
	cin>>numero;
	cout<<"Su numero es "<<numero<<endl;
	if (numero%2==0){
		cout<<"El numero es par"<<endl;
	}else{
		cout<<"El numero es impar"<<endl;
	}
	if (numero > 1 && numero < 25){
		cout<<"El numero se encuentra en el rango entre 1 y 25";
	}
	if (numero > 75 && numero < 100){
		cout<<"El numero es mayor a 75 y menor a 100";
	}
	if (numero > 26 && numero < 74){
		cout<<"El numero ingresado es invalido";
	}
	return 0;
}
