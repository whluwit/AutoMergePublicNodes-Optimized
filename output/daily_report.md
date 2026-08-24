# AutoNodes 每日报告

生成时间：2026-08-24 12:42:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 78511 |
| 去重后节点数 | 21921 |
| TCP 可达数 | 3000 |
| 真测通过数 | 546 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21921 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 33.6 |
| geo | 1.4 |
| probe | 50.8 |
| real_test | 103.6 |
| tcp | 35.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 22 | 22 | 0 | 100.0% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 199 | 187 | 12 | 94.0% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 61 | 55 | 6 | 90.2% |
| vless | 340 | 262 | 78 | 77.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 23 |
| geo:TimeoutError | 20 |
| 204:TimeoutError | 15 |
| geo:ClientOSError | 11 |
| 204:ProxyError | 6 |
| speed:ClientOSError | 6 |
| cn-block:ClientOSError | 5 |
| speed:TimeoutError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4988 |
| ConnectionRefusedError | 812 |
| gaierror | 213 |
| OSError | 15 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.981 | prefer | 330 | 0.918 | 1628 |
| zhangkai | 0.964 | prefer | 22 | 1.0 | 144 |
| DeltaKronecker-all | 0.858 | prefer | 79 | 0.785 | 5914 |
| Surfboard-tg-mixed | 0.823 | prefer | 165 | 0.745 | 6406 |
| mheidari-all | 0.819 | prefer | 44 | 0.75 | 14541 |
| nscl5-all | 0.352 | observe | 2 | 1.0 | 1008 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4899 |
| Epodonios-all | 0.255 | observe | 0 | None | 6919 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3990 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.745 | 123 | 42 | 165 |
| mheidari-all | 0.75 | 33 | 11 | 44 |
| DeltaKronecker-all | 0.785 | 62 | 17 | 79 |
| Au1rxx-base64 | 0.918 | 303 | 27 | 330 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 22 | 0 | 22 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14541 | yes | 3.57 | 0 |
| SoliSpirit-all | 7302 | yes | 3.42 | 0 |
| Epodonios-all | 6919 | yes | 3.74 | 0 |
| Surfboard-tg-mixed | 6406 | yes | 5.16 | 0 |
| DeltaKronecker-all | 5914 | yes | 4.85 | 0 |
| barry-far-vless | 5629 | yes | 3.99 | 0 |
| Surfboard-tg-vless | 5341 | yes | 2.96 | 0 |
| 10ium-ScrapeCategorize-Vless | 4899 | yes | 2.49 | 0 |
| mahdibland-V2RayAggregator | 4097 | yes | 2.68 | 0 |
| MatinGhanbari-all-sub | 3990 | yes | 2.57 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 32 |
| cn-block | 29 |
| 204 | 25 |
| speed | 12 |
