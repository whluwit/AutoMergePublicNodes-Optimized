# AutoNodes 每日报告

生成时间：2026-06-17 17:34:06

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/44 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/43 |
| 原始节点数 | 43725 |
| 去重后节点数 | 18176 |
| TCP 可达数 | 1500 |
| 真测通过数 | 110 |
| verified 输出数 | 110 |
| global 输出数 | 111 |
| all 输出数 | 18176 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.7 |
| generate | 20.8 |
| geo | 1.2 |
| probe | 27.1 |
| real_test | 51.7 |
| tcp | 19.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 5 | 1 | 4 | 20.0% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 144 | 78 | 66 | 54.2% |
| vless | 5 | 1 | 4 | 20.0% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 25 |
| 204:ProxyError | 17 |
| 204:TimeoutError | 8 |
| cn-block:ProxyError | 6 |
| speed:ProxyError | 5 |
| geo:status | 4 |
| cn-block:TimeoutError | 2 |
| geo:TimeoutError | 2 |
| 204:ClientOSError | 1 |
| geo:status | 1 |
| speed:TimeoutError | 1 |
| geo:ProxyError | 1 |
| geo:ClientOSError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 2535 |
| ConnectionRefusedError | 450 |
| gaierror | 114 |
| OSError | 30 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.87 | prefer | 28 | 0.893 | 73 |
| DeltaKronecker-all | 0.624 | observe | 147 | 0.544 | 7763 |
| Surfboard-tg-mixed | 0.4 | observe | 4 | 0.75 | 4729 |
| nscl5-all | 0.294 | observe | 1 | 1.0 | 967 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 2000 |
| Epodonios-all | 0.255 | observe | 0 | None | 3000 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3000 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 3000 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 3741 |
| barry-far-vless | 0.255 | observe | 0 | None | 2000 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.113 | observe | 3 | 0.0 | 0 | 588 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 8 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tonykong-base64 | 0.175 | observe | 0 | None | 0 | 5 |
| tonykong-clash | 0.175 | observe | 0 | None | 0 | 5 |
| Barabama-we | 0.176 | observe | 0 | None | 0 | 23 |
| Mr8AHAL | 0.176 | observe | 0 | None | 0 | 26 |
| abc-configs-readme-latest30 | 0.176 | observe | 0 | None | 0 | 19 |
| barabama-nodefree | 0.176 | observe | 0 | None | 0 | 23 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 3 | 3 |
| Barabama-yudou | 0.5 | 1 | 1 | 2 |
| DeltaKronecker-all | 0.544 | 80 | 67 | 147 |
| Surfboard-tg-mixed | 0.75 | 3 | 1 | 4 |
| snakem982 | 0.893 | 25 | 3 | 28 |
| nscl5-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 7763 | yes | 3.6 | 0 |
| Surfboard-tg-mixed | 4729 | yes | 2.0 | 0 |
| mahdibland-V2RayAggregator | 4541 | yes | 1.6 | 0 |
| Surfboard-tg-vless | 3741 | yes | 1.85 | 0 |
| Epodonios-all | 3000 | yes | 2.22 | 0 |
| SoliSpirit-all | 3000 | yes | 2.67 | 0 |
| MatinGhanbari-all-sub | 3000 | yes | 1.54 | 0 |
| mheidari-all | 2000 | yes | 3.31 | 0 |
| 10ium-ScrapeCategorize-Vless | 2000 | yes | 1.04 | 0 |
| barry-far-vless | 2000 | yes | 1.22 | 0 |

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
| speed | 31 |
| 204 | 26 |
| cn-block | 9 |
| geo | 9 |
