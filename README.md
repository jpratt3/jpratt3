## Jordan Pratt

Full stack engineer and insurance brokerage operations professional building production Python systems to automate workflows at Marsh.

I manage end to end client renewals at the largest commercial insurance brokerage in the world. This industry is ripe for automation: each year the same tasks need to be performed at roughly the same time. Within my Marsh workflow, I am able to complete manual tasks that used to take upwards of half an hour in seconds or minutes. With the rise of agentic SWE tools such as Claude Code, Codex, Cursor, etc., I believe the best person to build these automations out is no longer a dev that is several steps removed from the workflow, but rather the person who actually does the "thing".


### Projects

**[Options-MM-Minigame](https://github.com/jpratt3/Options-MM-Minigame)**: Options
market-taking simulator. Black–Scholes pricing with closed-form Greeks, an implied-vol
surface with strike smile and term structure, and four bot market makers quoting against
you. Scores edge capture and decision quality separately from P&L - you can have a lucky, profitable
session with bad quoting.
<br>`JavaScript` · `Black–Scholes` · `zero dependencies`

**[ESPNvsVegas-ADP](https://github.com/jpratt3/ESPNvsVegas-ADP)**: Prices fantasy
football players off sportsbook lines instead of arbitrary app rankings. Pulls season-long props
from DraftKings, Pinnacle, and Bovada, takes the median where books overlap, converts to
implied fantasy points under your scoring, and surfaces where the betting market
disagrees with ESPN's ADP. Re-centers on each position's startable median, since ESPN
runs 25–45 points higher thank the books across the board, the gap is bias rather than signal.
<br>`Python` · `FastAPI` · `multi-source aggregation` · `entity resolution`

**[Budgeting-App](https://github.com/jpratt3/Budgeting-App)**: Budgeting
dashboard connected to real bank & credit card data via Plaid's API. An ordered classification ladder where the ordering is
load-bearing and tested, recurring-charge detection from 12 months of history, internal
transfer and card-payment netting, and a spending review queue that compounds regretted
purchases forward.
<br>`Node` · `Express` · `SQLite` · `CI on 3 Node versions`

### Stack

`Python` `JavaScript` `SQLite` `FastAPI` `Express` `pandas` `NumPy`
