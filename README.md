### 1、使用方法
```javascript
const xbsTools = require('xsgg'); // 请替换成您实际使用的XBS工具库
// 调用示例
// const xbsFilePath = "https://cdn.jsdelivr.net/gh/Codebglh/img/test/%E9%A3%9E%E9%80%9F%E8%B5%84%E6%BA%90.xbs";
const xbsFilePath = "b.xbs"
const jsonFilePath='x.json'
// xbsTools.xbsTools.convertXbsToJson(xbsFilePath,jsonFilePath)
xbsTools.xbsTools.convertJsonToXbs(jsonFilePath,xbsFilePath)
```
