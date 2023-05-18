## ProgramaciÃ³n Concurrente: Un Enfoque PrÃ¡ctico

  
# ProgramaciÃ³n Concurrente: Un Enfoque PrÃ¡ctico
 
La programaciÃ³n concurrente es una tÃ©cnica que permite aprovechar al mÃ¡ximo los recursos de un sistema informÃ¡tico, mediante la ejecuciÃ³n simultÃ¡nea de varios procesos o hilos de control. Esta tÃ©cnica es especialmente Ãºtil en aplicaciones que requieren interacciÃ³n con el usuario, comunicaciÃ³n entre procesos, acceso a recursos compartidos o distribuidos, o cÃ¡lculos intensivos.
 
## Programacion Concurrente Palma 16.pdf


[**Download Zip**](https://www.google.com/url?q=https%3A%2F%2Fbyltly.com%2F2tKCbr&sa=D&sntz=1&usg=AOvVaw3Z57cbFgqjnaHqVQp9z3uy)

 
En este artÃ­culo se presenta un enfoque prÃ¡ctico para aprender los conceptos y las herramientas bÃ¡sicas de la programaciÃ³n concurrente, utilizando el lenguaje Java y la biblioteca de clases java.util.concurrent. Se explican los conceptos de proceso, hilo, sincronizaciÃ³n, exclusiÃ³n mutua, condiciÃ³n de carrera, bloqueo, monitor, semÃ¡foro, barrera y cola. Se muestran ejemplos de cÃ³digo que ilustran el uso de estas herramientas para resolver problemas tÃ­picos de la programaciÃ³n concurrente, como el productor-consumidor, el lector-escritor, el filÃ³sofo comensal y el problema de los fumadores.
 
El artÃ­culo estÃ¡ basado en el capÃ­tulo 16 del libro "ProgramaciÃ³n en Java: Un enfoque desde la ingenierÃ­a", de Luis Joyanes Aguilar y Ignacio Zahonero MartÃ­nez, publicado por la editorial McGraw-Hill en 2016. El libro es una referencia para los estudiantes y profesionales que quieren aprender a programar en Java con un enfoque orientado a objetos y basado en el desarrollo de proyectos reales.
  
Para crear un hilo de ejecuciÃ³n en Java, se puede utilizar la interfaz Runnable o la clase Thread. La interfaz Runnable define un mÃ©todo abstracto run, que contiene el cÃ³digo que se ejecutarÃ¡ en el hilo. La clase Thread implementa la interfaz Runnable y proporciona mÃ©todos para crear, iniciar, detener y controlar el estado de un hilo. Un ejemplo de creaciÃ³n e inicio de un hilo usando la interfaz Runnable es el siguiente:

    class MiHilo implements Runnable 
      public void run() 
        // CÃ³digo que se ejecutarÃ¡ en el hilo

    // CreaciÃ³n de un objeto Runnable
    Runnable r = new MiHilo();
    
    // CreaciÃ³n de un objeto Thread asociado al Runnable
    Thread t = new Thread(r);
    
    // Inicio del hilo
    t.start();

Un ejemplo de creaciÃ³n e inicio de un hilo usando la clase Thread es el siguiente:

    class MiHilo extends Thread 
      public void run() 
        // CÃ³digo que se ejecutarÃ¡ en el hilo

    // CreaciÃ³n de un objeto Thread
    Thread t = new MiHilo();
    
    // Inicio del hilo
    t.start();

Una vez iniciado un hilo, se puede consultar su estado mediante el mÃ©todo getState, que devuelve un valor del tipo enumerado Thread.State. Los posibles estados de un hilo son:
 
- NEW: El hilo ha sido creado pero no iniciado.
- RUNNABLE: El hilo estÃ¡ listo para ejecutarse o se estÃ¡ ejecutando.
- BLOCKED: El hilo estÃ¡ bloqueado esperando a entrar en una secciÃ³n crÃ­tica.
- WAITING: El hilo estÃ¡ esperando indefinidamente a que se cumpla una condiciÃ³n.
- TIMED\_WAITING: El hilo estÃ¡ esperando durante un tiempo determinado a que se cumpla una condiciÃ³n.
- TERMINATED: El hilo ha terminado su ejecuciÃ³n.

 0f148eb4a0
