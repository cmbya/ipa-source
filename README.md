# 霸霸的 IPA 软件源

关注列表中的 IPA 镜像，供 LiveContainer 软件源功能读取。安装包放在本仓库 Releases，不进入 Git 文件历史。

## 添加软件源

```text
https://cmbya.github.io/ipa-source/apps.json
```

备用直链：

```text
https://raw.githubusercontent.com/cmbya/ipa-source/main/apps.json
```

原样镜像，不替换 Bundle ID、不签名、不保证兼容。结构和下载校验通过不等于安全审查或手机安装实测。

## 来源与许可

每个镜像 Release 附 `LICENSE-upstream.txt` 和 `PROVENANCE.txt`，列出上游发布页、附件和 SHA-256。源中的应用说明也包含上游地址。未明确允许再分发或尚未满足源码义务的项目暂不公开镜像。

软件源目录由独立同步程序维护。关注列表、通知记录和凭据不在本公开仓库中发布。`state/mirror.json` 仅记录已经公开镜像的安装包信息。

旧 Release 不自动删除。移出关注范围后不再出现在当前源中，但历史安装包保留。若发现侵权或安全问题，请提交 Issue 说明。
