# AutoNodes 每日报告

生成时间：2026-07-28 08:32:07

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 86104 |
| 去重后节点数 | 23298 |
| TCP 可达数 | 3000 |
| 真测通过数 | 803 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23298 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 35.0 |
| geo | 1.4 |
| probe | 68.9 |
| real_test | 214.8 |
| tcp | 32.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 69 | 69 | 0 | 100.0% |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 149 | 130 | 19 | 87.2% |
| socks | 7 | 4 | 3 | 57.1% |
| trojan | 412 | 371 | 41 | 90.0% |
| vless | 535 | 218 | 317 | 40.7% |
| vmess | 1 | 0 | 1 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 168 |
| geo:ClientOSError | 58 |
| speed:ClientOSError | 50 |
| speed:TimeoutError | 27 |
| 204:TimeoutError | 25 |
| cn-block:TimeoutError | 22 |
| 204:ProxyError | 17 |
| cn-block:ClientOSError | 5 |
| geo:ProxyError | 3 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 2 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4407 |
| ConnectionRefusedError | 742 |
| gaierror | 275 |
| OSError | 222 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | prefer | 69 | 1.0 | 81 |
| Au1rxx-base64 | 0.977 | prefer | 426 | 0.925 | 1345 |
| mheidari-all | 0.874 | prefer | 100 | 0.8 | 18776 |
| Surfboard-tg-mixed | 0.53 | observe | 10 | 0.7 | 5743 |
| DeltaKronecker-all | 0.519 | observe | 572 | 0.439 | 5965 |
| ninja-vless | 0.279 | observe | 2 | 0.5 | 1791 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4972 |
| Epodonios-all | 0.255 | observe | 0 | None | 6749 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3972 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6579 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.17 | observe | 3 | 0.0 | 0 | 3959 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.439 | 251 | 321 | 572 |
| Barabama-yudou | 0.5 | 1 | 1 | 2 |
| ninja-vless | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.7 | 7 | 3 | 10 |
| mheidari-all | 0.8 | 80 | 20 | 100 |
| Au1rxx-base64 | 0.925 | 394 | 32 | 426 |
| zhangkai | 1.0 | 69 | 0 | 69 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18776 | yes | 3.91 | 0 |
| Epodonios-all | 6749 | yes | 2.07 | 0 |
| SoliSpirit-all | 6579 | yes | 1.55 | 0 |
| DeltaKronecker-all | 5965 | yes | 4.46 | 0 |
| Surfboard-tg-mixed | 5743 | yes | 2.78 | 0 |
| barry-far-vless | 5112 | yes | 0.69 | 0 |
| mahdibland-V2RayAggregator | 4991 | yes | 2.14 | 0 |
| 10ium-ScrapeCategorize-Vless | 4972 | yes | 1.33 | 0 |
| Surfboard-tg-vless | 4586 | yes | 2.94 | 0 |
| MatinGhanbari-all-sub | 3972 | yes | 1.13 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vmess | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 229 |
| speed | 79 |
| 204 | 45 |
| cn-block | 29 |
