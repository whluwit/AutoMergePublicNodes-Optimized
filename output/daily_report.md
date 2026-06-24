# AutoNodes 每日报告

生成时间：2026-06-24 14:25:56

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 77263 |
| 去重后节点数 | 22501 |
| TCP 可达数 | 3000 |
| 真测通过数 | 483 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22501 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| generate | 30.6 |
| geo | 1.4 |
| probe | 58.0 |
| real_test | 115.9 |
| tcp | 29.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 50 | 50 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 134 | 122 | 12 | 91.0% |
| trojan | 138 | 102 | 36 | 73.9% |
| vless | 308 | 203 | 105 | 65.9% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 62 |
| 204:TimeoutError | 24 |
| cn-block:TimeoutError | 22 |
| 204:ProxyError | 11 |
| geo:TimeoutError | 9 |
| 204:ClientOSError | 9 |
| geo:ClientOSError | 7 |
| speed:TimeoutError | 4 |
| cn-block:ClientOSError | 3 |
| speed:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4109 |
| ConnectionRefusedError | 616 |
| gaierror | 200 |
| OSError | 105 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.984 | prefer | 50 | 1.0 | 73 |
| Surfboard-tg-mixed | 0.856 | prefer | 284 | 0.778 | 5407 |
| mheidari-all | 0.787 | prefer | 165 | 0.709 | 15574 |
| Au1rxx-base64 | 0.77 | prefer | 62 | 0.774 | 113 |
| DeltaKronecker-all | 0.698 | observe | 74 | 0.622 | 6644 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4745 |
| Epodonios-all | 0.255 | observe | 0 | None | 8169 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3974 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7672 |

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
| DeltaKronecker-all | 0.622 | 46 | 28 | 74 |
| mheidari-all | 0.709 | 117 | 48 | 165 |
| Au1rxx-base64 | 0.774 | 48 | 14 | 62 |
| Surfboard-tg-mixed | 0.778 | 221 | 63 | 284 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 50 | 0 | 50 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15574 | yes | 3.75 | 0 |
| Epodonios-all | 8169 | yes | 2.71 | 0 |
| SoliSpirit-all | 7672 | yes | 2.67 | 0 |
| DeltaKronecker-all | 6644 | yes | 3.12 | 0 |
| Surfboard-tg-mixed | 5407 | yes | 2.39 | 0 |
| barry-far-vless | 4921 | yes | 0.89 | 0 |
| 10ium-ScrapeCategorize-Vless | 4745 | yes | 1.47 | 0 |
| mahdibland-V2RayAggregator | 4710 | yes | 1.43 | 0 |
| Surfboard-tg-vless | 4121 | yes | 1.98 | 0 |
| MatinGhanbari-all-sub | 3974 | yes | 1.68 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 67 |
| 204 | 44 |
| cn-block | 26 |
| geo | 16 |
