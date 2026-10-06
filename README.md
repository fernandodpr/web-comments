# web-comments

Comentarios de [fernandodpr.es](https://fernandodpr.es), guardados como
[GitHub Discussions](https://github.com/fernandodpr/web-comments/discussions)
mediante [giscus](https://giscus.app). Este repo no tiene código: solo
existe para alojar las conversaciones. Es público porque giscus lo exige.

## Cómo funciona

- Cada entrada del blog tiene **un hilo** en la categoría
  *Announcements* (solo el dueño y giscus pueden abrir hilos; los
  visitantes responden). La versión en español y en inglés de una
  entrada comparten el mismo hilo.
- El título del hilo es el identificador de la entrada (el nombre de su
  fichero en el blog), y el cuerpo termina en `<!-- sha1: ... -->`:
  giscus encuentra el hilo por ese hash. **No edites ni borres esa
  línea, ni cambies el título**, o la entrada dejará de mostrar sus
  comentarios.
- Los hilos se crean automáticamente al desplegar la web, antes de que
  nadie comente, para que el blog pueda enlazar a ellos.
- Se puede comentar desde el blog (autorizando la app de giscus con
  GitHub) o directamente aquí, en el hilo; en ambos casos aparece en la
  entrada.

## Moderación

Desde GitHub: ocultar o borrar comentarios, bloquear un hilo (*Lock
conversation*) o bloquear usuarios en la configuración de la cuenta.

## Usarlo en otra web

No hay que instalar nada: la app de giscus ya está instalada en este repo.
Configurar el script de giscus con `data-repo="fernandodpr/web-comments"`,
`data-repo-id="R_kgDOU-Imlw"` y una categoría (para no mezclarlo con el
blog, crear una nueva en *Settings → Discussions*, tipo Announcement) y
elegir un mapeo de términos que no choque con los del blog.
