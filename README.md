# Arduino-Directivas-De-Preprocesado

//Las directivas de preprocesado son las primeras que se
//ejecutan que son de "Pre" "Procesado"
//la mas comun de usar es #include todas las directivas
//empiezan con "#" 

#define //define una constante 
#define perimetro(x,y) (2*x+2*y) //Funcion con define
#define devolver return 0; //Sirve para cambiar palabras
#endif //Para terminar solo un "if" simple
#ifndef //if que verifica que "No exista" una constanta
#undef //elimina una variable y libera espacio
#warning //sirve para notificar un error
#error //sirve para enviar un error
#ifdef //Si, si existe una constante definida se ejecuta
#include //incluye un archivo de referencia 
#else //sino
#else if // si
#elif //es lo mismo que un else if 
#endif //Para terminar un ifndef
#pragma //Compatibilidad
#line //Es muy ambuiguo porque se basa en lineas para el orden

void setup() {
  Serial.begin(9600);
}

void loop() {
  Serial.println()
}
