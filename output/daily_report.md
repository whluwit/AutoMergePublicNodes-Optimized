# AutoNodes 每日报告

生成时间：2026-10-19 03:11:02

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 97392 |
| 去重后节点数 | 27686 |
| TCP 可达数 | 3000 |
| 真测通过数 | 503 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27686 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 90.1 |
| geo | 1.5 |
| probe | 278.0 |
| real_test | 365.9 |
| tcp | 48.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 44 | 17 | 27 | 38.6% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 124 | 115 | 9 | 92.7% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 46 | 41 | 5 | 89.1% |
| vless | 503 | 312 | 191 | 62.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 91 |
| geo:ClientOSError | 37 |
| cn-block:TimeoutError | 25 |
| speed:ClientOSError | 24 |
| 204:ProxyError | 22 |
| speed:TimeoutError | 10 |
| 204:ProxyConnectionError | 8 |
| cn-block:ClientOSError | 5 |
| 204:TimeoutError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6913 |
| ConnectionRefusedError | 1050 |
| gaierror | 414 |
| OSError | 239 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.936 | prefer | 404 | 0.871 | 1675 |
| Surfboard-tg-mixed | 0.698 | observe | 13 | 0.846 | 7003 |
| mheidari-all | 0.525 | observe | 261 | 0.444 | 23518 |
| DeltaKronecker-all | 0.45 | observe | 12 | 0.5 | 4750 |
| ermaozi | 0.432 | observe | 45 | 0.4 | 696 |
| Epodonios-all | 0.255 | observe | 0 | None | 7467 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9938 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5523 |
| barry-far-vless | 0.255 | observe | 0 | None | 5700 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.4 | 18 | 27 | 45 |
| mheidari-all | 0.444 | 116 | 145 | 261 |
| DeltaKronecker-all | 0.5 | 6 | 6 | 12 |
| Surfboard-tg-mixed | 0.846 | 11 | 2 | 13 |
| Au1rxx-base64 | 0.871 | 352 | 52 | 404 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23518 | yes | 7.17 | 0 |
| SoliSpirit-all | 9938 | yes | 3.84 | 0 |
| Epodonios-all | 7467 | yes | 5.7 | 0 |
| Surfboard-tg-mixed | 7003 | yes | 5.16 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.7 | 0 |
| barry-far-vless | 5700 | yes | 1.96 | 0 |
| Surfboard-tg-vless | 5523 | yes | 7.48 | 0 |
| 10ium-ScrapeCategorize-Vless | 4983 | yes | 3.24 | 0 |
| DeltaKronecker-all | 4750 | yes | 7.92 | 0 |
| mahdibland-V2RayAggregator | 4246 | yes | 0.27 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 128 |
| 204 | 38 |
| speed | 36 |
| cn-block | 32 |
