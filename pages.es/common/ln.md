# ln

> Crea enlaces a archivos y directorios.
> Más información: <https://www.gnu.org/software/coreutils/manual/html_node/ln-invocation.html>.

- Crea un enlace simbólico a un archivo o directorio:

`ln {{[-s|--symbolic]}} {{/ruta/al/archivo_o_directorio}} {{ruta/al/enlace_simbólico}}`

- Sobrescribe un enlace simbólico existente para que apunte a un archivo distinto:

`ln {{[-sf|--symbolic --force]}} {{/ruta/al/nuevo_archivo}} {{ruta/al/enlace_simbólico}}`

- Crea un enlace duro a un archivo:

`ln {{/ruta/al/archivo}} {{ruta/al/enlace_duro}}`
