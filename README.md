<!-- repo-usage-notes:start -->
## 功能与下载速查

V2Ray 网络代理核心的历史源码分支：代理协议、路由与传输组件；Go 项目，原 README 指向 v2fly 后续仓库。

### 下载到另一台电脑

- [下载源码 ZIP](https://github.com/lucc1832/v2ray-core/archive/refs/heads/master.zip)，或在仓库页面选择 **Code → Download ZIP**。
- 使用 GitHub CLI：`gh repo clone lucc1832/v2ray-core`。
- 整理时未发现本仓库 Releases 的安装包附件；上述 ZIP 是源码/资料，不是现成安装包。原说明中的其他下载入口见下文。

### 使用与迁移

本仓库用于历史源码参考，未发布本仓库二进制附件。按原 README 查看后续项目，或使用与此源码匹配的 Go 工具链构建。

说明依据本仓库文档与源码整理于 2026-09-23；此次整理未运行应用或活动脚本。
<!-- repo-usage-notes:end -->

# Move To https://github.com/v2fly/v2ray-core

***

# Project V

[![GitHub Test Badge][1]][2] [![codecov.io][3]][4] [![GoDoc][5]][6] [![codebeat][7]][8] [![Downloads][9]][10] [![Downloads][11]][12]

[1]: https://github.com/v2fly/v2ray-core/workflows/Test/badge.svg "GitHub Test Badge"
[2]: https://github.com/v2fly/v2ray-core/actions "GitHub Actions Page"
[3]: https://codecov.io/gh/v2fly/v2ray-core/branch/master/graph/badge.svg?branch=master "Coverage Badge"
[4]: https://codecov.io/gh/v2fly/v2ray-core?branch=master "Codecov Status"
[5]: https://godoc.org/v2ray.com/core?status.svg "GoDoc Badge"
[6]: https://godoc.org/v2ray.com/core "GoDoc"
[7]: https://goreportcard.com/badge/github.com/v2fly/v2ray-core "Goreportcard Badge"
[8]: https://goreportcard.com/report/github.com/v2fly/v2ray-core "Goreportcard Result"
[9]: https://img.shields.io/github/downloads/v2ray/v2ray-core/total.svg "v2ray/v2ray-core downloads count"
[10]: https://github.com/v2ray/v2ray-core/releases "v2ray/v2ray-core release page"
[11]: https://img.shields.io/github/downloads/v2fly/v2ray-core/total.svg "v2fly/v2ray-core downloads count"
[12]: https://github.com/v2fly/v2ray-core/releases "v2fly/v2ray-core release page"

Project V is a set of network tools that help you to build your own computer network. It secures your network connections and thus protects your privacy. See [our website](https://www.v2fly.org/) for more information.

## License

[The MIT License (MIT)](https://raw.githubusercontent.com/v2fly/v2ray-core/master/LICENSE)

## Credits

This repo relies on the following third-party projects:

- In production:
  - [gorilla/websocket](https://github.com/gorilla/websocket)
  - [gRPC](https://google.golang.org/grpc)
- For testing only:
  - [miekg/dns](https://github.com/miekg/dns)
  - [h12w/socks](https://github.com/h12w/socks)
