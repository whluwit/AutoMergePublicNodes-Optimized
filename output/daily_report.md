# AutoNodes 每日报告

生成时间：2026-09-07 21:08:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 6/101 |
| 原始节点数 | 90678 |
| 去重后节点数 | 25159 |
| TCP 可达数 | 3000 |
| 真测通过数 | 569 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25159 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 42.2 |
| geo | 1.5 |
| probe | 88.1 |
| real_test | 142.1 |
| tcp | 41.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 4 | 1 | 80.0% |
| http | 24 | 24 | 0 | 100.0% |
| hysteria2 | 34 | 33 | 1 | 97.1% |
| shadowsocks | 150 | 137 | 13 | 91.3% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 33 | 20 | 13 | 60.6% |
| vless | 420 | 347 | 73 | 82.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 26 |
| cn-block:TimeoutError | 16 |
| geo:ClientOSError | 13 |
| cn-block:ClientOSError | 9 |
| speed:ClientOSError | 9 |
| speed:TimeoutError | 9 |
| 204:ProxyError | 6 |
| geo:TimeoutError | 6 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| 204:ServerDisconnectedError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5241 |
| ConnectionRefusedError | 1041 |
| gaierror | 376 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 373 | 0.941 | 1703 |
| xiaoji235-airport-v2ray-all | 0.937 | prefer | 26 | 0.885 | 5750 |
| zhangkai | 0.929 | prefer | 24 | 0.958 | 144 |
| mheidari-all | 0.848 | prefer | 93 | 0.774 | 16413 |
| DeltaKronecker-all | 0.817 | prefer | 19 | 0.789 | 6417 |
| Surfboard-tg-mixed | 0.712 | prefer | 131 | 0.634 | 7444 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4650 |
| Epodonios-all | 0.255 | observe | 0 | None | 7899 |
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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 2 | 2 |
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.634 | 83 | 48 | 131 |
| mheidari-all | 0.774 | 72 | 21 | 93 |
| DeltaKronecker-all | 0.789 | 15 | 4 | 19 |
| xiaoji235-airport-v2ray-all | 0.885 | 23 | 3 | 26 |
| Au1rxx-base64 | 0.941 | 351 | 22 | 373 |
| zhangkai | 0.958 | 23 | 1 | 24 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16413 | yes | 4.95 | 0 |
| SoliSpirit-all | 8993 | yes | 4.98 | 0 |
| Epodonios-all | 7899 | yes | 0.61 | 0 |
| Surfboard-tg-mixed | 7444 | yes | 3.96 | 0 |
| DeltaKronecker-all | 6417 | yes | 5.48 | 0 |
| barry-far-vless | 6394 | yes | 2.61 | 0 |
| Surfboard-tg-vless | 6179 | yes | 4.47 | 0 |
| 10ium-ScrapeCategorize-Vless | 4650 | yes | 3.33 | 0 |
| mahdibland-V2RayAggregator | 4218 | yes | 1.89 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 3.13 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 38 |
| cn-block | 28 |
| geo | 19 |
| speed | 18 |
