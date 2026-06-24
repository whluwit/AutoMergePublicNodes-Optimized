# AutoNodes 每日报告

生成时间：2026-06-24 09:03:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 77169 |
| 去重后节点数 | 22356 |
| TCP 可达数 | 3000 |
| 真测通过数 | 394 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22356 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| generate | 32.2 |
| geo | 1.6 |
| probe | 51.0 |
| real_test | 105.3 |
| tcp | 29.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 50 | 50 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 118 | 97 | 21 | 82.2% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 245 | 145 | 100 | 59.2% |
| vless | 175 | 95 | 80 | 54.3% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 58 |
| geo:TimeoutError | 30 |
| 204:ProxyError | 22 |
| geo:ClientOSError | 17 |
| cn-block:TimeoutError | 16 |
| 204:TimeoutError | 15 |
| 204:ClientOSError | 11 |
| cn-block:ProxyError | 10 |
| geo:ProxyError | 7 |
| speed:ProxyError | 6 |
| cn-block:ClientOSError | 6 |
| speed:TimeoutError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4193 |
| ConnectionRefusedError | 612 |
| gaierror | 139 |
| OSError | 105 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.984 | prefer | 50 | 1.0 | 73 |
| Au1rxx-base64 | 0.942 | prefer | 30 | 0.967 | 124 |
| Surfboard-tg-mixed | 0.809 | prefer | 219 | 0.731 | 5405 |
| mheidari-all | 0.778 | prefer | 61 | 0.705 | 15611 |
| DeltaKronecker-all | 0.55 | observe | 232 | 0.47 | 6644 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| nscl5-all | 0.301 | observe | 1 | 1.0 | 1140 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4745 |
| Epodonios-all | 0.255 | observe | 0 | None | 8238 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3980 |

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
| tg-ISVvpn | 0.175 | observe | 0 | None | 0 | 10 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.47 | 109 | 123 | 232 |
| mheidari-all | 0.705 | 43 | 18 | 61 |
| Surfboard-tg-mixed | 0.731 | 160 | 59 | 219 |
| Au1rxx-base64 | 0.967 | 29 | 1 | 30 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 50 | 0 | 50 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15611 | yes | 3.68 | 0 |
| Epodonios-all | 8238 | yes | 2.32 | 0 |
| SoliSpirit-all | 7490 | yes | 2.75 | 0 |
| DeltaKronecker-all | 6644 | yes | 3.98 | 0 |
| Surfboard-tg-mixed | 5405 | yes | 2.46 | 0 |
| barry-far-vless | 4922 | yes | 1.88 | 0 |
| 10ium-ScrapeCategorize-Vless | 4745 | yes | 1.17 | 0 |
| mahdibland-V2RayAggregator | 4710 | yes | 1.17 | 0 |
| Surfboard-tg-vless | 4121 | yes | 2.02 | 0 |
| MatinGhanbari-all-sub | 3980 | yes | 1.96 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 67 |
| geo | 54 |
| 204 | 48 |
| cn-block | 32 |
