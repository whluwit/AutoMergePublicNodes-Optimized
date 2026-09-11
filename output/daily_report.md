# AutoNodes 每日报告

生成时间：2026-09-11 02:56:17

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 86971 |
| 去重后节点数 | 24411 |
| TCP 可达数 | 3000 |
| 真测通过数 | 619 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24411 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| generate | 77.8 |
| geo | 1.4 |
| probe | 312.3 |
| real_test | 516.4 |
| tcp | 42.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 59 | 36 | 23 | 61.0% |
| hysteria2 | 15 | 15 | 0 | 100.0% |
| shadowsocks | 175 | 168 | 7 | 96.0% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 67 | 44 | 23 | 65.7% |
| vless | 753 | 353 | 400 | 46.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 179 |
| speed:ClientOSError | 91 |
| geo:ClientOSError | 79 |
| speed:TimeoutError | 42 |
| 204:ProxyError | 19 |
| cn-block:TimeoutError | 15 |
| 204:ProxyConnectionError | 9 |
| cn-block:ClientOSError | 7 |
| 204:TimeoutError | 7 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |
| geo:parse | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6087 |
| ConnectionRefusedError | 961 |
| gaierror | 301 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.899 | prefer | 330 | 0.839 | 1551 |
| mheidari-all | 0.875 | prefer | 42 | 0.81 | 15718 |
| Surfboard-tg-mixed | 0.826 | prefer | 171 | 0.749 | 7329 |
| ermaozi | 0.71 | prefer | 50 | 0.7 | 431 |
| xiaoji235-airport-v2ray-all | 0.519 | observe | 5 | 1.0 | 3508 |
| DeltaKronecker-all | 0.375 | observe | 455 | 0.295 | 5853 |
| ermaozi-get_subscribe | 0.363 | observe | 15 | 0.4 | 461 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4995 |
| Epodonios-all | 0.255 | observe | 0 | None | 7793 |
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
| tg-oneclickvpnkeys | 0.0 | 0 | 2 | 2 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.295 | 134 | 321 | 455 |
| ermaozi-get_subscribe | 0.4 | 6 | 9 | 15 |
| ermaozi | 0.7 | 35 | 15 | 50 |
| Surfboard-tg-mixed | 0.749 | 128 | 43 | 171 |
| mheidari-all | 0.81 | 34 | 8 | 42 |
| Au1rxx-base64 | 0.839 | 277 | 53 | 330 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15718 | yes | 3.55 | 0 |
| SoliSpirit-all | 8685 | yes | 2.38 | 0 |
| Epodonios-all | 7793 | yes | 4.18 | 0 |
| Surfboard-tg-mixed | 7329 | yes | 2.78 | 0 |
| barry-far-vless | 6145 | yes | 1.0 | 0 |
| Surfboard-tg-vless | 5926 | yes | 2.6 | 0 |
| DeltaKronecker-all | 5853 | yes | 3.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 4995 | yes | 0.83 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 2.33 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 0.25 | 0 |

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
| geo | 259 |
| speed | 134 |
| 204 | 38 |
| cn-block | 24 |
