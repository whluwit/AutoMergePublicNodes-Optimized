# AutoNodes 每日报告

生成时间：2026-07-01 09:42:26

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 75612 |
| 去重后节点数 | 23071 |
| TCP 可达数 | 3000 |
| 真测通过数 | 425 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23071 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.9 |
| generate | 28.3 |
| geo | 1.5 |
| probe | 56.9 |
| real_test | 105.2 |
| tcp | 30.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 42 | 41 | 1 | 97.6% |
| hysteria2 | 4 | 3 | 1 | 75.0% |
| shadowsocks | 130 | 102 | 28 | 78.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 163 | 96 | 67 | 58.9% |
| vless | 372 | 177 | 195 | 47.6% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 159 |
| geo:TimeoutError | 28 |
| 204:ProxyError | 27 |
| 204:TimeoutError | 22 |
| cn-block:TimeoutError | 12 |
| cn-block:ClientOSError | 12 |
| geo:ClientOSError | 11 |
| 204:ClientOSError | 10 |
| speed:ProxyError | 5 |
| speed:TimeoutError | 4 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4155 |
| ConnectionRefusedError | 642 |
| gaierror | 193 |
| OSError | 144 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.957 | prefer | 42 | 0.976 | 61 |
| Au1rxx-base64 | 0.83 | prefer | 61 | 0.836 | 115 |
| Surfboard-tg-mixed | 0.675 | observe | 267 | 0.596 | 5595 |
| DeltaKronecker-all | 0.673 | observe | 121 | 0.595 | 7631 |
| mheidari-all | 0.524 | observe | 223 | 0.444 | 15660 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4308 |
| Epodonios-all | 0.255 | observe | 0 | None | 6487 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6549 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| chromego_merge | 0.175 | observe | 0 | None | 0 | 6 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| peasoft-NoMoreWalls | 0.175 | observe | 0 | None | 0 | 3 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.444 | 99 | 124 | 223 |
| ermaozi | 0.5 | 1 | 1 | 2 |
| DeltaKronecker-all | 0.595 | 72 | 49 | 121 |
| Surfboard-tg-mixed | 0.596 | 159 | 108 | 267 |
| Au1rxx-base64 | 0.836 | 51 | 10 | 61 |
| snakem982 | 0.976 | 41 | 1 | 42 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15660 | yes | 3.09 | 0 |
| DeltaKronecker-all | 7631 | yes | 2.98 | 0 |
| SoliSpirit-all | 6549 | yes | 1.84 | 0 |
| Epodonios-all | 6487 | yes | 1.1 | 0 |
| Surfboard-tg-mixed | 5595 | yes | 2.11 | 0 |
| mahdibland-V2RayAggregator | 5331 | yes | 1.66 | 0 |
| barry-far-vless | 4743 | yes | 1.46 | 0 |
| 10ium-ScrapeCategorize-Vless | 4308 | yes | 1.63 | 0 |
| Surfboard-tg-vless | 4151 | yes | 1.92 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.32 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 168 |
| 204 | 59 |
| geo | 40 |
| cn-block | 26 |
