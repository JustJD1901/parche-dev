# Parche Dev 2026

Sitio oficial del encuentro Parche Dev 2026, construido solo con HTML semántico.
Reto individual del Módulo 1 · HTML y CSS, RIWI.

Sitio publicado: https://justjd1901.github.io/parche-dev/

## Páginas

- Inicio
- Agenda
- Ponentes
- Inscripción y confirmación
- Código de conducta

## Cómo verlo en tu computador

1. Clona el repositorio.
2. Ábrelo en VS Code.
3. Abre index.html con Live Preview.

## Decisiones que tomé

- Los campos del formulario los separé haciendo uso de <div> para evitar hacer uso de la etiqueta <br> y facilitar el control de estilos en CSS
- En el apartado de "Lo que vas a encontrar" en la página de inicio, lo listé haciendo uso de <ul> pues las opciones dadas no requieren un orden lógico en la presentación
- Procuré en separar las lineas de texto en varias etiquetas de <p> evitando la etiqueta <br> para no tener problemas con el dieño reponsive y manejar las distancias y espaciados en CSS
### Respuestas a la investigación:

**¿Qué aparece después del `?` en la barra de direcciones?**
Después del '?' aparecen los datos inscritos en el formulario previamente llenado.

**¿Cómo se ven los espacios, las tildes y la arroba?**
Las tildes y arrobas se ven igual, pero los espacios se reemplazan por el símbolo '%'.

**¿Qué pasa con los campos que no llenaste?**
Los campos que quedaron vacíos en el formulario simplemente no aparecen en la barra de búsquedas.

**¿Por qué un formulario con contraseñas nunca debería usar `method="get"`?**
Porque la información queda visible en la barra de direcciones, en el historial, o también pueden quedar almacenadas en la caché del navegador.


## Lo que aprendí

- Aprendí a manejar formularios con su semántica adecuada.
- El manejo de tablas haciendo haciendo uso de sus etiquetas correspondientes para diferenciar encabezados y celdas.
- Enlazar páginas haciendo uso de la etiqueta <a> y del método href.

## Hecho por

Juan Daniel Ortiz Cadavid · [GitHub](https://github.com/JustJD1901)
