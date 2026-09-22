# AutoNodes 每日报告

生成时间：2026-09-22 11:01:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 91067 |
| 去重后节点数 | 25164 |
| TCP 可达数 | 3000 |
| 真测通过数 | 445 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25164 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| generate | 87.8 |
| geo | 1.4 |
| probe | 280.0 |
| real_test | 214.0 |
| tcp | 42.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 46 | 29 | 17 | 63.0% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 157 | 150 | 7 | 95.5% |
| socks | 5 | 1 | 4 | 20.0% |
| trojan | 18 | 5 | 13 | 27.8% |
| vless | 480 | 242 | 238 | 50.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 66 |
| cn-block:ClientOSError | 65 |
| speed:ClientOSError | 33 |
| 204:TimeoutError | 32 |
| geo:TimeoutError | 24 |
| 204:ProxyError | 21 |
| cn-block:TimeoutError | 17 |
| speed:TimeoutError | 11 |
| 204:ProxyConnectionError | 4 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5670 |
| ConnectionRefusedError | 914 |
| gaierror | 358 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.958 | prefer | 288 | 0.896 | 1630 |
| ermaozi | 0.651 | observe | 42 | 0.643 | 369 |
| Surfboard-tg-mixed | 0.646 | observe | 171 | 0.567 | 7043 |
| DeltaKronecker-all | 0.402 | observe | 19 | 0.316 | 6324 |
| mheidari-all | 0.36 | observe | 198 | 0.278 | 19835 |
| ermaozi-get_subscribe | 0.256 | observe | 4 | 0.5 | 393 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4915 |
| Epodonios-all | 0.255 | observe | 0 | None | 7495 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8686 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.278 | 55 | 143 | 198 |
| DeltaKronecker-all | 0.316 | 6 | 13 | 19 |
| ermaozi-get_subscribe | 0.5 | 2 | 2 | 4 |
| Surfboard-tg-mixed | 0.567 | 97 | 74 | 171 |
| ermaozi | 0.643 | 27 | 15 | 42 |
| Au1rxx-base64 | 0.896 | 258 | 30 | 288 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19835 | yes | 5.54 | 0 |
| SoliSpirit-all | 8686 | yes | 2.9 | 0 |
| Epodonios-all | 7495 | yes | 3.37 | 0 |
| Surfboard-tg-mixed | 7043 | yes | 3.96 | 0 |
| DeltaKronecker-all | 6324 | yes | 5.88 | 0 |
| barry-far-vless | 5817 | yes | 1.38 | 0 |
| Surfboard-tg-vless | 5601 | yes | 3.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 4915 | yes | 1.19 | 0 |
| mahdibland-V2RayAggregator | 4344 | yes | 3.08 | 0 |
| xiaoji235-airport-v2ray-all | 4242 | yes | 2.07 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 90 |
| cn-block | 84 |
| 204 | 61 |
| speed | 45 |
