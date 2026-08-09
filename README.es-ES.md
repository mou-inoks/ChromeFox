# Chrome Fox
***Un tema de userChrome.css para Firefox inspirado en el diseño de Chrome***

![Preview](https://typeling1578.github.io/MaterialFox-Plus/MaterialFox-Plus.png)
Este tema está impulsado por sangre, sudor y café. Si te gusta, por favor considera ayudar para apoyar su desarrollo continuo.

## Qué hace esto
Inspirado en el Material Design de Google y su interfaz de usuario más reciente de Google Chrome, este tema convierte tu Firefox en un navegador web con estilo Material. El objetivo era diseñar el navegador lo más parecido posible a Google Chrome, donde fuera práctico.

Este es un tema de userChrome.css, lo que significa que debes agregarlo manualmente a tu perfil de Firefox. El tema anula ciertos estilos del navegador. Actualmente, solo se ve afectada la interfaz de usuario principal (las páginas de configuración, etc., no lo están). Es posible que se diseñen más elementos de la interfaz en el futuro, pero un alcance más amplio se vuelve más difícil de mantener a medida que Mozilla actualiza el código de su navegador, por lo que algunos estilos de la interfaz podrían eliminarse o rehacerse si se vuelven inmanejables.

## ¿Qué versión utilizo?
Funciona con la versión más reciente o la 102ESR de Firefox.

## Instalación
1. [about:config] Establece ```toolkit.legacyUserProfileCustomizations.stylesheets``` en ```true``` (el valor predeterminado es ```false```).
2. [about:config] Establece ```svg.context-properties.content.enabled``` en ```true``` (el valor predeterminado es ```false```).
3. Copia la carpeta chrome en el directorio de tu perfil de Firefox. Para encontrar el directorio de tu perfil, ve a about:support o about:profiles.
4. Consulta las [Instrucciones recomendadas](#recommended-instructions) si prefieres una experiencia más similar a Chrome.
5. Reinicia Firefox.

### Instrucciones recomendadas
Replicar el comportamiento de Chrome para las pestañas recortadas:
* [about:config] Establece ```browser.tabs.tabClipWidth``` en ```83``` (el valor predeterminado es ```140```).

Replicar el texto "No seguro" de Chrome en HTTP:
* [about:config] Establece ```security.insecure_connection_text.enabled``` en ```true```.

* Agrega este tema de Firefox para tener exactamente el mismo color que el chrome anterior [Firefox theme](https://addons.mozilla.org/en-US/firefox/addon/default-compact-dark-theme/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search)

## Ten en cuenta
* Windows 7 ya no es compatible.
* Linux ya no es compatible oficialmente, pero puedes intentarlo; si deseas trabajar en ello, no dudes en hacer un PR.
* Es posible que algunas configuraciones de personalización ya no funcionen (como la densidad compacta/táctil).
* Algunos temas personalizados pueden entrar en conflicto con la barra de direcciones.
* Algunos temas que utilizan transparencia podrían no funcionar.


## Gracias al repositorio de muckSponge por la base 

enlace: [MaterialFox](https://github.com/muckSponge/MaterialFox)
