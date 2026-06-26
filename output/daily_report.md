# AutoNodes 每日报告

生成时间：2026-06-26 19:46:06

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 75714 |
| 去重后节点数 | 22771 |
| TCP 可达数 | 3000 |
| 真测通过数 | 296 |
| verified 输出数 | 296 |
| global 输出数 | 300 |
| all 输出数 | 22771 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| generate | 41.1 |
| geo | 1.3 |
| probe | 58.3 |
| real_test | 97.8 |
| tcp | 30.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 18 | 18 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 124 | 87 | 37 | 70.2% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 103 | 41 | 62 | 39.8% |
| vless | 276 | 143 | 133 | 51.8% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 82 |
| 204:TimeoutError | 49 |
| cn-block:TimeoutError | 24 |
| 204:ProxyError | 18 |
| 204:ClientOSError | 18 |
| geo:TimeoutError | 14 |
| geo:ClientOSError | 9 |
| cn-block:ClientOSError | 7 |
| speed:TimeoutError | 6 |
| geo:ProxyError | 3 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4423 |
| ConnectionRefusedError | 629 |
| OSError | 118 |
| gaierror | 89 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.89 | prefer | 18 | 1.0 | 39 |
| Au1rxx-base64 | 0.827 | prefer | 32 | 0.844 | 86 |
| mheidari-all | 0.666 | observe | 143 | 0.587 | 16147 |
| Surfboard-tg-mixed | 0.644 | observe | 239 | 0.565 | 5075 |
| DeltaKronecker-all | 0.396 | observe | 93 | 0.312 | 6283 |
| nscl5-all | 0.302 | observe | 1 | 1.0 | 1175 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4567 |
| Epodonios-all | 0.255 | observe | 0 | None | 7688 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
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
| DeltaKronecker-all | 0.312 | 29 | 64 | 93 |
| Surfboard-tg-mixed | 0.565 | 135 | 104 | 239 |
| mheidari-all | 0.587 | 84 | 59 | 143 |
| Au1rxx-base64 | 0.844 | 27 | 5 | 32 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 18 | 0 | 18 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16147 | yes | 3.23 | 0 |
| Epodonios-all | 7688 | yes | 2.25 | 0 |
| SoliSpirit-all | 7108 | yes | 1.9 | 0 |
| DeltaKronecker-all | 6283 | yes | 3.41 | 0 |
| mahdibland-V2RayAggregator | 5248 | yes | 1.57 | 0 |
| Surfboard-tg-mixed | 5075 | yes | 1.99 | 0 |
| 10ium-ScrapeCategorize-Vless | 4567 | yes | 1.54 | 0 |
| barry-far-vless | 4543 | yes | 1.67 | 0 |
| MatinGhanbari-all-sub | 3985 | yes | 0.96 | 0 |
| Surfboard-tg-vless | 3761 | yes | 1.77 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 90 |
| 204 | 85 |
| cn-block | 31 |
| geo | 26 |
