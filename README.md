# Tailwind by Aprendiendo

Medidas

- n \* 4 = px
- n / 4 = rem

Icono de Heroicons.dev: Añadir class="h-6 w-6" al svg ya que no lo trajo por defecto.

Tailwind utiliza Breakponts Mobile First.

Si nos encontramos en `index.astro` y queremos colocar una imagen desde la carpeta `public/img` no hace falta que coloquemos en el _src_ del elemento _img_, basta con colocar `src="img/article-1.webp"`, ya que asi trabaja Vite, siendo la carpeta raiz _`public`_ y, recordemos que Astro trabaja con él.

Al aplicar rounded al article vemos que los bordes superiores no se redondean ya que la imagen sobrepasa el límite del article. Para solucionar esto podemos aplicar overflow-hidden al elemento padre, quedando ahora si el article redondeado.
