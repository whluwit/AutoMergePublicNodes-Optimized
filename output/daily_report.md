# AutoNodes 每日报告

生成时间：2026-07-01 19:51:41

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 77098 |
| 去重后节点数 | 23239 |
| TCP 可达数 | 3000 |
| 真测通过数 | 330 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23239 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 44.3 |
| geo | 1.3 |
| probe | 48.1 |
| real_test | 97.0 |
| tcp | 30.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 6 | 3 | 3 | 50.0% |
| shadowsocks | 124 | 95 | 29 | 76.6% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 173 | 81 | 92 | 46.8% |
| vless | 172 | 109 | 63 | 63.4% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 89 |
| 204:ProxyError | 23 |
| 204:TimeoutError | 15 |
| cn-block:TimeoutError | 14 |
| geo:TimeoutError | 12 |
| cn-block:ClientOSError | 11 |
| 204:ClientOSError | 7 |
| geo:ClientOSError | 7 |
| cn-block:ProxyError | 4 |
| speed:TimeoutError | 4 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4390 |
| ConnectionRefusedError | 644 |
| gaierror | 183 |
| OSError | 145 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.794 | prefer | 211 | 0.716 | 5849 |
| Au1rxx-base64 | 0.777 | prefer | 51 | 0.784 | 82 |
| mheidari-all | 0.665 | observe | 39 | 0.59 | 16033 |
| DeltaKronecker-all | 0.524 | observe | 176 | 0.443 | 7631 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 169 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4308 |
| Epodonios-all | 0.255 | observe | 0 | None | 6737 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3974 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.141 | observe | 3 | 0.0 | 0 | 1298 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.443 | 78 | 98 | 176 |
| mheidari-all | 0.59 | 23 | 16 | 39 |
| Surfboard-tg-mixed | 0.716 | 151 | 60 | 211 |
| Au1rxx-base64 | 0.784 | 40 | 11 | 51 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16033 | yes | 3.31 | 0 |
| DeltaKronecker-all | 7631 | yes | 2.93 | 0 |
| Epodonios-all | 6737 | yes | 1.59 | 0 |
| SoliSpirit-all | 6642 | yes | 2.66 | 0 |
| Surfboard-tg-mixed | 5849 | yes | 2.01 | 0 |
| mahdibland-V2RayAggregator | 5331 | yes | 1.0 | 0 |
| barry-far-vless | 4858 | yes | 1.87 | 0 |
| Surfboard-tg-vless | 4351 | yes | 2.16 | 0 |
| 10ium-ScrapeCategorize-Vless | 4308 | yes | 1.63 | 0 |
| MatinGhanbari-all-sub | 3974 | yes | 1.95 | 0 |

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
| speed | 95 |
| 204 | 45 |
| cn-block | 29 |
| geo | 19 |
