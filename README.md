# JSON schema files for Opus menu structure

This repo is a means to publish JSON schema files on a public site so that they can be referenced in JSON files, for example:

```json
{
  "$schema": "https://Opus-PNC.github.io/opus-menu-schema-v2.json",
  "menuTree": {
    "menuType": "branch",
    "menuId": "mainMenu",
    "menuTitle": {
      "text": "** Main Menu **"
    }
    "submenus": [
      ...      
    ]
  }
  ...
}
```
