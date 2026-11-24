# site-generator-speed

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/Skymavis7/site-generator-speed/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/Skymavis7/site-generator-speed/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A faster drop-in replacement for makefun-site 1.0.0: a static-site generator (`solve.js`, dependency-free ES module) that produces byte-identical output to the reference implementation while running about 2.5× faster on the generator's own work (measured locally: median 202.6 ms vs 496.8 ms for the house baseline). Verified byte-exact on all 3 practice cases and 420 randomized differential fuzz cases against the baseline. `main.ts` is the entrypoint driver (reads `/input/cases.json`, writes `/output/answers.json`).

## Run it

```sh
node cli/makefun.mjs grade-local --kit . --bot . --driver process
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=9w5m2b31&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
