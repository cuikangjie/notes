### npm切换淘宝镜像源

* 通过config命令

```cmd
npm config set registry https://registry.npm.taobao.org
npm info underscore （如果上面配置正确这个命令会有字符串response）
```
* 命令行指定

```cmd
npm --registry https://registry.npm.taobao.org info underscore
```

* 编辑 ~/.npmrc 加入下面内容

```cmd
registry = https://registry.npm.taobao.org
```
