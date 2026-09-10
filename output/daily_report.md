# AutoNodes 每日报告

生成时间：2026-09-10 02:59:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83752 |
| 去重后节点数 | 21985 |
| TCP 可达数 | 3000 |
| 真测通过数 | 597 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21985 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 80.2 |
| geo | 1.4 |
| probe | 286.8 |
| real_test | 336.8 |
| tcp | 37.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 68 | 46 | 22 | 67.6% |
| hysteria2 | 11 | 11 | 0 | 100.0% |
| shadowsocks | 190 | 180 | 10 | 94.7% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 56 | 53 | 3 | 94.6% |
| vless | 488 | 303 | 185 | 62.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:TimeoutError | 45 |
| geo:ClientOSError | 44 |
| geo:TimeoutError | 39 |
| 204:ProxyError | 29 |
| speed:ClientOSError | 24 |
| cn-block:ClientOSError | 11 |
| 204:TimeoutError | 9 |
| cn-block:TimeoutError | 9 |
| 204:ProxyConnectionError | 4 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5123 |
| ConnectionRefusedError | 852 |
| gaierror | 334 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 293 | 0.956 | 1545 |
| Surfboard-tg-mixed | 0.867 | prefer | 176 | 0.79 | 7448 |
| ermaozi | 0.709 | prefer | 53 | 0.698 | 449 |
| mheidari-all | 0.653 | observe | 162 | 0.574 | 16259 |
| ermaozi-get_subscribe | 0.502 | observe | 16 | 0.562 | 469 |
| DeltaKronecker-all | 0.399 | observe | 111 | 0.315 | 5187 |
| tg-oneclickvpnkeys | 0.317 | observe | 2 | 1.0 | 147 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 53 |
| Epodonios-all | 0.255 | observe | 0 | None | 7910 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.315 | 35 | 76 | 111 |
| ermaozi-get_subscribe | 0.562 | 9 | 7 | 16 |
| mheidari-all | 0.574 | 93 | 69 | 162 |
| ermaozi | 0.698 | 37 | 16 | 53 |
| Surfboard-tg-mixed | 0.79 | 139 | 37 | 176 |
| Au1rxx-base64 | 0.956 | 280 | 13 | 293 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16259 | yes | 5.19 | 0 |
| SoliSpirit-all | 8678 | yes | 2.53 | 0 |
| Epodonios-all | 7910 | yes | 3.58 | 0 |
| Surfboard-tg-mixed | 7448 | yes | 4.62 | 0 |
| barry-far-vless | 6333 | yes | 0.8 | 0 |
| Surfboard-tg-vless | 6108 | yes | 4.15 | 0 |
| DeltaKronecker-all | 5187 | yes | 2.96 | 0 |
| 10ium-ScrapeCategorize-Vless | 4795 | yes | 1.28 | 0 |
| mahdibland-V2RayAggregator | 4247 | yes | 3.27 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.6 | 0 |

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
| geo | 84 |
| speed | 69 |
| 204 | 45 |
| cn-block | 23 |
