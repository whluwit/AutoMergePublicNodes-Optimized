# AutoNodes 每日报告

生成时间：2026-09-21 21:46:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 88638 |
| 去重后节点数 | 25157 |
| TCP 可达数 | 3000 |
| 真测通过数 | 537 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25157 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 80.8 |
| geo | 1.4 |
| probe | 219.3 |
| real_test | 230.9 |
| tcp | 42.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 36 | 25 | 11 | 69.4% |
| hysteria2 | 18 | 16 | 2 | 88.9% |
| shadowsocks | 157 | 144 | 13 | 91.7% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 27 | 17 | 10 | 63.0% |
| vless | 561 | 328 | 233 | 58.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 68 |
| geo:ClientOSError | 54 |
| geo:TimeoutError | 50 |
| speed:ClientOSError | 29 |
| 204:TimeoutError | 21 |
| 204:ProxyError | 15 |
| speed:TimeoutError | 14 |
| cn-block:TimeoutError | 12 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5873 |
| ConnectionRefusedError | 932 |
| gaierror | 357 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.962 | prefer | 276 | 0.895 | 1752 |
| ermaozi | 0.69 | observe | 35 | 0.686 | 350 |
| Surfboard-tg-mixed | 0.664 | observe | 164 | 0.585 | 7273 |
| mheidari-all | 0.591 | observe | 323 | 0.511 | 20197 |
| DeltaKronecker-all | 0.373 | observe | 5 | 0.6 | 6181 |
| ermaozi-get_subscribe | 0.27 | observe | 1 | 1.0 | 377 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 138 |
| Epodonios-all | 0.255 | observe | 0 | None | 7717 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8749 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| roosterkid-openproxylist-v2ray | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.511 | 165 | 158 | 323 |
| Surfboard-tg-mixed | 0.585 | 96 | 68 | 164 |
| DeltaKronecker-all | 0.6 | 3 | 2 | 5 |
| ermaozi | 0.686 | 24 | 11 | 35 |
| Au1rxx-base64 | 0.895 | 247 | 29 | 276 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20197 | yes | 5.7 | 0 |
| SoliSpirit-all | 8749 | yes | 4.61 | 0 |
| Epodonios-all | 7717 | yes | 3.53 | 0 |
| Surfboard-tg-mixed | 7273 | yes | 4.72 | 0 |
| DeltaKronecker-all | 6181 | yes | 6.1 | 0 |
| barry-far-vless | 6075 | yes | 2.43 | 0 |
| Surfboard-tg-vless | 5859 | yes | 4.46 | 0 |
| 10ium-ScrapeCategorize-Vless | 5290 | yes | 3.43 | 0 |
| mahdibland-V2RayAggregator | 4344 | yes | 0.16 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 3.98 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 104 |
| cn-block | 83 |
| speed | 43 |
| 204 | 41 |
