# Plugins for c-lightning emulating some LND (lncli) commands

[![tippin.me](https://badgen.net/badge/%E2%9A%A1%EF%B8%8Ftippin.me/@kristapsk/F0918E)](https://tippin.me/@kristapsk)

**I'm no longer maintainging this, use [cln-scripts](https://github.com/kristapsk/cln-scripts) instead!**

This is a collection of some plugins for [c-lightning](https://github.com/ElementsProject/lightning) emulating some of the commands of [LND (lncli)](https://github.com/LightningNetwork/lnd).

| name                                                                    | description                                                                      |
| ------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| [channelbalance](https://github.com/kristapsk/lightning-channelbalance) | Returns the sum of the total available channel balance across all open channels. |
| [feereport](https://github.com/kristapsk/lightning-feereport/)          | Returns the current fee policies of all active channels.                         |
| [walletbalance](https://github.com/kristapsk/lightning-walletbalance)   | Compute and display the wallet's current balance.                                |

If you have written other plugins emulating LND commands, feel free to submit a PR by adding your plugin as a submodule.

