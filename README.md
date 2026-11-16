# Rueda Libre

Rueda Libre es un sitio web informativo para un emprendimiento de Medellín dedicado al alquiler de bicicletas y a la organización de recorridos guiados por la ciudad. La página presenta sus servicios, tarifas, bicicletas y formas de contacto, y orienta a los visitantes sobre cómo reservar.

## Funciones

- **Inicio:** presenta el emprendimiento, sus servicios, la ubicación en Laureles, indicaciones para alquilar, una sección de flota y beneficios.
- **Tarifas:** muestra precios de alquiler por tipo de bicicleta y duración, además de recorridos guiados con distancia, duración, nivel y precio.
- **Reservas:** presenta los horarios de atención y un formulario para ingresar datos personales, teléfono y fecha de alquiler. El formulario incluye validaciones básicas del navegador.
- **Contacto:** ofrece enlaces de correo electrónico y un acceso a WhatsApp.
- **Diseño adaptable:** utiliza Bootstrap y CSS para organizar parte del contenido según el tamaño de pantalla.

> **Nota:** el formulario de reservas es solo visual: actualmente utiliza `action="#"` y no envía ni guarda los datos. El enlace de correo abre el programa de correo del visitante. Antes de publicar el sitio, se deben configurar los datos reales de contacto y conectar el formulario a un servicio de reservas.

## Tecnologías

- HTML5
- CSS3
- Bootstrap 5.3.8, cargado desde CDN
- Google Fonts: Montserrat y Open Sans

No se requiere instalar dependencias ni compilar el proyecto. Bootstrap y las fuentes se cargan desde internet.

## Estructura del proyecto

```text
rueda-libre/
├── index.html                 # Página de inicio
├── css/
│   └── styles.css             # Estilos compartidos
├── img/                       # Imágenes del sitio
├── paginas/
│   ├── reservas.html          # Horarios y formulario de reserva
│   └── tarifas.html           # Tarifas de alquiler y recorridos
└── pruebas/
    └── catalogo-bootstrap.html
```

## Cómo ver el sitio

1. Descarga o clona este repositorio.
2. Abre `index.html` en un navegador.
3. Usa el menú para visitar **Tarifas** y **Reservas**.

También puedes abrir la carpeta con Visual Studio Code y usar una extensión de servidor local, como Live Server.
