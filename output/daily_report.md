# AutoNodes 每日报告

生成时间：2026-09-06 10:14:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 96060 |
| 去重后节点数 | 25350 |
| TCP 可达数 | 3000 |
| 真测通过数 | 548 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25350 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 44.3 |
| geo | 1.5 |
| probe | 85.7 |
| real_test | 115.7 |
| tcp | 42.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 26 | 24 | 2 | 92.3% |
| hysteria2 | 20 | 20 | 0 | 100.0% |
| shadowsocks | 166 | 147 | 19 | 88.6% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 40 | 34 | 6 | 85.0% |
| vless | 386 | 319 | 67 | 82.6% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 23 |
| cn-block:ClientOSError | 17 |
| geo:ClientOSError | 13 |
| 204:TimeoutError | 12 |
| speed:ClientOSError | 7 |
| 204:ProxyError | 6 |
| speed:TimeoutError | 6 |
| geo:TimeoutError | 3 |
| 204:ProxyConnectionError | 2 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5738 |
| ConnectionRefusedError | 1017 |
| gaierror | 343 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.965 | prefer | 366 | 0.896 | 1781 |
| zhangkai | 0.886 | prefer | 23 | 0.913 | 144 |
| Surfboard-tg-mixed | 0.88 | prefer | 153 | 0.804 | 7318 |
| mheidari-all | 0.818 | prefer | 78 | 0.744 | 22388 |
| DeltaKronecker-all | 0.745 | prefer | 17 | 0.765 | 5856 |
| tg-oneclickvpnkeys | 0.363 | observe | 3 | 1.0 | 133 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6965 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4791 |
| Epodonios-all | 0.255 | observe | 0 | None | 7771 |

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
| mheidari-all | 0.744 | 58 | 20 | 78 |
| DeltaKronecker-all | 0.765 | 13 | 4 | 17 |
| Surfboard-tg-mixed | 0.804 | 123 | 30 | 153 |
| Au1rxx-base64 | 0.896 | 328 | 38 | 366 |
| zhangkai | 0.913 | 21 | 2 | 23 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22388 | yes | 5.98 | 0 |
| SoliSpirit-all | 8223 | yes | 1.87 | 0 |
| Epodonios-all | 7771 | yes | 6.33 | 0 |
| Surfboard-tg-mixed | 7318 | yes | 4.62 | 0 |
| xiaoji235-airport-v2ray-all | 6965 | yes | 3.7 | 0 |
| barry-far-vless | 6223 | yes | 2.57 | 0 |
| Surfboard-tg-vless | 6005 | yes | 4.35 | 0 |
| DeltaKronecker-all | 5856 | yes | 7.06 | 0 |
| 10ium-ScrapeCategorize-Vless | 4791 | yes | 2.28 | 0 |
| mahdibland-V2RayAggregator | 4111 | yes | 0.59 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 42 |
| 204 | 22 |
| geo | 18 |
| speed | 13 |
