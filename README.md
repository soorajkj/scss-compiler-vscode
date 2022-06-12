# Vscode scss compiler settings

1. create a folder with a name ".vscode" in the root of your project.
2. inside the folder create a file named "settings.json".
3. copy the code down below and paste it the "seetings.json".
4. change the save path 

```js
{
  "liveSassCompile.settings.formats": [
    {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": null,
      "savePathSegmentKeys": null,
      "savePathReplaceSegmentsWith": null
    },
    {
      "format": "compressed",
      "extensionName": ".min.css",
      "savePath": null,
      "savePathSegmentKeys": null,
      "savePathReplaceSegmentsWith": null
    }
  ],
  "liveSassCompile.settings.generateMap": false,
  "liveSassCompile.settings.showOutputWindowOn": "Error",
  "liveSassCompile.settings.excludeList": [
    "/**/node_modules/**",
    "/.vscode/**"
  ],
  "liveSassCompile.settings.autoprefix": ["> 1%", "last 2 versions"]
}
```
