# AutoNodes 每日报告

生成时间：2026-09-12 15:04:37

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 82953 |
| 去重后节点数 | 22795 |
| TCP 可达数 | 3000 |
| 真测通过数 | 399 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22795 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 80.7 |
| geo | 1.4 |
| probe | 270.5 |
| real_test | 245.3 |
| tcp | 37.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 43 | 26 | 17 | 60.5% |
| hysteria2 | 22 | 19 | 3 | 86.4% |
| shadowsocks | 126 | 114 | 12 | 90.5% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 47 | 35 | 12 | 74.5% |
| vless | 306 | 202 | 104 | 66.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 36 |
| 204:TimeoutError | 23 |
| 204:ProxyError | 18 |
| cn-block:TimeoutError | 18 |
| speed:ClientOSError | 13 |
| cn-block:ClientOSError | 11 |
| speed:TimeoutError | 11 |
| geo:TimeoutError | 9 |
| 204:ProxyConnectionError | 5 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4678 |
| ConnectionRefusedError | 871 |
| gaierror | 472 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.859 | prefer | 264 | 0.803 | 1455 |
| Surfboard-tg-mixed | 0.775 | prefer | 126 | 0.698 | 7345 |
| mheidari-all | 0.729 | prefer | 72 | 0.653 | 15620 |
| DeltaKronecker-all | 0.685 | observe | 41 | 0.61 | 5970 |
| ermaozi | 0.583 | observe | 35 | 0.571 | 393 |
| ermaozi-get_subscribe | 0.465 | observe | 7 | 0.857 | 408 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4793 |
| Epodonios-all | 0.255 | observe | 0 | None | 7743 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.571 | 20 | 15 | 35 |
| DeltaKronecker-all | 0.61 | 25 | 16 | 41 |
| mheidari-all | 0.653 | 47 | 25 | 72 |
| Surfboard-tg-mixed | 0.698 | 88 | 38 | 126 |
| Au1rxx-base64 | 0.803 | 212 | 52 | 264 |
| ermaozi-get_subscribe | 0.857 | 6 | 1 | 7 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15620 | yes | 4.92 | 0 |
| SoliSpirit-all | 8825 | yes | 2.16 | 0 |
| Epodonios-all | 7743 | yes | 3.29 | 0 |
| Surfboard-tg-mixed | 7345 | yes | 4.27 | 0 |
| barry-far-vless | 6112 | yes | 1.41 | 0 |
| DeltaKronecker-all | 5970 | yes | 5.35 | 0 |
| Surfboard-tg-vless | 5912 | yes | 3.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 4793 | yes | 0.96 | 0 |
| mahdibland-V2RayAggregator | 4207 | yes | 0.58 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.71 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 49 |
| geo | 46 |
| cn-block | 29 |
| speed | 24 |
