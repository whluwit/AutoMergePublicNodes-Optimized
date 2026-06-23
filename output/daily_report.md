# AutoNodes 每日报告

生成时间：2026-06-23 02:53:17

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 78573 |
| 去重后节点数 | 22837 |
| TCP 可达数 | 3000 |
| 真测通过数 | 429 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22837 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 22.3 |
| geo | 1.3 |
| probe | 68.6 |
| real_test | 161.0 |
| tcp | 30.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 58 | 58 | 0 | 100.0% |
| hysteria2 | 4 | 3 | 1 | 75.0% |
| shadowsocks | 77 | 72 | 5 | 93.5% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 72 | 59 | 13 | 81.9% |
| vless | 931 | 232 | 699 | 24.9% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 311 |
| geo:TimeoutError | 241 |
| 204:TimeoutError | 57 |
| speed:TimeoutError | 40 |
| geo:ClientOSError | 39 |
| cn-block:TimeoutError | 10 |
| 204:ClientOSError | 7 |
| 204:ProxyError | 7 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4225 |
| ConnectionRefusedError | 614 |
| gaierror | 231 |
| OSError | 108 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.987 | prefer | 58 | 1.0 | 95 |
| Surfboard-tg-mixed | 0.805 | prefer | 16 | 0.875 | 5421 |
| Au1rxx-base64 | 0.746 | prefer | 94 | 0.745 | 149 |
| mheidari-all | 0.647 | observe | 192 | 0.568 | 15546 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| DeltaKronecker-all | 0.305 | observe | 784 | 0.224 | 7452 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4466 |
| Epodonios-all | 0.255 | observe | 0 | None | 8267 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3976 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7735 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.17 | observe | 1 | 0.0 | 0 | 1064 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.224 | 176 | 608 | 784 |
| mheidari-all | 0.568 | 109 | 83 | 192 |
| Au1rxx-base64 | 0.745 | 70 | 24 | 94 |
| Surfboard-tg-mixed | 0.875 | 14 | 2 | 16 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 58 | 0 | 58 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15546 | yes | 3.78 | 0 |
| Epodonios-all | 8267 | yes | 3.4 | 0 |
| SoliSpirit-all | 7735 | yes | 1.46 | 0 |
| DeltaKronecker-all | 7452 | yes | 3.7 | 0 |
| Surfboard-tg-mixed | 5421 | yes | 2.08 | 0 |
| barry-far-vless | 5140 | yes | 1.06 | 0 |
| mahdibland-V2RayAggregator | 4547 | yes | 0.43 | 0 |
| 10ium-ScrapeCategorize-Vless | 4466 | yes | 0.87 | 0 |
| Surfboard-tg-vless | 4156 | yes | 1.85 | 0 |
| MatinGhanbari-all-sub | 3976 | yes | 1.15 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 352 |
| geo | 281 |
| 204 | 71 |
| cn-block | 14 |
