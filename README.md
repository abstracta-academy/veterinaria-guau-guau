# Veterinaria Guau Guau – Sitio de práctica de testing

Aplicación web ficticia para practicar testing de software. Todos los datos son sintéticos.

**Versión:** 1.0.0

## Acceso

- Usuario: `veterinario`
- Contraseña: `Guau2026`

## Pantallas

1. Login
2. Registro de nuevo cliente
3. Ingreso de mascota
4. Ingreso de vacunas
5. Clientes registrados
6. Mascotas registradas (con búsqueda)
7. Ficha de la mascota (datos, dueño y vacunas)

Los requerimientos funcionales están en el documento *Implementación Página Web Veterinaria Guau Guau – Versión 1*.

## Funciones principales

- Registrar un cliente con sus mascotas y las vacunas de cada mascota.
- Agregar una mascota a un cliente ya registrado (Clientes > Agregar mascota).
- Ver la ficha de una mascota con su dueño y sus vacunas, y editarla (Mascotas > nombre de la mascota > Editar mascota).

## Archivos

Cada pantalla es un archivo HTML autocontenido (incluye sus estilos y su lógica):
`index.html`, `cliente.html`, `mascota.html`, `vacuna.html`, `clientes.html`, `mascotas.html` y `ficha.html`.
Mantené los siete archivos juntos en la misma carpeta para que la navegación funcione.

## Cómo usarlo

### Online (GitHub Pages)

1. Subí el contenido de esta carpeta a un repositorio de GitHub (en la raíz).
2. En el repositorio: **Settings → Pages → Build and deployment**.
3. En *Source* elegí **Deploy from a branch**, rama `main`, carpeta `/ (root)`, y guardá.
4. En unos minutos el sitio queda disponible en `https://<tu-usuario>.github.io/<nombre-del-repositorio>/`.

### En tu computadora

- Abrí `index.html` con doble clic (recomendado: Chrome o Edge).
- Si usás Firefox y la navegación entre pantallas no conserva los datos, serví la carpeta con un servidor local:
  `python3 -m http.server 8000` y abrí `http://localhost:8000`.

## Datos

El sitio guarda la información en el navegador (no hay servidor ni base de datos).
Para volver a los datos de prueba iniciales, usá el botón **Restablecer datos de prueba** en la pantalla *Clientes registrados*.
