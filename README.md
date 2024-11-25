本地启动方式

```sh
Jekyll s
```

本地构件，将静态文件生成至于 `_site` 目录下

```shell
Jekyll build
```

构建的 `_site` 目录会导致 css、html 引入错误

将 `_site/index.html` 中的 `/resume.io` 替换成 `.`

如果已经部署到服务器上，运行下面替换命令

```shell
sed -i '' 's#/resume.io#.#g' _site/index.html
```
