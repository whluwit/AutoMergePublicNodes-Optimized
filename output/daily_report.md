# AutoNodes 每日报告

生成时间：2026-06-27 13:27:48

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 77292 |
| 去重后节点数 | 23007 |
| TCP 可达数 | 3000 |
| 真测通过数 | 382 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23007 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 48.7 |
| geo | 1.4 |
| probe | 47.2 |
| real_test | 107.2 |
| tcp | 30.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 18 | 18 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 101 | 88 | 13 | 87.1% |
| trojan | 280 | 156 | 124 | 55.7% |
| vless | 174 | 113 | 61 | 64.9% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 86 |
| 204:ProxyError | 28 |
| 204:TimeoutError | 28 |
| cn-block:TimeoutError | 12 |
| geo:TimeoutError | 12 |
| cn-block:ProxyError | 8 |
| 204:ClientOSError | 8 |
| geo:ClientOSError | 6 |
| speed:TimeoutError | 3 |
| cn-block:ClientOSError | 3 |
| geo:ProxyError | 2 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4217 |
| ConnectionRefusedError | 657 |
| gaierror | 213 |
| OSError | 140 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.89 | prefer | 18 | 1.0 | 39 |
| Surfboard-tg-mixed | 0.835 | prefer | 251 | 0.757 | 5186 |
| mheidari-all | 0.833 | prefer | 91 | 0.758 | 16363 |
| Au1rxx-base64 | 0.788 | prefer | 35 | 0.8 | 93 |
| DeltaKronecker-all | 0.491 | observe | 183 | 0.41 | 6822 |
| nscl5-all | 0.359 | observe | 2 | 1.0 | 1186 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4579 |
| Epodonios-all | 0.255 | observe | 0 | None | 7866 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3977 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7361 |

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
| tg-ConfigWireguard | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.41 | 75 | 108 | 183 |
| Surfboard-tg-mixed | 0.757 | 190 | 61 | 251 |
| mheidari-all | 0.758 | 69 | 22 | 91 |
| Au1rxx-base64 | 0.8 | 28 | 7 | 35 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 18 | 0 | 18 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16363 | yes | 3.73 | 0 |
| Epodonios-all | 7866 | yes | 2.06 | 0 |
| SoliSpirit-all | 7361 | yes | 2.39 | 0 |
| DeltaKronecker-all | 6822 | yes | 4.07 | 0 |
| mahdibland-V2RayAggregator | 5283 | yes | 1.58 | 0 |
| Surfboard-tg-mixed | 5186 | yes | 2.23 | 0 |
| barry-far-vless | 4584 | yes | 1.93 | 0 |
| 10ium-ScrapeCategorize-Vless | 4579 | yes | 1.58 | 0 |
| MatinGhanbari-all-sub | 3977 | yes | 2.01 | 0 |
| Surfboard-tg-vless | 3808 | yes | 2.65 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 91 |
| 204 | 64 |
| cn-block | 23 |
| geo | 20 |
