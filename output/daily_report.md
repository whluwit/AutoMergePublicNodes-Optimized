# AutoNodes 每日报告

生成时间：2026-09-01 16:03:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 84240 |
| 去重后节点数 | 24694 |
| TCP 可达数 | 3000 |
| 真测通过数 | 609 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24694 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 54.2 |
| geo | 1.4 |
| probe | 89.4 |
| real_test | 131.4 |
| tcp | 41.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 21 | 2 | 91.3% |
| hysteria2 | 9 | 9 | 0 | 100.0% |
| shadowsocks | 144 | 135 | 9 | 93.8% |
| socks | 4 | 0 | 4 | 0.0% |
| trojan | 20 | 18 | 2 | 90.0% |
| vless | 527 | 426 | 101 | 80.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 28 |
| cn-block:TimeoutError | 23 |
| cn-block:ClientOSError | 17 |
| geo:ClientOSError | 10 |
| speed:ClientOSError | 8 |
| 204:ProxyError | 8 |
| 204:ProxyConnectionError | 7 |
| speed:TimeoutError | 5 |
| geo:TimeoutError | 5 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5449 |
| ConnectionRefusedError | 970 |
| gaierror | 333 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.982 | prefer | 383 | 0.914 | 1760 |
| zhangkai | 0.886 | prefer | 23 | 0.913 | 144 |
| mheidari-all | 0.853 | prefer | 148 | 0.777 | 17557 |
| Surfboard-tg-mixed | 0.798 | prefer | 168 | 0.72 | 6964 |
| DeltaKronecker-all | 0.287 | observe | 2 | 0.5 | 7294 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4708 |
| Epodonios-all | 0.255 | observe | 0 | None | 7367 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8076 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.72 | 121 | 47 | 168 |
| mheidari-all | 0.777 | 115 | 33 | 148 |
| zhangkai | 0.913 | 21 | 2 | 23 |
| Au1rxx-base64 | 0.914 | 350 | 33 | 383 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17557 | yes | 5.25 | 0 |
| SoliSpirit-all | 8076 | yes | 3.8 | 0 |
| Epodonios-all | 7367 | yes | 1.27 | 0 |
| DeltaKronecker-all | 7294 | yes | 5.69 | 0 |
| Surfboard-tg-mixed | 6964 | yes | 4.42 | 0 |
| barry-far-vless | 6013 | yes | 0.82 | 0 |
| Surfboard-tg-vless | 5838 | yes | 4.19 | 0 |
| 10ium-ScrapeCategorize-Vless | 4708 | yes | 2.71 | 0 |
| mahdibland-V2RayAggregator | 4013 | yes | 1.07 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.49 | 0 |

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
| 204 | 45 |
| cn-block | 44 |
| geo | 16 |
| speed | 13 |
