# Chatbot Inteligente en C++ - Laboratorio 12

## Descripción

Este proyecto consiste en la creación de un chatbot básico utilizando C++. El objetivo principal es interpretar preguntas realizadas por el usuario y proporcionar respuestas basadas en una base de conocimiento local.  
Se implementaron diversas estrategias de búsqueda: coincidencia exacta, búsqueda por palabras clave, y (opcionalmente) búsqueda por similaridad de frases utilizando el algoritmo de distancia de Levenshtein.

## Características

- **Carga de conocimiento** desde un archivo de texto `conocimiento.txt`.
- **Búsqueda exacta** de preguntas.
- **Búsqueda por palabras clave** ignorando diferencias de mayúsculas/minúsculas.
- **Búsqueda por similaridad** mediante distancia de Levenshtein para encontrar coincidencias aproximadas.
- **Manejo de errores**: respuestas predeterminadas si no se encuentra coincidencia.
- **Personalización de mensajes** para una mejor experiencia de usuario.

## Tecnologías Utilizadas

- Lenguaje de programación **C++**
- Librerías estándar de C++ (`<iostream>`, `<fstream>`, `<string>`, `<sstream>`, `<map>`, `<vector>`, `<algorithm>`)

## Estructura del Proyecto

Ícono	Significado
📁 Algoritmos-IA-y-APIs	Es la carpeta principal (tu proyecto GitHub).
├── conocimiento.txt	Archivo con las preguntas y respuestas.
├── Algoritmos IA y APIs.cpp	El código fuente que hicimos.
├── informe.txt	Tu informe/documentación del laboratorio.
├── README.md	El mismo archivo que estamos creando ahora.


## Instrucciones de Uso

1. Clona o descarga este repositorio.
2. Asegúrate de que `conocimiento.txt` esté en la misma carpeta que el archivo `.cpp`.
3. Compila el proyecto utilizando un compilador de C++.
4. Ejecuta el programa y realiza preguntas al chatbot.
5. Escribe `salir` para finalizar la conversación.

## Requisitos

- Compilador compatible con C++ (Visual Studio, g++, etc.)
- Archivo `conocimiento.txt` correctamente estructurado con preguntas y respuestas separadas por `|`.


## Créditos

- Desarrollado por: **Brayan Omar Barrios Enríquez**
- Asistencia técnica y optimización de algoritmos mediante el uso de **ChatGPT** como herramienta de apoyo.

## Licencia

Este proyecto es de carácter académico y no posee licencia comercial. Uso libre para fines educativos.
