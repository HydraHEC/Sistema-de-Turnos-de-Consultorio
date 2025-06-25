# 🩺Sistema de Turnos de consultorio
(repositorio hecho con propositos estudiantiles para demostrar mi conocimiento para una materia "universitaria", no considerar profesionalmente fuera de la inspiracion o la curiosidad)

## ✍️Descripción del Caso
El Centro Clinico llamado: **La Periferia** recibe muchos pacientes diariamente y actualmente los turnos son gestionados de forma manual, lo que les ha causado problemas como; la doble asignacion de turnos, la falta de avisos cuando a una persona le llega su turno, dificultad para integrar nuevas interfaces (como pantallas [totems] y dispositivos móviles) y las configuraciones inconsistentes entre distintas sedes del consultorio (incluso entre dispositivos de la misma sede).

Acudieron a mi para que les pueda diseñar/crear un sistema que pueda reolver sus problemas, un sistema que:
- registre turnos rapidamente
- notifique en pantalla o sistema cuando se llame un turno
- posea la misma configuracion entre dispositivos
- sea facilmente adaptable a formas de visualizacion e interaccion

Con los requisitos que me diero hice un sistema a modo de "piloto" con el cual puedan simular el funcionamiento del sistema final y asi poder recibir su feedback para ajustarlo a lo que necesitan


---
## ✅Descripción General del Sistema

Es un sistema programado en Java con interfaz gui; programada en el IDE Apache Netbeans 25 con JDK 22, esta cuenta con botones para emitir turnos normales o turnos para urgencias (pacientes traidos en ambulancias generalmente), una tabla con la cola de turnos y un historial donde se ve que turno va a que sala medica y cuando esta se desocupa (tras terminar la visita/sesion del paciente). el diseño es sencillo pero funcional, intencionado para en un futuro dividir sus funciones en diferentes pantallas (como suele ser en otras clinicas donde hay varias pantallas mostrando la cola de turnos):
![img](img/image01.png)
