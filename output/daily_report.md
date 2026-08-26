# AutoNodes 每日报告

生成时间：2026-08-26 01:05:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 79265 |
| 去重后节点数 | 22523 |
| TCP 可达数 | 3000 |
| 真测通过数 | 723 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22523 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 22.6 |
| geo | 1.6 |
| probe | 61.8 |
| real_test | 175.3 |
| tcp | 36.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 30 | 29 | 1 | 96.7% |
| shadowsocks | 208 | 195 | 13 | 93.8% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 69 | 51 | 18 | 73.9% |
| vless | 895 | 419 | 476 | 46.8% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 282 |
| speed:ClientOSError | 72 |
| geo:ClientOSError | 62 |
| speed:TimeoutError | 62 |
| cn-block:ClientOSError | 10 |
| 204:TimeoutError | 7 |
| cn-block:TimeoutError | 7 |
| 204:ProxyError | 4 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5072 |
| ConnectionRefusedError | 870 |
| gaierror | 289 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.999 | prefer | 478 | 0.923 | 1943 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.963 | prefer | 92 | 0.891 | 6512 |
| mheidari-all | 0.551 | observe | 138 | 0.471 | 14587 |
| tg-oneclickvpnkeys | 0.319 | observe | 2 | 1.0 | 191 |
| DeltaKronecker-all | 0.301 | observe | 491 | 0.22 | 6340 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7017 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3987 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.22 | 108 | 383 | 491 |
| mheidari-all | 0.471 | 65 | 73 | 138 |
| Surfboard-tg-mixed | 0.891 | 82 | 10 | 92 |
| Au1rxx-base64 | 0.923 | 441 | 37 | 478 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14587 | yes | 4.42 | 0 |
| SoliSpirit-all | 7056 | yes | 4.83 | 0 |
| Epodonios-all | 7017 | yes | 1.55 | 0 |
| Surfboard-tg-mixed | 6512 | yes | 2.37 | 0 |
| DeltaKronecker-all | 6340 | yes | 4.52 | 0 |
| barry-far-vless | 5602 | yes | 0.98 | 0 |
| Surfboard-tg-vless | 5328 | yes | 4.04 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 1.27 | 0 |
| mahdibland-V2RayAggregator | 4119 | yes | 1.29 | 0 |
| MatinGhanbari-all-sub | 3987 | yes | 1.04 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 344 |
| speed | 135 |
| cn-block | 19 |
| 204 | 11 |
