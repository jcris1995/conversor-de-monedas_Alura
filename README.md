<p align="center">
  <img src=https://github.com/DavidVF7/Conversor-de-Monedas/assets/103916971/645bfae6-38cf-4f90-add7-8f9b3929cb5a"
</p>

# Conversor de Monedas
💵 💱 💶
Una herramienta práctica y eficiente para convertir divisas en tiempo real.

Creado como parte del desafío "Conversor de Monedas", planteado por Alura Latam en conjunto con Oracle dentro del programa ONE, como parte de la especialización en Back-End.

## Descripción de proyecto 📝

Este proyecto es un Conversor de Monedas desarrollado en Java, diseñado para realizar conversiones de divisas en tiempo real utilizando una API de tasas de cambio actualizadas. Su funcionalidad permite a los usuarios:

*Solicitar y procesar datos de tasas de cambio desde una API externa.
*Convertir diversas monedas de forma rápida y precisa.
*Visualizar un historial detallado de conversiones, incluyendo la fecha y hora de cada consulta.
*El proyecto destaca por su interfaz clara, su estructura optimizada para facilitar el mantenimiento y su capacidad de adaptarse a nuevos requerimientos, siendo una solución ideal para gestionar conversiones monetarias de manera eficiente.

## Tecnologías Utilizadas 💻

*Lenguaje de Programación: Java, utilizado para el desarrollo principal de la aplicación.
*API de Tasas de Cambio: API en tiempo real para obtener las tasas de conversión entre diferentes divisas.
*Biblioteca Gson: Empleada para analizar y procesar las respuestas JSON de la API, transformándolas en objetos Java.
*Control de Versiones: Git y GitHub para gestionar el versionado del proyecto y la colaboración en equipo.
*IDE (Entorno de Desarrollo Integrado): IntelliJ IDEA, utilizado para escribir, depurar y ejecutar el código del proyecto.
*Estas tecnologías permiten garantizar una aplicación robusta, eficiente y fácil de mantener.

## Clases y Funcionalidades 🧩

### Calculos.java

se encarga de gestionar la lógica principal vinculada a las conversiones de divisas. Incluye métodos para almacenar los valores asociados a las monedas, ejecutar las conversiones entre ellas y generar mensajes de respuesta adecuados para los usuarios.

### ConsultaConversion.java

Se encarga de realizar solicitudes a una API externa para obtener las tasas de cambio actualizadas entre distintas divisas.

### GeneradorDeArchivos.java

Clase responsable de almacenar el historial de consultas en un archivo de texto, permitiendo registrar las conversiones realizadas para su posterior consulta.

### Principal.java

El punto de entrada principal del programa. Esta clase gestiona la interacción con el usuario a través de la consola, presentando un menú de opciones y coordinando las operaciones necesarias para realizar las conversiones de moneda.

## 👨‍💻 Desarrollador de proyecto:

Jean Cristian Valencia García 

## Instrucciones de uso: 

*Clona este repositorio en tu máquina local.
*Abre el proyecto en IntelliJ IDEA o en el IDE de tu preferencia.
*Ejecuta la clase Principal.java para iniciar la aplicación.
*Sigue las instrucciones que aparecerán en la consola para realizar las conversiones de moneda.

¡Disfruta usando el conversor de monedas!
