

babel 源码浅析



# Glossary



preser

plugin

@babel-core

types

tarverse

parser









## 大纲

ast

parser

acorn

traverse



preset



preset-env



useBuiltin

根据 UA 过滤属性





执行转换的关键代码

trasnformFile/index.js 



@preset-env 自带的特性检测插件

@preset-env/use-built-ins-plugin



// traverse.visitors.merge 将多个 visitor 合并在一起,同时注入 state
