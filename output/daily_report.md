# AutoNodes 每日报告

生成时间：2026-06-26 09:02:25

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 82728 |
| 去重后节点数 | 22675 |
| TCP 可达数 | 3000 |
| 真测通过数 | 402 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22675 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 41.3 |
| geo | 1.3 |
| probe | 63.7 |
| real_test | 117.9 |
| tcp | 30.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 114 | 90 | 24 | 78.9% |
| trojan | 140 | 76 | 64 | 54.3% |
| vless | 294 | 193 | 101 | 65.6% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 68 |
| geo:TimeoutError | 26 |
| cn-block:TimeoutError | 19 |
| 204:TimeoutError | 19 |
| 204:ProxyError | 18 |
| 204:ClientOSError | 16 |
| geo:ClientOSError | 8 |
| cn-block:ClientOSError | 5 |
| speed:TimeoutError | 4 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 2 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4275 |
| ConnectionRefusedError | 629 |
| gaierror | 188 |
| OSError | 118 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.977 | prefer | 36 | 1.0 | 82 |
| Surfboard-tg-mixed | 0.797 | prefer | 203 | 0.719 | 5153 |
| mheidari-all | 0.773 | prefer | 203 | 0.695 | 16243 |
| Au1rxx-base64 | 0.754 | prefer | 38 | 0.763 | 91 |
| DeltaKronecker-all | 0.516 | observe | 108 | 0.435 | 12590 |
| nscl5-all | 0.358 | observe | 2 | 1.0 | 1175 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4567 |
| Epodonios-all | 0.255 | observe | 0 | None | 7806 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3985 |

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
| tg-ISVvpn | 0.175 | observe | 0 | None | 0 | 11 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.435 | 47 | 61 | 108 |
| mheidari-all | 0.695 | 141 | 62 | 203 |
| Surfboard-tg-mixed | 0.719 | 146 | 57 | 203 |
| Au1rxx-base64 | 0.763 | 29 | 9 | 38 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16243 | yes | 3.48 | 0 |
| DeltaKronecker-all | 12590 | yes | 4.01 | 0 |
| Epodonios-all | 7806 | yes | 2.99 | 0 |
| SoliSpirit-all | 7436 | yes | 2.75 | 0 |
| mahdibland-V2RayAggregator | 5185 | yes | 1.75 | 0 |
| Surfboard-tg-mixed | 5153 | yes | 2.3 | 0 |
| barry-far-vless | 4575 | yes | 1.66 | 0 |
| 10ium-ScrapeCategorize-Vless | 4567 | yes | 1.07 | 0 |
| MatinGhanbari-all-sub | 3985 | yes | 1.49 | 0 |
| Surfboard-tg-vless | 3827 | yes | 2.46 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 75 |
| 204 | 53 |
| geo | 34 |
| cn-block | 27 |
