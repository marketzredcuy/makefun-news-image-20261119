# news-image-20261119 — Thursday 19 November 2026

A classic newspaper front page summing up the world's news of
Thursday 19 November 2026: **35 stories, 6 continents, one day**.

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/marketzredcuy/makefun-news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/marketzredcuy/makefun-news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

`main.py` copies the pre-composed `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png` and verifies size, format and
dimensions (at most 1 MiB and 1024x1024, and square).

## Stories

Twelve main stories, each illustrated with its own flat icon:

1. The world court finds Myanmar committed genocide against the Rohingya.
2. Trump, Putin and Xi hold their first trilateral summit in Shenzhen.
3. Ukraine hits the Crimean Bridge for a third time in four days.
4. Iran widens its Gulf attacks; two tankers hit mines in Hormuz.
5. Israeli tanks cross the Gaza Yellow Line.
6. Anthropic shares soar 34% on their stock market debut.
7. Wall Street slides for a fifth straight day.
8. The Senate rejects the Iran war-powers resolution, 51-48.
9. Denmark backs the Greenland defence deal, 109-0.
10. Ethiopia and Eritrea mass troops along their border.
11. The US and Venezuela sign a military cooperation deal.
12. Fiji declares a state of disaster over El Niño.

Twenty-three more stories fill the "ALSO ON THURSDAY" list: the Haiti
raid, Bangladesh turmoil, COP31, the EU's €45 billion Ukraine loan,
North Korea's uranium enrichment, Russian bombers in Vietnam,
Ukrainian strikes on Russian refining, Trump and Vance, Musk, Islam
becoming the largest religion, children in conflict zones, the Gaza
peace plan rating, Indonesia's asset-forfeiture bill, the Senegal boat
capsize, the Pete Rose pardon, Sanders ruling out 2028, the GTA 6
release, Bitcoin, Nvidia, the FAA ground stop, the UK-Norway naval
deal, Serbia's speaker, and Voyager 1 reaching one light-day.

## Design

The front page follows the classic broadsheet: a globe icon and the
"THE DAY IN WORLD NEWS" masthead, a 4x3 grid of twelve illustrated
story cards with numbered tags and category ribbons, a "WHERE IT
HAPPENED" world map with numbered dots marking where each main story
happened (the map is a real Natural Earth 110m land silhouette with
the dots placed at the true locations), a three-column "ALSO" list,
and a sources line at the bottom. Every headline and date was checked
against real reporting from Thursday 19 November 2026.

## How the image was made

The page was rendered from an HTML layout (build_newspaper.py) and
screenshotted at exactly 1024x1024, instead of using an AI image
generator. AI image generators render newspaper text unreliably: every
generation we tried had garbled words, duplicated numbers, merged
lines or missing items. The HTML render has exact text — every word,
number and date is correct, with no typos, no duplicated stories and
no missing numbers. The map dots sit on the true locations; clustered
dots are nudged a few pixels apart so their circles do not hide each
other, which is standard practice for clustered map points.
