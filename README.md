# Vu3+TS Client Manage System
- https://www.youtube.com/watch?v=QNujr9Z7o4I&list=PLsbVibQXuLjpzrwXPpJ4wmF0TKldZuFIY&index=32&



## Setup
```
  vue create vue3-ts-cms

    Manually select feature
      Choose Vue version
      Babel
      TypeScript
      CSS Pre-processors
      Linter / Formatter
```

- Setup editor
install EditorConfig for VS code
create editorconfig
```
```


- Setup prettier

install VS Code prettier extension 

insttall and prettire 
```
  npm i prettier -D
``` 

create .prettierrc and .prettierignore

在package.json 添加script
```
  "prettier": "prettier --write 。"
```
用于format 所有file

- setup ESLint
create .eslintrc.js
Install eslint VS Code extension

解决eslint和prettier冲突的问题：

安装插件：（vue在创建项目时，如果选择prettier，那么这两个插件会自动安装）
```shell
npm i eslint-plugin-prettier eslint-config-prettier -D
```
modify .eslintrc.js
```
    'plugin:prettier/recommended'
```

- setup husky
```shell
npx husky-init && npm install
```