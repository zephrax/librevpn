% LVPN(1) Manual de LibreVPN | lvpn
% Nicolás Reynolds <fauno@endefensadelsl.org>
% 2013

# NOMBRE

LibreVPN

## SINOPSIS

  lvpn comando -opciones parametros


# OPCIONES

-h
:    Ayuda

-c
:    Lista de comandos disponibles


# DESCRIPCION

## ¿Cómo empiezo?

Leyendo el sitio http://librevpn.org.ar o la ayuda de _lvpn init_ :)

## ¿Donde está mi nodo?

El comando _lvpn init_ crea tu nodo dentro del directorio _nodos/_.
Podés tener varios nodos pero instalar uno por sistema (usando _lvpn
install tunodo_).

Cualquier comando que aplique cambios en tu nodo, debe instalarse luego
usando el comando _lvpn install tunodo_.

Consultar la ayuda de cada comando usando la opción -h luego del nombre de
comando:

	lvpn add-host -h


# VER TAMBIEN

_lvpn-init(1)_
