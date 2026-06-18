# AutoNodes Daily Report

Generated at: 2026-06-18 04:22:16

## Summary

| Metric | Value |
| --- | --- |
| Health status | warning |
| Health ok | True |
| Sources healthy | 44/44 |
| Cleanup disable/downweight | 0/1 |
| Cleanup prefer/observe | 4/39 |
| Raw nodes | 67675 |
| Dedup nodes | 22191 |
| TCP ok | 799 |
| Real ok | 618 |
| Verified output | 300 |
| Global output | 300 |
| All output | 22191 |
| All output mode | full |

## Stage Durations

| Stage | Seconds |
| --- | --- |
| fetch | 3.2 |
| generate | 37.4 |
| geo | 1.3 |
| probe | 99.2 |
| real_test | 70.8 |
| tcp | 60.4 |

## Protocol Pass Rate

| Protocol | Tested | Passed | Failed | Pass Rate |
| --- | --- | --- | --- | --- |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 111 | 102 | 9 | 91.9% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 162 | 131 | 31 | 80.9% |
| vless | 491 | 351 | 140 | 71.5% |
| vmess | 5 | 5 | 0 | 100.0% |

## Main Real-Test Errors

| Error | Count |
| --- | --- |
| general:unknown | 130 |
| speed:ClientOSError | 23 |
| geo:TimeoutError | 9 |
| 204:ClientOSError | 6 |
| geo:ClientOSError | 2 |
| speed:TimeoutError | 2 |
| cn-block:ProxyError | 2 |
| cn-block:TimeoutError | 2 |
| 204:TimeoutError | 2 |
| 204:ProxyError | 1 |
| cn-block:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP Precheck Errors

| Error | Count |
| --- | --- |
| TimeoutError | 3093 |
| ConnectionRefusedError | 607 |
| gaierror | 331 |
| OSError | 60 |

## Best Sources By Score

| Source | Score | Recommendation | Tested | Pass Rate | Parsed |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.966 | prefer | 25 | 1.0 | 73 |
| Surfboard-tg-mixed | 0.941 | prefer | 350 | 0.863 | 4586 |
| mheidari-all | 0.837 | prefer | 216 | 0.759 | 13927 |
| Au1rxx-base64 | 0.817 | prefer | 83 | 0.819 | 126 |
| DeltaKronecker-all | 0.58 | observe | 112 | 0.5 | 7763 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| xiaoji235-airport-v2ray-all | 0.289 | observe | 1 | 1.0 | 847 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4274 |
| Epodonios-all | 0.255 | observe | 0 | None | 6401 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3977 |

## Sources Needing Attention

| Source | Score | Recommendation | Tested | Pass Rate | Dead | Parsed |
| --- | --- | --- | --- | --- | --- | --- |
| ninja-vless | 0.128 | downweight | 10 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tonykong-base64 | 0.175 | observe | 0 | None | 0 | 5 |
| tonykong-clash | 0.175 | observe | 0 | None | 0 | 5 |
| Barabama-we | 0.176 | observe | 0 | None | 0 | 23 |
| Mr8AHAL | 0.176 | observe | 0 | None | 0 | 26 |
| Pawdroid | 0.176 | observe | 0 | None | 0 | 20 |
| abc-configs-readme-latest30 | 0.176 | observe | 0 | None | 0 | 22 |
| barabama-nodefree | 0.176 | observe | 0 | None | 0 | 23 |

## Source Cleanup Suggestions

| Bucket | Source | Score | Tested | Pass Rate | Dead | Reason |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ninja-vless | 0.128 | 10 | 0.0 | 0 | low score with tested >= 5 |

## Worst Sources By Real-Test Pass Rate

| Source | Pass Rate | Passed | Failed | Tested |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 10 | 10 |
| DeltaKronecker-all | 0.5 | 56 | 56 | 112 |
| mheidari-all | 0.759 | 164 | 52 | 216 |
| Au1rxx-base64 | 0.819 | 68 | 15 | 83 |
| Surfboard-tg-mixed | 0.863 | 302 | 48 | 350 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 25 | 0 | 25 |

## Top Sources By Parsed Nodes

| Source | Nodes | OK | Duration | Consecutive Dead |
| --- | --- | --- | --- | --- |
| mheidari-all | 13927 | yes | 2.94 | 0 |
| DeltaKronecker-all | 7763 | yes | 2.8 | 0 |
| Epodonios-all | 6401 | yes | 2.19 | 0 |
| SoliSpirit-all | 5959 | yes | 2.04 | 0 |
| Surfboard-tg-mixed | 4586 | yes | 2.35 | 0 |
| mahdibland-V2RayAggregator | 4541 | yes | 1.33 | 0 |
| 10ium-ScrapeCategorize-Vless | 4274 | yes | 1.31 | 0 |
| barry-far-vless | 4240 | yes | 1.15 | 0 |
| MatinGhanbari-all-sub | 3977 | yes | 1.77 | 0 |
| Surfboard-tg-vless | 3590 | yes | 1.56 | 0 |

## Trend Alerts

No trend alerts.

## Health Alerts

### Real-test error alerts
| Error | Count |
| --- | --- |
| general | 130 |
| speed | 25 |
| geo | 12 |
| 204 | 9 |
| cn-block | 5 |
