# Vscode scss compiler settings

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
}
```

formats can be `expanded`, `compressed`, `compact`. default is `expanded`
