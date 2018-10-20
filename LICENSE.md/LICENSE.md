#include <iostream> 
using namespace std; 
int main() { 
int Alumnos, Notas; 
char Nombre[20];
float promedio, nota; 
float promedioGeneral = 0; 
cout<<"Cantidad de alumnos: "; 
cin>>Alumnos; 

for(int i = 0; i < Alumnos; i++){ 
cout<<i+1<<" alumno\n"; 
cout<<"Cantidad de notas: "; 
cin>>Notas; 
cout<<"Registre su nombre: ";cin>>Nombre;

for(int j = 0; j < Notas; j++){ 
cout<<j+1<<" nota: "; 
cin>>nota; 
promedio  += nota; 
}	
promedio /= Notas; 
cout<<"\nPromedio: "<<promedio<<"\n\n"; 
promedioGeneral += promedio; 
} 
cin.get(); 
return 0; 
}
