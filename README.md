# Introducción a Flask

¡Bienvenido al repositorio **Introducción a Flask**! Este proyecto es una recopilación de aplicaciones y ejemplos básicos diseñados para ayudarte a dar los primeros pasos con el framework Flask en Python. Cada subproyecto se enfoca en un concepto fundamental relacionado con el enrutamiento y el manejo de peticiones.

## 📁 Estructura del Repositorio

A continuación se describen los diferentes proyectos básicos de Flask incluidos en esta carpeta:

- **`routebasic`**:
  Demuestra la creación de las rutas más elementales en Flask. Ideal para entender cómo mapear una URL a una función sencilla que devuelve un contenido al usuario, utilizando el decorador `@app.route()`.

- **`routecrud`**:
  Ejemplo centrado en las operaciones CRUD básicas (Crear, Leer, Actualizar, Eliminar). Muestra cómo manejar datos u objetos a través de las rutas, introduciendo la lógica para manipular información dinámicamente con diferentes endpoints.

- **`routeparam`**:
  Se enfoca en el uso de parámetros dentro de las rutas. Aquí podrás ver cómo capturar valores dinámicos directamente desde la URL (por ejemplo, `/usuario/<nombre>`) y pasarlos a tus funciones para generar respuestas más personalizadas.

- **`routetype`**:
  Explora los diferentes métodos HTTP (como `GET`, `POST`, `PUT`, `DELETE`) en las rutas. También demuestra cómo usar conversores o tipos de datos específicos en las URLs (por ejemplo, validando que un parámetro sea estrictamente un entero o un string).

## 🚀 Requisitos y Configuración

Para ejecutar cualquiera de estos proyectos locales, necesitarás tener instalado Python. Es altamente recomendable trabajar dentro de un entorno virtual para mantener las dependencias aisladas.

### Pasos Rápidos

1. **Clona y accede al repositorio:**

   ```bash
   git clone https://github.com/Ale-72/Introduccion-a-Flask
   cd Flask
   ```

2. **Crea y activa un entorno virtual (Opcional pero muy recomendado):**

   ```bash
   python -m venv venv

   # En Windows:
   venv\Scripts\activate

   # En macOS/Linux:
   source venv/bin/activate
   ```

3. **Instala las dependencias (Flask):**
   Si cada carpeta incluye su propio `requirements.txt`, instálalo o instala Flask globalmente en tu entorno:

   ```bash
   pip install Flask
   ```

4. **Ejecuta cualquier ejemplo:**
   Navega a la carpeta del proyecto que desees probar y ejecuta la aplicación:
   ```bash
   cd routebasic
   python app.py
   ```
   _Luego, abre tu navegador web y ve a `http://127.0.0.1:5000/`._

## 📄 Licencia

Este proyecto se distribuye bajo la licencia MIT.
