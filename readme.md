# ¿Qué es una cartera profesional y por qué es necesaria?

Los profesionales de ciberseguridad utilizan **carteras profesionales** para demostrar su educación, habilidades y conocimientos en seguridad cuando solicitan puestos de trabajo. Así, pueden mostrar a las/los potenciales empleadoras/es que les apasiona su trabajo y que pueden desempeñar el puesto que solicitan. 

Una cartera profesional es más completa que un currículum, que por lo general es un resumen de una o dos páginas que brinda información sobre educación, experiencia laboral y logros.

## Opciones para crear tu cartera

Existen varias maneras de presentar una cartera, ya sea autoalojada o en línea. Algunas opciones comunes son:

1. Carpeta de documentos
2. Google Drive o Dropbox™
3. Google Sites
4. Repositorios Git

### Opción 1: Carpeta de documentos

**Descripción:** Una carpeta de documentos es un directorio creado y almacenado en tu computadora. Tú administras la carpeta, las subcarpetas, los documentos y las imágenes. Mantener tus documentos profesionales bien organizados te ahorrará tiempo cuando solicites empleo.

Un ejemplo de estructura de carpetas podría ser:

- **Documentos profesionales**
  - Currículum
  - Educación
  - Herramientas de ciberseguridad
  - Programación

**Configuración:** La creación de carpetas varía según el sistema operativo que uses. Puedes buscar instrucciones en línea para configurarlas en tu computadora.

### Opción 2: Google Drive o Dropbox

**Descripción:** Estas plataformas en la nube te permiten almacenar y compartir documentos de manera sencilla. Cada cambio que hagas en un documento será visible automáticamente para las personas con las que lo compartas.

**Configuración:** Para más información sobre cómo cargar y compartir archivos, visita las páginas de ayuda de [Google Drive](https://drive.google.com) o [Dropbox](https://www.dropbox.com).

### Opción 3: Google Sites

**Descripción:** Google Sites ofrece una manera fácil de presentar tu cartera en forma de sitio web. Permite diseños personalizables, páginas web responsivas y la opción de contenido incrustado. Al finalizar, obtendrás una URL única que puedes compartir en tu currículum.

**Configuración:** Para aprender a crear un sitio, visita la página de [Google Sites](https://sites.google.com).

### Opción 4: Repositorios Git

**Descripción:** Un repositorio Git es una carpeta dentro de un proyecto. Puedes usarlo para almacenar los documentos, laboratorios y capturas de pantalla que completes durante tu formación. Entre las opciones más utilizadas están:

- GitLab
- Bitbucket™
- GitHub

**Configuración:** Para comenzar con GitHub, sigue las instrucciones del documento [Comienza con GitHub](https://github.com).

## Elementos para tu cartera de proyectos

Hay diversas oportunidades para desarrollar elementos para la cartera. Algunos ejemplos incluyen:

- Redacción de una declaración profesional
- Auditoría de seguridad
- Análisis de la estructura y seguridad de la red
- Uso de comandos de Linux para gestionar permisos de archivos
- Consultas SQL para análisis de datos
- Identificación de vulnerabilidades
- Documentación de incidentes
- Importación y análisis de archivos relacionados con la seguridad
- Creación o revisión de un currículum

> **Nota:** No incluyas documentos privados, protegidos por derechos de autor o de propiedad intelectual en tu cartera. Asegúrate de mantener tu sitio o repositorio privado hasta que esté completo.

## Conclusiones clave

Desarrollar una cartera bien organizada y completa a lo largo de tu formación es crucial para aumentar tus posibilidades de impresionar a potenciales empleadoras/es y asegurar un trabajo en ciberseguridad. Cuanto más proactivo/a seas al crear tu cartera, mayores serán tus oportunidades.

## Ejemplo de código para tu cartera en GitHub

Un ejemplo sencillo que puedes incluir en tu repositorio de GitHub podría ser un script para verificar permisos de archivos en Linux usando comandos de terminal:

```bash
#!/bin/bash

# Verifica los permisos de un archivo
if [ -e "$1" ]; then
    ls -l "$1"
else
    echo "El archivo no existe."
fi
