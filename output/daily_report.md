# AutoNodes 每日报告

生成时间：2026-09-02 02:38:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 82084 |
| 去重后节点数 | 23584 |
| TCP 可达数 | 3000 |
| 真测通过数 | 617 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23584 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 28.2 |
| geo | 1.4 |
| probe | 81.6 |
| real_test | 167.8 |
| tcp | 38.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 102 | 99 | 3 | 97.1% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 67 | 41 | 26 | 61.2% |
| vless | 869 | 434 | 435 | 49.9% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 218 |
| geo:ClientOSError | 76 |
| speed:ClientOSError | 63 |
| speed:TimeoutError | 55 |
| cn-block:TimeoutError | 27 |
| 204:TimeoutError | 11 |
| cn-block:ClientOSError | 6 |
| 204:ProxyError | 6 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42554: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5377 |
| ConnectionRefusedError | 889 |
| gaierror | 319 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.984 | prefer | 415 | 0.916 | 1750 |
| zhangkai | 0.929 | prefer | 24 | 0.958 | 144 |
| mheidari-all | 0.616 | observe | 136 | 0.537 | 15712 |
| Surfboard-tg-mixed | 0.556 | observe | 12 | 0.667 | 6990 |
| DeltaKronecker-all | 0.348 | observe | 495 | 0.267 | 7294 |
| ninja-vless | 0.327 | observe | 1 | 1.0 | 1791 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4708 |
| Epodonios-all | 0.255 | observe | 0 | None | 7407 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7632 |

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
| DeltaKronecker-all | 0.267 | 132 | 363 | 495 |
| mheidari-all | 0.537 | 73 | 63 | 136 |
| Surfboard-tg-mixed | 0.667 | 8 | 4 | 12 |
| Au1rxx-base64 | 0.916 | 380 | 35 | 415 |
| zhangkai | 0.958 | 23 | 1 | 24 |
| ninja-vless | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15712 | yes | 3.71 | 0 |
| SoliSpirit-all | 7632 | yes | 3.51 | 0 |
| Epodonios-all | 7407 | yes | 3.9 | 0 |
| DeltaKronecker-all | 7294 | yes | 3.89 | 0 |
| Surfboard-tg-mixed | 6990 | yes | 2.71 | 0 |
| barry-far-vless | 6027 | yes | 2.25 | 0 |
| Surfboard-tg-vless | 5850 | yes | 3.25 | 0 |
| 10ium-ScrapeCategorize-Vless | 4708 | yes | 2.43 | 0 |
| mahdibland-V2RayAggregator | 4159 | yes | 1.15 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.72 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 296 |
| speed | 118 |
| cn-block | 33 |
| 204 | 19 |
| sing-box exited 1 | 1 |
