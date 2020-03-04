## setting.json
```
{
    // vue文件eslint格式化规则
    "[vue]": {
        "editor.defaultFormatter": "octref.vetur"
    },
    "[javascript]": {
        "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
    },
    // 回车键使用linefeed,即\n
    "files.eol": "\n",
    // eslint检测的文件类型
    "eslint.validate": [
        "javascript",
        "vue"
    ],
    // vue template 部分格式化样式
    "vetur.format.defaultFormatter.html": "prettier",
    "vetur.format.defaultFormatter.js": "prettier-eslint",
    // 保存自动eslint格式化
    "editor.formatOnSave": true,
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    },
    // nuxt/vue-cli 路径自动填充
    "path-intellisense.mappings": {
        "~": "${workspaceRoot}",
        "@": "${workspaceRoot}"
    },
}
```
## packages
eslint
path Intellisense
prettier eslint
vetur
vs sequential number
vue 2 snippets
