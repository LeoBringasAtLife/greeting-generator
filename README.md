# Generador de Saludos

Esta es una aplicación minimalista creada con HTML, CSS y JavaScript vanilla.
El usuario ingresa su nombre y recibe un saludo personalizado.

## Características

- Input de texto para ingresar nombre
- Botón para enviar el nombre
- Saludo personalizado mostrado en grande
- Soporte para enviar con tecla Enter
- Interfaz centrada y responsive
- Estilos minimalistas y limpios

## Tecnologías

- **HTML5** - Estructura
- **CSS3** - Estilos (Flexbox)
- **JavaScript (Vanilla)** - Lógica interactiva

## Estructura

```
proyecto/
└── index.html (HTML + CSS + JS integrados)
```

## Cómo usar

1. Abre el archivo `index.html` en tu navegador
2. Escribe tu nombre en el input
3. Haz clic en "Enviar" o presiona Enter
4. ¡Recibirás tu saludo personalizado! 🎉

## Código principal

```javascript
function mostrarSaludo() {
    const nombre = document.getElementById('nombre').value.trim();
    const saludo = document.getElementById('approve');
    
    if (nombre) {
        saludo.textContent = 'Hola, ' + nombre.toUpperCase();
        document.getElementById('nombre').value = '';
    }
}
```

## Personalización

Puedes modificar:
- Colores de fondo en `background: #f0f0f0`
- Tamaño de fuente en `.approve { font-size: 38px }`
- Placeholder del input
- Mensaje del saludo

## Notas

- El nombre se convierte a mayúsculas automáticamente
- El input se limpia después de enviar
- Funciona con Enter o click en el botón
- Sin dependencias externas

---

**Autor:** [LeoBringasAtLife]
