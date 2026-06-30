# AutoNodes 每日报告

生成时间：2026-06-30 02:57:56

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 104/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 75440 |
| 去重后节点数 | 23025 |
| TCP 可达数 | 3000 |
| 真测通过数 | 681 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23025 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| generate | 34.9 |
| geo | 1.4 |
| probe | 58.6 |
| real_test | 155.5 |
| tcp | 30.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 135 | 125 | 10 | 92.6% |
| socks | 7 | 6 | 1 | 85.7% |
| trojan | 162 | 137 | 25 | 84.6% |
| vless | 667 | 370 | 297 | 55.5% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 125 |
| geo:TimeoutError | 107 |
| speed:TimeoutError | 39 |
| geo:ClientOSError | 29 |
| 204:ProxyError | 8 |
| 204:ClientOSError | 8 |
| cn-block:TimeoutError | 6 |
| cn-block:ClientOSError | 6 |
| 204:TimeoutError | 3 |
| cn-block:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4192 |
| ConnectionRefusedError | 635 |
| gaierror | 281 |
| OSError | 132 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.848 | prefer | 352 | 0.77 | 5456 |
| mheidari-all | 0.824 | prefer | 350 | 0.746 | 15873 |
| Au1rxx-base64 | 0.706 | prefer | 55 | 0.709 | 101 |
| DeltaKronecker-all | 0.415 | observe | 216 | 0.333 | 7004 |
| xiaoji235-airport-v2ray-all | 0.303 | observe | 1 | 1.0 | 1204 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 6395 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3983 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6670 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| 10ium-ScrapeCategorize-Vless | 0.17 | observe | 3 | 0.0 | 0 | 4653 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.333 | 72 | 144 | 216 |
| Au1rxx-base64 | 0.709 | 39 | 16 | 55 |
| mheidari-all | 0.746 | 261 | 89 | 350 |
| Surfboard-tg-mixed | 0.77 | 271 | 81 | 352 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15873 | yes | 3.44 | 0 |
| DeltaKronecker-all | 7004 | yes | 3.79 | 0 |
| SoliSpirit-all | 6670 | yes | 2.76 | 0 |
| Epodonios-all | 6395 | yes | 3.64 | 0 |
| Surfboard-tg-mixed | 5456 | yes | 2.45 | 0 |
| mahdibland-V2RayAggregator | 5353 | yes | 0.2 | 0 |
| 10ium-ScrapeCategorize-Vless | 4653 | yes | 1.82 | 0 |
| barry-far-vless | 4588 | yes | 2.11 | 0 |
| Surfboard-tg-vless | 4008 | yes | 2.27 | 0 |
| MatinGhanbari-all-sub | 3983 | yes | 2.2 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 165 |
| geo | 136 |
| 204 | 19 |
| cn-block | 13 |
