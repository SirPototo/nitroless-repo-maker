# Making your own Nitroless repo

 1. At the repo's root, create an `index.json` like so: 
    ```json
    {
        "name": "Amy's Repo", 
        "path": "emotes", 
        "emotes" : [
            {
               "name": "02boba",
               "type": ".png",
            },
            {
               "name": "fbk_shake",
               "type": ".gif",
            },
        ],
    }
    ```
2. Also at the repo's root, add an `RepoImage.png` that will serve as the icon

All emote images should be 48x48 pixels so they display correctly inside Discord.
