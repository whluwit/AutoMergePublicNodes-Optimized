# AutoNodes 每日报告

生成时间：2026-09-22 20:55:56

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 84310 |
| 去重后节点数 | 23815 |
| TCP 可达数 | 3000 |
| 真测通过数 | 405 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23815 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| generate | 73.9 |
| geo | 1.4 |
| probe | 200.8 |
| real_test | 145.3 |
| tcp | 39.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 33 | 17 | 16 | 51.5% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 165 | 151 | 14 | 91.5% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 22 | 14 | 8 | 63.6% |
| vless | 301 | 202 | 99 | 67.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 37 |
| geo:ClientOSError | 24 |
| 204:ProxyConnectionError | 14 |
| cn-block:ClientOSError | 13 |
| 204:ProxyError | 12 |
| cn-block:TimeoutError | 12 |
| 204:TimeoutError | 10 |
| geo:TimeoutError | 9 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| speed:TimeoutError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5391 |
| ConnectionRefusedError | 820 |
| gaierror | 258 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.928 | prefer | 31 | 0.871 | 6324 |
| Au1rxx-base64 | 0.909 | prefer | 292 | 0.842 | 1718 |
| mheidari-all | 0.818 | prefer | 78 | 0.744 | 15951 |
| Surfboard-tg-mixed | 0.598 | observe | 108 | 0.519 | 7279 |
| ermaozi | 0.594 | observe | 29 | 0.586 | 325 |
| Epodonios-all | 0.255 | observe | 0 | None | 7749 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9217 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5930 |
| barry-far-vless | 0.255 | observe | 0 | None | 5928 |

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
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.25 | 1 | 3 | 4 |
| Surfboard-tg-mixed | 0.519 | 56 | 52 | 108 |
| ermaozi | 0.586 | 17 | 12 | 29 |
| mheidari-all | 0.744 | 58 | 20 | 78 |
| Au1rxx-base64 | 0.842 | 246 | 46 | 292 |
| DeltaKronecker-all | 0.871 | 27 | 4 | 31 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15951 | yes | 5.35 | 0 |
| SoliSpirit-all | 9217 | yes | 2.75 | 0 |
| Epodonios-all | 7749 | yes | 3.49 | 0 |
| Surfboard-tg-mixed | 7279 | yes | 4.3 | 0 |
| DeltaKronecker-all | 6324 | yes | 5.29 | 0 |
| Surfboard-tg-vless | 5930 | yes | 3.74 | 0 |
| barry-far-vless | 5928 | yes | 2.37 | 0 |
| 10ium-ScrapeCategorize-Vless | 4915 | yes | 1.89 | 0 |
| mahdibland-V2RayAggregator | 4252 | yes | 3.03 | 0 |
| xiaoji235-airport-v2ray-all | 4242 | yes | 3.73 | 0 |

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
| 204 | 40 |
| speed | 40 |
| geo | 33 |
| cn-block | 28 |
