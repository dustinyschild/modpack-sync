# modpack-sync

Repo for syncing minecraft modpacks

## Run Server
1. cd D:\Servers\Minecraft\Java\docker-compose.yml
2. docker compose up -d

See servers running in Docker Desktop

## Stop Server
1. cd D:\Servers\Minecraft\Java\docker-compose.yml
2. docker compose down

## Repo structure
Repo lives at ~/{Username}/curseforge/minecraft and manages /Instances

- root
    - servers
        - {servername}
            - {servername}.zip
            - mods
    

## Todo

- Upload new mods script (me only)
    - zip mod files
- Profile updater script (easy 1 click mod updating)
package with minecraft profile

1. 