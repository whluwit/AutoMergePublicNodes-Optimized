# AutoNodes 每日报告

生成时间：2026-06-17 17:41:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 0/44 |
| 原始节点数 | 43729 |
| 去重后节点数 | 18177 |
| TCP 可达数 | 1500 |
| 真测通过数 | 102 |
| verified 输出数 | 102 |
| global 输出数 | 106 |
| all 输出数 | 18177 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.7 |
| generate | 19.1 |
| geo | 1.2 |
| probe | 25.9 |
| real_test | 40.0 |
| tcp | 20.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 24 | 24 | 0 | 100.0% |
| hysteria2 | 2 | 1 | 1 | 50.0% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 138 | 70 | 68 | 50.7% |
| vless | 33 | 2 | 31 | 6.1% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 27 |
| geo:status | 27 |
| 204:ProxyError | 11 |
| speed:ProxyError | 7 |
| cn-block:ClientOSError | 6 |
| 204:TimeoutError | 4 |
| cn-block:ProxyError | 4 |
| speed:TimeoutError | 3 |
| cn-block:TimeoutError | 3 |
| geo:TimeoutError | 3 |
| geo:ProxyError | 3 |
| geo:ClientOSError | 2 |
| geo:status | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 2752 |
| ConnectionRefusedError | 438 |
| gaierror | 61 |
| OSError | 30 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.605 | observe | 139 | 0.525 | 7763 |
| snakem982 | 0.459 | observe | 55 | 0.455 | 73 |
| Surfboard-tg-mixed | 0.284 | observe | 6 | 0.333 | 4729 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Au1rxx-base64 | 0.26 | observe | 1 | 1.0 | 118 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 2000 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3741 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 8 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tonykong-base64 | 0.175 | observe | 0 | None | 0 | 5 |
| tonykong-clash | 0.175 | observe | 0 | None | 0 | 5 |
| Barabama-we | 0.176 | observe | 0 | None | 0 | 23 |
| Mr8AHAL | 0.176 | observe | 0 | None | 0 | 26 |
| abc-configs-readme-latest30 | 0.176 | observe | 0 | None | 0 | 17 |
| barabama-nodefree | 0.176 | observe | 0 | None | 0 | 23 |
| ermaozi | 0.176 | observe | 0 | None | 0 | 29 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Epodonios-all | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.333 | 2 | 4 | 6 |
| snakem982 | 0.455 | 25 | 30 | 55 |
| DeltaKronecker-all | 0.525 | 73 | 66 | 139 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| Au1rxx-base64 | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 7763 | yes | 3.48 | 0 |
| Surfboard-tg-mixed | 4729 | yes | 2.28 | 0 |
| mahdibland-V2RayAggregator | 4541 | yes | 1.7 | 0 |
| Surfboard-tg-vless | 3741 | yes | 1.84 | 0 |
| Epodonios-all | 3000 | yes | 2.06 | 0 |
| SoliSpirit-all | 3000 | yes | 3.17 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 1.07 | 0 |
| mheidari-all | 2000 | yes | 3.1 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 1.44 | 0 |
| barry-far-vless | 2000 | yes | 1.25 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vless | 0.061 |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 37 |
| geo | 36 |
| 204 | 15 |
| cn-block | 13 |
