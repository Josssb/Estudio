# Historias de Usuario

Este archivo contiene las historias de usuario para la aplicación de entrada de datos del vehículo.

## Historia de Usuario 1: Ingresar Datos del Vehículo

**Como** usuario de la aplicación,  
**Quiero** poder ingresar la información básica del vehículo (marca, modelo, cilindrada, tipo de combustible, capacidad en pasajeros),  
**Para** poder almacenar y ver estos detalles.

### Criterios de Aceptación:
- El usuario puede ingresar la marca del vehículo y la aplicación debe aceptar cualquier cadena de texto.
- El usuario puede ingresar el modelo del vehículo y la aplicación debe aceptar cualquier cadena de texto.
- El usuario puede ingresar la cilindrada y el tipo de combustible del vehículo, y la aplicación debe aceptar cualquier cadena de texto.
- El usuario puede ingresar la capacidad en pasajeros del vehículo, y la aplicación debe aceptar solo números enteros.

## Historia de Usuario 2: Mostrar Datos Ingresados

**Como** usuario de la aplicación,  
**Quiero** ver los datos del vehículo que ingresé en un formato claro y organizado,  
**Para** confirmar que la información proporcionada es correcta.

### Criterios de Aceptación:
- La aplicación muestra un mensaje de confirmación con los detalles ingresados por el usuario, incluyendo marca, modelo, cilindrada, tipo de combustible y capacidad en pasajeros.

## Historia de Usuario 3: Validación de Entrada

**Como** desarrollador de la aplicación,  
**Quiero** validar las entradas del usuario,  
**Para** asegurar que los datos ingresados sean adecuados y evitar posibles errores.

### Criterios de Aceptación:
- El sistema verifica que la capacidad de pasajeros sea un número entero.
- El sistema muestra un mensaje de error si se ingresa un valor no válido.
