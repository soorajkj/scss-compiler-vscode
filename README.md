### vscode scss compiler settings

```javascript
{
  "liveSassCompile.settings.formats": [
    // you can add more option object combining `format`, `extensionName`, `savePath` etc...
    // this is default
    {
      "format": "expanded", // it can be `expanded`, `compressed`, `compact`. default is `expanded`
      "extensionName": ".css", // it can `.css` or `.min.css`. default is `.css`
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



