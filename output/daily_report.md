# AutoNodes 每日报告

生成时间：2026-06-29 15:43:41

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 104/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 77444 |
| 去重后节点数 | 23262 |
| TCP 可达数 | 3000 |
| 真测通过数 | 497 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23262 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.0 |
| generate | 38.9 |
| geo | 1.4 |
| probe | 49.9 |
| real_test | 126.2 |
| tcp | 31.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 94 | 77 | 17 | 81.9% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 129 | 95 | 34 | 73.6% |
| vless | 410 | 281 | 129 | 68.5% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 86 |
| geo:TimeoutError | 17 |
| cn-block:TimeoutError | 17 |
| 204:TimeoutError | 13 |
| 204:ClientOSError | 12 |
| speed:TimeoutError | 11 |
| geo:ClientOSError | 8 |
| 204:ProxyError | 7 |
| cn-block:ClientOSError | 7 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4367 |
| ConnectionRefusedError | 653 |
| gaierror | 198 |
| OSError | 131 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.87 | prefer | 269 | 0.792 | 15881 |
| Au1rxx-base64 | 0.821 | prefer | 31 | 0.839 | 80 |
| Surfboard-tg-mixed | 0.769 | prefer | 262 | 0.691 | 5497 |
| DeltaKronecker-all | 0.574 | observe | 77 | 0.494 | 7004 |
| nscl5-all | 0.302 | observe | 1 | 1.0 | 1166 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4653 |
| Epodonios-all | 0.255 | observe | 0 | None | 7616 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |
| tg-ConfigWireguard | 0.175 | observe | 0 | None | 0 | 12 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.494 | 38 | 39 | 77 |
| Surfboard-tg-mixed | 0.691 | 181 | 81 | 262 |
| mheidari-all | 0.792 | 213 | 56 | 269 |
| Au1rxx-base64 | 0.839 | 26 | 5 | 31 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15881 | yes | 3.23 | 0 |
| Epodonios-all | 7616 | yes | 2.67 | 0 |
| SoliSpirit-all | 7472 | yes | 1.9 | 0 |
| DeltaKronecker-all | 7004 | yes | 3.35 | 0 |
| Surfboard-tg-mixed | 5497 | yes | 2.82 | 0 |
| mahdibland-V2RayAggregator | 5278 | yes | 1.76 | 0 |
| 10ium-ScrapeCategorize-Vless | 4653 | yes | 1.47 | 0 |
| barry-far-vless | 4553 | yes | 1.56 | 0 |
| Surfboard-tg-vless | 3986 | yes | 1.57 | 0 |
| MatinGhanbari-all-sub | 3975 | yes | 1.31 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 97 |
| 204 | 32 |
| geo | 27 |
| cn-block | 25 |
