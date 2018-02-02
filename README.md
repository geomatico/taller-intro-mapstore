# Taller de iniciación a Mapstore 2

    git clone mapstore2
    npm install
    mkdir ../Tallerico
    node ./createProject.js custom Tallerico 0.0.1 "Talleri.co" "https:github.com/<username>/tallerico" ../tallerico

Arrancar con:

    npm start

En `localConfig.json` poner (o no, no van los CSS):

```json
{
    ...
    "themePrefix": "default"
}
```

Editar `js/plugins.js` para añadir un nuevo plugin:

    
```js
import BackgroundSelectorPlugin from '../MapStore2/web/client/plugins/BackgroundSelector';

module.exports = {
    plugins: {
        ...
      BackgroundSelectorPlugin: BackgroundSelectorPlugin
    }
}
```

