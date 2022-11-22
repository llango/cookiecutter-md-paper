# cookiecutter-md-paper

一个用 Markdown 中编写论文的[Cookiecutter](https://github.com/cookiecutter/cookiecutter)。

## 特征

- 使用一列或两列布局
- 支持双倍间距和行号 
- 可定制的字体大小和边距 
- 开箱即用的 APA、AMA、MLA、CMS、IEEE、Nature 和 ACS 引文样式 
- 通过[Textlint](https://textlint.github.io)进行语法检查（和修复！）
- 用于生成 PDF 和 Word 文件的预配置脚本（通过 `npm run pdf`  和 `npm run docx` ) 

## 用法

首先，您需要 [安装 Cookiecutter](https://cookiecutter.readthedocs.io/en/1.7.0/installation.html):

```shell
# pip 安装
pip install cookiecutter

# Mac 安装
brew install cookiecutter

# Conda 安装
conda config --add channels conda-forge && conda install cookiecutter
```

然后，使用 Cookiecutter 搭建论文的脚手架： 

```shell
cookiecutter https://github.com/llango/cookiecutter-md-paper
```
