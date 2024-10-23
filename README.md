# modpack-sync

Repo for syncing minecraft modpacks

## Repo structure
Repo lives at ~/{Username}/curseforge/minecraft and manages /Instances
- root
    - profile.zip
    - servers
        - {servername}
            
            - mods

## Todo

- Upload new mods script (me only)
    - zip mod files
    - push to github

- Profile updater script (easy 1 click mod updating)
    - package with minecraft profile
    - get new mods.zip from modpack-sync repo
    - unzip into /Instances/{servername}