# Tren - Aplicación de Recarga de Abono

## Descripción
**Tren** es una aplicación de escritorio desarrollada en Java con Swing que permite a los usuarios recargar su abono mensual para el tren. La interfaz gráfica es sencilla e intuitiva, con campos para introducir usuario, contraseña, cantidad a recargar y selección del mes de la recarga.  

La aplicación valida los datos introducidos y muestra mensajes informativos según sea necesario, garantizando una experiencia de usuario clara y segura.

---

## Funcionalidades

1. **Ingreso de Usuario y Contraseña**
   - El usuario debe ingresar su nombre de usuario.
   - La contraseña debe tener al menos 8 caracteres.
   - Se muestran mensajes de error si alguno de los campos está vacío o la contraseña no cumple con el mínimo de caracteres.

2. **Recarga de Dinero**
   - El usuario puede ingresar la cantidad de dinero a recargar mediante un `JSpinner`.
   - La cantidad debe ser mayor a 0. De lo contrario, se muestra un mensaje de error.

3. **Selección de Mes**
   - Mediante el componente `JMonthChooser`, el usuario selecciona el mes para el que se desea realizar la recarga.
   - Se muestra el nombre del mes seleccionado en el mensaje de confirmación.

4. **Confirmación de Recarga**
   - Si todos los campos son válidos, se muestra un mensaje de éxito indicando la cantidad recargada y el mes correspondiente.

5. **Control de Cierre de Ventana**
   - Al intentar cerrar la ventana, la aplicación solicita confirmación mediante un `JOptionPane`.
   - Solo si el usuario confirma, la aplicación se cierra correctamente.

---

## Componentes de la Interfaz

- **JTextField** `nombreUsuario` → Para ingresar el nombre del usuario.
- **JPasswordField** `contraUsuario` → Para ingresar la contraseña.
- **JSpinner** `dineroRecarga` → Para seleccionar la cantidad a recargar.
- **JMonthChooser** `mesRecarga` → Para seleccionar el mes de la recarga.
- **JButton** `recargarAbonoButton` → Botón para realizar la recarga.
- **JLabel** → Para mostrar títulos, iconos y etiquetas de los campos.

---

## Uso

1. Ingresar el nombre de usuario.
2. Introducir la contraseña (mínimo 8 caracteres).
3. Seleccionar la cantidad de dinero a recargar.
4. Elegir el mes para la recarga.
5. Pulsar **Recargar Abono**.
6. Verificar el mensaje de confirmación.

---

## Capturas de Pantalla

### Pantalla Principal
*Aquí puedes añadir la captura de la ventana principal de la aplicación.*

![Pantalla Principal](ruta/a/tu/captura1.png)

### Error por Campos Vacíos
*Captura mostrando el mensaje de error al dejar el usuario o la contraseña vacíos.*

![Error Campos Vacíos](ruta/a/tu/captura2.png)

### Recarga Exitosa
*Captura mostrando el mensaje de éxito al recargar el abono.*

![Recarga Exitosa](ruta/a/tu/captura3.png)

---

## Requisitos

- Java 8 o superior.
- Librería `JCalendar` de Toedter para `JMonthChooser`.
- IDE compatible con formularios `.form` de IntelliJ (opcional para modificar GUI).

---

## Instalación

1. Clonar el repositorio.
2. Asegurarse de tener la librería `JCalendar` incluida en el proyecto.
3. Compilar el proyecto y ejecutar la clase `Tren`.

---

## Autor
**Tu Nombre**  
Proyecto de ejemplo de interfaz gráfica para recarga de abono de tren.
