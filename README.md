# Generador de código QR 

Este código pertenece a los bots que operan en las redes **TRON**, **Ravencoin** y **Zcash**.  
Su función es generar un **QR directo** con la dirección que el usuario ingresa, sin redirecciones ni modificaciones.

---

### 🧩 ¿Qué hace?

El comando `/qr` permite crear un código QR que contiene **exactamente la dirección enviada por el usuario**.  
No se reemplaza, altera ni apunta a ninguna otra dirección.

Ejemplo de uso en Telegram:
/qr t1ZcashDireccionDeEjemplo

---

### ⚙️ Cómo funciona

1. El bot recibe la dirección.
2. Verifica que sea válida (en este caso, direcciones de Zcash).
3. Genera un código QR con esa dirección como único contenido.
4. Añade el ícono de la red (Zcash) al centro del QR.
5. Envía la imagen al usuario junto con una advertencia sobre usar solo la red correcta.

---

### 🔒 Transparencia

- El QR **no contiene enlaces ocultos ni redirecciones**.  
- El texto codificado es **exactamente la dirección ingresada**.  
- Cualquier usuario puede verificarlo escaneando el QR con cualquier lector público.

---

### 📝 Nota final

Este código se publica **por transparencia y confianza**.  
Su única función es mostrar, de forma verificable, que los códigos QR generados por los bots apuntan **solo** a la dirección que el usuario indica.  
No se almacena, modifica ni reenvía ninguna dirección a terceros.

El objetivo es mantener prácticas abiertas y verificables en proyectos relacionados con **criptomonedas y privacidad**.
