# AutoNodes 每日报告

生成时间：2026-09-24 21:13:55

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 98160 |
| 去重后节点数 | 26542 |
| TCP 可达数 | 3000 |
| 真测通过数 | 400 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26542 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 75.3 |
| geo | 1.5 |
| probe | 245.8 |
| real_test | 197.1 |
| tcp | 43.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 15 | 5 | 10 | 33.3% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 174 | 148 | 26 | 85.1% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 9 | 8 | 1 | 88.9% |
| vless | 291 | 217 | 74 | 74.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 32 |
| 204:TimeoutError | 22 |
| cn-block:TimeoutError | 19 |
| 204:ProxyError | 18 |
| 204:ProxyConnectionError | 7 |
| 204:ClientOSError | 3 |
| speed:ClientOSError | 3 |
| speed:TimeoutError | 3 |
| geo:ClientOSError | 2 |
| geo:TimeoutError | 2 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5774 |
| ConnectionRefusedError | 1000 |
| gaierror | 413 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.983 | prefer | 265 | 0.921 | 1629 |
| Surfboard-tg-mixed | 0.801 | prefer | 59 | 0.729 | 7419 |
| mheidari-all | 0.702 | prefer | 170 | 0.624 | 22744 |
| ermaozi | 0.321 | observe | 13 | 0.385 | 298 |
| ermaozi-get_subscribe | 0.267 | observe | 1 | 1.0 | 304 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5307 |
| Epodonios-all | 0.255 | observe | 0 | None | 7888 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9109 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 2 | 2 |
| ermaozi | 0.385 | 5 | 8 | 13 |
| mheidari-all | 0.624 | 106 | 64 | 170 |
| Surfboard-tg-mixed | 0.729 | 43 | 16 | 59 |
| Au1rxx-base64 | 0.921 | 244 | 21 | 265 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22744 | yes | 6.05 | 0 |
| SoliSpirit-all | 9109 | yes | 2.49 | 0 |
| Epodonios-all | 7888 | yes | 3.06 | 0 |
| Surfboard-tg-mixed | 7419 | yes | 4.36 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.55 | 0 |
| barry-far-vless | 6215 | yes | 1.73 | 0 |
| Surfboard-tg-vless | 5963 | yes | 4.55 | 0 |
| DeltaKronecker-all | 5845 | yes | 5.06 | 0 |
| 10ium-ScrapeCategorize-Vless | 5307 | yes | 0.87 | 0 |
| mahdibland-V2RayAggregator | 4405 | yes | 2.53 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 52 |
| 204 | 50 |
| speed | 7 |
| geo | 5 |
