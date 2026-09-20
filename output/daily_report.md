# AutoNodes 每日报告

生成时间：2026-09-20 15:28:29

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 84315 |
| 去重后节点数 | 23455 |
| TCP 可达数 | 3000 |
| 真测通过数 | 499 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23455 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 84.6 |
| geo | 1.5 |
| probe | 234.4 |
| real_test | 204.1 |
| tcp | 38.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 27 | 20 | 7 | 74.1% |
| hysteria2 | 15 | 15 | 0 | 100.0% |
| shadowsocks | 176 | 159 | 17 | 90.3% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 4 | 4 | 0 | 100.0% |
| vless | 439 | 297 | 142 | 67.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 47 |
| geo:TimeoutError | 24 |
| cn-block:ClientOSError | 19 |
| cn-block:TimeoutError | 19 |
| 204:ProxyError | 18 |
| 204:TimeoutError | 15 |
| speed:ClientOSError | 11 |
| speed:TimeoutError | 7 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 2 |
| 204:ProxyConnectionError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5527 |
| ConnectionRefusedError | 784 |
| gaierror | 290 |
| OSError | 15 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.988 | prefer | 283 | 0.926 | 1621 |
| ermaozi | 0.839 | prefer | 21 | 0.857 | 314 |
| Surfboard-tg-mixed | 0.725 | prefer | 195 | 0.646 | 7133 |
| mheidari-all | 0.665 | observe | 92 | 0.587 | 16459 |
| DeltaKronecker-all | 0.611 | observe | 62 | 0.532 | 6092 |
| roosterkid-openproxylist-v2ray | 0.317 | observe | 2 | 1.0 | 150 |
| tg-oneclickvpnkeys | 0.315 | observe | 2 | 1.0 | 103 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.259 | observe | 3 | 0.333 | 5238 |
| Epodonios-all | 0.255 | observe | 0 | None | 7577 |

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
| mahdibland-V2RayAggregator | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 3 | 3 |
| 10ium-ScrapeCategorize-Vless | 0.333 | 1 | 2 | 3 |
| DeltaKronecker-all | 0.532 | 33 | 29 | 62 |
| mheidari-all | 0.587 | 54 | 38 | 92 |
| Surfboard-tg-mixed | 0.646 | 126 | 69 | 195 |
| ermaozi | 0.857 | 18 | 3 | 21 |
| Au1rxx-base64 | 0.926 | 262 | 21 | 283 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16459 | yes | 4.94 | 0 |
| SoliSpirit-all | 9286 | yes | 3.38 | 0 |
| Epodonios-all | 7577 | yes | 3.44 | 0 |
| Surfboard-tg-mixed | 7133 | yes | 4.19 | 0 |
| DeltaKronecker-all | 6092 | yes | 4.15 | 0 |
| barry-far-vless | 5960 | yes | 1.45 | 0 |
| Surfboard-tg-vless | 5703 | yes | 3.92 | 0 |
| 10ium-ScrapeCategorize-Vless | 5238 | yes | 1.8 | 0 |
| mahdibland-V2RayAggregator | 4315 | yes | 1.96 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.23 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 71 |
| cn-block | 42 |
| 204 | 36 |
| speed | 19 |
