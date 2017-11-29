# Open in VS Code:
Create a new Automator Service
- Open Automator
- Click *Create New Service*, click *Choose*
- In the middle column find *Run Shell Script*
- In the right column choose *Service receives selected: files* and *folders in any application*
- Double click on *Run Shell Script* in middle column
- Choose *Shell: /bin/bash* and *Pass input: as arguments*
- Enter `"/Applications/Visual Studio Code.app/Contents/MacOS/Electron" $@`
- Click *File->Save* or `cmd+S` to save new Automator Service, name it as you like it to be displayed in *Finder*
# Use:
- Select folder and right click, choose *Services -> Open in VS Code*

## Couple of Screenshots as a guide
Automator
---------
![Automator](https://user-images.githubusercontent.com/25623699/33377731-2ca2a098-d51b-11e7-90e1-ccbb7b43db61.jpg)
Right Click Service Menu
------------------------
![context menu](https://user-images.githubusercontent.com/25623699/33377732-2cc7d05c-d51b-11e7-88c5-797a14b810eb.jpg)
