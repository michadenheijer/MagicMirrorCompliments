# MagicMirror-Compliments
I wanted the MagicMirror compliments in my own language, so here are some translations. Feel free to add your own language!

## How to add the compliments to your MagicMirror
### Step 1: Check for supported languages
At the moment there are just four languages: 
- English ```en.json```
- German ```de.json```
- Dutch ```nl.json```
- Chuvash ```cv.json```

### Step 2: Change config
Open your config:
```bash
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
        remoteFile: "https://raw.githubusercontent.com/michadenheijer/MagicMirrorCompliments/main/nl.json"
    }
},
```
Change ```nl.json``` to your own language like ```en.json``` or ```fr.json```. The abbreviation of your language can be found above.

## Credits
Dutch and English languages by [Micha den Heijer](https://github.com/michadenheijer), 
German language by [fixing-it](https://github.com/fixing-it).
# Visit MagicMirror!
[MagicMirror](https://github.com/MichMich/MagicMirror)
