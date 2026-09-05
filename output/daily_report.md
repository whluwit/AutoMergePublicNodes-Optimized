# AutoNodes 每日报告

生成时间：2026-09-05 02:43:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 84220 |
| 去重后节点数 | 23645 |
| TCP 可达数 | 3000 |
| 真测通过数 | 728 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23645 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 35.9 |
| geo | 1.5 |
| probe | 87.0 |
| real_test | 154.7 |
| tcp | 39.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 28 | 28 | 0 | 100.0% |
| hysteria2 | 12 | 12 | 0 | 100.0% |
| shadowsocks | 180 | 172 | 8 | 95.6% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 82 | 51 | 31 | 62.2% |
| vless | 656 | 460 | 196 | 70.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 87 |
| speed:TimeoutError | 44 |
| geo:ClientOSError | 38 |
| speed:ClientOSError | 22 |
| cn-block:TimeoutError | 17 |
| 204:TimeoutError | 10 |
| cn-block:ClientOSError | 9 |
| 204:ProxyError | 4 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5473 |
| ConnectionRefusedError | 905 |
| gaierror | 323 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 393 | 0.929 | 1887 |
| zhangkai | 0.962 | prefer | 21 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.877 | prefer | 210 | 0.8 | 7265 |
| mheidari-all | 0.686 | observe | 229 | 0.607 | 16194 |
| tg-oneclickvpnkeys | 0.554 | observe | 8 | 1.0 | 118 |
| DeltaKronecker-all | 0.35 | observe | 98 | 0.265 | 7089 |
| Epodonios-all | 0.255 | observe | 0 | None | 7727 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8088 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6067 |

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
| 10ium-ScrapeCategorize-Vless | 0.25 | 1 | 3 | 4 |
| DeltaKronecker-all | 0.265 | 26 | 72 | 98 |
| mheidari-all | 0.607 | 139 | 90 | 229 |
| Surfboard-tg-mixed | 0.8 | 168 | 42 | 210 |
| Au1rxx-base64 | 0.929 | 365 | 28 | 393 |
| tg-oneclickvpnkeys | 1.0 | 8 | 0 | 8 |
| zhangkai | 1.0 | 21 | 0 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16194 | yes | 4.47 | 0 |
| SoliSpirit-all | 8088 | yes | 5.8 | 0 |
| Epodonios-all | 7727 | yes | 5.04 | 0 |
| Surfboard-tg-mixed | 7265 | yes | 4.08 | 0 |
| DeltaKronecker-all | 7089 | yes | 5.34 | 0 |
| barry-far-vless | 6282 | yes | 0.91 | 0 |
| Surfboard-tg-vless | 6067 | yes | 4.75 | 0 |
| 10ium-ScrapeCategorize-Vless | 4810 | yes | 3.18 | 0 |
| mahdibland-V2RayAggregator | 4095 | yes | 0.18 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.7 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 126 |
| speed | 67 |
| cn-block | 26 |
| 204 | 17 |
