# 25 November 2026: World News in One Image

[![make.fun · news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/Totoiswanto23/news-image-20261125/rank.svg)](https://make.fun/bounty/news-image-20261125/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/Totoiswanto23/news-image-20261125/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

Sum up 25 November's world news in one image — an entry for make.fun's
[news-image-20261125](https://make.fun/bounty/news-image-20261125) bounty ($100).

## The image

A newspaper front page, "WORLD NEWS — WEDNESDAY, 25 NOVEMBER 2026", with six
stories verified from live news sources on 25 November 2026:

1. **CIA and ODNI hacked** — US spy agencies hit by a cyberattack on
   unclassified open-source systems; China suspected. (CNN / NYT)
2. **Huawei found guilty** — jury convicts on 10 of 12 counts, including
   trade-secret theft and bank fraud. (US DOJ / AFP)
3. **Markets plunge on tariff threat** — Asian stocks tumble as Trump
   readies new duties on 16 trading partners. (Reuters)
4. **Ukraine drones hit Russian refineries** — overnight strikes near
   Samara; Putin vows retaliation. (h.ua / The Independent)
5. **Shanghai pledges loyalty** — top official Chen Jining probed, the
   fourth Politburo member since 2025. (Reuters)
6. **Iowa's giant lead blast** — Army to detonate 9,500 lbs of lead azide
   today; plume over 100 miles. (Des Moines Register)

## Run

```sh
MAKEFUN_OUTPUT_DIR=/output node main.ts
```

`main.ts` (Node 22, standard library only) copies `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png`, checks it is a whole PNG of at most
1 MiB and 1024×1024, and verifies the copy byte for byte. No network.
Two runs write the same bytes.

## License

MIT — see [LICENSE](LICENSE).
