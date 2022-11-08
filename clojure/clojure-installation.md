## Instalación en Mac 

### Java

Revisar que se tenga `Java` instalado con la versión mínima 11.

Comando para verificar versión de `Java`.

```
~$ java -version
```

En caso de no tener instalado `Java`, se pueda instalar la versión de la siguiente [página](https://adoptium.net/es/).

### Leiningen

Instalación del `lein script`

```
~$ curl https://raw.githubusercontent.com/technomancy/leiningen/stable/bin/lein > lein
```

Mover `lein script` al direction de programas del usuario

```
~$ sudo mv lein /usr/local/bin/lein
```

Agregar permisos de ejecución al `lein script`

```
~$ sudo chmod a+x /usr/local/bin/lein
```

Verificar versión de `lein`

```
~$ lein version
```

### Clojure CLI

1. Verificar la instalación de `Homebrew`

Actualización de `homebrew`

```
~$ brew update
```

En caso de no tener `homebrew`, revisar el siguiente [enlace](https://brew.sh/)

2. Instalar Clojure CLI

Mediante el siguiente comando se puede instalar `Clojure CLI` a tráves de `homebrew`

```
~$ brew install clojure/tools/clojure
```

Actualizar instalación previa

```
~$ brew upgrade clojure/tools/clojure
```

Verificar instalación

```
~$ clj
```

## Referencias

[How To Install Clojure](https://ericnormand.me/guide/how-to-install-clojure)