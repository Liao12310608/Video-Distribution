# Video Distribution

Video 应用的订阅分发产物。当前 Kazumi 功能包版本为 **2.0.1**，签名修订号 **20001**。

请先安装支持宿主包名校验的新版 Video，再从“服务 → ＋ → Cat 订阅”导入：

[Kazumi Cat 订阅](https://raw.githubusercontent.com/Liao12310608/Video-Distribution/refs/heads/main/p/8c80ff516a524be7a56296a860a93011/index.js.md5)

本版本仅支持宿主包名 `com.yingxia.hmos`。未提供宿主身份或包名不匹配时拒绝启动；旧版应用需要先升级。现有服务可编辑原实例并重新保存，保留服务身份、规则、收藏和观看记录。

本版本只校验包名，不校验应用签名证书。包名限制不能防止修改后的客户端伪装，旧程序的公开历史和下载副本也无法撤回。

`index.js`、`index.js.md5` 和 `index.js.sig` 必须成套使用。仓库仅保存发布产物，不保存应用源码、构建脚本、播放站点、规则或签名私钥。
