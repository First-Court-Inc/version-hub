# Version Hub

Static badge endpoints for deployment versions across environments. Badges read directly from the JSON files in this repository, so updating a version only requires editing the corresponding `message` field.

## Jury Reactions
<!-- jury-reactions -->
**PROD** ![prod](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/First-Court-Inc/version-hub/main/jury-reactions/PROD.json&cacheSeconds=300)
**QA**   ![qa](   https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/First-Court-Inc/version-hub/main/jury-reactions/QA.json&cacheSeconds=300)
**DEV**  ![dev](  https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/First-Court-Inc/version-hub/main/jury-reactions/DEV.json&cacheSeconds=300)

## Prepare to Persuade
<!-- prepare-to-persuade -->
**PROD** ![prod](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/First-Court-Inc/version-hub/main/prepare-to-persuade/PROD.json&cacheSeconds=300)
**QA**   ![qa](   https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/First-Court-Inc/version-hub/main/prepare-to-persuade/QA.json&cacheSeconds=300)
**DEV**  ![dev](  https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/First-Court-Inc/version-hub/main/prepare-to-persuade/DEV.json&cacheSeconds=300)

## Red Zone
<!-- red-zone -->
**PROD** ![prod](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/First-Court-Inc/version-hub/main/red-zone/PROD.json&cacheSeconds=300)
**QA**   ![qa](   https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/First-Court-Inc/version-hub/main/red-zone/QA.json&cacheSeconds=300)
**DEV**  ![dev](  https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/First-Court-Inc/version-hub/main/red-zone/DEV.json&cacheSeconds=300)

## Updating Badges
1. Edit the relevant JSON file and update the `message` field with the new version.
2. Commit and push the change; badges will refresh automatically within the configured `cacheSeconds` window.
