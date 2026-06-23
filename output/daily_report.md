# AutoNodes 每日报告

生成时间：2026-06-23 19:59:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 77578 |
| 去重后节点数 | 22291 |
| TCP 可达数 | 3000 |
| 真测通过数 | 351 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22291 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 31.6 |
| geo | 1.4 |
| probe | 60.1 |
| real_test | 122.2 |
| tcp | 29.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 50 | 50 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 117 | 100 | 17 | 85.5% |
| trojan | 102 | 54 | 48 | 52.9% |
| vless | 274 | 141 | 133 | 51.5% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 59 |
| geo:ClientOSError | 52 |
| 204:TimeoutError | 23 |
| 204:ProxyError | 14 |
| cn-block:TimeoutError | 11 |
| geo:TimeoutError | 8 |
| cn-block:ProxyError | 7 |
| cn-block:ClientOSError | 6 |
| speed:TimeoutError | 6 |
| geo:ProxyError | 6 |
| 204:ClientOSError | 4 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4228 |
| ConnectionRefusedError | 609 |
| gaierror | 161 |
| OSError | 105 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.984 | prefer | 50 | 1.0 | 73 |
| Surfboard-tg-mixed | 0.811 | prefer | 191 | 0.733 | 5526 |
| Au1rxx-base64 | 0.755 | prefer | 70 | 0.757 | 124 |
| mheidari-all | 0.556 | observe | 162 | 0.475 | 15741 |
| DeltaKronecker-all | 0.475 | observe | 74 | 0.392 | 6437 |
| Surfboard-tg-vless | 0.335 | observe | 1 | 1.0 | 4176 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4576 |
| Epodonios-all | 0.255 | observe | 0 | None | 8189 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| tg-ISVvpn | 0.175 | observe | 0 | None | 0 | 9 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.392 | 29 | 45 | 74 |
| mheidari-all | 0.475 | 77 | 85 | 162 |
| Surfboard-tg-mixed | 0.733 | 140 | 51 | 191 |
| Au1rxx-base64 | 0.757 | 53 | 17 | 70 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-vless | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 50 | 0 | 50 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15741 | yes | 3.71 | 0 |
| Epodonios-all | 8189 | yes | 3.27 | 0 |
| SoliSpirit-all | 7580 | yes | 2.26 | 0 |
| DeltaKronecker-all | 6437 | yes | 3.54 | 0 |
| Surfboard-tg-mixed | 5526 | yes | 1.32 | 0 |
| barry-far-vless | 4987 | yes | 1.3 | 0 |
| mahdibland-V2RayAggregator | 4664 | yes | 0.73 | 0 |
| 10ium-ScrapeCategorize-Vless | 4576 | yes | 1.6 | 0 |
| Surfboard-tg-vless | 4176 | yes | 1.47 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.41 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 67 |
| geo | 66 |
| 204 | 41 |
| cn-block | 24 |
