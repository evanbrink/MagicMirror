Evan's README - for instructions/reminders/progress notes

------RUNNING ON MAC------
1. Navigate to directory in terminal. As of 12/26/19:

   $   cd ~/Documents/Projects/MagicMirror/MagicMirror/

2. For server only mode (open in web browser):

   $   npm install && node serveronly

   Then go to link in terminal using web browser (eg. http://localhost:8080/)

2. (alt) For full display version:

   $   npm install && npm start

   To close use cmd+Q



------FILE DESCRIPTIONS------
compliments.js - I have modified this to have inspirational quotes
config.js - modify this to change the layout



------USEFUL REFERENCES------
Github: https://github.com/MichMich/MagicMirror
Documentation: https://docs.magicmirror.builders/getting-started/configuration.html#raspberry-specific
3rd Party Modules: https://github.com/MichMich/MagicMirror/wiki/3rd-Party-Modules


-----Thoughts on deployment-------
1. Github repo that includes everything but config file (or config file with personal data removed/defined in another file from variables)
2. Bash script for config deployment over ssh