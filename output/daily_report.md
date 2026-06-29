# AutoNodes 每日报告

生成时间：2026-06-29 10:53:22

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 75732 |
| 去重后节点数 | 22987 |
| TCP 可达数 | 3000 |
| 真测通过数 | 497 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22987 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| generate | 41.6 |
| geo | 1.3 |
| probe | 60.9 |
| real_test | 149.2 |
| tcp | 30.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 111 | 79 | 32 | 71.2% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 155 | 96 | 59 | 61.9% |
| vless | 374 | 279 | 95 | 74.6% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 70 |
| cn-block:TimeoutError | 27 |
| 204:TimeoutError | 24 |
| 204:ClientOSError | 18 |
| geo:TimeoutError | 12 |
| speed:TimeoutError | 11 |
| 204:ProxyError | 8 |
| cn-block:ClientOSError | 7 |
| geo:ClientOSError | 6 |
| geo:ProxyError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4257 |
| ConnectionRefusedError | 643 |
| gaierror | 221 |
| OSError | 131 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.862 | prefer | 273 | 0.784 | 15787 |
| Au1rxx-base64 | 0.799 | prefer | 37 | 0.811 | 95 |
| Surfboard-tg-mixed | 0.753 | prefer | 252 | 0.675 | 5150 |
| DeltaKronecker-all | 0.615 | observe | 84 | 0.536 | 7004 |
| nscl5-all | 0.358 | observe | 2 | 1.0 | 1166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4653 |
| Epodonios-all | 0.255 | observe | 0 | None | 7391 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6789 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Parsashonam | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.536 | 45 | 39 | 84 |
| Surfboard-tg-mixed | 0.675 | 170 | 82 | 252 |
| mheidari-all | 0.784 | 214 | 59 | 273 |
| Au1rxx-base64 | 0.811 | 30 | 7 | 37 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15787 | yes | 2.69 | 0 |
| Epodonios-all | 7391 | yes | 2.99 | 0 |
| DeltaKronecker-all | 7004 | yes | 4.03 | 0 |
| SoliSpirit-all | 6789 | yes | 1.98 | 0 |
| mahdibland-V2RayAggregator | 5278 | yes | 1.7 | 0 |
| Surfboard-tg-mixed | 5150 | yes | 1.63 | 0 |
| 10ium-ScrapeCategorize-Vless | 4653 | yes | 0.83 | 0 |
| barry-far-vless | 4344 | yes | 0.99 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.08 | 0 |
| Surfboard-tg-vless | 3760 | yes | 1.82 | 0 |

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
| speed | 81 |
| 204 | 50 |
| cn-block | 35 |
| geo | 21 |
