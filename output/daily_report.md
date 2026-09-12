# AutoNodes 每日报告

生成时间：2026-09-12 10:09:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 83041 |
| 去重后节点数 | 22802 |
| TCP 可达数 | 3000 |
| 真测通过数 | 454 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22802 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 80.1 |
| geo | 1.4 |
| probe | 292.3 |
| real_test | 252.3 |
| tcp | 38.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 63 | 32 | 31 | 50.8% |
| hysteria2 | 23 | 18 | 5 | 78.3% |
| shadowsocks | 159 | 142 | 17 | 89.3% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 33 | 25 | 8 | 75.8% |
| vless | 357 | 235 | 122 | 65.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 53 |
| 204:ProxyError | 28 |
| cn-block:TimeoutError | 21 |
| speed:ClientOSError | 16 |
| geo:TimeoutError | 16 |
| 204:TimeoutError | 14 |
| 204:ProxyConnectionError | 12 |
| cn-block:ClientOSError | 7 |
| speed:TimeoutError | 7 |
| 204:ClientOSError | 6 |
| geo:ProxyError | 3 |
| speed:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5480 |
| ConnectionRefusedError | 883 |
| gaierror | 395 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.92 | prefer | 287 | 0.857 | 1636 |
| mheidari-all | 0.747 | prefer | 82 | 0.671 | 15628 |
| Surfboard-tg-mixed | 0.734 | prefer | 128 | 0.656 | 7232 |
| ermaozi | 0.591 | observe | 52 | 0.577 | 434 |
| DeltaKronecker-all | 0.547 | observe | 73 | 0.466 | 5970 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Surfboard-tg-vless | 0.287 | observe | 2 | 0.5 | 5899 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4793 |
| Epodonios-all | 0.255 | observe | 0 | None | 7695 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.23 | 12 | 0.25 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.25 | 3 | 9 | 12 |
| DeltaKronecker-all | 0.466 | 34 | 39 | 73 |
| Surfboard-tg-vless | 0.5 | 1 | 1 | 2 |
| ermaozi | 0.577 | 30 | 22 | 52 |
| Surfboard-tg-mixed | 0.656 | 84 | 44 | 128 |
| mheidari-all | 0.671 | 55 | 27 | 82 |
| Au1rxx-base64 | 0.857 | 246 | 41 | 287 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15628 | yes | 6.25 | 0 |
| SoliSpirit-all | 8653 | yes | 1.95 | 0 |
| Epodonios-all | 7695 | yes | 3.52 | 0 |
| Surfboard-tg-mixed | 7232 | yes | 4.64 | 0 |
| barry-far-vless | 6084 | yes | 0.79 | 0 |
| DeltaKronecker-all | 5970 | yes | 5.52 | 0 |
| Surfboard-tg-vless | 5899 | yes | 4.42 | 0 |
| 10ium-ScrapeCategorize-Vless | 4793 | yes | 1.0 | 0 |
| mahdibland-V2RayAggregator | 4207 | yes | 3.26 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.08 | 0 |

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
| geo | 72 |
| 204 | 60 |
| cn-block | 29 |
| speed | 24 |
