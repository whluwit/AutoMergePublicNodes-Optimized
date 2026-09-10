# AutoNodes 每日报告

生成时间：2026-09-10 20:32:07

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 83485 |
| 去重后节点数 | 22832 |
| TCP 可达数 | 3000 |
| 真测通过数 | 393 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22832 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| generate | 75.0 |
| geo | 1.4 |
| probe | 282.2 |
| real_test | 239.0 |
| tcp | 39.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 25 | 22 | 3 | 88.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 151 | 135 | 16 | 89.4% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 22 | 17 | 5 | 77.3% |
| vless | 280 | 202 | 78 | 72.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 21 |
| 204:TimeoutError | 21 |
| cn-block:TimeoutError | 16 |
| 204:ProxyError | 13 |
| cn-block:ClientOSError | 13 |
| geo:TimeoutError | 10 |
| 204:ClientOSError | 6 |
| speed:ClientOSError | 4 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5507 |
| ConnectionRefusedError | 891 |
| gaierror | 283 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.934 | prefer | 257 | 0.872 | 1642 |
| ermaozi | 0.856 | prefer | 23 | 0.87 | 405 |
| DeltaKronecker-all | 0.853 | prefer | 16 | 0.938 | 5853 |
| Surfboard-tg-mixed | 0.758 | prefer | 144 | 0.681 | 7221 |
| mheidari-all | 0.715 | prefer | 50 | 0.64 | 15823 |
| tg-oneclickvpnkeys | 0.319 | observe | 2 | 1.0 | 194 |
| roosterkid-openproxylist-v2ray | 0.275 | observe | 3 | 0.667 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4995 |
| Epodonios-all | 0.255 | observe | 0 | None | 7677 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.64 | 32 | 18 | 50 |
| roosterkid-openproxylist-v2ray | 0.667 | 2 | 1 | 3 |
| Surfboard-tg-mixed | 0.681 | 98 | 46 | 144 |
| ermaozi | 0.87 | 20 | 3 | 23 |
| Au1rxx-base64 | 0.872 | 224 | 33 | 257 |
| DeltaKronecker-all | 0.938 | 15 | 1 | 16 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15823 | yes | 3.92 | 0 |
| SoliSpirit-all | 8881 | yes | 2.22 | 0 |
| Epodonios-all | 7677 | yes | 4.9 | 0 |
| Surfboard-tg-mixed | 7221 | yes | 4.11 | 0 |
| barry-far-vless | 6058 | yes | 1.65 | 0 |
| DeltaKronecker-all | 5853 | yes | 3.1 | 0 |
| Surfboard-tg-vless | 5840 | yes | 3.25 | 0 |
| 10ium-ScrapeCategorize-Vless | 4995 | yes | 1.47 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 2.45 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.73 | 0 |

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
| 204 | 40 |
| geo | 31 |
| cn-block | 30 |
| speed | 4 |
