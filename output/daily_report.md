# AutoNodes 每日报告

生成时间：2026-07-28 19:20:25

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 80684 |
| 去重后节点数 | 23093 |
| TCP 可达数 | 3000 |
| 真测通过数 | 408 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23093 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| generate | 33.1 |
| geo | 1.4 |
| probe | 53.8 |
| real_test | 111.3 |
| tcp | 33.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 14 | 11 | 3 | 78.6% |
| shadowsocks | 160 | 137 | 23 | 85.6% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 47 | 36 | 11 | 76.6% |
| vless | 415 | 222 | 193 | 53.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 63 |
| 204:TimeoutError | 36 |
| geo:TimeoutError | 34 |
| geo:ClientOSError | 19 |
| cn-block:ProxyError | 18 |
| cn-block:TimeoutError | 18 |
| speed:ClientOSError | 17 |
| speed:TimeoutError | 15 |
| cn-block:ClientOSError | 5 |
| geo:ProxyError | 4 |
| 204:ClientOSError | 1 |
| speed:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4368 |
| ConnectionRefusedError | 758 |
| gaierror | 309 |
| OSError | 223 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.932 | prefer | 285 | 0.881 | 1352 |
| Surfboard-tg-mixed | 0.547 | observe | 9 | 0.778 | 5820 |
| DeltaKronecker-all | 0.504 | observe | 335 | 0.424 | 5965 |
| mheidari-all | 0.489 | observe | 6 | 0.833 | 17171 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 4972 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| Epodonios-all | 0.255 | observe | 0 | None | 6834 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3971 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6507 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| zhangkai | 0.129 | observe | 1 | 0.0 | 0 | 33 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| zhangkai | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.424 | 142 | 193 | 335 |
| Surfboard-tg-mixed | 0.778 | 7 | 2 | 9 |
| mheidari-all | 0.833 | 5 | 1 | 6 |
| Au1rxx-base64 | 0.881 | 251 | 34 | 285 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17171 | yes | 3.56 | 0 |
| Epodonios-all | 6834 | yes | 3.74 | 0 |
| SoliSpirit-all | 6507 | yes | 2.83 | 0 |
| DeltaKronecker-all | 5965 | yes | 4.17 | 0 |
| Surfboard-tg-mixed | 5820 | yes | 3.1 | 0 |
| barry-far-vless | 5117 | yes | 1.3 | 0 |
| mahdibland-V2RayAggregator | 5059 | yes | 2.48 | 0 |
| 10ium-ScrapeCategorize-Vless | 4972 | yes | 1.63 | 0 |
| Surfboard-tg-vless | 4597 | yes | 2.94 | 0 |
| MatinGhanbari-all-sub | 3971 | yes | 1.44 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 100 |
| geo | 57 |
| cn-block | 41 |
| speed | 34 |
