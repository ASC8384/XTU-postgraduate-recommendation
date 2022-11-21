# 湘潭大学保研攻略
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-6-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

WIP

## 如何贡献

Fork 之后提交 PR。

您可以在 `docs/source` 目录下进行文档的编写。其中，`院校` 目录将学校名称作为子目录，`学院名称`作为子目录里的具体文件名，并将`学院名称`作为文件的标题。如果写的是参加夏令营或预推免的经验，请开个小标题，加上自己的年级（譬如 19 级）或参与报名的时间（如2022-09-28）。

您可以使用 Markdown 或者 [reStructuredText](http://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html) 进行撰写。但是学校名称的目录下必须建立 `index.rst`，内容如下：

```text
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

## 贡献者✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://ellenwong.github.io/about/"><img src="https://avatars.githubusercontent.com/u/35458803?v=4?s=100" width="100px;" alt="EllenWong"/><br /><sub><b>EllenWong</b></sub></a><br /><a href="#content-EllenWong" title="Content">🖋</a></td>
      <td align="center"><a href="http://www.asc8384.top/"><img src="https://avatars.githubusercontent.com/u/29878345?v=4?s=100" width="100px;" alt="ASC_8384"/><br /><sub><b>ASC_8384</b></sub></a><br /><a href="#content-ASC8384" title="Content">🖋</a> <a href="https://github.com/ASC8384/XTU-postgraduate-recommendation/pulls?q=is%3Apr+reviewed-by%3AASC8384" title="Reviewed Pull Requests">👀</a> <a href="#ideas-ASC8384" title="Ideas, Planning, & Feedback">🤔</a> <a href="#infra-ASC8384" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
      <td align="center"><a href="https://github.com/pc-mysql"><img src="https://avatars.githubusercontent.com/u/52450205?v=4?s=100" width="100px;" alt="pc-mysql"/><br /><sub><b>pc-mysql</b></sub></a><br /><a href="#content-pc-mysql" title="Content">🖋</a></td>
      <td align="center"><a href="https://github.com/wanghongyu2001"><img src="https://avatars.githubusercontent.com/u/114321093?v=4?s=100" width="100px;" alt="wanghongyu2001"/><br /><sub><b>wanghongyu2001</b></sub></a><br /><a href="#content-wanghongyu2001" title="Content">🖋</a></td>
      <td align="center"><a href="https://github.com/litchimango"><img src="https://avatars.githubusercontent.com/u/59715401?v=4?s=100" width="100px;" alt="litchimango"/><br /><sub><b>litchimango</b></sub></a><br /><a href="#content-litchimango" title="Content">🖋</a></td>
      <td align="center"><a href="https://github.com/fantasy-99"><img src="https://avatars.githubusercontent.com/u/56767204?v=4?s=100" width="100px;" alt="Hongbo Zhao"/><br /><sub><b>Hongbo Zhao</b></sub></a><br /><a href="#content-fantasy-99" title="Content">🖋</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

## 其它

感谢 [南大软院保研攻略](https://github.com/NJU-SE-15-share-review/postgraduate-recommendation) 提供的灵感。
