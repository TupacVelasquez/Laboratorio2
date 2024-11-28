# Laboratorio2
Componentes personalizados y uso de API para imagenes

Este laboratorio es una demostración de cómo crear componentes web personalizados utilizando **Web Components**. Contiene varios componentes reutilizables (custom-header, custom-menu, custom-main, custom-footer, cutom-table, custom-gallery, custom -profile) que se utilizan en las páginas `index.html`, `tabla.html`, y `galeria.html`.

## Estructura del Proyecto

El proyecto está estructurado de la siguiente manera:

index.html: Usa los componentes (custom-header, custom-menu, custom-main, custom-profile, custom-footer)
tabla.html: Usa los componentes (custom-header, custom-menu, custom-tabla, custom-footer)
galeria.html: Usa los componentes (custom-header, custom-menu, custom-gallery, custom-footer)

## Descripción de los Componentes

### 1. **`custom-header`**
   - **Descripción**: Componente que muestra el encabezado de la página con un logo y un título.
   - **Uso**: `<custom-header></custom-header>`
   - **Ubicación**: `ComponentesPersonalizados/custom-header.js`
   
   Este componente es responsable de mostrar el logo y el título en la parte superior de la página. Puedes agregar este componente en cualquier parte de tu página HTML para mostrar el encabezado.

### 2. **`custom-menu`**
   - **Descripción**: Componente que crea un menú de navegación horizontal con enlaces a las páginas del proyecto.
   - **Uso**: `<custom-menu></custom-menu>`
   - **Ubicación**: `ComponentesPersonalizados/custom-menu.js`
   
   Este componente muestra un menú de navegación con enlaces a las páginas `index.html`, `tabla.html`, y `galeria.html`. Cada elemento de menú cambia de color cuando el ratón pasa sobre él.

### 3. **`custom-main`**
   - **Descripción**: Componente que se encarga de mostrar el contenido principal de la página.
   - **Uso**: `<custom-main></custom-main>`
   - **Ubicación**: `ComponentesPersonalizados/custom-main.js`
   
   Este componente se utiliza para mostrar un mensaje de bienvenida al usuario a nuestra página y con una imagen de fondo.

### 4. **`custom-footer`**
   - **Descripción**: Componente que muestra un pie de página con el logo de la ESPE, derechos reservados y enlaces a redes sociales.
   - **Uso**: `<custom-footer></custom-footer>`
   - **Ubicación**: `ComponentesPersonalizados/custom-footer.js`
   
   Este componente coloca el pie de página en la parte inferior de cada página con enlaces a redes sociales como Facebook, Twitter e Instagram.

### 5. **`custom-table`**
   - **Descripción**: Componente que muestra una tabla de datos.
   - **Uso**: `<custom-table></custom-table>`
   - **Ubicación**: `ComponentesPersonalizados/custom-table.js`
   
   Este componente es utilizado para mostrar tablas dinámicas de datos. Puedes configurarlo con datos en formato de tabla para presentarlos de manera organizada.

### 6. **`custom-gallery`**
   - **Descripción**: Componente que crea una galería de imágenes con un diseño en cuadrícula.
   - **Uso**: `<custom-gallery></custom-gallery>`
   - **Ubicación**: `ComponentesPersonalizados/custom-gallery.js`
   
   Este componente se encarga de mostrar imágenes en un formato de galería con una estructura de cuadrícula.

### 7. **`custom-profile`**
   - **Descripción**: Componente que representa una página de perfil de usuario con información personalizada.
   - **Uso**: `<custom-profile></custom-profile>`
   - **Ubicación**: `ComponentesPersonalizados/custom-profile.js`

   Este componente se encarga de mostrar la imagen del usuario el nombre y dos botones en este caso de "Seguir" y "Mensaje"
   de un usuario con infomración pesonalizada.






