# AutoNodes 每日报告

生成时间：2026-09-04 10:31:48

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 83985 |
| 去重后节点数 | 23373 |
| TCP 可达数 | 3000 |
| 真测通过数 | 615 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23373 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 40.9 |
| geo | 1.5 |
| probe | 88.1 |
| real_test | 134.9 |
| tcp | 37.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 27 | 27 | 0 | 100.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 163 | 152 | 11 | 93.3% |
| socks | 14 | 9 | 5 | 64.3% |
| trojan | 55 | 34 | 21 | 61.8% |
| vless | 466 | 372 | 94 | 79.8% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:TimeoutError | 28 |
| 204:TimeoutError | 21 |
| geo:TimeoutError | 19 |
| geo:ClientOSError | 18 |
| cn-block:TimeoutError | 17 |
| cn-block:ClientOSError | 10 |
| speed:ClientOSError | 7 |
| 204:ClientOSError | 6 |
| 204:ProxyError | 4 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5372 |
| ConnectionRefusedError | 886 |
| gaierror | 311 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Au1rxx-base64 | 0.964 | prefer | 367 | 0.896 | 1736 |
| mheidari-all | 0.828 | prefer | 145 | 0.752 | 15923 |
| Surfboard-tg-mixed | 0.82 | prefer | 167 | 0.743 | 7319 |
| DeltaKronecker-all | 0.747 | prefer | 37 | 0.676 | 7089 |
| tg-oneclickvpnkeys | 0.443 | observe | 5 | 1.0 | 102 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4810 |
| Epodonios-all | 0.255 | observe | 0 | None | 7763 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7993 |

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
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.676 | 25 | 12 | 37 |
| Surfboard-tg-mixed | 0.743 | 124 | 43 | 167 |
| mheidari-all | 0.752 | 109 | 36 | 145 |
| Au1rxx-base64 | 0.896 | 329 | 38 | 367 |
| tg-oneclickvpnkeys | 1.0 | 5 | 0 | 5 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15923 | yes | 5.01 | 0 |
| SoliSpirit-all | 7993 | yes | 4.41 | 0 |
| Epodonios-all | 7763 | yes | 3.45 | 0 |
| Surfboard-tg-mixed | 7319 | yes | 3.7 | 0 |
| DeltaKronecker-all | 7089 | yes | 5.73 | 0 |
| barry-far-vless | 6426 | yes | 3.03 | 0 |
| Surfboard-tg-vless | 6206 | yes | 4.23 | 0 |
| 10ium-ScrapeCategorize-Vless | 4810 | yes | 4.37 | 0 |
| mahdibland-V2RayAggregator | 4123 | yes | 1.67 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 4.46 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 37 |
| speed | 35 |
| 204 | 31 |
| cn-block | 29 |
