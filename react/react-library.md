## Librería de react typescript

1. Creación del proyecto

```
~$ npm init
```

2. Instalación de dependencias

```
~$ npm install react typescript tslib @types/react --save-dev
```

3. Ejecutar configuración inicial predeterminada de `typescript`

```
~$ npx tsc --init
```

4. Instalación de dependencia para empaquetar la librería

```
~$ npm install rollup @rollup/plugin-node-resolve @rollup/plugin-commonjs rollup-plugin-dts --save-dev
```

**Nota** 
Actualmente hay algunas discrepancias con la última version de `@rollup/plugin-typescript` por lo que se recomiendo utilizar la versión `8.3.3`.

```
~$ npm i @rollup/plugin-typescript@8.3.3 --save-dev --force
```

