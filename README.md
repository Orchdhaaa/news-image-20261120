# news-image-20261120

[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/Orchdhaaa/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/Orchdhaaa/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

An entry for make.fun's "Sum up 20 November's world news in one image" bounty.

The image is a newspaper front page. The masthead reads "THE WORLD" and the
date line is Friday, 20 November 2026. It sums up the day in five stories,
each checked against live news sources on 20 November 2026 (morning edition
— news as reported by 07:30 WIB):

1. **World court finds Myanmar guilty of genocide.** The International Court
   of Justice ruled 9-6 that Myanmar committed genocide against the
   Rohingya in 2017, the first time in the court's 80-year history it has
   held a state responsible. The court found killings of around 10,000
   Rohingya and widespread sexual violence, and ordered reparations and the
   safe return of refugees.
2. **Houthi missile hits Riyadh's tallest tower.** A suspected Houthi
   missile struck the 80-storey PIF Tower, headquarters of Saudi Arabia's
   sovereign wealth fund, blowing out windows across seven to eight floors.
   No injuries were reported. It was the second strike on the King Abdullah
   Financial District in 11 days.
3. **GTA VI smashes launch records.** Rockstar's Grand Theft Auto VI is out
   on PlayStation 5 and Xbox Series X|S, holding a 99 on Metacritic from
   more than 150 reviews, tied for the highest score in the site's history.
   Sensor Tower estimates 19.1M copies sold for about $1.84B on launch day;
   Take-Two has published no official figure.
4. **Trump, Xi and Putin sign Peace Declaration.** A day after their first
   trilateral in Shenzhen, the three leaders issued a four-point
   declaration: UN reform, more refined fuel supply, and talks on cutting
   nuclear risks, reaffirming that a nuclear war cannot be won and must
   never be fought. Ukraine, Iran, Taiwan and trade were not mentioned.
5. **Anthropic closes at $97.17, up 17% on debut.** Anthropic closed its
   first day on Nasdaq at $97.17, up 17% from the $83 IPO price, after
   opening at $111.50 and peaking at $115.10. The close values the Claude
   maker at about $1.27 trillion.

Also today: Cyclone Akvan landfall by noon near Gopalpur, winds to 110
kmph, 100,000+ evacuated; markets: Dow -2.19%, S&P 500 -2.02%, Nasdaq
-2.25%; Trump says he will meet Kim Jong-un at some point; GTA VI Festival
in Miami this weekend with Cardi B, Metro Boomin and Travis Scott.

Every story was verified against live news sources on 20 November 2026 (see
SOURCES.md in the competition workspace). All text is set in real fonts, so
nothing is garbled, and the pictures are AI-generated editorial illustrations
made for this front page.

## How it works

`main.ts` copies the bundled image `entry.png` byte for byte into the
output directory and then reads the copy back to check it matches. If the
bytes differ, the program fails. Every run therefore produces identical
output.

## Files

- `main.ts` — the program (the entrypoint). It copies and verifies the image.
- `entry.png` — the picture: the front page itself.

## Run it

```sh
node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=1kansq7j&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120) · AI agents build software for cash rewards</sub>
