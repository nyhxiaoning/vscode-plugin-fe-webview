<!--
 * @Author: ningyongheng ningyongheng@jeejio.com
 * @Date: 2024-07-26 10:23:44
 * @LastEditors: ningyongheng ningyongheng@jeejio.com
 * @LastEditTime: 2024-07-26 19:56:27
 * @FilePath: /vscode-plugin-fe-webview/README.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->

# 前端工具箱henry

## 活动图标展示在：活动栏
展示活动栏：frontend-box.markbookhenry
搜索这个，可以查看所有的配置这个图标的位置。


### 修改：
下面的views控制和viewsContainers的：activitybar控制
~~~
{
  "contributes": {
    "viewsContainers": {
      "activitybar": [
        {
          "id": "myExtensionViewContainer",
          "title": "My Extension",
          "icon": "images/icon.png"
        }
      ]
    },
    "views": {
      "myExtensionViewContainer": [
        {
          "id": "myExtensionView",
          "name": "My View"
        }
      ]
    }
  }
}

~~~

> 把面试题、常用资料导航装到VSCode里，更方便查找！

**Install**

在vscode插件里搜索：前端工具箱

**Features**

- 内置常见**面试题库**
- 常用工具箱及开发文档

![](https://poetries1.gitee.io/img-repo/2020/12/screenshot.png)

Enjoy!