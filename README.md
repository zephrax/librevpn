# LibreVPN

> http://librevpn.org.ar

LibreVPN es una red libre virtual.

Estos son los scripts de configuración y administración de la VPN y aplican
muchas de las acciones comunes sobre tinc.

Para obtener ayuda, ejecutar `lvpn -h`.  Cada comando tiene su -h tambien.


## Requisitos

tinc (1 o 1.1), avahi-daemon, bash.

Además los scripts informan sobre otros comandos que pueden llegar a
necesitar.


## Desarrollador*s

Ver _doc/CONVENCIONES.markdown_.

## I18n en progreso

    mkdir -p locale/en/LC_MESSAGES
    msgfmt -o locale/en/LC_MESSAGES/lvpn.mo locale/en.po
    export TEXTDOMAINDIR=$PWD/locale

## Ideas

- https://pad.riseup.net/p/lvpn
