# shenpp.top

这是一个可部署到 GitHub Pages 的静态个人网站。

## 部署到 GitHub Pages

1. 新建一个 GitHub 仓库，比如 `shenpp.top` 或 `<你的用户名>.github.io`。
2. 把本目录里的文件推到仓库默认分支。
3. 在仓库 `Settings -> Pages` 中选择从分支发布，目录选 `/root`。
4. `Custom domain` 填写 `shenpp.top`，并开启 `Enforce HTTPS`。
5. 在域名 DNS 服务商处配置解析。

## 推荐 DNS

根域名 `shenpp.top`：

```text
A  @  185.199.108.153
A  @  185.199.109.153
A  @  185.199.110.153
A  @  185.199.111.153
```

如果也想让 `www.shenpp.top` 可访问：

```text
CNAME  www  948066198.github.io
```

DNS 生效可能需要一段时间，GitHub 文档提示最多可能需要 24 小时。
