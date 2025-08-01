# Android QA Challenge

## Caso de uso
Quiero registrar el contenido de lo que un usuario ve en su teléfono Android.

Este reto te pide explorar lo que sí es posible hacer desde el punto de vista técnico, legal y práctico en Android, respetando el consentimiento y la privacidad del usuario.

---

## 📂 Estructura esperada

- `content_android.txt`: Respuestas sobre grabación de pantalla y transmisión.
- `detection_android.txt`: Respuestas sobre detección de actividad y apps.
- `network_android.txt`: Respuestas sobre análisis de red.
- `poc/`: Carpeta opcional con tu prueba de concepto (código, video, o diagrama).

Puedes agregar imagenes o links a herramientas visuales
---

## 🧩 Tareas

### 🔹 Transmisión y captura de contenido (`content_android.txt`)

1. Diseña un flujo de usuario para una app que permita grabar toda la pantalla del dispositivo (incluso si el usuario cambia entre apps).  
   - ¿Qué clases o frameworks utilizarías?
   - ¿Qué restricciones debes considerar (DRM, permisos, batería)?

2. ¿Es posible detectar y extraer los frames de video de una app de streaming?  
   - ¿Qué métodos o técnicas usarías para acceder al contenido en pantalla o sus elementos visibles?

3. ¿Cómo podrías enviar esa grabación o captura de pantalla a un servidor en tiempo real sin afectar el rendimiento del dispositivo?

---

### 🔹 Detección de actividad y apps (`detection_android.txt`)

4. ¿Qué métodos existen para detectar qué apps tiene instaladas un usuario y cuáles están activas en ese momento?  
   - ¿Qué permisos necesitas?
   - ¿Qué cambios ha habido en versiones recientes de Android sobre esto?

5. ¿Cómo podrías detectar que el usuario está viendo contenido de una app de streaming?  
   - Propón un enfoque técnico (por ejemplo, uso del Servicio de Accesibilidad, captura de pantalla, análisis de tráfico de red, etc.)

6. ¿Puedes saber qué película o episodio está viendo el usuario sin acceder directamente a la app?  
   - Describe una solución técnica viable.

---

### 🔹 Análisis de red (`network_android.txt`)

7. ¿Puedes capturar tráfico de red desde el dispositivo? ¿Qué herramientas o APIs usarías (por ejemplo: VPN local, tráfico TLS, análisis de paquetes)?  
   - ¿Qué limitaciones existen con contenido cifrado (HTTPS/DRM)?

8. ¿Podrías inferir qué contenido se está viendo (por ejemplo, URL de un video, nombre de archivo, dominio)?  

---

## 🚀 Prueba de concepto (POC)

Crea una prueba de concepto que demuestre estas capacidades:

- Grabar la pantalla del dispositivo (con consentimiento) mientras se navega entre apps.
- Analizar tráfico de red y generar inferencias sobre el contenido consumido.
- Mostrar una lista de apps instaladas clasificadas como "entretenimiento".

> La prueba de concepto puede ser:
> - Código funcional (Kotlin o Java)
> - Un video explicativo o de demo
> - Un esquema técnico (diagrama de arquitectura, flujo de datos, etc.)


ℹ️ **Duración**: 3 días a partir de la aceptación del reto.
