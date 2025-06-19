# 📋 Horario Laboral Interactivo

Una aplicación web completa para el registro y control de horarios laborales con funcionalidad de guardado persistente.

## 🚀 Características

- **Registro completo de trabajador**: Nombre, mes y año
- **Tabla de horarios diarios**: Entrada, salida y cálculo automático de horas trabajadas
- **Campo de incidencias**: Para registrar observaciones diarias
- **Firma digital**: Canvas interactivo para firmar el horario
- **Guardado persistente**: Los datos se mantienen guardados en el navegador
- **Exportación**: Posibilidad de exportar los datos a archivo de texto
- **Diseño responsivo**: Compatible con dispositivos móviles y de escritorio

## 📁 Archivos incluidos

- `index.html` - Estructura principal de la aplicación
- `style.css` - Estilos y diseño visual
- `script.js` - Lógica de la aplicación y funcionalidades
- `README.md` - Este archivo de instrucciones

## 🔧 Instalación y uso

### Opción 1: Uso local
1. Descarga todos los archivos en una carpeta
2. Abre el archivo `index.html` en tu navegador web
3. ¡Listo! La aplicación estará funcionando

### Opción 2: Servidor web local
Si prefieres usar un servidor web local:
```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (si tienes npx instalado)
npx serve .
```

## 📖 Guía de uso

### 1. Información básica
- Ingresa el **nombre del trabajador**
- Selecciona el **mes** y **año** correspondiente
- La tabla de horarios se generará automáticamente con todos los días del mes

### 2. Registro de horarios
- **Entrada**: Selecciona la hora de entrada para cada día
- **Salida**: Selecciona la hora de salida para cada día
- **Horas trabajadas**: Se calculan automáticamente al completar entrada y salida
- **Incidencias**: Escribe cualquier observación o incidencia del día

### 3. Firma digital
- Usa el mouse o el dedo (en dispositivos táctiles) para firmar en el recuadro
- Botón "Limpiar Firma" para borrar y volver a firmar

### 4. Gestión de datos

#### Guardar datos
- Haz clic en **"💾 Guardar Datos"**
- Los datos se guardan automáticamente en el navegador
- Aparecerá una notificación de confirmación

#### Cargar datos
- Haz clic en **"📂 Cargar Datos"**
- Se mostrará una lista de horarios guardados previamente
- Selecciona el horario que deseas cargar

#### Exportar datos
- Haz clic en **"📄 Exportar"**
- Se descargará un archivo de texto con toda la información del horario

## 💡 Consejos de uso

1. **Guardado automático**: Los datos se guardan por trabajador, mes y año
2. **Carga automática**: Al abrir la aplicación, se carga automáticamente el último horario del mes actual
3. **Múltiples horarios**: Puedes tener varios horarios guardados para diferentes trabajadores o períodos
4. **Compatibilidad**: Funciona en Chrome, Firefox, Safari y Edge
5. **Sin internet**: Una vez cargada, la aplicación funciona sin conexión a internet

## 🔒 Privacidad y seguridad

- Todos los datos se almacenan localmente en tu navegador
- No se envía información a servidores externos
- Los datos persisten hasta que limpies el almacenamiento del navegador
- Para mayor seguridad, puedes exportar regularmente tus horarios

## 🛠️ Solución de problemas

### Los datos no se guardan
- Verifica que el navegador permita el almacenamiento local
- Asegúrate de completar el nombre del trabajador, mes y año antes de guardar

### La firma no funciona
- En dispositivos móviles, usa el dedo directamente sobre el canvas
- En computadoras, usa el mouse manteniendo presionado el botón izquierdo

### La tabla no aparece
- Selecciona primero el mes y año
- La tabla se genera automáticamente al completar ambos campos

## 📱 Compatibilidad

- **Navegadores**: Chrome 60+, Firefox 55+, Safari 12+, Edge 79+
- **Dispositivos**: Computadoras, tablets y smartphones
- **Sistemas**: Windows, macOS, Linux, iOS, Android

## 🆘 Soporte

Si encuentras algún problema o tienes sugerencias:
1. Verifica que estés usando una versión actualizada del navegador
2. Intenta limpiar la caché del navegador
3. Asegúrate de que JavaScript esté habilitado

---

**© 2025 Sistema de Horarios - Todos los derechos reservados**

*Aplicación desarrollada para facilitar el control y registro de horarios laborales de manera digital y eficiente.*

