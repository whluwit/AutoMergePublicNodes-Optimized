# AutoNodes 每日报告

生成时间：2026-07-20 02:37:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 86121 |
| 去重后节点数 | 24160 |
| TCP 可达数 | 3000 |
| 真测通过数 | 624 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24160 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 31.3 |
| geo | 1.0 |
| probe | 61.5 |
| real_test | 132.2 |
| tcp | 34.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 151 | 142 | 9 | 94.0% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 351 | 335 | 16 | 95.4% |
| vless | 420 | 102 | 318 | 24.3% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 136 |
| geo:TimeoutError | 73 |
| 204:TimeoutError | 52 |
| geo:ClientOSError | 33 |
| speed:TimeoutError | 20 |
| cn-block:TimeoutError | 14 |
| cn-block:ClientOSError | 5 |
| 204:ProxyError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| speed:ClientPayloadError | 1 |
| geo:parse | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4686 |
| ConnectionRefusedError | 691 |
| gaierror | 565 |
| OSError | 217 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.988 | prefer | 254 | 0.949 | 1061 |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| DeltaKronecker-all | 0.697 | observe | 160 | 0.619 | 6235 |
| mheidari-all | 0.663 | observe | 197 | 0.584 | 19448 |
| Surfboard-tg-mixed | 0.572 | observe | 238 | 0.492 | 5229 |
| chromego_merge | 0.479 | observe | 6 | 1.0 | 54 |
| nscl5-all | 0.335 | observe | 1 | 1.0 | 2755 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4478 |
| Epodonios-all | 0.255 | observe | 0 | None | 6589 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | xiaoji235-airport-v2ray-all | 0.215 | 72 | 0.125 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| xiaoji235-airport-v2ray-all | 0.125 | 9 | 63 | 72 |
| Surfboard-tg-mixed | 0.492 | 117 | 121 | 238 |
| mheidari-all | 0.584 | 115 | 82 | 197 |
| DeltaKronecker-all | 0.619 | 99 | 61 | 160 |
| Au1rxx-base64 | 0.949 | 241 | 13 | 254 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| chromego_merge | 1.0 | 6 | 0 | 6 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19448 | yes | 4.5 | 0 |
| SoliSpirit-all | 6990 | yes | 2.92 | 0 |
| Epodonios-all | 6589 | yes | 0.29 | 0 |
| DeltaKronecker-all | 6235 | yes | 4.81 | 0 |
| Surfboard-tg-mixed | 5229 | yes | 2.65 | 0 |
| mahdibland-V2RayAggregator | 5229 | yes | 2.46 | 0 |
| xiaoji235-airport-v2ray-all | 5035 | yes | 1.61 | 0 |
| barry-far-vless | 4960 | yes | 3.09 | 0 |
| 10ium-ScrapeCategorize-Vless | 4478 | yes | 2.55 | 0 |
| Surfboard-tg-vless | 4170 | yes | 2.8 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 157 |
| geo | 107 |
| 204 | 59 |
| cn-block | 21 |
