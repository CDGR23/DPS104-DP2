# DPS104 - DP2

## Integrantes
- **César Daniel Guzmán Ramírez** — `GR220295`  
- **Nelson Steven Rivas Tobar** — `RT221664`

---

### Ejercicio 1
Desarrollar una aplicación móvil en React Native que permita la gestión de citas para un taller mecánico. La aplicación debe contar con un formulario de registro de citas, almacenamiento local de datos mediante AsyncStorage, y una interfaz de usuario responsiva utilizando Flexbox.
La aplicación debe permitir a los usuarios agendar citas, ingresando el nombre del cliente, modelo del vehículo, fecha y hora de la cita, y una descripción opcional del problema. Se deben implementar validaciones para garantizar que el nombre del cliente tenga al menos tres caracteres, la fecha y hora sean posteriores al momento actual, y que no existan citas duplicadas con la misma fecha y vehículo.
La interfaz debe mostrar la lista de citas almacenadas en AsyncStorage, organizadas en tarjetas con el nombre del cliente, modelo del vehículo y la fecha/hora de la cita. Se debe permitir a los usuarios eliminar citas, con una confirmación previa antes de la eliminación.
Además, la aplicación debe incluir navegación entre pantallas utilizando React Navigation, implementando un Stack Navigator con las siguientes vistas:

- Pantalla de Inicio: Muestra la lista de citas registradas.
- Pantalla de Agregar Cita: Permite a los usuarios registrar una nueva cita.
- Pantalla de Editar Cita: Facilita la modificación de una cita existente.
El diseño de la aplicación debe ser responsivo, organizando las citas en una sola columna en modo vertical y dos columnas en modo horizontal.

[Ejercicio 1](https://snack.expo.dev/@cdgr/dp2-ejercicio-1)

---

### Ejercicio 2
Se requiere el desarrollo de una aplicación móvil en React Native que permita visualizar información sobre platillos típicos a partir de un objeto JSON, mostrando detalles como nombre, descripción, foto, ingredientes, región de origen, precio y categoría. La interfaz debe estructurarse mediante Flexbox, asegurando una disposición adaptable en diferentes tamaños y orientaciones de pantalla, con una organización en una columna en modo vertical y dos columnas en modo horizontal. La navegación se gestionará mediante React Navigation con Stack Navigator, permitiendo moverse entre una pantalla principal, donde se mostrará un resumen del platillo en una tarjeta con imagen y descripción breve, y una pantalla de detalles, donde se visualizará la información completa con la lista de ingredientes.

[Ejercicio 2](https://snack.expo.dev/@6nelson9/platillos?platform=ios)

---
