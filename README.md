# static-web-server-lzcapp

懒猫微服社区商店打包：[Static Web Server](https://static-web-server.net)（joseluisq/static-web-server v2.44.1）。

镜像：joseluisq/static-web-server:2.44.1（amd64，mirror 模式 require_digest_match）。

静态文件根目录挂载在 /lzcapp/var/data（容器内 /public，SERVER_ROOT 显式指定）。
本应用无账号体系，保持平台入口鉴权，不加 public_path。
