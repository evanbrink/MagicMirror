# Evan's README - for instructions/reminders/progress notes

## ------RUNNING ON MAC------

1. Navigate to directory in terminal. As of 12/26/19:

```
$   cd ~/Documents/Projects/MagicMirror/MagicMirror/
```

2. (Only necessary once) Navigate to the modules/MMM-Todoist folder and install dependencies there:

```
$  cd modules/MMM-Todoist
$  npm install
```

3. For server only mode (open in web browser):

```
$   npm install && node serveronly
```

4. Then go to link in terminal using web browser (eg. http://localhost:8080/)

5. (alt) For full display version:

```
$   npm install && npm start
```

To close use cmd+Q

## ------FILE DESCRIPTIONS------

compliments.js - I have modified this to have inspirational quotes  
config.js - modify this to change the layout

## ------USEFUL REFERENCES------

- Github for Main Project: [https://github.com/MichMich/MagicMirror](https://github.com/MichMich/MagicMirror)
- My Fork on Github [https://github.com/evanbrink/MagicMirror](https://github.com/evanbrink/MagicMirror)
- Documentation: [https://docs.magicmirror.builders/getting-started/configuration.html#raspberry-specific](https://docs.magicmirror.builders/getting-started/configuration.html#raspberry-specific)
- 3rd Party Modules: [https://github.com/MichMich/MagicMirror/wiki/3rd-Party-Modules](https://github.com/MichMich/MagicMirror/wiki/3rd-Party-Modules)
- Todoist 3rd party Module [https://github.com/cbrooker/MMM-Todoist](https://github.com/cbrooker/MMM-Todoist)

## -----Thoughts on deployment-------

- Github repo that includes everything but config file (or config file with personal data removed/defined in another file from variables)
- Bash script for config deployment over ssh

## Evan's Changelog

**12/29/2021 -** I made [my own fork](https://github.com/evanbrink/MagicMirror) of the repository for my own development. This includes everything except the `config.js` file (which is where most of the customization is happening). In the future I might want to look into moving all the sensitive information out of the config.js file and importing it. That way I could include the `config.js` file in the git repository and use it more as a layout file - making it easier to update on the raspberry pi.

I also incorporated the [Todoist module](https://github.com/cbrooker/MMM-Todoist). This is git cloned on my macbook in the `~/Documents/Projects/MagicMirror/MagicMirror/modules/MMM-Todoist` folder. It requires its own dependency installation (outlined above in step 2)
