## node-blog
使用 `Express` + `MongoDB` 搭建博客

### 全局安装 `eslint`：
  npm i eslint -g  
运行：  
  eslint --init  
初始化 `eslint` 配置，依次选择：

-> Use a popular style guide  
-> Standard  
-> JSON

## eslint配置
``` js
# editorconfig.org
root = true

[*]
indent_style = space
indent_size = 2
end_of_line = lf
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true
tab_width = 2

[*.md]
trim_trailing_whitespace = false

[Makefile]
indent_style = tab
```
