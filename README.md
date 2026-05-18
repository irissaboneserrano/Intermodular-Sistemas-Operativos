# Intermodular-Sistemas-Operativos
# Proyecto Intermodular  
## Sistemas Operativos Monopuesto  
### 1º SMR

**Alumno:** Iris Saboné Serrano

# Índice

1. Elección del sistema operativo  
2. Instalación del sistema operativo  
   - 2.1 Selección de idioma y configuración inicial  
   - 2.2 Selección de opción de configuración  
   - 2.3 Clave de producto  
   - 2.4 Selección de versión de Windows  
   - 2.5 Términos de licencia y partición del disco  
   - 2.6 Preparación de la instalación  
   - 2.7 Configuración regional  
3. Configuración básica del sistema  
   - 3.1 Asignar nombre al dispositivo  
   - 3.2 Configuración de uso  
   - 3.3 Configuración de cuenta  
   - 3.4 Configuración de red  
4. Gestión de usuarios  
   - 4.1 Configurar lo necesario  
5. Instalación de software necesario  
6. Medidas básicas de seguridad  

---

# 1. Elección del sistema operativo

Se ha seleccionado el sistema operativo **Windows 11** para los equipos de la empresa debido a sus ventajas en un entorno de diseño gráfico y herramientas ofimáticas.

Windows 11 es compatible con la mayoría de programas profesionales de diseño, como herramientas de edición de imagen, ilustración y contenido digital.

Además, es un sistema operativo fácil de usar, lo que facilita el trabajo de los empleados.

Otra ventaja importante es su integración con redes, lo que facilita la compartición de archivos entre los distintos equipos, algo esencial en un entorno donde se trabaja con proyectos de gran tamaño.

También ofrece actualizaciones de seguridad, un buen rendimiento en equipos modernos y herramientas de protección como el firewall y antivirus, lo que ayuda a mantener los sistemas seguros frente a posibles amenazas.

Por todo ello, Windows 11 se considera la opción más adecuada para cubrir las necesidades de la empresa.

---

# 2. Instalación del sistema operativo

Se ha realizado la instalación del sistema operativo **Windows 11** en los equipos de la empresa mediante un proceso estándar.

## 2.1 Selección de idioma y configuración inicial

En esta primera pantalla se debe seleccionar el idioma, formato de hora y moneda y tipo de teclado.

En este caso, se selecciona el idioma español. Esta configuración es importante ya que determina el idioma de todo el sistema operativo.

## 2.2 Selección de opción de configuración

En esta pantalla se selecciona el tipo de acción que se quiere realizar sobre el equipo.

Se elige la opción **“Instalar Windows 11”**, ya que se va a realizar una instalación completa del sistema operativo desde cero.

Además, se marca la casilla que indica que se aceptan las condiciones de la instalación, incluyendo la eliminación de todos los archivos, aplicaciones y configuraciones del equipo.

Esta selección también es importante porque implica que se realizará una instalación limpia, lo que garantiza un sistema más estable.

## 2.3 Clave de producto

En este paso se solicita la introducción de la clave de producto de Windows.

En este caso, se selecciona **“No tengo clave de producto”**, lo que permite continuar con la instalación sin activar el sistema en ese mismo momento.

Esto es útil en entornos de prueba o cuando la activación se hará posteriormente.

## 2.4 Selección de versión de Windows

En esta pantalla se selecciona la versión del sistema operativo que se va a instalar.

Se selecciona una versión específica en función de las necesidades del equipo, teniendo en cuenta la gestión de usuarios, seguridad y funcionalidades.

En el caso de mi empresa he elegido **Windows 11 Pro**.

## 2.5 Términos de licencia y partición del disco

En primer lugar, se aceptan los términos de licencia del sistema, algo necesario para poder continuar con la instalación.

A continuación, se selecciona el disco duro o partición donde se instalará Windows.

Se elige el disco principal del equipo, permitiendo que el sistema se instale en él.

## 2.6 Preparación de la instalación

En esta pantalla se muestra un resumen de la configuración.

A continuación, comienza la instalación del sistema operativo.

## 2.7 Configuración regional

Una vez finalizada la instalación, se inicia la configuración inicial del sistema.

Aquí se selecciona la región del equipo, en este caso **España**, lo que permite ajustar configuraciones regionales como idioma, formato de fecha y servicios disponibles.

También preguntará si se quiere una distribución del teclado; se selecciona **Omitir**.

---

# 3. Configuración básica del sistema

## 3.1 Asignar nombre al dispositivo

En este paso se asigna un nombre al dispositivo.

Este nombre permitirá identificar el equipo dentro de una red.

## 3.2 Configuración de uso

En esta pantalla se selecciona qué uso va a tener el equipo, ya sea personal, profesional o educativo.

## 3.3 Configuración de cuenta

En esta pantalla se solicita iniciar sesión con una cuenta de Microsoft.

Ya que no es un equipo personal, se debe utilizar la combinación **Shift + F10** para abrir **cmd** y escribir:

```cmd
start ms-cxh:localonly
## 3.4 Configuración de red

Se ha realizado la configuración de red, permitiendo así su conexión a Internet y la red local de la empresa.

Para ello, se ha asignado una dirección IP al equipo, junto con la máscara de subred y puerta de enlace.

Ruta de configuración:

**Configuración → Red e Internet → Configuración de red avanzada → Ethernet**

En **Más opciones del adaptador**, se selecciona **IPv4** y se asigna la dirección correspondiente.

Para comprobar que todo está correctamente establecido, se abre **cmd** y se ejecuta el comando correspondiente.

---

# 4. Gestión de usuarios

Se han creado distintos usuarios con diferentes funciones dentro de la empresa.

Los usuarios estándar tienen permisos limitados para garantizar la seguridad, mientras que el administrador puede realizar tareas de configuración y mantenimiento del sistema.

## 1. Administrador

- Instala programas  
- Cambia configuraciones  
- Gestiona los otros usuarios  

## 2. Diseño

- Solo usa programas  
- No accede al sistema  

## 3. Marketing

- Uso normal: navegador, redes y ofimática  

## 4. Administración

- Trabajo de oficina: documentos y facturación  

## 5. Técnico

También debe ser administrador porque:

- Puede instalar software  
- Puede solucionar problemas  

### 4.1 Configurar lo necesario

Se han asignado contraseñas a todos los usuarios, asegurando que sean seguras.

Además, se recomienda cambiar las contraseñas periódicamente y evitar el uso de contraseñas simples.

Para ello, cada usuario debe ir a:

**Configuración → Cuentas → Opciones de inicio de sesión**

Y ahí establecer una contraseña para iniciar sesión.

Por último, en cuanto a los permisos de cada usuario, se puede ver qué tipo de cuenta es cada una yendo a:

**Configuración → Cuentas → Otros usuarios**

---

# 5. Instalación de software necesario

Se han instalado aplicaciones básicas como navegador web, herramientas de ofimática y programas necesarios.

## Navegador → Google Chrome

- Navegador rápido y compatible con todas las páginas  
- Permite usar herramientas online de diseño  
- Sincronización con cuentas  

## Suite ofimática → Microsoft Office

- Para crear documentos, hojas de cálculo y presentaciones  

## Software de diseño → Adobe Creative Cloud

- Edición de imágenes  
- Diseño vectorial (logos e ilustraciones)  
- Maquetación (revistas y carteles)  

## Software de gestión → Holded

- Gestión de facturas y clientes  
- Control de ingresos y gastos  
- Organización de la empresa  

---

# 6. Medidas básicas de seguridad

## Actualizaciones del sistema

- Mantener Windows 11 actualizado  
- Instalar actualizaciones de seguridad automáticamente  
- Actualizar también los programas, especialmente Adobe  

## Uso de contraseñas seguras

- Contraseñas largas  
- Mezclar letras, números y símbolos  
- No usar la misma contraseña para todo  
- Cambiarlas periódicamente  

## Firewall

- Activar el firewall de Windows Defender Firewall  

## Antivirus

- Usar Microsoft Defender (incluido en Windows 11)  
- Mantenerlo actualizado  
- Realizar análisis periódicos  

## Copias de seguridad

- Guardar copias de seguridad  
- Usar disco externo o nube (por ejemplo, Google Drive)  

## Correo y descargas

- No abrir archivos de correos sospechosos  
- Descargar solo desde páginas oficiales  
- Evitar enlaces desconocidos  

## Control de usuarios

- Cada trabajador con su cuenta  
- Evitar usar cuentas de administrador para todo para evitar problemas o equivocaciones
