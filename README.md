# 🧱 Pared Interactiva Stranger Things

Este proyecto recrea una pared interactiva inspirada en *Stranger Things*, que responde a la proximidad detectada con un sensor ultrasónico y enciende luces LED que forman la palabra **HELP**, simulando el clásico efecto de comunicación sobrenatural de la serie.

## 🎯 Objetivo

Crear un montaje funcional y visualmente impactante que reaccione a la presencia cercana encendiendo los LEDs en secuencia para simular una alerta o mensaje. Ideal como decoración interactiva o proyecto de Halloween.

---

## 🧰 Materiales

- 1x Arduino Uno
- 1x Sensor ultrasónico HC-SR04
- 4x LEDs (Rojo, Amarillo, Verde, Azul – o los colores que prefieras)
- 4x Resistencias 220 Ω
- Cables macho-macho
- Protoboard (opcional)
- Fuente de alimentación USB o batería 9V
- Cartel o base para pegar las letras **H**, **E**, **L**, **P**

---

## 🔌 Conexiones

### LEDs:
- LED H → Pin digital 8
- LED E → Pin digital 9
- LED L → Pin digital 10
- LED P → Pin digital 11  
(Todos con resistencia y conexión a GND)

### Sensor ultrasónico HC-SR04:
- VCC → 5V  
- GND → GND  
- TRIG → Pin digital 6  
- ECHO → Pin digital 7

---
![image](https://github.com/user-attachments/assets/dcab518c-6052-4641-a5f5-5a9b77581b30)


## 💡 Funcionamiento

1. Al iniciarse, el Arduino mide constantemente la distancia con el sensor ultrasónico.
2. Si detecta un objeto a menos de 25 cm (puede ajustarse en el código), enciende los LEDs uno por uno formando la palabra **HELP**.
3. Pasado un tiempo, se apagan y reinicia la detección.

---

## 💾 Código

El código se encuentra en el archivo codigo_arduino. Es fácil de modificar para cambiar colores, letras o condiciones de activación.

---

## 📸 Resultado Final

Aquí puedes ver fotos del montaje real del proyecto y cómo se ve encendido. ¡Scroll más abajo para ver la galería!

![image](https://github.com/user-attachments/assets/c586e693-eead-4eea-a758-44c5f653700e)
![image](https://github.com/user-attachments/assets/d684011a-7104-4b56-9f77-805883e23d72)


---

## 📦 Recomendaciones

- Puedes pegar los LEDs sobre cartón o papel con las letras marcadas para mayor impacto visual.
- Si quieres hacerlo portátil, puedes alimentarlo con un portapilas de 6V o una batería recargable.
- También puedes combinar este montaje con sonido o efectos usando un módulo adicional (por ejemplo, DFPlayer Mini).

---

## 💬 Autor

Proyecto desarrollado por [Andrea Ruge](https://github.com/RugeAndrea).  
¡Inspirado en la serie Stranger Things y en la magia de los proyectos interactivos!


