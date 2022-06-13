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

| Settings | Desc| Options | Default |
| ------------- | -------------:| -----:| --------------:|
| liveSassCompile.settings.formats      | right-aligned | $1600 | Value |
| col 2 is      | centered      |   $12 | value |
| zebra stripes | are neat      |    $1 | value |

formats can be `expanded`, `compressed`, `compact`. default is `expanded`
