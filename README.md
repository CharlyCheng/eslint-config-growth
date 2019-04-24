# Growth FE js 标准
本标准基于 [eslint-config-airbnb](https://github.com/airbnb/javascript)


## Install

安装配置包

```bash
npm install --save-dev eslint-config-growth
```

## 配置
编辑 .eslintrc 加入即可

```.eslintrc
{
  "extends": "eslint-config-growth"，
  "rules": {}
}
```

## 注意事项
eslint 的插件安装位置要和 eslint 的安装位置保持一致，如果 eslint 是 global 的，那么插件也需要是 global 的。