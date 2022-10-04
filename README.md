# 湘潭大学保研攻略

WIP

## 如何贡献

Fork 之后提交 PR。

可以在 `docs/source` 目录下进行文档的编写。其中，`院校` 目录将学校名称作为子目录，学院名称作为子目录里的具体文件名，可以使用 Markdown 或者 [reStructuredText](http://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html) 进行撰写。但是学校名称的目录下必须建立 `index.rst`，内容如下：

```
学校名称
===================================

.. toctree::
    :maxdepth: 1
    :glob:

    *
```

本项目使用[sphinx](http://www.sphinx-doc.org/en/master/contents.html)进行文档生成，如果需要学习对项目进行修改，请查看sphinx的文档。

### 构建

1. Clone 本项目
2. 安装相应依赖包
3. 在 `source` 目录下执行 `make html`
4. 使用浏览器打开 `build/html/index.html`，即可预览已经产生的文档！

## 贡献者

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

## 其它

感谢 [南大软院保研攻略](https://github.com/NJU-SE-15-share-review/postgraduate-recommendation) 提供的灵感。