# AutoNodes 每日报告

生成时间：2026-09-05 14:31:09

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 83776 |
| 去重后节点数 | 22573 |
| TCP 可达数 | 3000 |
| 真测通过数 | 554 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22573 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 29.0 |
| geo | 1.3 |
| probe | 67.5 |
| real_test | 113.9 |
| tcp | 37.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 29 | 29 | 0 | 100.0% |
| hysteria2 | 13 | 13 | 0 | 100.0% |
| shadowsocks | 170 | 156 | 14 | 91.8% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 48 | 39 | 9 | 81.2% |
| vless | 367 | 314 | 53 | 85.6% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 19 |
| 204:TimeoutError | 13 |
| cn-block:TimeoutError | 13 |
| cn-block:ClientOSError | 9 |
| speed:TimeoutError | 7 |
| 204:ClientOSError | 3 |
| 204:ProxyError | 3 |
| speed:ClientOSError | 3 |
| geo:TimeoutError | 3 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:46280: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5334 |
| ConnectionRefusedError | 892 |
| gaierror | 344 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.993 | prefer | 401 | 0.928 | 1685 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.823 | prefer | 138 | 0.746 | 7313 |
| mheidari-all | 0.82 | prefer | 48 | 0.75 | 16245 |
| DeltaKronecker-all | 0.801 | prefer | 13 | 1.0 | 6212 |
| tg-oneclickvpnkeys | 0.482 | observe | 6 | 1.0 | 118 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 52 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4887 |
| Epodonios-all | 0.255 | observe | 0 | None | 7776 |
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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.746 | 103 | 35 | 138 |
| mheidari-all | 0.75 | 36 | 12 | 48 |
| Au1rxx-base64 | 0.928 | 372 | 29 | 401 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 6 | 0 | 6 |
| DeltaKronecker-all | 1.0 | 13 | 0 | 13 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16245 | yes | 3.58 | 0 |
| SoliSpirit-all | 8453 | yes | 2.68 | 0 |
| Epodonios-all | 7776 | yes | 2.27 | 0 |
| Surfboard-tg-mixed | 7313 | yes | 3.02 | 0 |
| barry-far-vless | 6414 | yes | 2.26 | 0 |
| DeltaKronecker-all | 6212 | yes | 3.73 | 0 |
| Surfboard-tg-vless | 6193 | yes | 2.43 | 0 |
| 10ium-ScrapeCategorize-Vless | 4887 | yes | 2.09 | 0 |
| mahdibland-V2RayAggregator | 4095 | yes | 0.63 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.92 | 0 |

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
| geo | 24 |
| cn-block | 23 |
| 204 | 19 |
| speed | 10 |
| sing-box exited 1 | 1 |
