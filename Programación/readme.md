Este repositorio contiene el código y documentación correspondiente a la programación del robot sumo.
El objetivo del software es controlar el comportamiento autónomo del robot durante un combate, asegurando velocidad de respuesta, estabilidad y estrategia frente al oponente.

🛠️ Tecnologías y Herramientas
	•	Lenguaje: C/C++ (Arduino IDE)
	•	Microcontrolador: ESP32.
	•	Librerías utilizadas:
	•	Servo.h → control de servos o motores.
	•	NewPing.h → manejo de sensores ultrasónicos.
	•	QTRSensors.h → detección de línea negra/blanca.

 🚦 Lógica del Programa
	1.	Inicialización: Configuración de sensores y motores.
	2.	Bucle principal (loop):
	•	Leer sensores.
	•	Determinar si se detecta línea o enemigo.
	•	Decidir estrategia según el estado.
	3.	Acciones posibles:
	•	Avanzar rápido hacia el oponente.
	•	Girar buscando al oponente.
	•	Retroceder y esquivar.
	•	Ajustar dirección si se detecta el borde del área.
