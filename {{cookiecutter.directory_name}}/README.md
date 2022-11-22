# {{ cookiecutter.title }}

## 依赖

要渲染论文，您需要:

1. pandoc
2. pandoc-citeproc
3. LaTeX
4. Node.js (可选，用于检查和使用快捷方式，可以通过 `npm run` 操作)

有关详细信息，请查看 Pandoc 的 [安装说明](https://pandoc.org/installing.html).

{% if cookiecutter.use_linter == "y"-%}
接下来，安装 linting 的依赖项:

```
npm install
```
{%- endif %}

## 用法

在此目录中，运行：

```shell
# 生成pdf， 注意指定pdf-engine
pandoc paper.md --filter pandoc-citeproc -o paper.pdf --pdf-engine=xelatex
# 简写模式
npm run pdf

# 生成word文件
pandoc paper.md --filter pandoc-citeproc -o paper.docx
# 简写模式
npm run docx

{% if cookiecutter.use_linter == "y" -%}
# 找出你论文中可能的错误
npm run lint

# 自动修复这些错误并美化文件
npm run fix
{%- endif %}
```
{% if cookiecutter.use_linter == "y"-%}

请注意，您应该 *within* 包含您的参考文献，以确保 linter（将句子保持在不同行以获得更多信息差异）不会将它们分解： 
```
比如 [@Lee2019]. 而不是. [@Lee2019]
```
{%- endif %}
