# AutoNodes 每日报告

生成时间：2026-09-03 02:45:20

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83179 |
| 去重后节点数 | 23551 |
| TCP 可达数 | 3000 |
| 真测通过数 | 739 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23551 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| generate | 33.3 |
| geo | 1.4 |
| probe | 85.7 |
| real_test | 156.6 |
| tcp | 37.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 18 | 18 | 0 | 100.0% |
| shadowsocks | 180 | 173 | 7 | 96.1% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 75 | 44 | 31 | 58.7% |
| vless | 777 | 475 | 302 | 61.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 140 |
| speed:ClientOSError | 62 |
| speed:TimeoutError | 61 |
| geo:ClientOSError | 36 |
| cn-block:TimeoutError | 17 |
| 204:TimeoutError | 8 |
| cn-block:ClientOSError | 6 |
| 204:ProxyError | 5 |
| 204:ClientOSError | 3 |
| 204:ProxyConnectionError | 2 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4592 |
| ConnectionRefusedError | 900 |
| gaierror | 339 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.987 | prefer | 364 | 0.918 | 1782 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.837 | prefer | 237 | 0.759 | 7117 |
| DeltaKronecker-all | 0.543 | observe | 52 | 0.462 | 7295 |
| mheidari-all | 0.52 | observe | 400 | 0.44 | 16261 |
| tg-oneclickvpnkeys | 0.316 | observe | 2 | 1.0 | 131 |
| Epodonios-all | 0.255 | observe | 0 | None | 7558 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7726 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5933 |

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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.44 | 176 | 224 | 400 |
| DeltaKronecker-all | 0.462 | 24 | 28 | 52 |
| Surfboard-tg-mixed | 0.759 | 180 | 57 | 237 |
| Au1rxx-base64 | 0.918 | 334 | 30 | 364 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16261 | yes | 4.05 | 0 |
| SoliSpirit-all | 7726 | yes | 4.13 | 0 |
| Epodonios-all | 7558 | yes | 4.3 | 0 |
| DeltaKronecker-all | 7295 | yes | 4.9 | 0 |
| Surfboard-tg-mixed | 7117 | yes | 3.68 | 0 |
| barry-far-vless | 6145 | yes | 2.69 | 0 |
| Surfboard-tg-vless | 5933 | yes | 3.0 | 0 |
| 10ium-ScrapeCategorize-Vless | 4765 | yes | 2.94 | 0 |
| mahdibland-V2RayAggregator | 4066 | yes | 0.18 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.76 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 176 |
| speed | 124 |
| cn-block | 24 |
| 204 | 18 |
