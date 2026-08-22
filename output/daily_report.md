# AutoNodes 每日报告

生成时间：2026-08-22 01:04:04

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 93034 |
| 去重后节点数 | 23011 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1098 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23011 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 47.1 |
| geo | 0.8 |
| probe | 69.0 |
| real_test | 230.8 |
| tcp | 38.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 111 | 111 | 0 | 100.0% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 117 | 112 | 5 | 95.7% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 525 | 479 | 46 | 91.2% |
| vless | 720 | 375 | 345 | 52.1% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 123 |
| geo:ClientOSError | 97 |
| speed:TimeoutError | 86 |
| 204:ProxyError | 40 |
| speed:ClientOSError | 25 |
| cn-block:TimeoutError | 13 |
| 204:TimeoutError | 7 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5205 |
| ConnectionRefusedError | 927 |
| gaierror | 445 |
| OSError | 221 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 633 | 0.927 | 1933 |
| zhangkai | 0.997 | prefer | 110 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.863 | prefer | 21 | 0.81 | 6379 |
| mheidari-all | 0.606 | observe | 717 | 0.526 | 21889 |
| DeltaKronecker-all | 0.361 | observe | 10 | 0.4 | 4245 |
| ninja-vless | 0.327 | observe | 1 | 1.0 | 1791 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 162 |
| nscl5-all | 0.259 | observe | 3 | 0.333 | 3321 |
| Epodonios-all | 0.255 | observe | 0 | None | 7089 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3987 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.333 | 1 | 2 | 3 |
| DeltaKronecker-all | 0.4 | 4 | 6 | 10 |
| mheidari-all | 0.526 | 377 | 340 | 717 |
| Surfboard-tg-mixed | 0.81 | 17 | 4 | 21 |
| Au1rxx-base64 | 0.927 | 587 | 46 | 633 |
| ninja-vless | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 110 | 0 | 110 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21889 | yes | 4.43 | 0 |
| SoliSpirit-all | 7131 | yes | 3.38 | 0 |
| Epodonios-all | 7089 | yes | 4.61 | 0 |
| Surfboard-tg-mixed | 6379 | yes | 5.03 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 1.29 | 0 |
| barry-far-vless | 5511 | yes | 0.9 | 0 |
| Surfboard-tg-vless | 5190 | yes | 3.24 | 0 |
| 10ium-ScrapeCategorize-Vless | 5148 | yes | 0.52 | 0 |
| DeltaKronecker-all | 4245 | yes | 5.08 | 0 |
| mahdibland-V2RayAggregator | 4091 | yes | 1.52 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 221 |
| speed | 111 |
| 204 | 50 |
| cn-block | 18 |
