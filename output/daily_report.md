# AutoNodes 每日报告

生成时间：2026-07-18 02:05:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 98/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 82903 |
| 去重后节点数 | 25435 |
| TCP 可达数 | 3000 |
| 真测通过数 | 760 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25435 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 23.2 |
| geo | 0.9 |
| probe | 48.3 |
| real_test | 122.3 |
| tcp | 34.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 149 | 136 | 13 | 91.3% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 568 | 551 | 17 | 97.0% |
| vless | 165 | 26 | 139 | 15.8% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 94 |
| geo:TimeoutError | 35 |
| cn-block:TimeoutError | 13 |
| geo:ClientOSError | 10 |
| speed:TimeoutError | 8 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 3 |
| 204:TimeoutError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4681 |
| ConnectionRefusedError | 701 |
| gaierror | 245 |
| OSError | 218 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.988 | prefer | 161 | 0.913 | 5576 |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.972 | prefer | 313 | 0.895 | 16586 |
| Au1rxx-base64 | 0.911 | prefer | 125 | 0.912 | 149 |
| DeltaKronecker-all | 0.688 | observe | 284 | 0.609 | 8967 |
| xiaoji235-airport-v2ray-all | 0.629 | observe | 8 | 1.0 | 4321 |
| nscl5-all | 0.39 | observe | 2 | 1.0 | 1976 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4428 |
| Epodonios-all | 0.255 | observe | 0 | None | 6707 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3970 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.609 | 173 | 111 | 284 |
| mheidari-all | 0.895 | 280 | 33 | 313 |
| Au1rxx-base64 | 0.912 | 114 | 11 | 125 |
| Surfboard-tg-mixed | 0.913 | 147 | 14 | 161 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| xiaoji235-airport-v2ray-all | 1.0 | 8 | 0 | 8 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16586 | yes | 3.6 | 0 |
| DeltaKronecker-all | 8967 | yes | 3.47 | 0 |
| SoliSpirit-all | 6820 | yes | 2.04 | 0 |
| Epodonios-all | 6707 | yes | 1.65 | 0 |
| Surfboard-tg-mixed | 5576 | yes | 2.07 | 0 |
| mahdibland-V2RayAggregator | 5263 | yes | 0.66 | 0 |
| barry-far-vless | 4912 | yes | 1.24 | 0 |
| 10ium-ScrapeCategorize-Vless | 4428 | yes | 1.44 | 0 |
| xiaoji235-airport-v2ray-all | 4321 | yes | 1.43 | 0 |
| Surfboard-tg-vless | 4298 | yes | 2.22 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 102 |
| geo | 45 |
| cn-block | 18 |
| 204 | 5 |
