# AutoNodes 每日报告

生成时间：2026-07-02 08:53:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 76077 |
| 去重后节点数 | 23089 |
| TCP 可达数 | 3000 |
| 真测通过数 | 433 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23089 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 46.7 |
| geo | 1.5 |
| probe | 48.2 |
| real_test | 100.0 |
| tcp | 30.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 9 | 3 | 6 | 33.3% |
| shadowsocks | 84 | 78 | 6 | 92.9% |
| socks | 39 | 36 | 3 | 92.3% |
| trojan | 269 | 177 | 92 | 65.8% |
| vless | 175 | 99 | 76 | 56.6% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 77 |
| geo:TimeoutError | 30 |
| 204:ProxyError | 23 |
| 204:ClientOSError | 11 |
| geo:ClientOSError | 10 |
| cn-block:TimeoutError | 7 |
| cn-block:ProxyError | 6 |
| cn-block:ClientOSError | 6 |
| geo:ProxyError | 5 |
| speed:TimeoutError | 4 |
| 204:TimeoutError | 4 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4173 |
| ConnectionRefusedError | 695 |
| gaierror | 214 |
| OSError | 151 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.836 | prefer | 219 | 0.758 | 5705 |
| Au1rxx-base64 | 0.746 | prefer | 60 | 0.75 | 106 |
| mheidari-all | 0.724 | prefer | 85 | 0.647 | 15877 |
| DeltaKronecker-all | 0.694 | observe | 205 | 0.615 | 7467 |
| tg-LonUp_M | 0.318 | observe | 2 | 1.0 | 179 |
| nscl5-all | 0.301 | observe | 1 | 1.0 | 1162 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| ermaozi | 0.256 | observe | 1 | 1.0 | 20 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4254 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.12 | downweight | 6 | 0.0 | 0 | 1293 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | xiaoji235-airport-v2ray-all | 0.12 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 6 | 6 |
| DeltaKronecker-all | 0.615 | 126 | 79 | 205 |
| mheidari-all | 0.647 | 55 | 30 | 85 |
| Au1rxx-base64 | 0.75 | 45 | 15 | 60 |
| Surfboard-tg-mixed | 0.758 | 166 | 53 | 219 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15877 | yes | 3.59 | 0 |
| DeltaKronecker-all | 7467 | yes | 3.97 | 0 |
| SoliSpirit-all | 6693 | yes | 2.34 | 0 |
| Epodonios-all | 6497 | yes | 0.54 | 0 |
| Surfboard-tg-mixed | 5705 | yes | 2.14 | 0 |
| mahdibland-V2RayAggregator | 5365 | yes | 0.16 | 0 |
| barry-far-vless | 4756 | yes | 1.51 | 0 |
| 10ium-ScrapeCategorize-Vless | 4254 | yes | 1.75 | 0 |
| Surfboard-tg-vless | 4232 | yes | 2.7 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 2.0 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 81 |
| geo | 45 |
| 204 | 38 |
| cn-block | 19 |
