# Controlador en Python para Conexión por Firmata a Arduino y Detección de Manos con Cámara 🖐️📷

Este proyecto proporciona archivos en Python que permiten controlar una conexión por Firmata a un Arduino y utilizar una cámara para la detección de manos. El Arduino puede ser utilizado para interactuar con dispositivos físicos, mientras que la detección de manos a través de la cámara puede ser utilizada para realizar acciones basadas en gestos.

## Características 🛠️

- **Control por Firmata:** Utiliza la biblioteca `pyfirmata` de Python para establecer una conexión por Firmata con un Arduino, permitiendo el control de dispositivos físicos conectados al Arduino desde el programa en Python.

- **Detección de Manos:** Utiliza una biblioteca de detección de objetos o gestos basada en visión por computadora para detectar manos en tiempo real a través de una cámara.

- **Interfaz con Arduino:** Proporciona una interfaz entre el programa en Python y el Arduino, permitiendo enviar comandos y recibir datos para controlar dispositivos conectados.

## Requisitos 📦

- Python 3.x instalado en tu sistema.
- Bibliotecas Python: `pyfirmata` para la conexión con Arduino y la biblioteca de detección de manos (p. ej., `opencv`, `mediapipe`, `tensorflow`, etc.) para la detección de manos.

## Uso 📝

1. **Clonar el Repositorio:** Clona este repositorio en tu sistema local utilizando Git.

2. **Instalar Dependencias:** Instala las dependencias necesarias utilizando pip o conda. Por ejemplo: `pip install pyfirmata opencv-python`.

3. **Conectar Arduino:** Conecta tu Arduino al ordenador y carga un sketch de Firmata en él utilizando el IDE de Arduino.

4. **Ejecutar el Programa:** Ejecuta el programa Python proporcionado. Asegúrate de seleccionar el puerto COM correcto para la conexión con el Arduino.

5. **Detección de Manos:** La cámara se activará y comenzará a detectar manos en tiempo real. Puedes interactuar con el Arduino enviando comandos desde el programa Python.

## Video de Funcionamiento 📹

🎥[Video de Funcionamiento](https://www.youtube.com/watch?v=sbsLhMg-s3c)

## Contribuciones 🚀

¡Contribuciones son bienvenidas! Si tienes ideas para mejorar el programa, corregir errores o agregar nuevas características, no dudes en abrir un "issue" o enviar un "pull request".

## Créditos 🙌

Este proyecto fue creado por PICAIO SAS y está inspirado en proyectos similares de la comunidad de visión por computadora y Arduino.

## Licencia 📝

Este proyecto está bajo la licencia [MIT](LICENSE).

