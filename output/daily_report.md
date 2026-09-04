# AutoNodes 每日报告

生成时间：2026-09-04 20:15:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 84222 |
| 去重后节点数 | 23527 |
| TCP 可达数 | 3000 |
| 真测通过数 | 587 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23527 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 37.3 |
| geo | 1.4 |
| probe | 71.4 |
| real_test | 127.3 |
| tcp | 38.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 27 | 27 | 0 | 100.0% |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 162 | 145 | 17 | 89.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 19 | 16 | 3 | 84.2% |
| vless | 485 | 383 | 102 | 79.0% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 27 |
| geo:ClientOSError | 22 |
| 204:TimeoutError | 18 |
| cn-block:ClientOSError | 14 |
| 204:ProxyError | 12 |
| speed:TimeoutError | 10 |
| speed:ClientOSError | 9 |
| geo:TimeoutError | 8 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5302 |
| ConnectionRefusedError | 890 |
| gaierror | 337 |
| OSError | 15 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.962 | prefer | 21 | 1.0 | 144 |
| Au1rxx-base64 | 0.952 | prefer | 346 | 0.884 | 1756 |
| mheidari-all | 0.899 | prefer | 114 | 0.825 | 16096 |
| Surfboard-tg-mixed | 0.807 | prefer | 170 | 0.729 | 7342 |
| DeltaKronecker-all | 0.747 | prefer | 49 | 0.673 | 7089 |
| tg-oneclickvpnkeys | 0.554 | observe | 8 | 1.0 | 118 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 50 |
| Epodonios-all | 0.255 | observe | 0 | None | 7798 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8118 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.673 | 33 | 16 | 49 |
| Surfboard-tg-mixed | 0.729 | 124 | 46 | 170 |
| mheidari-all | 0.825 | 94 | 20 | 114 |
| Au1rxx-base64 | 0.884 | 306 | 40 | 346 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 8 | 0 | 8 |
| zhangkai | 1.0 | 21 | 0 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16096 | yes | 3.32 | 0 |
| SoliSpirit-all | 8118 | yes | 2.59 | 0 |
| Epodonios-all | 7798 | yes | 0.71 | 0 |
| Surfboard-tg-mixed | 7342 | yes | 2.54 | 0 |
| DeltaKronecker-all | 7089 | yes | 3.85 | 0 |
| barry-far-vless | 6376 | yes | 1.84 | 0 |
| Surfboard-tg-vless | 6159 | yes | 3.49 | 0 |
| 10ium-ScrapeCategorize-Vless | 4810 | yes | 1.7 | 0 |
| mahdibland-V2RayAggregator | 4095 | yes | 0.55 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.52 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 42 |
| 204 | 32 |
| geo | 31 |
| speed | 19 |
