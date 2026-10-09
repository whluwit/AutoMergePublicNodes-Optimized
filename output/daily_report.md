# AutoNodes 每日报告

生成时间：2026-10-09 04:33:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 98011 |
| 去重后节点数 | 27733 |
| TCP 可达数 | 3000 |
| 真测通过数 | 545 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27733 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| generate | 87.8 |
| geo | 1.4 |
| probe | 343.8 |
| real_test | 578.5 |
| tcp | 47.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 0 | 5 | 0.0% |
| http | 65 | 50 | 15 | 76.9% |
| hysteria2 | 26 | 26 | 0 | 100.0% |
| shadowsocks | 167 | 157 | 10 | 94.0% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 92 | 83 | 9 | 90.2% |
| vless | 549 | 226 | 323 | 41.2% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 171 |
| speed:TimeoutError | 74 |
| geo:ClientOSError | 34 |
| speed:ClientOSError | 29 |
| 204:ProxyError | 22 |
| cn-block:TimeoutError | 15 |
| 204:TimeoutError | 7 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 5 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6766 |
| ConnectionRefusedError | 1009 |
| gaierror | 389 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.996 | prefer | 363 | 0.928 | 1756 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.766 | prefer | 49 | 0.694 | 7069 |
| ermaozi-get_subscribe | 0.604 | observe | 48 | 0.583 | 607 |
| mheidari-all | 0.37 | observe | 412 | 0.289 | 23125 |
| DeltaKronecker-all | 0.305 | observe | 10 | 0.3 | 5197 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5081 |
| Epodonios-all | 0.255 | observe | 0 | None | 7569 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.289 | 119 | 293 | 412 |
| DeltaKronecker-all | 0.3 | 3 | 7 | 10 |
| ermaozi-get_subscribe | 0.583 | 28 | 20 | 48 |
| Surfboard-tg-mixed | 0.694 | 34 | 15 | 49 |
| Au1rxx-base64 | 0.928 | 337 | 26 | 363 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23125 | yes | 4.47 | 0 |
| SoliSpirit-all | 9901 | yes | 1.66 | 0 |
| Epodonios-all | 7569 | yes | 2.24 | 0 |
| Surfboard-tg-mixed | 7069 | yes | 2.97 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.4 | 0 |
| barry-far-vless | 5823 | yes | 0.7 | 0 |
| Surfboard-tg-vless | 5581 | yes | 3.91 | 0 |
| DeltaKronecker-all | 5197 | yes | 5.36 | 0 |
| 10ium-ScrapeCategorize-Vless | 5081 | yes | 0.51 | 0 |
| mahdibland-V2RayAggregator | 4362 | yes | 2.44 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 205 |
| speed | 104 |
| 204 | 34 |
| cn-block | 20 |
