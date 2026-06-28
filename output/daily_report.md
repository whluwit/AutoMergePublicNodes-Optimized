# AutoNodes 每日报告

生成时间：2026-06-28 13:32:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 104/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 76138 |
| 去重后节点数 | 22875 |
| TCP 可达数 | 3000 |
| 真测通过数 | 565 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22875 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 41.7 |
| geo | 1.4 |
| probe | 69.0 |
| real_test | 174.6 |
| tcp | 30.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 115 | 96 | 19 | 83.5% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 165 | 110 | 55 | 66.7% |
| vless | 424 | 317 | 107 | 74.8% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 72 |
| 204:TimeoutError | 23 |
| speed:TimeoutError | 19 |
| geo:ClientOSError | 16 |
| geo:TimeoutError | 14 |
| 204:ClientOSError | 12 |
| cn-block:TimeoutError | 10 |
| 204:ProxyError | 9 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4238 |
| ConnectionRefusedError | 644 |
| gaierror | 228 |
| OSError | 122 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.861 | prefer | 341 | 0.783 | 16291 |
| Au1rxx-base64 | 0.859 | prefer | 53 | 0.868 | 105 |
| Surfboard-tg-mixed | 0.792 | prefer | 238 | 0.714 | 4987 |
| DeltaKronecker-all | 0.65 | observe | 77 | 0.571 | 6788 |
| xiaoji235-airport-v2ray-all | 0.305 | observe | 1 | 1.0 | 1261 |
| nscl5-all | 0.302 | observe | 1 | 1.0 | 1174 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7519 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.571 | 44 | 33 | 77 |
| Surfboard-tg-mixed | 0.714 | 170 | 68 | 238 |
| mheidari-all | 0.783 | 267 | 74 | 341 |
| Au1rxx-base64 | 0.868 | 46 | 7 | 53 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16291 | yes | 3.66 | 0 |
| Epodonios-all | 7519 | yes | 1.95 | 0 |
| SoliSpirit-all | 7282 | yes | 2.11 | 0 |
| DeltaKronecker-all | 6788 | yes | 3.76 | 0 |
| mahdibland-V2RayAggregator | 5325 | yes | 2.17 | 0 |
| Surfboard-tg-mixed | 4987 | yes | 3.19 | 0 |
| barry-far-vless | 4502 | yes | 1.26 | 0 |
| 10ium-ScrapeCategorize-Vless | 4327 | yes | 1.44 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.35 | 0 |
| Surfboard-tg-vless | 3691 | yes | 2.08 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 91 |
| 204 | 44 |
| geo | 30 |
| cn-block | 18 |
