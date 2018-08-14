# MagicMirror-Compliments
I wanted the compliments in my own language, so right now its only in Dutch, but I will try to add more languages soon!

## How to add the compliments to your MagicMirror
### Step 1: Check for supported languages
At the moment there are just two language's: 
- English ```en.json```
- Dutch ```nl.json```

### Step 2: Change config
Open your config:
```
sudo nano ~/MagicMirror/config/config.js
```
Scroll till you can see the compliments module. It looks something like this:
```javascript
{
    module: "compliments",
    position: "lower_third"
},
```
Change it to:
```javascript
{
    module: "compliments",
    position: "lower_third",
    config: {
        remoteFile: "https://raw.githubusercontent.com/michadenheijer/MagicMirrorCompliments/master/nl.json"
    }
},
```
Change ```nl.json``` to your own language like ```en.json``` or ```fr.json```. The abbreviation of your language can be found above.

# Visit MagicMirror!
[MagicMirror](https://github.com/MichMich/MagicMirror)
