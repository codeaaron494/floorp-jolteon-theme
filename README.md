# Floorp Jolteon Theme

Un tema personalizado para el navegador **Floorp** basado en una estética neón, inspirado en la elegancia de Jolteon. Este tema utiliza una estructura modular para facilitar la personalización, el mantenimiento y la legibilidad del código.

## Características
* **Diseño Modular:** Código separado en módulos específicos para facilitar cambios rápidos (colores, layout, barra de herramientas, etc.).
* **Estética Neón:** Esquema de colores vibrante con efectos de *glow* (brillo) y sombras adaptadas.
* **Control de Ventana Personalizado:** Botones de control de ventana (minimizar, maximizar, cerrar) animados con GIFs de Pokémon.
* **Sidebar Oscuro:** Interfaz optimizada con una barra lateral de color negro puro para una mejor integración.

## Instalación

1.  Abre tu carpeta de perfil de Floorp:
    * Puedes acceder escribiendo `about:support` en la barra de direcciones y haciendo clic en **"Abrir carpeta del perfil"**.
2.  Dentro de la carpeta de tu perfil, crea una carpeta llamada `chrome` (si aún no existe).
3.  Copia todo el contenido de este repositorio dentro de la carpeta `chrome`.
4.  Asegúrate de que la estructura sea la siguiente:
    ```text
    chrome/
    ├── userChrome.css
    ├── userContent.css
    ├── modules/
    │   ├── _variables.css
    │   ├── _layout.css
    │   ├── _urlbar.css
    │   ├── _tabs.css
    │   ├── _sidebar.css
    │   ├── _window-controls.css
    │   └── _toolbars.css
    └── assets/
        ├── jolteon.gif
        ├── vaporeon.gif
        ├── umbreon.gif
        └── flareon.gif
    ```
5.  Reinicia Floorp para aplicar los cambios.

## Estructura Modular
* `_variables.css`: Define toda la paleta de colores del tema.
* `_layout.css`: Gestiona la estructura base y fuentes globales.
* `_urlbar.css`: Estilos específicos para la barra de direcciones.
* `_window-controls.css`: Gestión de los iconos animados de ventana.

## Personalización
Si deseas cambiar algún color, simplemente edita el archivo `modules/_variables.css`. Al estar modularizado, no necesitas navegar por cientos de líneas de código para encontrar los valores que deseas ajustar.

## Créditos
* Basado en la personalización de [userChrome.org](https://userChrome.org).
* Inspirado en la comunidad de entusiastas de personalización de Firefox/Floorp.

---
*Si te gusta este tema, ¡considera darle una estrella al repositorio!*