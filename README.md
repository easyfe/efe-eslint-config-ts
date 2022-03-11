### @easyfe/eslint-config-ts 包使用方法

## 使用方法

#### 第一步
```javascript
 npm i @easyfe/eslint-config-ts -D
```

#### 第二步

```javascript
 在项目根目录下面新建 .eslintrc.js 配置文件 文件配置如下

module.exports = {
    extends: ["@easyfe/eslint-config-ts"],
};
 
```

#### 第三步

```javascript
 在项目根目录下面新建 .prettierrc 配置文件 文件配置如下

{
    "tabWidth": 4,
    "trailingComma": "none",
    "endOfLine": "auto",
    "semi": true,
    "printWidth": 120,
    "singleQuote": false
}
```

#### 注意

```javascript
安装了 @easyfe/eslint-config-ts 之后 原本项目里面的关于 eslint prettier

的依赖都可以去掉了 

```