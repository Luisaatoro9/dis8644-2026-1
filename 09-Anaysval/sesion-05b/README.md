# sesion-05b

En esta clase vimos sistemas en los que las acciones ocurren de forma progresiva, siguiendo un orden en el tiempo. 

Entendimos que una señal no actúa toda de golpe, sino que se va desplazando por etapas, lo que permite generar secuencias. 

---

### Clock 

- Es la señal que marca el ritmo.
- Cada pulso = un paso.
- Puede hacerse con 555 o 4093. 

### Chip 4017

Cuando le llega un pulso (desde el clock), cambia la salida activa:

Parte en Q0, luego pasa a Q1, después Q2, y así sucesivamente hasta Q9.
Después de la última, vuelve a empezar desde el principio, formando un ciclo continuo.
- Solo una salida está activa a la vez, lo que hace que la secuencia sea clara y ordenada.
  
### Entradas

- CLK (Clock): hace avanzar la secuencia
- CI: pausa el conteo
- MR: reinicia desde el inicio
  
### Salidas

- Q0 a Q9: se activan una por una
  
### Alimentación

- VCC / GND

  
