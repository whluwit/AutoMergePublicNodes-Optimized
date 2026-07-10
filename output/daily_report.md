# AutoNodes 每日报告

生成时间：2026-07-10 19:25:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 76180 |
| 去重后节点数 | 23857 |
| TCP 可达数 | 3000 |
| 真测通过数 | 279 |
| verified 输出数 | 279 |
| global 输出数 | 293 |
| all 输出数 | 23857 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 50.0 |
| geo | 1.7 |
| probe | 52.3 |
| real_test | 98.2 |
| tcp | 32.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 116 | 97 | 19 | 83.6% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 105 | 53 | 52 | 50.5% |
| vless | 200 | 84 | 116 | 42.0% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 84 |
| geo:TimeoutError | 25 |
| 204:TimeoutError | 20 |
| cn-block:TimeoutError | 14 |
| 204:ProxyError | 13 |
| cn-block:ProxyError | 6 |
| 204:ClientOSError | 6 |
| cn-block:ClientOSError | 5 |
| speed:TimeoutError | 4 |
| geo:ProxyError | 4 |
| geo:ClientOSError | 4 |
| speed:ProxyError | 4 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4619 |
| ConnectionRefusedError | 675 |
| OSError | 194 |
| gaierror | 193 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.829 | prefer | 72 | 0.833 | 120 |
| mheidari-all | 0.772 | prefer | 24 | 0.708 | 16338 |
| Surfboard-tg-mixed | 0.606 | observe | 232 | 0.526 | 5583 |
| DeltaKronecker-all | 0.503 | observe | 102 | 0.422 | 7600 |
| nscl5-all | 0.301 | observe | 1 | 1.0 | 1148 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4165 |
| Epodonios-all | 0.255 | observe | 0 | None | 6378 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3971 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6475 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 8 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.422 | 43 | 59 | 102 |
| Surfboard-tg-mixed | 0.526 | 122 | 110 | 232 |
| mheidari-all | 0.708 | 17 | 7 | 24 |
| Au1rxx-base64 | 0.833 | 60 | 12 | 72 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16338 | yes | 3.55 | 0 |
| DeltaKronecker-all | 7600 | yes | 3.75 | 0 |
| SoliSpirit-all | 6475 | yes | 1.56 | 0 |
| Epodonios-all | 6378 | yes | 1.74 | 0 |
| Surfboard-tg-mixed | 5583 | yes | 2.28 | 0 |
| mahdibland-V2RayAggregator | 5415 | yes | 1.56 | 0 |
| barry-far-vless | 4674 | yes | 1.11 | 0 |
| Surfboard-tg-vless | 4208 | yes | 2.04 | 0 |
| 10ium-ScrapeCategorize-Vless | 4165 | yes | 1.31 | 0 |
| MatinGhanbari-all-sub | 3971 | yes | 1.65 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 92 |
| 204 | 39 |
| geo | 33 |
| cn-block | 25 |
