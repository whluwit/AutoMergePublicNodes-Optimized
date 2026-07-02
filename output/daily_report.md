# AutoNodes 每日报告

生成时间：2026-07-02 19:22:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 104/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 77440 |
| 去重后节点数 | 23177 |
| TCP 可达数 | 3000 |
| 真测通过数 | 352 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23177 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 39.7 |
| geo | 1.4 |
| probe | 58.9 |
| real_test | 105.9 |
| tcp | 30.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 6 | 3 | 3 | 50.0% |
| shadowsocks | 119 | 93 | 26 | 78.2% |
| socks | 30 | 26 | 4 | 86.7% |
| trojan | 36 | 16 | 20 | 44.4% |
| vless | 368 | 175 | 193 | 47.6% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 145 |
| 204:TimeoutError | 31 |
| geo:TimeoutError | 23 |
| cn-block:TimeoutError | 13 |
| 204:ClientOSError | 10 |
| cn-block:ClientOSError | 7 |
| geo:ClientOSError | 6 |
| speed:TimeoutError | 5 |
| 204:ProxyError | 4 |
| speed:ClientPayloadError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4053 |
| ConnectionRefusedError | 719 |
| gaierror | 256 |
| OSError | 153 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.836 | prefer | 28 | 0.857 | 58 |
| Surfboard-tg-mixed | 0.668 | observe | 294 | 0.588 | 6022 |
| DeltaKronecker-all | 0.594 | observe | 70 | 0.514 | 7467 |
| mheidari-all | 0.565 | observe | 165 | 0.485 | 16059 |
| nscl5-all | 0.358 | observe | 2 | 1.0 | 1162 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4254 |
| Epodonios-all | 0.255 | observe | 0 | None | 6895 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.155 | observe | 2 | 0.0 | 0 | 1293 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ermaozi | 0.175 | observe | 0 | None | 0 | 6 |
| ermaozi-get_subscribe | 0.175 | observe | 0 | None | 0 | 6 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.485 | 80 | 85 | 165 |
| DeltaKronecker-all | 0.514 | 36 | 34 | 70 |
| Surfboard-tg-mixed | 0.588 | 173 | 121 | 294 |
| Au1rxx-base64 | 0.857 | 24 | 4 | 28 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16059 | yes | 3.59 | 0 |
| DeltaKronecker-all | 7467 | yes | 3.5 | 0 |
| Epodonios-all | 6895 | yes | 1.68 | 0 |
| SoliSpirit-all | 6658 | yes | 2.46 | 0 |
| Surfboard-tg-mixed | 6022 | yes | 2.4 | 0 |
| mahdibland-V2RayAggregator | 5372 | yes | 0.65 | 0 |
| barry-far-vless | 5048 | yes | 1.32 | 0 |
| Surfboard-tg-vless | 4492 | yes | 2.06 | 0 |
| 10ium-ScrapeCategorize-Vless | 4254 | yes | 1.13 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.41 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 151 |
| 204 | 45 |
| geo | 30 |
| cn-block | 20 |
