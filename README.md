<p align="center"><img src="brand/mark.png" width="220" alt=""></p>

<h1 align="center">glasspad</h1>
<p align="center"><b>a launchpad you can read.</b></p>

same curve as the pad everyone already knows. the rules are frozen the day it ships, and every change is a public diff.

- **verified build.** the program on chain is built from this code, and anyone can check the hash.
- **upgrade key burned.** nobody can change the program. not us. not anyone.
- **no admin.** no fee switch, no pause button, no authority account. the fee rate and the curve are constants in the source.
- **public diff.** a page that says exactly which functions differ from the other pad's deployed program, generated with the reconstruction's own scoring harness.
- **no wallet to watch.** every coin, trade and graduation is readable with nothing connected.

**fees, in one line:** 1.4% on every curve trade. 1% to the platform (half to the team, half buys and burns the platform coin), 0.4% to the launcher. 1 sol when a coin graduates to its raydium pool, where the lp is burned.

| repo | what |
|---|---|
| `glasspad-program` | the curve program, anchor. the one that gets the verified build |
| `glasspad-site` | glasspad.fun. static, reads only the chain |
| `glasspad-indexer` | events in, ledger out, and the burn crank anyone can run |

site: [glasspad.fun](https://glasspad.fun) · docs, every address and the diff page go live with the site.

unaudited. the code is public, the build is verified, nobody can change it. nobody has audited it either.
