# AutoNodes 每日报告

生成时间：2026-07-05 08:50:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 79583 |
| 去重后节点数 | 23923 |
| TCP 可达数 | 3000 |
| 真测通过数 | 381 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23923 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| generate | 18.7 |
| geo | 1.5 |
| probe | 44.8 |
| real_test | 72.1 |
| tcp | 31.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 118 | 104 | 14 | 88.1% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 245 | 220 | 25 | 89.8% |
| vless | 44 | 11 | 33 | 25.0% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 19 |
| 204:ProxyError | 13 |
| speed:ClientOSError | 12 |
| 204:ClientOSError | 12 |
| 204:TimeoutError | 7 |
| geo:ClientOSError | 4 |
| cn-block:TimeoutError | 4 |
| speed:TimeoutError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4366 |
| ConnectionRefusedError | 782 |
| gaierror | 183 |
| OSError | 155 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.913 | prefer | 82 | 0.841 | 16512 |
| Au1rxx-base64 | 0.911 | prefer | 30 | 0.933 | 109 |
| DeltaKronecker-all | 0.905 | prefer | 192 | 0.828 | 7739 |
| Surfboard-tg-mixed | 0.859 | prefer | 111 | 0.784 | 6080 |
| nscl5-all | 0.308 | observe | 1 | 1.0 | 1323 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4662 |
| Epodonios-all | 0.255 | observe | 0 | None | 6920 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3975 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.784 | 87 | 24 | 111 |
| DeltaKronecker-all | 0.828 | 159 | 33 | 192 |
| mheidari-all | 0.841 | 69 | 13 | 82 |
| Au1rxx-base64 | 0.933 | 28 | 2 | 30 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16512 | yes | 2.97 | 0 |
| DeltaKronecker-all | 7739 | yes | 3.71 | 0 |
| SoliSpirit-all | 7236 | yes | 3.03 | 0 |
| Epodonios-all | 6920 | yes | 3.16 | 0 |
| Surfboard-tg-mixed | 6080 | yes | 1.81 | 0 |
| mahdibland-V2RayAggregator | 5372 | yes | 0.49 | 0 |
| barry-far-vless | 5158 | yes | 1.47 | 0 |
| 10ium-ScrapeCategorize-Vless | 4662 | yes | 1.66 | 0 |
| Surfboard-tg-vless | 4554 | yes | 1.96 | 0 |
| MatinGhanbari-all-sub | 3975 | yes | 1.26 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 32 |
| geo | 23 |
| speed | 13 |
| cn-block | 5 |
