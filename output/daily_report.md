# AutoNodes 每日报告

生成时间：2026-09-20 20:22:02

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 83604 |
| 去重后节点数 | 23442 |
| TCP 可达数 | 3000 |
| 真测通过数 | 438 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23442 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 91.6 |
| geo | 1.5 |
| probe | 227.2 |
| real_test | 197.8 |
| tcp | 39.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 33 | 28 | 5 | 84.8% |
| hysteria2 | 13 | 13 | 0 | 100.0% |
| shadowsocks | 161 | 147 | 14 | 91.3% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 17 | 11 | 6 | 64.7% |
| vless | 337 | 238 | 99 | 70.6% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 26 |
| geo:ClientOSError | 23 |
| geo:TimeoutError | 20 |
| speed:ClientOSError | 14 |
| 204:ProxyError | 12 |
| cn-block:TimeoutError | 12 |
| cn-block:ClientOSError | 8 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| speed:TimeoutError | 3 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5663 |
| ConnectionRefusedError | 787 |
| gaierror | 284 |
| OSError | 17 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.973 | prefer | 249 | 0.912 | 1621 |
| mheidari-all | 0.88 | prefer | 38 | 0.816 | 16265 |
| ermaozi | 0.87 | prefer | 26 | 0.885 | 314 |
| DeltaKronecker-all | 0.845 | prefer | 32 | 0.781 | 6092 |
| Surfboard-tg-mixed | 0.691 | observe | 206 | 0.612 | 7161 |
| tg-oneclickvpnkeys | 0.403 | observe | 4 | 1.0 | 74 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4315 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| Epodonios-all | 0.255 | observe | 0 | None | 7615 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 3 | 3 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 3 | 3 |
| Surfboard-tg-mixed | 0.612 | 126 | 80 | 206 |
| DeltaKronecker-all | 0.781 | 25 | 7 | 32 |
| mheidari-all | 0.816 | 31 | 7 | 38 |
| ermaozi | 0.885 | 23 | 3 | 26 |
| Au1rxx-base64 | 0.912 | 227 | 22 | 249 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16265 | yes | 4.99 | 0 |
| SoliSpirit-all | 8753 | yes | 3.01 | 0 |
| Epodonios-all | 7615 | yes | 5.3 | 0 |
| Surfboard-tg-mixed | 7161 | yes | 4.21 | 0 |
| DeltaKronecker-all | 6092 | yes | 4.41 | 0 |
| barry-far-vless | 5924 | yes | 1.06 | 0 |
| Surfboard-tg-vless | 5710 | yes | 3.47 | 0 |
| 10ium-ScrapeCategorize-Vless | 5238 | yes | 1.29 | 0 |
| mahdibland-V2RayAggregator | 4315 | yes | 3.06 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.65 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 43 |
| 204 | 42 |
| cn-block | 23 |
| speed | 18 |
