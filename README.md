# react-udemy-1

### Creación del proyecto
- Para crear el "cascarón" del proyecto utilizaremos la siguiente línea de código en la carpeta raíz donde la querramos.
``` 
npx create-react-app nombre-del-proyecto
```

### Limpieza del cascarón
- Borraremos los siguientes elementos dentro de la carpeta src
  1. App.test
  2. logo.svg
  3. setupTests.js
- Dentro de App.js borramos todo lo que está dentro del div "App" y le modificamos su nombre a "app"




-------------------------
## <b> BonusTrack </b>

### Emmet ([LINK](https://emmet.io/))
- Emmet es una extension para VsCode que nos brinda atajos para crear más rápido las tablas o bases de html

```javascript
tr>td*3 (nos va a crear)
      <tr>
        <td></td>
        <td></td>
        <td></td>
      </tr>
```

#### Instalación
1. Bajarse la extension Mithril Emmet en VsCode
2. Ir a File -> Preferences -> Settings y tocar arriba a la derecha el boton de "Open Settings JSON"
3. Incluir lo siguiente al final del archivo:
```javascript
"emmet.includeLanguages": {
        "javascript": "javascriptreact"
    }
```
