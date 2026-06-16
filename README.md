# Plan de Estudios Interactivo - Ingeniería de Sistemas (UNICEN)

## Introducción
Este proyecto surgió por la necesidad de tener un tracker visual e interactivo para saber exactamente cómo estoy parado en la carrera. 

Solo sirve para el plan de estudios 2025

## Características Principales
- **Sistema de correlatividades:** Al pasar el cursor sobre una materia, el plan oscurece el resto y resalta automáticamente qué materias previas faltan aprobar (rojo), cuáles ya están cumplidas (verde) y qué materias futuras se desbloquean (violeta).
- **Cálculo automático:** Muestra en tiempo real el porcentaje de avance de la carrera y el promedio general según las notas ingresadas.
- **100% Local y Privado:** El estado de las materias y las notas se guardan directamente en el `localStorage` del navegador. No usa bases de datos externas ni recolecta información.
- **Exportar/Importar JSON:** Permite descargar un backup de tu progreso en un archivo `.json` para llevarlo a otra PC o navegador, y volver a importarlo con un clic.
- **Integración con SIU Guaraní:** Podés subir directamente tu Historia Académica en formato Excel y el sistema mapea y actualiza automáticamente todos tus estados y notas.

## Uso
Simplemente abrí el archivo `index.html` en cualquier navegador web moderno. 
- Hacé clic en las materias para cambiar su estado (Sin cursar, Cursando, Aprobada, Finalizada) y cargar tu nota de forma manual.
- O usá el botón **"Cargar Excel del SIU"** para subir tu archivo original descargado del sistema y dejar que la página complete todo tu progreso por arte de magia.
