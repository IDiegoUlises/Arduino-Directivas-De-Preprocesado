# Arduino Directivas De Preprocesado

Las directivas de preprocesado son las primeras instrucciones que se ejecutan en el compilador no las verifica que esten correctas es decir puedes escribir codigo que es equivocado que falta una ";" o este mal escrito y el programa puede funcionar porque el compilador no verifica que las instrucciones de pre-Procesado esten correctas.

* las instrucciones de preprocesado es el primer programa invocado por el compilador
* todas las directivas de PreProcesado empiezan con "#" 

el proceso de compilacion sucede en tres etapas

* Preprocesado
* Compilado
* Enlazado

#include library.h" //llama a una libreria

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
