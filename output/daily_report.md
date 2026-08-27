# AutoNodes 每日报告

生成时间：2026-08-27 06:58:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 88858 |
| 去重后节点数 | 24427 |
| TCP 可达数 | 3000 |
| 真测通过数 | 510 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24427 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 36.4 |
| geo | 1.5 |
| probe | 49.5 |
| real_test | 108.7 |
| tcp | 39.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 189 | 174 | 15 | 92.1% |
| socks | 5 | 1 | 4 | 20.0% |
| trojan | 45 | 36 | 9 | 80.0% |
| vless | 362 | 253 | 109 | 69.9% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 43 |
| geo:ClientOSError | 21 |
| speed:TimeoutError | 17 |
| 204:TimeoutError | 15 |
| speed:ClientOSError | 14 |
| cn-block:TimeoutError | 11 |
| cn-block:ClientOSError | 7 |
| 204:ProxyError | 5 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5386 |
| ConnectionRefusedError | 944 |
| gaierror | 370 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.994 | prefer | 329 | 0.93 | 1668 |
| zhangkai | 0.929 | prefer | 24 | 0.958 | 144 |
| Surfboard-tg-mixed | 0.862 | prefer | 154 | 0.786 | 6600 |
| mheidari-all | 0.523 | observe | 104 | 0.442 | 19260 |
| DeltaKronecker-all | 0.462 | observe | 32 | 0.375 | 6107 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4825 |
| Epodonios-all | 0.255 | observe | 0 | None | 7097 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.375 | 12 | 20 | 32 |
| mheidari-all | 0.442 | 46 | 58 | 104 |
| Surfboard-tg-mixed | 0.786 | 121 | 33 | 154 |
| Au1rxx-base64 | 0.93 | 306 | 23 | 329 |
| zhangkai | 0.958 | 23 | 1 | 24 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19260 | yes | 5.56 | 0 |
| SoliSpirit-all | 7131 | yes | 4.13 | 0 |
| Epodonios-all | 7097 | yes | 2.95 | 0 |
| Surfboard-tg-mixed | 6600 | yes | 4.15 | 0 |
| DeltaKronecker-all | 6107 | yes | 6.22 | 0 |
| barry-far-vless | 5696 | yes | 3.21 | 0 |
| xiaoji235-airport-v2ray-all | 5418 | yes | 2.26 | 0 |
| Surfboard-tg-vless | 5353 | yes | 3.49 | 0 |
| 10ium-ScrapeCategorize-Vless | 4825 | yes | 3.46 | 0 |
| mahdibland-V2RayAggregator | 4011 | yes | 0.33 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 64 |
| speed | 32 |
| 204 | 22 |
| cn-block | 21 |
