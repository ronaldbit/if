# Icon Font Project

Un proyecto de iconos de fuente que proporciona una colección de iconos personalizables y escalables para tus aplicaciones web.

![Accede a la web y busca el icono perfecto para tu proyecto](https://icons.ronaldbit.com/assets/img/if.png)

## Licencia

Este proyecto está licenciado bajo la **Licencia Creative Commons Attribution-NonCommercial 4.0 (CC BY-NC 4.0)**. Esto significa que puedes usar, modificar y compartir el proyecto, pero no puedes usarlo con fines comerciales. Siempre debes dar crédito al autor original.

## Características

- Colección de iconos escalables en formato de fuente.
- Personalización fácil de colores y tamaños a través de CSS.
- Compatible con todos los navegadores modernos.
- Incluye ejemplos de uso y documentación.

## Instalación

Para usar este proyecto, sigue estos pasos:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/ronaldbit/if.git
   ```

   O descarga los archivos como ZIP desde el repositorio.

2. Entra en la carpeta del proyecto:
   ```bash
   cd if
   ```

3. Agrega los archivos CSS a tu proyecto. Puedes copiarlos a tu carpeta de estilos o usarlos desde la carpeta del repositorio.

### Cómo usar los iconos

Agrega las siguientes líneas en la sección `<head>` de tu archivo HTML:

```html
<link rel="stylesheet" href="if.css">
<link rel="stylesheet" href="if-all.css">
```

Una vez que hayas incluido los archivos CSS, puedes comenzar a usar los iconos en tu HTML. Por ejemplo, para mostrar un icono, utiliza el siguiente código:

```html
<i class="ifs if-icons"></i> <!-- Esto mostrará el icono deseado -->
```

### Ejemplo:

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="if.css">
    <link rel="stylesheet" href="if-all.css">
    <title>Ejemplo de Icon Font</title>
</head>
<body>
    <h1>Ejemplo de Uso de Iconos de Fuente</h1>
    <i class="ifs if-user-tie"></i> <!-- Icono de usuario -->
</body>
</html>
```

## Personalización

Puedes personalizar el tamaño y color de los iconos añadiendo clases. Por ejemplo:

```css
<i class="ifs if-user-tie if-2xl"></i>
<i class="ifs if-user-tie if-red"></i>
<i class="ifs if-user-tie if-flip-vertical"></i>
```

Incluso agregar animaciónes. Por ejemplo:

```css
<i class="ifs if-user-tie if-fade"></i>
<i class="ifs if-user-tie if-beat-fade"></i>
```

Para ver más personalizaciones, puedes visitar la [web](https://icons.ronaldbit.com).

## Contribuciones

Las contribuciones son bienvenidas. Si deseas contribuir a este proyecto, sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b nombre_de_rama`).
3. Realiza tus cambios y haz un commit (`git commit -m 'Agrega un nuevo icono'`).
4. Haz push a la rama (`git push origin nombre_de_rama`).
5. Abre un Pull Request.

## Créditos

- **RonaldRamos** - Autor original del proyecto.
- [Enlace a tu perfil de GitHub](https://github.com/ronaldbit)

## Contacto

Si tienes alguna pregunta o necesitas más información, no dudes en contactarme:

- Correo: hola@ronaldbit.com
