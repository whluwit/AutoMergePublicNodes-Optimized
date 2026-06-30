# AutoNodes 每日报告

生成时间：2026-06-30 14:13:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 74551 |
| 去重后节点数 | 23027 |
| TCP 可达数 | 3000 |
| 真测通过数 | 451 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23027 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| generate | 34.5 |
| geo | 1.4 |
| probe | 55.8 |
| real_test | 113.1 |
| tcp | 29.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 104 | 85 | 19 | 81.7% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 167 | 110 | 57 | 65.9% |
| vless | 358 | 212 | 146 | 59.2% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 114 |
| 204:TimeoutError | 17 |
| 204:ProxyError | 16 |
| geo:TimeoutError | 16 |
| 204:ClientOSError | 16 |
| geo:ClientOSError | 15 |
| speed:TimeoutError | 9 |
| cn-block:ClientOSError | 8 |
| cn-block:ProxyError | 7 |
| cn-block:TimeoutError | 3 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4159 |
| ConnectionRefusedError | 622 |
| gaierror | 222 |
| OSError | 132 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.8 | prefer | 47 | 0.809 | 102 |
| Surfboard-tg-mixed | 0.741 | prefer | 293 | 0.662 | 5386 |
| DeltaKronecker-all | 0.739 | prefer | 83 | 0.663 | 7352 |
| mheidari-all | 0.667 | observe | 211 | 0.588 | 15693 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| xiaoji235-airport-v2ray-all | 0.303 | observe | 1 | 1.0 | 1204 |
| nscl5-all | 0.3 | observe | 1 | 1.0 | 1136 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4139 |
| Epodonios-all | 0.255 | observe | 0 | None | 6322 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.588 | 124 | 87 | 211 |
| Surfboard-tg-mixed | 0.662 | 194 | 99 | 293 |
| DeltaKronecker-all | 0.663 | 55 | 28 | 83 |
| Au1rxx-base64 | 0.809 | 38 | 9 | 47 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15693 | yes | 3.38 | 0 |
| DeltaKronecker-all | 7352 | yes | 3.37 | 0 |
| SoliSpirit-all | 6506 | yes | 1.77 | 0 |
| Epodonios-all | 6322 | yes | 1.63 | 0 |
| Surfboard-tg-mixed | 5386 | yes | 1.98 | 0 |
| mahdibland-V2RayAggregator | 5353 | yes | 2.2 | 0 |
| barry-far-vless | 4531 | yes | 1.52 | 0 |
| 10ium-ScrapeCategorize-Vless | 4139 | yes | 1.35 | 0 |
| MatinGhanbari-all-sub | 3978 | yes | 2.3 | 0 |
| Surfboard-tg-vless | 3959 | yes | 2.12 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 124 |
| 204 | 49 |
| geo | 32 |
| cn-block | 18 |
