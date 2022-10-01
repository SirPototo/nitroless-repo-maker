# Making your own Nitroless repo

 1. At the repo's root, create an `index.json` like so: 
    ```json
    {
       "name": "Example Repo",
       "icon": "icon.jpg",
       "path": "emotes",
       "emotes" : [
           {
               "name": "imageone",
               "type": "png"
           },
           {
               "name": "imagetwo",
               "type": "gif"
           },
           {
               "name": "imagethree",
               "type": "jpg"
           }
       ]
    }
    ```

All emote images should be 48x48 pixels so they display correctly inside Discord.