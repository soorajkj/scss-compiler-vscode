# Vscode scss compiler settings

```javascript
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

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

formats can be `expanded`, `compressed`, `compact`. default is `expanded`
