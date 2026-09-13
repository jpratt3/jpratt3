## Jordan Pratt

Risk and insurance background at Marsh McLennan.

Underwriting and market making rhyme. Both price an uncertain future payout, collect a
spread for warehousing the risk, and live or die on whether the edge survives the
variance. Most of what I build is an attempt to make that edge legible: take a market
that quotes a number, work out what the number implies, and find where two markets
disagree.

### Projects

**[Options-MM-Minigame](https://github.com/jpratt3/Options-MM-Minigame)** — Options
market-making simulator. Black–Scholes pricing with closed-form Greeks, an implied-vol
surface with strike smile and term structure, and four bot market makers quoting against
you. Scores edge capture and decision quality separately from P&L, because a profitable
session with bad quoting is a favorable tape, not a repeatable process.
<br>`JavaScript` · `Black–Scholes` · `zero dependencies`

**[ESPNvsVegas-ADP](https://github.com/jpratt3/ESPNvsVegas-ADP)** — Prices fantasy
football players off sportsbook lines instead of app rankings. Pulls season-long props
from DraftKings, Pinnacle, and Bovada, takes the median where books overlap, converts to
implied fantasy points under your scoring, and surfaces where the betting market
disagrees with ESPN's ADP. Re-centers on each position's startable median, since ESPN
runs 25–45 points hot across the board and the raw gap is bias rather than signal.
<br>`Python` · `FastAPI` · `multi-source aggregation` · `entity resolution`

**[Budgeting-App](https://github.com/jpratt3/Budgeting-App)** — Local-first budgeting
dashboard over the Plaid API. An ordered classification ladder where the ordering is
load-bearing and tested, recurring-charge detection from 12 months of history, internal
transfer and card-payment netting, and a spending review queue that compounds regretted
purchases forward.
<br>`Node` · `Express` · `SQLite` · `CI on 3 Node versions`

### Currently

Options pricing and volatility surface modeling · market microstructure · quantifying
edge in games with known priors. Poker and Catan on the side, which is the same habit
with worse expected value.

### Stack

`Python` `JavaScript` `SQLite` `FastAPI` `Express` `pandas` `NumPy`
