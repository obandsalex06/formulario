# formulario
# Formulario de Registro en HTML y CSS en la misma hoja

Este proyecto es un formulario de registro desarrollado en HTML y CSS que permite a los usuarios ingresar sus datos personales de forma sencilla, atractiva y accesible. Está diseñado para ser responsivo y fácil de usar.

## Características del formulario

- Campos de entrada para nombres, apellidos, correo electrónico, fecha de nacimiento, ciudad, teléfono y contraseña.
- Validaciones básicas en los campos con expresiones regulares (`pattern`) y atributos como `required`, `minlength` y `placeholder`.
- Selector de fecha para la fecha de nacimiento.
- Menú desplegable (select) para elegir la ciudad.
- Radio buttons para seleccionar el nivel de experiencia en programación (Principiante, Intermedio, Avanzado), alineados horizontalmente.
- Checkbox para aceptar los términos y condiciones, correctamente alineado con su etiqueta.
- Área de texto para comentarios adicionales.
- Diseño visual moderno con fondo personalizado, bordes redondeados y colores suaves.
- Diseño adaptativo (responsive) para dispositivos móviles gracias al `viewport` y uso de `max-width`.

## Validaciones incluidas

- **Nombre y Apellido**: Solo letras y espacios, entre 3 y 40 caracteres.
- **Correo electrónico**: Validación automática con `type="email"`.
- **Fecha de nacimiento**: Campo de tipo `date`.
- **Teléfono**: Solo números (exactamente 10 dígitos).
- **Contraseña**: Debe tener mínimo 6 caracteres, incluyendo al menos una letra y un número.
- **Campos obligatorios**: Todos los campos son obligatorios excepto los comentarios adicionales.

## Diseño visual

El formulario se presenta dentro de una caja semitransparente centrada sobre una imagen de fondo (`../_img/image.png`). Usa `flexbox` para mejorar la alineación de los campos tipo radio y checkbox.

## Estructura recomendada del proyecto
formulario/
├── _img/
│ └── image.png
├── index.html
└── README.md

## Autor
Alex Jhair Obando Zuñiga
ficha: 3147235
fecha: 04/06/2025