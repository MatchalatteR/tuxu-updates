# 图序 TUXU 下载与更新

此仓库仅托管安装包、更新说明和校验文件。开发源码仓库独立管理。

[下载最新版本](https://github.com/MatchalatteR/tuxu-updates/releases/latest)

- macOS：Apple Silicon，macOS 13 或更高。应用采用 ad-hoc 签名，未做 Apple 公证。
- Windows：x64。当前安装包完成交叉构建和静态检查，尚未完成 Windows 原生运行验收；没有发布者代码签名。
- 首批 v2.1.16 为客户验收版。请使用独立工作区先验收。源码整合仍在评审流程中。
- 安装前退出旧版并完整备份工作区。下载后核对 SHA-256。更新入口只下载和校验，安装由用户手动完成。
- 正常业务数据、账号密码、发布凭据和签名私钥不在此仓库中。

本仓库不使用 GitHub Actions。更新检查使用公开 Releases API，无需客户提供 GitHub 账号或仓库令牌。

若网络无法访问 GitHub，请联系维护者获取经校验的离线安装包。本仓库不承诺中国大陆各运营商的网络可达性。
