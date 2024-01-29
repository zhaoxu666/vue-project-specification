# 制定前端规范
## 一、引入ESlint Airbnb规范

### 安装ESlint

```npm
// 安装ESlint  采用vue-cli的 add 命令直接添加eslint
vue add eslint 
```

### 配置选项

```npm
// 选择规范：Airbnb
? Pick an ESLint config : Airbnb
// 选择验证时机: 保存时验证
? Pick additional lint features: Lint on save
```

### VSCode下载ESLint插件

在`VSCode`编辑器中下载`ESLint`插件，重启`VSCode`后就会在编辑器中看到不符合规范的代码会有报错

### 官方文档

[eslint-config-airbnb](https://github.com/vuejs/eslint-config-airbnb)

[airbnb规范](https://github.com/airbnb/javascript#readme)

## 二、引入Prettier格式化ESlint

**我们引入ESlint后，我们会出现很多报错，并且我们只能通过手动去进行修改，引入Prettier后将自动帮我们进行调整为符合ESlint规范的代码**

### 我们格式化代码风格仍然采用airbnb采用得风格

在根目录添加`.prettierrc`文件

```.prettierrc
{
  "semi": true,
  "singleQuote": true,
  "trailingComma": "all"
}

```

### vscode下载prettier插件

在`vscode`插件库中搜索`prettier`

### 设置保存后自动格式化

在`vscode`中`文件/File`选项选择`首选项/Preferences`选择`设置/Settings`搜索`save`将`Format On Save`勾选上

**ps: 设置后如果不生效，重启vscode**