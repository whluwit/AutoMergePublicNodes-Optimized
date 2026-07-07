# AutoNodes 每日报告

生成时间：2026-07-07 09:37:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 84946 |
| 去重后节点数 | 24814 |
| TCP 可达数 | 3000 |
| 真测通过数 | 344 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24814 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.0 |
| generate | 18.6 |
| geo | 1.3 |
| probe | 46.9 |
| real_test | 72.8 |
| tcp | 31.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 5 | 4 | 1 | 80.0% |
| shadowsocks | 130 | 111 | 19 | 85.4% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 194 | 175 | 19 | 90.2% |
| vless | 55 | 10 | 45 | 18.2% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 26 |
| speed:ClientOSError | 23 |
| 204:TimeoutError | 7 |
| 204:ClientOSError | 6 |
| geo:ClientOSError | 5 |
| 204:ProxyError | 5 |
| speed:TimeoutError | 3 |
| cn-block:ClientOSError | 3 |
| cn-block:TimeoutError | 3 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4533 |
| ConnectionRefusedError | 827 |
| OSError | 170 |
| gaierror | 121 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.904 | prefer | 106 | 0.83 | 6102 |
| DeltaKronecker-all | 0.867 | prefer | 125 | 0.792 | 8472 |
| mheidari-all | 0.822 | prefer | 95 | 0.747 | 18158 |
| Au1rxx-base64 | 0.751 | prefer | 61 | 0.754 | 118 |
| xiaoji235-airport-v2ray-all | 0.4 | observe | 4 | 0.75 | 3626 |
| nscl5-all | 0.314 | observe | 1 | 1.0 | 1478 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4700 |
| Epodonios-all | 0.255 | observe | 0 | None | 7013 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3972 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.747 | 71 | 24 | 95 |
| xiaoji235-airport-v2ray-all | 0.75 | 3 | 1 | 4 |
| Au1rxx-base64 | 0.754 | 46 | 15 | 61 |
| DeltaKronecker-all | 0.792 | 99 | 26 | 125 |
| Surfboard-tg-mixed | 0.83 | 88 | 18 | 106 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18158 | yes | 2.71 | 0 |
| DeltaKronecker-all | 8472 | yes | 2.81 | 0 |
| SoliSpirit-all | 7353 | yes | 1.56 | 0 |
| Epodonios-all | 7013 | yes | 0.37 | 0 |
| Surfboard-tg-mixed | 6102 | yes | 1.8 | 0 |
| mahdibland-V2RayAggregator | 5338 | yes | 0.44 | 0 |
| barry-far-vless | 5256 | yes | 1.27 | 0 |
| 10ium-ScrapeCategorize-Vless | 4700 | yes | 0.79 | 0 |
| Surfboard-tg-vless | 4575 | yes | 1.91 | 0 |
| MatinGhanbari-all-sub | 3972 | yes | 1.33 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 33 |
| speed | 27 |
| 204 | 18 |
| cn-block | 7 |
