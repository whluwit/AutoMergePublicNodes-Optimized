# AutoNodes 每日报告

生成时间：2026-06-25 14:26:37

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 83048 |
| 去重后节点数 | 23008 |
| TCP 可达数 | 3000 |
| 真测通过数 | 312 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23008 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| generate | 32.9 |
| geo | 1.4 |
| probe | 56.8 |
| real_test | 134.0 |
| tcp | 30.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 119 | 97 | 22 | 81.5% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 208 | 95 | 113 | 45.7% |
| vless | 235 | 76 | 159 | 32.3% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 114 |
| speed:ClientOSError | 72 |
| 204:ProxyError | 27 |
| cn-block:ProxyError | 15 |
| geo:ProxyError | 12 |
| cn-block:TimeoutError | 12 |
| geo:TimeoutError | 9 |
| 204:ClientOSError | 9 |
| cn-block:ClientOSError | 9 |
| speed:ProxyError | 7 |
| speed:TimeoutError | 4 |
| geo:ClientOSError | 3 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4154 |
| ConnectionRefusedError | 648 |
| gaierror | 230 |
| OSError | 112 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.977 | prefer | 36 | 1.0 | 82 |
| Au1rxx-base64 | 0.893 | prefer | 34 | 0.912 | 101 |
| mheidari-all | 0.627 | observe | 62 | 0.548 | 16105 |
| Surfboard-tg-mixed | 0.524 | observe | 322 | 0.444 | 5229 |
| DeltaKronecker-all | 0.521 | observe | 150 | 0.44 | 12590 |
| nscl5-all | 0.3 | observe | 1 | 1.0 | 1136 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4787 |
| Epodonios-all | 0.255 | observe | 0 | None | 7910 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3974 |

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
| DeltaKronecker-all | 0.44 | 66 | 84 | 150 |
| Surfboard-tg-mixed | 0.444 | 143 | 179 | 322 |
| mheidari-all | 0.548 | 34 | 28 | 62 |
| Au1rxx-base64 | 0.912 | 31 | 3 | 34 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16105 | yes | 3.83 | 0 |
| DeltaKronecker-all | 12590 | yes | 4.24 | 0 |
| Epodonios-all | 7910 | yes | 1.47 | 0 |
| SoliSpirit-all | 7492 | yes | 2.75 | 0 |
| Surfboard-tg-mixed | 5229 | yes | 2.79 | 0 |
| mahdibland-V2RayAggregator | 5133 | yes | 2.05 | 0 |
| 10ium-ScrapeCategorize-Vless | 4787 | yes | 1.7 | 0 |
| barry-far-vless | 4673 | yes | 1.89 | 0 |
| MatinGhanbari-all-sub | 3974 | yes | 2.21 | 0 |
| Surfboard-tg-vless | 3885 | yes | 2.63 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 150 |
| speed | 84 |
| cn-block | 36 |
| geo | 24 |
