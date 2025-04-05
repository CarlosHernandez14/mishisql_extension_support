# MiShiSQL Extension

MiShiSQL es una extensión para Visual Studio Code que ofrece resaltado de sintaxis, autocompletado y fragmentos de código para tu nuevo lenguaje de consultas SQL basado en ANTLR4. Con esta herramienta, trabajarás de manera más eficiente en tus proyectos de compiladores y análisis de lenguaje.

## Características

- **Resaltado de sintaxis:** Las palabras reservadas, comentarios y estructuras de MiShiSQL se resaltan automáticamente usando una gramática TextMate personalizada.
- **Autocompletado:** Sugerencias contextuales basadas en la gramática definida, para ayudarte a escribir consultas SQL de manera rápida.
- **Snippets y fragmentos de código:** Incluye plantillas para acelerar la creación de consultas comunes.
- **Integración con ANTLR4:** Aprovecha el poder de ANTLR4 para análisis y validación de tu código.

Puedes ver MiShiSQL en acción en la siguiente demostración:

## Requisitos

- **Visual Studio Code:** Se recomienda tener la última versión instalada.
- **ANTLR4:** La extensión está diseñada para trabajar con gramáticas definidas en ANTLR4.
- Otras dependencias propias de tu entorno de desarrollo.

## Configuración de la Extensión

La extensión ofrece algunas opciones de configuración que puedes ajustar en VSCode:

- **`mishisql.enable`**: Activa o desactiva la extensión.
- **`mishisql.autocomplete`**: Configura el comportamiento del autocompletado (por ejemplo, "simple" o "avanzado").
- **`mishisql.theme`**: Permite elegir el tema de resaltado para la sintaxis de MiShiSQL.

Para cambiar estas opciones, ve a las configuraciones de VSCode y busca `mishisql`.

## Problemas Conocidos

- En ocasiones, el autocompletado puede tardar en activarse con consultas muy extensas.
- Puede haber conflictos con otras extensiones que también manejen SQL o resalten sintaxis.

## Notas de la Versión

### 1.0.0
- Lanzamiento inicial de MiShiSQL.
- Soporte básico para resaltado de sintaxis y autocompletado.

### 1.1.0
- Mejoras en la detección de palabras reservadas.
- Nuevos snippets añadidos para consultas comunes.
- Ajustes en la configuración para mayor personalización.

---

## Trabajando con Markdown en VSCode

Aprovecha las funciones de Markdown de VSCode para editar este archivo:

- **Dividir el editor:** `Cmd+\` en macOS o `Ctrl+\` en Windows y Linux.
- **Vista previa:** `Shift+Cmd+V` en macOS o `Shift+Ctrl+V` en Windows y Linux.
- **Sugerencias de Markdown:** Presiona `Ctrl+Space` para ver una lista de snippets disponibles.

## Más Información

- [Documentación de Visual Studio Code](https://code.visualstudio.com/docs)
- [Guía de Gramáticas TextMate para VSCode](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide)
- [ANTLR4](https://www.antlr.org/)

**¡Disfruta usando MiShiSQL y feliz codificación!**
