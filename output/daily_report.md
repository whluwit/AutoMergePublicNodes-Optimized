# AutoNodes 每日报告

生成时间：2026-06-27 08:35:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 77211 |
| 去重后节点数 | 22988 |
| TCP 可达数 | 3000 |
| 真测通过数 | 438 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22988 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 44.0 |
| geo | 1.4 |
| probe | 57.1 |
| real_test | 105.2 |
| tcp | 30.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 18 | 18 | 0 | 100.0% |
| hysteria2 | 4 | 3 | 1 | 75.0% |
| shadowsocks | 126 | 95 | 31 | 75.4% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 172 | 138 | 34 | 80.2% |
| vless | 314 | 180 | 134 | 57.3% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 84 |
| geo:TimeoutError | 32 |
| 204:ClientOSError | 22 |
| 204:TimeoutError | 15 |
| cn-block:TimeoutError | 13 |
| 204:ProxyError | 11 |
| geo:ClientOSError | 10 |
| speed:TimeoutError | 8 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4182 |
| ConnectionRefusedError | 655 |
| gaierror | 224 |
| OSError | 140 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.89 | prefer | 18 | 1.0 | 39 |
| Au1rxx-base64 | 0.809 | prefer | 34 | 0.824 | 91 |
| Surfboard-tg-mixed | 0.806 | prefer | 261 | 0.728 | 5179 |
| mheidari-all | 0.713 | prefer | 216 | 0.634 | 16368 |
| DeltaKronecker-all | 0.678 | observe | 105 | 0.6 | 6822 |
| nscl5-all | 0.302 | observe | 1 | 1.0 | 1186 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4579 |
| Epodonios-all | 0.255 | observe | 0 | None | 7835 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3979 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7359 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.171 | observe | 1 | 0.0 | 0 | 1084 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.5 | 1 | 1 | 2 |
| DeltaKronecker-all | 0.6 | 63 | 42 | 105 |
| mheidari-all | 0.634 | 137 | 79 | 216 |
| Surfboard-tg-mixed | 0.728 | 190 | 71 | 261 |
| Au1rxx-base64 | 0.824 | 28 | 6 | 34 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 18 | 0 | 18 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16368 | yes | 3.64 | 0 |
| Epodonios-all | 7835 | yes | 1.81 | 0 |
| SoliSpirit-all | 7359 | yes | 2.52 | 0 |
| DeltaKronecker-all | 6822 | yes | 3.9 | 0 |
| mahdibland-V2RayAggregator | 5283 | yes | 0.41 | 0 |
| Surfboard-tg-mixed | 5179 | yes | 2.34 | 0 |
| 10ium-ScrapeCategorize-Vless | 4579 | yes | 1.14 | 0 |
| barry-far-vless | 4577 | yes | 1.59 | 0 |
| MatinGhanbari-all-sub | 3979 | yes | 1.67 | 0 |
| Surfboard-tg-vless | 3796 | yes | 1.98 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 92 |
| 204 | 48 |
| geo | 42 |
| cn-block | 18 |
