---
title: "Crear un archivo nuevo con Markdown"
tags:
  - Offrol
  - Colaboracion
date: miércoles, marzo 29º 2023, 11:44:14 am
lastmod: miércoles, marzo 29º 2023, 11:44:28 am
---

# 2. Crear un archivo nuevo con Markdown

Tú, que has decidido ir un paso más allá, quieres crear o editar un artículo para la Wiki usando Markdown. Quizá te preguntes qué es Markdown, pero te anticipo que lo has estado usando todo este tiempo sin darte cuenta. Para usar este método no es necesario instalar nada en tu equipo.

## ¿Qué es Markdown?

Markdown es un lenguaje de marcado ligero para texto que es compatible con infinidad de plataformas. Sirve para darle formato a texto poniendo negritas, cursivas, enlaces, encabezados... y que otras webs o programas sean capaces de leer ese formato.

Es el mismo sistema que utilizan aplicaciones como **Discord** y **Whatsapp** para poner las negritas o los bloques de código, así que es posible que lo hayas usado sin saber que estabas usando Markdown.

No vamos a explicar aquí cómo usar Markdown, para eso tienes la [[colaboracion/guia-estilo|Guía de Estilo de la Wiki]]. Échale un ojo, sepas o no usar Markdown.

## Crear un archivo en Markdown

Para que la Wiki reconozca correctamente el nuevo archivo debe tener unas características concretas (formato de archivo .md y un encabezado YAML correcto), así que la manera más fácil de saltarse todo eso que copies la **[plantilla](https://raw.githubusercontent.com/Musrha/umbral/hugo/content/templates/plantilla.md)** de página de la Wiki.

Después, entra en [StackEdit](https://stackedit.io), un editor de Markdown que funciona desde el navegador (no hace falta crearse cuenta). Tras pinchar arriba en Start Writing te aparecerá la ventana de la apliación. Puedes borrar todo el texto que te aparece por defecto

![](images/tutorial4.jpg)

La parte izquierda es donde editarás el texto y la derecha es una previsualización. Pega el texto de la plantilla en la izquierda y verás la previsualización.

Aquí ya puedes escribir y editar todo lo que creas necesario. Recuerda seguir la [[colaboracion/guia-estilo|Guía de Estilo de la Wiki]] para que todo funcione correctamente y, cuando hayas terminado, copia todo el texto de la izquierda. **Asegúrate de que no hay un espacio en blanco encima de los tres guiones del principio.**

![](images/tutorial5.jpg)

Ve a [Github de la Wiki](https://github.com/Musrha/umbral/tree/hugo/content) y navega hasta la carpeta donde estará el archivo. En esta caso, será *habitantes/aventureros/osarios*. Ahora, debes pinchar en **Add File** y en el desplegable que aparecerá, pincha en **Create new file**.

![](images/tutorial6.jpg)

Arriba, en Name your file... debes escribir el nombre del archivo, **siempre en minúsculas y con guiones en vez de espacios, terminando en .md**. Como ves en el ejemplo, Denoroth sería denoroth.md* y Villa del Hambre sería *villa-del-hambre.md*. Pega después el texto que habías copiado anteriormente en StackEdit y pinchar en **Propose new file**.

Te saldrán un par de ventanas más, pero no debes hacer nada más en ellas que seguir adelante pinchando en **Create pull request** en ambos casos.

![](images/tutorial7.jpg)

![](images/tutorial8.jpg)

Y ya está. Una vez lo hayas enviado, el archivo quedará pendiente para que uno de los colaboradores del Pacto lo revise y acepte. Una vez lo haga, [[habitantes/otros-habitantes/guifre|Guifré]] y el resto de obreros de [[levaryck/civilizaciones/ciudades/billalmedio|Billalmedio]] actualizarán la Wiki automáticamente en unos minutos.!
