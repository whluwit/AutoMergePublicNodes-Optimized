# AutoNodes 每日报告

生成时间：2026-09-01 03:19:17

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 79254 |
| 去重后节点数 | 22371 |
| TCP 可达数 | 3000 |
| 真测通过数 | 737 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22371 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 26.7 |
| geo | 1.2 |
| probe | 85.2 |
| real_test | 137.7 |
| tcp | 35.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 27 | 26 | 1 | 96.3% |
| shadowsocks | 175 | 168 | 7 | 96.0% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 70 | 43 | 27 | 61.4% |
| vless | 648 | 474 | 174 | 73.1% |
| vmess | 3 | 1 | 2 | 33.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 57 |
| geo:ClientOSError | 42 |
| speed:TimeoutError | 42 |
| speed:ClientOSError | 16 |
| 204:TimeoutError | 16 |
| cn-block:ClientOSError | 11 |
| cn-block:TimeoutError | 9 |
| 204:ProxyConnectionError | 6 |
| 204:ProxyError | 6 |
| 204:ClientOSError | 4 |
| speed:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4809 |
| ConnectionRefusedError | 923 |
| gaierror | 364 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.988 | prefer | 286 | 0.944 | 1183 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.841 | prefer | 266 | 0.763 | 6997 |
| mheidari-all | 0.837 | prefer | 274 | 0.759 | 15162 |
| DeltaKronecker-all | 0.427 | observe | 96 | 0.344 | 5904 |
| Epodonios-all | 0.255 | observe | 0 | None | 7436 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7826 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5908 |
| barry-far-vless | 0.255 | observe | 0 | None | 6067 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.344 | 33 | 63 | 96 |
| mheidari-all | 0.759 | 208 | 66 | 274 |
| Surfboard-tg-mixed | 0.763 | 203 | 63 | 266 |
| Au1rxx-base64 | 0.944 | 270 | 16 | 286 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15162 | yes | 4.5 | 0 |
| SoliSpirit-all | 7826 | yes | 3.87 | 0 |
| Epodonios-all | 7436 | yes | 2.66 | 0 |
| Surfboard-tg-mixed | 6997 | yes | 3.54 | 0 |
| barry-far-vless | 6067 | yes | 2.87 | 0 |
| Surfboard-tg-vless | 5908 | yes | 2.99 | 0 |
| DeltaKronecker-all | 5904 | yes | 4.81 | 0 |
| 10ium-ScrapeCategorize-Vless | 4657 | yes | 2.34 | 0 |
| mahdibland-V2RayAggregator | 4025 | yes | 0.14 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.42 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 100 |
| speed | 60 |
| 204 | 32 |
| cn-block | 21 |
