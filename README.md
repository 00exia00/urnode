# 2026年07月25日08时05分 免费节点订阅说明

本目录中的配置整理自公开节点页面。

文件已于 2026年07月25日08时05分 下载、合并和校验。它们是当天的静态快照，不会自动更新。

## AI 中转站推荐

[**Krill**](https://www.krill-ai.net/register?invite=01DNZVB0RF) 是一个 AI API 中转服务，适合需要稳定调用多模型接口、降低直连波动、统一管理额度和密钥的使用场景。服务侧重高可用接入、快速响应和便捷配置，新用户可通过注册地址了解试用与套餐信息。最低0.1倍率，大促期间折上折。grok0.001倍率。

网站注册地址：[**Krill**](https://www.krill-ai.net/register?invite=01DNZVB0RF)

说明：以上链接包含邀请参数，请按需自行判断是否使用。

## 文件说明

### `clash-merged-20260725.yaml`

- 适用于使用 Clash Meta（Mihomo）内核的客户端，例如 Clash Verge Rev。
- 合并了页面上的 Clash 订阅链接 0-4。
- 合并后保留 648 条节点。
- 已处理节点重名、下载来源后缀和已知内核兼容性问题。
- YAML 结构、节点名称唯一性和策略组引用均已校验。

导入方式：在 Clash Verge Rev 中打开“订阅”或“配置”页面，选择导入本地配置，然后选择此 YAML 文件。

### `v2ray-merged-20260725.txt`

- 适用于支持标准 V2Ray Base64 订阅格式的客户端。
- 合并了页面上的 V2Ray 订阅链接 0-4。
- 合并去重后保留 1320 条节点。
- 文件内容为 Base64 编码的节点 URI 列表。
- 已校验 Base64 可正常解码。

导入方式：如果客户端支持从文件导入订阅，可直接选择此 TXT 文件；如果客户端只接受订阅网址，需要先将该文件托管到可访问的 HTTPS 地址，再填入文件链接。

### `sing-box-20260725.json`

- 适用于 Sing-box 客户端。
- 页面当天只提供了一份 Sing-box 配置，因此没有执行多文件合并。
- 配置包含 54 个 `outbounds`。
- JSON 语法和主要结构已校验。

导入方式：备份现有配置后，将此文件作为 Sing-box 配置导入；不同客户端的图形界面和配置目录可能不同，请以对应客户端文档为准。

## 客户端工具

| 工具 | Windows | macOS | Android | iOS | 备注 |
| --- | --- | --- | --- | --- | --- |
| V2Ray | [V2rayN](https://github.com/2dust/v2rayN/releases) | [V2rayU](https://github.com/yanue/V2rayU/releases)<br>[V2rayX](https://github.com/Cenmrev/V2RayX/releases) | [V2rayNG](https://github.com/2dust/v2rayNG/releases)<br>[Actinium](https://github.com/V2Ray-Android/Actinium/releases)<br>[BifrostV](https://play.google.com/store/apps/details?id=com.github.dawndiy.bifrostv) | [Kitsunebi](https://apps.apple.com/us/app/kitsunebi-proxy-utility/id1446584073) | [官网](https://www.v2ray.com/) |
| Sing-box | [sing-box](https://github.com/SagerNet/sing-box/releases) | [SFM](https://sing-box.sagernet.org/clients/apple/) | [SFA](https://sing-box.sagernet.org/clients/android/) | [SFI](https://sing-box.sagernet.org/clients/apple/) | Windows 客户端可在 sing-box Releases 下载；iOS/macOS 可能需要非中国大陆 Apple 账号或 TestFlight |
| Clash | [**Clash Verge Rev**](https://github.com/clash-verge-rev/clash-verge-rev/releases)<br>[**Clash**](https://github.com/Fndroid/clash_for_windows_pkg/releases)<br>[ClashDotNet](https://github.com/ClashDotNetFramework/ClashDotNetFramework/releases)<br>[Clashy](https://github.com/SpongeNobody/Clashy/releases)<br>[ClashXW](https://github.com/ysc3839/ClashXW/releases)<br>[ClashMini](https://github.com/MetaCubeX/Clash.Mini/releases) | [**Clash Verge Rev**](https://github.com/clash-verge-rev/clash-verge-rev/releases)<br>[**ClashX Pro**](https://install.appcenter.ms/users/clashx/apps/clashx-pro/distribution_groups/public)<br>[**ClashX**](https://github.com/yichengchen/clashX/releases)<br>[Clashy](https://github.com/SpongeNobody/Clashy/releases) | [Clash](https://github.com/Kr328/ClashForAndroid/releases)<br>[**ClashR**](https://github.com/BROBIRD/ClashForAndroid/releases) |  | [Clash Verge Rev 官网](https://www.clashverge.dev/)<br>[ClashR 文档](https://docs.cfw.lbyczf.com/) |

## 使用提示

- 免费公开节点通常存在失效快、速度波动大、连接不稳定等情况，节点数量不代表实际可用数量。
- 建议导入后先运行延迟测试，并删除长期不可用的节点。
- 不要通过来源不明的免费节点传输密码、支付信息、私密文件或其他敏感数据。
- 部分协议或字段需要较新的客户端内核；如果导入失败，请先更新 Clash Meta、V2Ray 或 Sing-box 客户端。
- 使用前请了解并遵守所在地法律法规及所访问服务的使用条款。

## 免责声明

本目录内容仅用于技术研究、配置格式学习和客户端兼容性测试，不提供任何可用性、稳定性、速度或安全性保证。公开节点可能由第三方维护，存在失效、劫持、记录流量、泄露信息等风险；使用者应自行判断并承担全部后果。

请勿将本项目内容用于违反当地法律法规、服务条款或侵犯他人权益的用途。因使用、复制、分发或修改本目录内容造成的任何问题，维护者不承担责任。

## 开源说明

本目录中的整理脚本和说明文档采用 MIT License，可用于学习、研究和二次整理。若进行公开分发，请保留必要的说明、免责声明和来源性质描述，并避免加入个人隐私信息、账号凭据、访问令牌或其他敏感内容。

节点配置来自公开网络页面，版权、商标和服务条款归原作者或对应服务方所有；第三方客户端名称和链接仅作兼容性参考，不代表与相关项目存在从属、授权或背书关系。

