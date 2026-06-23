# AutoNodes 每日报告

生成时间：2026-06-23 09:36:06

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 76189 |
| 去重后节点数 | 21935 |
| TCP 可达数 | 3000 |
| 真测通过数 | 371 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21935 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| generate | 34.2 |
| geo | 1.4 |
| probe | 65.8 |
| real_test | 115.6 |
| tcp | 29.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 58 | 58 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 98 | 88 | 10 | 89.8% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 105 | 56 | 49 | 53.3% |
| vless | 300 | 161 | 139 | 53.7% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 71 |
| 204:TimeoutError | 33 |
| 204:ProxyError | 18 |
| geo:TimeoutError | 16 |
| cn-block:TimeoutError | 16 |
| geo:ClientOSError | 11 |
| speed:TimeoutError | 10 |
| speed:ProxyError | 7 |
| cn-block:ClientOSError | 5 |
| geo:ProxyError | 5 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4183 |
| ConnectionRefusedError | 579 |
| gaierror | 139 |
| OSError | 105 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.987 | prefer | 58 | 1.0 | 95 |
| Au1rxx-base64 | 0.761 | prefer | 76 | 0.763 | 126 |
| Surfboard-tg-mixed | 0.727 | prefer | 205 | 0.649 | 5285 |
| DeltaKronecker-all | 0.664 | observe | 75 | 0.587 | 6437 |
| mheidari-all | 0.58 | observe | 152 | 0.5 | 15546 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4576 |
| Epodonios-all | 0.255 | observe | 0 | None | 7878 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7202 |

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
| tg-ConfigWireguard | 0.175 | observe | 0 | None | 0 | 6 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.5 | 76 | 76 | 152 |
| DeltaKronecker-all | 0.587 | 44 | 31 | 75 |
| Surfboard-tg-mixed | 0.649 | 133 | 72 | 205 |
| Au1rxx-base64 | 0.763 | 58 | 18 | 76 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 58 | 0 | 58 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15546 | yes | 3.74 | 0 |
| Epodonios-all | 7878 | yes | 2.3 | 0 |
| SoliSpirit-all | 7202 | yes | 2.09 | 0 |
| DeltaKronecker-all | 6437 | yes | 3.29 | 0 |
| Surfboard-tg-mixed | 5285 | yes | 2.61 | 0 |
| barry-far-vless | 4896 | yes | 1.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 4576 | yes | 0.99 | 0 |
| mahdibland-V2RayAggregator | 4477 | yes | 1.64 | 0 |
| Surfboard-tg-vless | 4084 | yes | 2.73 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.14 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 88 |
| 204 | 53 |
| geo | 32 |
| cn-block | 25 |
