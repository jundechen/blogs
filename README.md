此网站使用了 [hugo](https://gohugo.io/) 来生成。

## 怎么部署
1. 运行 make.ipynb, 将所有 jupyter notebook 文件转换成 markdown 格式的文件
2. 在 blogs 目录里运行 hugo
3. 运行 git add -A
4. 运行 git commit -m "comment message"
5. 运行 git push

网站所有静态文件都放在了 /docs 目录里面, 该目录可以在 config.toml 文件里配置