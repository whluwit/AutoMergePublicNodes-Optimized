# AutoNodes 每日报告

生成时间：2026-06-27 19:18:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 76872 |
| 去重后节点数 | 23153 |
| TCP 可达数 | 3000 |
| 真测通过数 | 376 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23153 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 46.6 |
| geo | 1.4 |
| probe | 61.4 |
| real_test | 108.0 |
| tcp | 31.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 6 | 3 | 3 | 50.0% |
| shadowsocks | 111 | 88 | 23 | 79.3% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 99 | 64 | 35 | 64.6% |
| vless | 297 | 178 | 119 | 59.9% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 92 |
| 204:TimeoutError | 21 |
| 204:ClientOSError | 15 |
| cn-block:TimeoutError | 15 |
| geo:TimeoutError | 10 |
| 204:ProxyError | 8 |
| geo:ClientOSError | 7 |
| speed:TimeoutError | 6 |
| cn-block:ClientOSError | 4 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4342 |
| ConnectionRefusedError | 660 |
| gaierror | 198 |
| OSError | 141 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.8 | prefer | 198 | 0.722 | 5150 |
| Au1rxx-base64 | 0.733 | prefer | 46 | 0.739 | 95 |
| mheidari-all | 0.701 | prefer | 167 | 0.623 | 16142 |
| DeltaKronecker-all | 0.623 | observe | 103 | 0.544 | 6822 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| nscl5-all | 0.302 | observe | 1 | 1.0 | 1186 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4579 |
| Epodonios-all | 0.255 | observe | 0 | None | 7776 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3981 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.133 | observe | 3 | 0.0 | 0 | 1084 |
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
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.544 | 56 | 47 | 103 |
| mheidari-all | 0.623 | 104 | 63 | 167 |
| Surfboard-tg-mixed | 0.722 | 143 | 55 | 198 |
| Au1rxx-base64 | 0.739 | 34 | 12 | 46 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16142 | yes | 3.18 | 0 |
| Epodonios-all | 7776 | yes | 3.84 | 0 |
| SoliSpirit-all | 7287 | yes | 3.23 | 0 |
| DeltaKronecker-all | 6822 | yes | 4.01 | 0 |
| mahdibland-V2RayAggregator | 5287 | yes | 0.44 | 0 |
| Surfboard-tg-mixed | 5150 | yes | 2.47 | 0 |
| 10ium-ScrapeCategorize-Vless | 4579 | yes | 1.86 | 0 |
| barry-far-vless | 4576 | yes | 1.02 | 0 |
| MatinGhanbari-all-sub | 3981 | yes | 1.12 | 0 |
| Surfboard-tg-vless | 3804 | yes | 1.99 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 99 |
| 204 | 44 |
| cn-block | 19 |
| geo | 18 |
