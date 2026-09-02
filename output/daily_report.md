# AutoNodes 每日报告

生成时间：2026-09-02 10:33:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 82426 |
| 去重后节点数 | 23484 |
| TCP 可达数 | 3000 |
| 真测通过数 | 626 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23484 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.9 |
| generate | 38.4 |
| geo | 1.4 |
| probe | 68.4 |
| real_test | 135.5 |
| tcp | 38.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 24 | 24 | 0 | 100.0% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 154 | 142 | 12 | 92.2% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 51 | 36 | 15 | 70.6% |
| vless | 513 | 403 | 110 | 78.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 24 |
| cn-block:TimeoutError | 23 |
| speed:TimeoutError | 20 |
| geo:ClientOSError | 19 |
| 204:TimeoutError | 17 |
| speed:ClientOSError | 12 |
| cn-block:ClientOSError | 9 |
| 204:ProxyError | 7 |
| 204:ClientOSError | 5 |
| speed:ProxyError | 3 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5118 |
| ConnectionRefusedError | 885 |
| gaierror | 313 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.967 | prefer | 405 | 0.896 | 1826 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.865 | prefer | 161 | 0.789 | 6989 |
| mheidari-all | 0.744 | prefer | 141 | 0.667 | 15813 |
| DeltaKronecker-all | 0.609 | observe | 32 | 0.531 | 7295 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 102 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 47 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4765 |
| Epodonios-all | 0.255 | observe | 0 | None | 7428 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.531 | 17 | 15 | 32 |
| mheidari-all | 0.667 | 94 | 47 | 141 |
| Surfboard-tg-mixed | 0.789 | 127 | 34 | 161 |
| Au1rxx-base64 | 0.896 | 363 | 42 | 405 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15813 | yes | 3.51 | 0 |
| SoliSpirit-all | 7727 | yes | 1.95 | 0 |
| Epodonios-all | 7428 | yes | 3.95 | 0 |
| DeltaKronecker-all | 7295 | yes | 2.87 | 0 |
| Surfboard-tg-mixed | 6989 | yes | 2.34 | 0 |
| barry-far-vless | 6070 | yes | 1.21 | 0 |
| Surfboard-tg-vless | 5862 | yes | 2.46 | 0 |
| 10ium-ScrapeCategorize-Vless | 4765 | yes | 1.35 | 0 |
| mahdibland-V2RayAggregator | 4066 | yes | 1.82 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.39 | 0 |

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
| geo | 43 |
| speed | 35 |
| cn-block | 34 |
| 204 | 29 |
