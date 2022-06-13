### vscode scss compiler settings

```javascript
{
  "liveSassCompile.settings.formats": [
    // default format
    {
       // it can be `expanded`, `compressed`, `compact`. default is `expanded`
      "format": "expanded", 
      // it can `.css` or `.min.css`. default is `.css`
      "extensionName": ".css", 
      "savePath": null,
      "savePathSegmentKeys": null,
      "savePathReplaceSegmentsWith": null
    } 
  ],
  // create a map file. it can be `true` or `false`. default is `true`.
  "liveSassCompile.settings.generateMap": false,
  "liveSassCompile.settings.showOutputWindowOn": "Error",
  "liveSassCompile.settings.excludeList": [
    "/**/node_modules/**",
    "/.vscode/**"
  ],
}
```



