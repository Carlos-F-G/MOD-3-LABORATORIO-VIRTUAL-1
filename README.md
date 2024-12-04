# Proyecto: Hospital Web - Evaluación M3 - Laboratorio Virtual 1

Este parte del proyecto corresponde al desarrollo de un sistema para gestionar citas médicas del sitio web hospital, cumpliendo con los requisitos solicitados en la evaluación. A continuación, se describen los puntos principales implementados y desarrollados.
##

## **Funcionalidades Principales **

### **Listado de Doctores Dinámico:**
  - Se implementó un JSON con la información de los doctores, incluyendo su nombre, especialidad, experiencia, descripción y foto.
  - Los datos se renderizan dinámicamente en la página utilizando JavaScript para mostrar las tarjetas de cada doctor.

### **2. Modal para Reservar Citas:**
  - Al hacer clic en el botón "Solicitar Hora" de un doctor, se abre un modal dinámico que muestra un formulario de reserva.
  -El nombre del doctor se completa automáticamente en el formulario.


### **3.Confirmación de Citas:**
  -Al enviar el formulario de reserva, se muestra un modal de confirmación con el mensaje: "¡Tu hora fue agendada con éxito!"..

### **4.Operaciones con JSON:**
  - Clonación y modificación de datos del JSON sin afectar el original.
  - Fusión de datos adicionales con los doctores para agregar servicios.
  - Transformación del JSON a un formato legible utilizando JSON.stringify().

### **5. Ordenamiento y Búsqueda:**
  - Implementación de funciones para ordenar doctores por nombre y experiencia.
  - Realización de una búsqueda binaria para encontrar doctores por nombre.

### **6. Pilas y Colas:**
  - Uso de una pila para gestionar el registro y procesamiento de citas.
  - Uso de una cola para gestionar pacientes en espera.

### **7. Validación de Formulario:**
  - El formulario de reserva incluye validaciones básicas, como campos requeridos para nombre, correo y fecha.



 

### **Tecnologías Usadas**

HTML: Para la estructura de la página.
CSS/SASS: Para los estilos y diseño visual.
JavaScript (ES6): Para la lógica de la aplicación y manejo de eventos.
JSON: Para gestionar y manipular datos de los doctores.
DOM (Document Object Model): Para la interacción dinámica con la página.
Consola del Navegador: Para pruebas y depuración.

Carlos Farias Galdames
