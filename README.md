
Breve introducción teórico-práctica en castellano a GPG.

Esta charla forma parte de las [Jornadas de Tecnología y Cultura
Libre](http://libreeko.libremanuals.net/) que tiene lugar en el [ESLA EKO de
Carabanchel](https://eslaeko.net/) los días 24, 25 y 26 de Junio.

Para compilar la presentación a PDF hace falta tener `make`, `texlive`,
`textlive-latex-extra` y `texlive-generic-extra` instalados y ejecutar `make`.

El directorio `gnupg` contiene las claves y la configuración de algunos de los
ejemplos mencionados en la presentación. Para establecer dicho directorio como
fuente para `gpg2` basta con ejecutar `export
GNUPGHOME=/ubicacion/del/directorio/gnupg` en la misma shell en donde se van a
ejecutar los comandos de `gpg2`.

# Descripción

Pequeña introducción teórico-práctica a GPG: tipos de cifrado, (des)cifrado,
firmas digitales, confianza, correspondencia y gestión de contraseñas con GPG.

Una breve introducción teórica de unos 20-30 minutos, seguida de un taller
práctico de 60-90 minutos. Es recomendable que toda persona tenga acceso a un
terminal.

Si es posible, lo ideal sería llevarlo a cabo hacia el inicio del encuentro,
para que así la gente pueda afianzar los nuevos conceptos y herramientas y
podamos realizar una keysigning party hacia el final del encuentro.

Paquetes que sería interesante tener instalados:

- gnupg2
- gnupg-agent
- gnupg-curl
- guncat
- kgpg
- pass
- qtpass
- PassFF (addon para firefox)
- icedove
- enigmail
- claws-mail
- claws-mail-smime-plugin
- pius
