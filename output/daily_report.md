# AutoNodes 每日报告

生成时间：2026-10-16 16:10:06

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 1/105 |
| 原始节点数 | 99256 |
| 去重后节点数 | 27687 |
| TCP 可达数 | 3000 |
| 真测通过数 | 388 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27687 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| generate | 91.7 |
| geo | 1.5 |
| probe | 280.3 |
| real_test | 277.4 |
| tcp | 48.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 59 | 23 | 36 | 39.0% |
| hysteria2 | 14 | 10 | 4 | 71.4% |
| shadowsocks | 155 | 133 | 22 | 85.8% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 24 | 20 | 4 | 83.3% |
| vless | 305 | 199 | 106 | 65.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 43 |
| 204:TimeoutError | 40 |
| cn-block:TimeoutError | 23 |
| speed:TimeoutError | 18 |
| speed:ClientOSError | 15 |
| 204:ClientOSError | 10 |
| geo:TimeoutError | 9 |
| geo:ClientOSError | 7 |
| cn-block:ClientOSError | 3 |
| 204:ProxyConnectionError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6761 |
| ConnectionRefusedError | 1055 |
| gaierror | 282 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.836 | prefer | 449 | 0.757 | 1991 |
| mheidari-all | 0.668 | observe | 32 | 0.594 | 23974 |
| ermaozi | 0.408 | observe | 58 | 0.379 | 618 |
| Surfboard-tg-mixed | 0.382 | observe | 14 | 0.357 | 7090 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 79 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5024 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1991 |
| Epodonios-all | 0.255 | observe | 0 | None | 7602 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.153 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 5 | 5 |
| Surfboard-tg-mixed | 0.357 | 5 | 9 | 14 |
| ermaozi | 0.379 | 22 | 36 | 58 |
| mheidari-all | 0.594 | 19 | 13 | 32 |
| Au1rxx-base64 | 0.757 | 340 | 109 | 449 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23974 | yes | 6.29 | 0 |
| SoliSpirit-all | 10100 | yes | 6.4 | 0 |
| Epodonios-all | 7602 | yes | 6.75 | 0 |
| Surfboard-tg-mixed | 7090 | yes | 4.76 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.4 | 0 |
| barry-far-vless | 5822 | yes | 2.12 | 0 |
| Surfboard-tg-vless | 5572 | yes | 4.52 | 0 |
| 10ium-ScrapeCategorize-Vless | 5024 | yes | 4.33 | 0 |
| DeltaKronecker-all | 4946 | yes | 7.56 | 0 |
| mahdibland-V2RayAggregator | 4265 | yes | 0.96 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 95 |
| speed | 34 |
| cn-block | 27 |
| geo | 17 |
