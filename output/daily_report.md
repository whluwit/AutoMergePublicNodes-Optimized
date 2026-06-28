# AutoNodes 每日报告

生成时间：2026-06-28 08:51:37

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 75951 |
| 去重后节点数 | 22914 |
| TCP 可达数 | 3000 |
| 真测通过数 | 558 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22914 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| generate | 37.7 |
| geo | 1.4 |
| probe | 65.6 |
| real_test | 161.1 |
| tcp | 30.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 37 | 37 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 120 | 102 | 18 | 85.0% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 173 | 127 | 46 | 73.4% |
| vless | 425 | 285 | 140 | 67.1% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 72 |
| speed:TimeoutError | 37 |
| cn-block:TimeoutError | 20 |
| 204:ClientOSError | 18 |
| 204:TimeoutError | 16 |
| geo:TimeoutError | 15 |
| geo:ClientOSError | 11 |
| 204:ProxyError | 8 |
| cn-block:ClientOSError | 4 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4188 |
| ConnectionRefusedError | 642 |
| gaierror | 221 |
| OSError | 122 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.977 | prefer | 37 | 1.0 | 61 |
| Au1rxx-base64 | 0.825 | prefer | 37 | 0.838 | 117 |
| mheidari-all | 0.807 | prefer | 353 | 0.728 | 16289 |
| Surfboard-tg-mixed | 0.803 | prefer | 254 | 0.724 | 5004 |
| DeltaKronecker-all | 0.678 | observe | 80 | 0.6 | 6788 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7560 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3976 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6985 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-LonUp_M | 0.135 | observe | 1 | 0.0 | 0 | 179 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |
| tg-ConfigWireguard | 0.175 | observe | 0 | None | 0 | 7 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-LonUp_M | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.6 | 48 | 32 | 80 |
| Surfboard-tg-mixed | 0.724 | 184 | 70 | 254 |
| mheidari-all | 0.728 | 257 | 96 | 353 |
| Au1rxx-base64 | 0.838 | 31 | 6 | 37 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 37 | 0 | 37 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16289 | yes | 3.6 | 0 |
| Epodonios-all | 7560 | yes | 2.05 | 0 |
| SoliSpirit-all | 6985 | yes | 2.48 | 0 |
| DeltaKronecker-all | 6788 | yes | 3.76 | 0 |
| mahdibland-V2RayAggregator | 5325 | yes | 0.23 | 0 |
| Surfboard-tg-mixed | 5004 | yes | 2.3 | 0 |
| barry-far-vless | 4456 | yes | 1.26 | 0 |
| 10ium-ScrapeCategorize-Vless | 4327 | yes | 1.45 | 0 |
| MatinGhanbari-all-sub | 3976 | yes | 1.54 | 0 |
| Surfboard-tg-vless | 3679 | yes | 2.44 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 110 |
| 204 | 42 |
| geo | 28 |
| cn-block | 25 |
