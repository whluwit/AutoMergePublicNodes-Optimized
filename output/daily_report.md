# AutoNodes 每日报告

生成时间：2026-07-17 19:04:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 79988 |
| 去重后节点数 | 25147 |
| TCP 可达数 | 3000 |
| 真测通过数 | 348 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25147 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| generate | 34.3 |
| geo | 1.0 |
| probe | 54.7 |
| real_test | 101.5 |
| tcp | 34.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 108 | 89 | 19 | 82.4% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 252 | 208 | 44 | 82.5% |
| vless | 130 | 8 | 122 | 6.2% |
| vmess | 4 | 3 | 1 | 75.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 109 |
| 204:TimeoutError | 25 |
| speed:ClientOSError | 20 |
| cn-block:TimeoutError | 12 |
| speed:TimeoutError | 6 |
| geo:ClientOSError | 6 |
| 204:ProxyError | 3 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4732 |
| ConnectionRefusedError | 682 |
| gaierror | 230 |
| OSError | 217 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.896 | prefer | 134 | 0.896 | 150 |
| Surfboard-tg-mixed | 0.797 | prefer | 118 | 0.72 | 5558 |
| mheidari-all | 0.538 | observe | 22 | 0.455 | 16753 |
| DeltaKronecker-all | 0.507 | observe | 225 | 0.427 | 8967 |
| xiaoji235-airport-v2ray-all | 0.322 | observe | 1 | 1.0 | 1680 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4428 |
| Epodonios-all | 0.255 | observe | 0 | None | 6514 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6777 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.427 | 96 | 129 | 225 |
| mheidari-all | 0.455 | 10 | 12 | 22 |
| Surfboard-tg-mixed | 0.72 | 85 | 33 | 118 |
| Au1rxx-base64 | 0.896 | 120 | 14 | 134 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16753 | yes | 3.26 | 0 |
| DeltaKronecker-all | 8967 | yes | 3.21 | 0 |
| SoliSpirit-all | 6777 | yes | 1.37 | 0 |
| Epodonios-all | 6514 | yes | 2.81 | 0 |
| Surfboard-tg-mixed | 5558 | yes | 1.94 | 0 |
| mahdibland-V2RayAggregator | 5263 | yes | 1.34 | 0 |
| barry-far-vless | 4875 | yes | 0.88 | 0 |
| 10ium-ScrapeCategorize-Vless | 4428 | yes | 1.04 | 0 |
| Surfboard-tg-vless | 4258 | yes | 1.79 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.13 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vless | 0.062 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 116 |
| 204 | 31 |
| speed | 27 |
| cn-block | 15 |
