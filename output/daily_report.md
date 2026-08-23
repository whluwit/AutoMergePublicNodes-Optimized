# AutoNodes 每日报告

生成时间：2026-08-23 01:06:45

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 83287 |
| 去重后节点数 | 23720 |
| TCP 可达数 | 3000 |
| 真测通过数 | 866 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23720 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 36.2 |
| geo | 1.4 |
| probe | 58.5 |
| real_test | 166.9 |
| tcp | 39.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 114 | 114 | 0 | 100.0% |
| hysteria2 | 25 | 25 | 0 | 100.0% |
| shadowsocks | 185 | 180 | 5 | 97.3% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 200 | 179 | 21 | 89.5% |
| vless | 563 | 366 | 197 | 65.0% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 84 |
| speed:TimeoutError | 47 |
| geo:ClientOSError | 32 |
| cn-block:TimeoutError | 22 |
| speed:ClientOSError | 13 |
| 204:TimeoutError | 9 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| 204:ProxyError | 4 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5190 |
| ConnectionRefusedError | 1006 |
| gaierror | 643 |
| OSError | 229 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 513 | 0.943 | 1723 |
| zhangkai | 0.988 | prefer | 113 | 0.991 | 144 |
| Surfboard-tg-mixed | 0.893 | prefer | 207 | 0.816 | 6333 |
| mheidari-all | 0.548 | observe | 154 | 0.468 | 14498 |
| nscl5-all | 0.355 | observe | 2 | 1.0 | 1082 |
| DeltaKronecker-all | 0.347 | observe | 88 | 0.261 | 5015 |
| tg-oneclickvpnkeys | 0.317 | observe | 2 | 1.0 | 146 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5096 |
| Epodonios-all | 0.255 | observe | 0 | None | 6920 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | xiaoji235-airport-v2ray-all | 0.197 | 9 | 0.111 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| xiaoji235-airport-v2ray-all | 0.111 | 1 | 8 | 9 |
| DeltaKronecker-all | 0.261 | 23 | 65 | 88 |
| mheidari-all | 0.468 | 72 | 82 | 154 |
| Surfboard-tg-mixed | 0.816 | 169 | 38 | 207 |
| Au1rxx-base64 | 0.943 | 484 | 29 | 513 |
| zhangkai | 0.991 | 112 | 1 | 113 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14498 | yes | 4.43 | 0 |
| SoliSpirit-all | 6994 | yes | 4.43 | 0 |
| Epodonios-all | 6920 | yes | 4.08 | 0 |
| Surfboard-tg-mixed | 6333 | yes | 5.14 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 3.37 | 0 |
| barry-far-vless | 5496 | yes | 2.22 | 0 |
| Surfboard-tg-vless | 5187 | yes | 3.29 | 0 |
| 10ium-ScrapeCategorize-Vless | 5096 | yes | 2.54 | 0 |
| DeltaKronecker-all | 5015 | yes | 5.2 | 0 |
| mahdibland-V2RayAggregator | 4074 | yes | 1.35 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 116 |
| speed | 60 |
| cn-block | 32 |
| 204 | 18 |
