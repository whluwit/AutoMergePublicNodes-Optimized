# AutoNodes 每日报告

生成时间：2026-06-25 19:57:33

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 82452 |
| 去重后节点数 | 22858 |
| TCP 可达数 | 3000 |
| 真测通过数 | 302 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22858 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| generate | 42.8 |
| geo | 1.3 |
| probe | 57.4 |
| real_test | 104.8 |
| tcp | 29.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 105 | 83 | 22 | 79.0% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 176 | 76 | 100 | 43.2% |
| vless | 141 | 98 | 43 | 69.5% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 51 |
| 204:TimeoutError | 27 |
| 204:ProxyError | 20 |
| cn-block:TimeoutError | 17 |
| 204:ClientOSError | 15 |
| geo:TimeoutError | 12 |
| cn-block:ClientOSError | 6 |
| geo:ProxyError | 5 |
| geo:ClientOSError | 5 |
| speed:TimeoutError | 4 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4253 |
| ConnectionRefusedError | 637 |
| gaierror | 186 |
| OSError | 111 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.977 | prefer | 36 | 1.0 | 82 |
| Au1rxx-base64 | 0.828 | prefer | 49 | 0.837 | 104 |
| mheidari-all | 0.739 | prefer | 177 | 0.661 | 16098 |
| Surfboard-tg-mixed | 0.665 | observe | 92 | 0.587 | 5257 |
| DeltaKronecker-all | 0.544 | observe | 110 | 0.464 | 12590 |
| nscl5-all | 0.357 | observe | 2 | 1.0 | 1136 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4787 |
| Epodonios-all | 0.255 | observe | 0 | None | 7883 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7166 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
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
| DeltaKronecker-all | 0.464 | 51 | 59 | 110 |
| Barabama-yudou | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.587 | 54 | 38 | 92 |
| mheidari-all | 0.661 | 117 | 60 | 177 |
| Au1rxx-base64 | 0.837 | 41 | 8 | 49 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16098 | yes | 3.79 | 0 |
| DeltaKronecker-all | 12590 | yes | 3.8 | 0 |
| Epodonios-all | 7883 | yes | 2.55 | 0 |
| SoliSpirit-all | 7166 | yes | 2.65 | 0 |
| Surfboard-tg-mixed | 5257 | yes | 1.83 | 0 |
| mahdibland-V2RayAggregator | 5117 | yes | 2.05 | 0 |
| 10ium-ScrapeCategorize-Vless | 4787 | yes | 1.87 | 0 |
| barry-far-vless | 4620 | yes | 1.64 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.47 | 0 |
| Surfboard-tg-vless | 3824 | yes | 1.96 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 62 |
| speed | 57 |
| cn-block | 25 |
| geo | 22 |
