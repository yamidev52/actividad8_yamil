# 🧩 Actividad 8 – Aplicación Android (Proyecto de Mensajes SMS)

## 📱 Descripción del Proyecto
Esta aplicación permite **monitorear números telefónicos** y **recibir notificaciones simuladas por SMS** dentro del dispositivo.  
El usuario puede agregar números a una lista, activar el monitoreo y simular mensajes de texto entrantes.  
El objetivo es comprender el uso de **Broadcast Receivers** y **servicios del sistema Android**, enfocándose en la recepción y gestión de mensajes.

---

## 🎯 Objetivos de aprendizaje
- Integración con servicios nativos del dispositivo Android.  
- Implementación práctica de **Broadcast Receivers** para capturar eventos del sistema.  
- Uso del **Notification Manager** para generar notificaciones dinámicas.  
- Aplicación del manejo eficiente de **hilos y tareas en segundo plano**.  
- Fortalecer habilidades de programación con Kotlin en Android Studio.

---

## 🧰 Tecnologías utilizadas
- **Android SDK API 28+**  
- **Lenguaje:** Kotlin  
- **Android Studio** (con AndroidX habilitado):contentReference[oaicite:0]{index=0}  
- **Broadcast Receivers**  
- **Notification Manager**  
- **RecyclerView & View Binding**  
- **ConstraintLayout**

---

## ⚙️ Funcionalidades implementadas
- ➕ **Agregar número de teléfono:** el usuario introduce un número y lo agrega a la lista de monitoreo.  
- 📋 **Visualización de números monitoreados:** los números se muestran dinámicamente en un `RecyclerView`.  
- 📡 **Monitoreo activo:** indicador visual que muestra si el servicio de monitoreo está activo.  
- 💬 **Simulación de SMS:** botón para generar un mensaje SMS simulado que activa el `BroadcastReceiver`.  
- 🔔 **Notificaciones locales:** muestra alertas en la barra de notificaciones cuando se recibe un mensaje simulado.

---
## 🧩 Interfaz de usuario

### Primera Vista
![image](https://github.com/user-attachments/assets/c360fef3-575d-4e14-bf9d-674fa0de6d1a)

### Notificaciones de Mensaje
![image](https://github.com/user-attachments/assets/c4570ec5-5026-4dee-abbe-ca417fc3bfe9)




