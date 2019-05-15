# market maker-fee chaser
deribit mm-replication (a modified version of https://github.com/deribit/deribit-api-python)

Only for hobby/educational purposes only: a copy paste project made by a non-programmer. USE THE SOFTWARE AT YOUR OWN RISK.

Always start by running a trading bot in test server and do not engage money before you understand how it works and what profit/loss you should expect.

It is strongly recommended you to have coding and Python knowledge. Do not hesitate to read the source code and understand the mechanism of this bot.

# improvements:
- additional ability to:
  a) respond to strong market movement (both of qty and price)
  b) change bid/ask based on certain parameters (equity, maintenance margin, etc)
  c) perform multi accounts task

- refresh/tidy up/improve efficiency bot code
- add eth qty (x10)
- add/improve bot code related to e mail/time/telegram
- not fully delta neutral yet (still holding significant position in one side)

# Risk management:
- Prioritise long over short (since short is a bit riskier). Short only for balancing (offsetted margin to avoid liquidation and allow higher long position)
- Focus on protecting capital instead of making transactions
- Cut loss?
- Allow risk position update by e mail/telegram

Basic premises:
- All up, will be go down. And, vice versa
- Profit is earned slowly. Rely on small but continuos 24 H transactions instead of big one time transaction



