**This branch only exists to not break any existing MagicMirror setups, please update the URL from ```master``` to ```main```.**

So for example change the complements section in ```config.js```, from:
```js
{
    module: "compliments",
    position: "lower_third",
    config: {
        remoteFile: "https://raw.githubusercontent.com/michadenheijer/MagicMirrorCompliments/master/nl.json"
    }
},
```
To:
```js
{
    module: "compliments",
    position: "lower_third",
    config: {
        remoteFile: "https://raw.githubusercontent.com/michadenheijer/MagicMirrorCompliments/main/nl.json"
    }
},
```

Change ``nl.json`` for your own language, for example:

- English ```en.json```
- German ```de.json```
- Dutch ```nl.json```
