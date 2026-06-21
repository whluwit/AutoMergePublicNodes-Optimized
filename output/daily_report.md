# AutoNodes 每日报告

生成时间：2026-06-21 23:43:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 73413 |
| 去重后节点数 | 22044 |
| TCP 可达数 | 3000 |
| 真测通过数 | 784 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22044 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 20.8 |
| geo | 1.3 |
| probe | 50.4 |
| real_test | 122.8 |
| tcp | 29.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 69 | 69 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 142 | 132 | 10 | 93.0% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 121 | 114 | 7 | 94.2% |
| vless | 551 | 462 | 89 | 83.8% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 36 |
| geo:TimeoutError | 18 |
| speed:TimeoutError | 11 |
| cn-block:TimeoutError | 11 |
| 204:ProxyError | 8 |
| 204:TimeoutError | 8 |
| 204:ClientOSError | 4 |
| geo:ClientOSError | 4 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4262 |
| ConnectionRefusedError | 598 |
| gaierror | 120 |
| OSError | 109 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.991 | prefer | 69 | 1.0 | 131 |
| mheidari-all | 0.99 | prefer | 322 | 0.913 | 15086 |
| Au1rxx-base64 | 0.943 | prefer | 93 | 0.946 | 145 |
| DeltaKronecker-all | 0.929 | prefer | 84 | 0.857 | 6748 |
| Surfboard-tg-mixed | 0.89 | prefer | 319 | 0.812 | 4776 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4494 |
| Epodonios-all | 0.255 | observe | 0 | None | 7251 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3978 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6970 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |
| tg-ConfigWireguard | 0.175 | observe | 0 | None | 0 | 5 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.812 | 259 | 60 | 319 |
| DeltaKronecker-all | 0.857 | 72 | 12 | 84 |
| mheidari-all | 0.913 | 294 | 28 | 322 |
| Au1rxx-base64 | 0.946 | 88 | 5 | 93 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 69 | 0 | 69 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15086 | yes | 3.76 | 0 |
| Epodonios-all | 7251 | yes | 2.14 | 0 |
| SoliSpirit-all | 6970 | yes | 1.86 | 0 |
| DeltaKronecker-all | 6748 | yes | 3.86 | 0 |
| Surfboard-tg-mixed | 4776 | yes | 2.57 | 0 |
| barry-far-vless | 4524 | yes | 1.36 | 0 |
| mahdibland-V2RayAggregator | 4505 | yes | 1.54 | 0 |
| 10ium-ScrapeCategorize-Vless | 4494 | yes | 1.57 | 0 |
| MatinGhanbari-all-sub | 3978 | yes | 1.2 | 0 |
| Surfboard-tg-vless | 3678 | yes | 2.39 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 47 |
| geo | 23 |
| 204 | 20 |
| cn-block | 16 |
