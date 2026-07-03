# AutoNodes 每日报告

生成时间：2026-07-03 19:16:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 78197 |
| 去重后节点数 | 23106 |
| TCP 可达数 | 3000 |
| 真测通过数 | 209 |
| verified 输出数 | 209 |
| global 输出数 | 217 |
| all 输出数 | 23106 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| generate | 30.7 |
| geo | 1.3 |
| probe | 43.7 |
| real_test | 71.5 |
| tcp | 30.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 80 | 62 | 18 | 77.5% |
| socks | 4 | 4 | 0 | 100.0% |
| trojan | 113 | 58 | 55 | 51.3% |
| vless | 110 | 41 | 69 | 37.3% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 45 |
| geo:TimeoutError | 19 |
| 204:ProxyError | 16 |
| 204:ClientOSError | 11 |
| geo:ProxyError | 10 |
| 204:TimeoutError | 9 |
| cn-block:TimeoutError | 9 |
| geo:ClientOSError | 7 |
| cn-block:ProxyError | 7 |
| speed:ProxyError | 4 |
| cn-block:ClientOSError | 3 |
| speed:TimeoutError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4220 |
| ConnectionRefusedError | 692 |
| OSError | 155 |
| gaierror | 149 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.837 | prefer | 22 | 0.864 | 84 |
| DeltaKronecker-all | 0.618 | observe | 104 | 0.538 | 6997 |
| Surfboard-tg-mixed | 0.606 | observe | 169 | 0.527 | 6201 |
| nscl5-all | 0.403 | observe | 3 | 1.0 | 1114 |
| mheidari-all | 0.326 | observe | 15 | 0.267 | 16169 |
| tg-ConfigV2rayNG | 0.319 | observe | 2 | 1.0 | 200 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4368 |
| Epodonios-all | 0.255 | observe | 0 | None | 7138 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ermaozi | 0.175 | observe | 0 | None | 0 | 12 |
| ermaozi-get_subscribe | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.267 | 4 | 11 | 15 |
| Surfboard-tg-mixed | 0.527 | 89 | 80 | 169 |
| DeltaKronecker-all | 0.538 | 56 | 48 | 104 |
| Au1rxx-base64 | 0.864 | 19 | 3 | 22 |
| tg-ConfigV2rayNG | 1.0 | 2 | 0 | 2 |
| nscl5-all | 1.0 | 3 | 0 | 3 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16169 | yes | 2.99 | 0 |
| Epodonios-all | 7138 | yes | 1.5 | 0 |
| DeltaKronecker-all | 6997 | yes | 3.15 | 0 |
| SoliSpirit-all | 6834 | yes | 1.91 | 0 |
| Surfboard-tg-mixed | 6201 | yes | 2.11 | 0 |
| mahdibland-V2RayAggregator | 5333 | yes | 1.57 | 0 |
| barry-far-vless | 5303 | yes | 1.21 | 0 |
| Surfboard-tg-vless | 4705 | yes | 1.85 | 0 |
| 10ium-ScrapeCategorize-Vless | 4368 | yes | 1.0 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.29 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 51 |
| 204 | 36 |
| geo | 36 |
| cn-block | 19 |
