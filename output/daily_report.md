# AutoNodes Daily Report

Generated at: 2026-06-18 20:40:04

## Summary

| Metric | Value |
| --- | --- |
| Health status | warning |
| Health ok | True |
| Sources healthy | 106/107 |
| Cleanup disable/downweight | 0/0 |
| Cleanup prefer/observe | 4/103 |
| Raw nodes | 69799 |
| Dedup nodes | 21997 |
| TCP ok | 659 |
| Real ok | 529 |
| Verified output | 300 |
| Global output | 300 |
| All output | 21997 |
| All output mode | full |

## Stage Durations

| Stage | Seconds |
| --- | --- |
| fetch | 4.0 |
| generate | 61.7 |
| geo | 1.3 |
| probe | 98.9 |
| real_test | 165.2 |
| tcp | 65.0 |

## Protocol Pass Rate

| Protocol | Tested | Passed | Failed | Pass Rate |
| --- | --- | --- | --- | --- |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 118 | 99 | 19 | 83.9% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 66 | 28 | 38 | 42.4% |
| vless | 440 | 367 | 73 | 83.4% |
| vmess | 6 | 6 | 0 | 100.0% |

## Main Real-Test Errors

| Error | Count |
| --- | --- |
| 204:TimeoutError | 34 |
| speed:ClientOSError | 25 |
| cn-block:TimeoutError | 19 |
| 204:ProxyError | 13 |
| geo:TimeoutError | 12 |
| geo:ClientOSError | 9 |
| speed:TimeoutError | 8 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 2 |
| speed:ProxyError | 1 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP Precheck Errors

| Error | Count |
| --- | --- |
| TimeoutError | 3474 |
| ConnectionRefusedError | 650 |
| gaierror | 333 |
| OSError | 62 |

## Best Sources By Score

| Source | Score | Recommendation | Tested | Pass Rate | Parsed |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.966 | prefer | 25 | 1.0 | 73 |
| Surfboard-tg-mixed | 0.921 | prefer | 300 | 0.843 | 4575 |
| Au1rxx-base64 | 0.898 | prefer | 73 | 0.904 | 111 |
| mheidari-all | 0.825 | prefer | 202 | 0.748 | 14225 |
| DeltaKronecker-all | 0.639 | observe | 57 | 0.561 | 7112 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4494 |
| Epodonios-all | 0.255 | observe | 0 | None | 6153 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6239 |

## Sources Needing Attention

| Source | Score | Recommendation | Tested | Pass Rate | Dead | Parsed |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 7 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |
| tg-ConfigWireguard | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-ISVvpn | 0.175 | observe | 0 | None | 0 | 8 |

## Worst Sources By Real-Test Pass Rate

| Source | Pass Rate | Passed | Failed | Tested |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.561 | 32 | 25 | 57 |
| mheidari-all | 0.748 | 151 | 51 | 202 |
| Surfboard-tg-mixed | 0.843 | 253 | 47 | 300 |
| Au1rxx-base64 | 0.904 | 66 | 7 | 73 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 25 | 0 | 25 |

## Top Sources By Parsed Nodes

| Source | Nodes | OK | Duration | Consecutive Dead |
| --- | --- | --- | --- | --- |
| mheidari-all | 14225 | yes | 2.96 | 0 |
| DeltaKronecker-all | 7112 | yes | 2.43 | 0 |
| SoliSpirit-all | 6239 | yes | 1.74 | 0 |
| Epodonios-all | 6153 | yes | 1.17 | 0 |
| mahdibland-V2RayAggregator | 4615 | yes | 0.92 | 0 |
| Surfboard-tg-mixed | 4575 | yes | 2.38 | 0 |
| 10ium-ScrapeCategorize-Vless | 4494 | yes | 1.41 | 0 |
| barry-far-vless | 4076 | yes | 1.07 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.2 | 0 |
| Surfboard-tg-vless | 3625 | yes | 1.29 | 0 |

## Trend Alerts

No trend alerts.

## Health Alerts

### Real-test error alerts
| Error | Count |
| --- | --- |
| 204 | 52 |
| speed | 34 |
| geo | 22 |
| cn-block | 22 |
