<p align="center">
  <a href="../../releases/latest">
    <img src="./assets/readme-banner.png" alt="Kill Economy: a shared kill-point ledger for your squad" width="100%">
  </a>
</p>

<div align="center">

# Kill Economy

</div>

<div align="center">

  Kill Economy turns your squad's house rules into a real economy. Every raid kill is a point, and you spend points on bans, loadout picks, loot rights or anything else you can agree on. Bounties, 1v1s, trades and debts are all tracked in one ledger that nobody can fudge.<br>
  Runs on Windows 10 and 11.

</div>

## Screenshots

<p align="center">
  <img src="./Screenshots/overview.png" alt="Kill Economy - Overview" width="100%">
</p>

Each game gets its own look. Points are shared across all of them, while rules, shop, bans, debts and deals stay with the game you have selected:

<p align="center">
  <img src="./Screenshots/rules.png" alt="Tarkov: olive and sand" width="32%">
  <img src="./Screenshots/theme-mk1.png" alt="MK1: charcoal, jade and gold" width="32%">
  <img src="./Screenshots/theme-valorant.png" alt="Valorant" width="32%">
</p>
<p align="center">
  <img src="./Screenshots/theme-sf6.png" alt="Street Fighter 6" width="32%">
  <img src="./Screenshots/rules-valorant.png" alt="Valorant rules" width="32%">
  <img src="./Screenshots/bans-mk1.png" alt="MK1 bans" width="32%">
</p>

| | |
|:---:|:---:|
| ![Bounties](./Screenshots/bounties.png) | ![Sektant tab](./Screenshots/bounties-sektant.png) |
| Bounty contracts | Sektant, Full and Boss tabs |
| ![Bounty settlement](./Screenshots/bounty-settlement.png) | ![Bounty prices](./Screenshots/bounty-prices.png) |
| Settlement with a live payout split | Editable bounty prices, with the written rules alongside |
| ![Trades](./Screenshots/trades.png) | ![Redemptions](./Screenshots/redemptions.png) |
| One trade book across every game | Redeem points for anything, at your price |
| ![Shop](./Screenshots/shop.png) | ![Rules](./Screenshots/rules.png) |
| Shop | Rules of engagement |
| ![Bans](./Screenshots/bans.png) | ![1v1s](./Screenshots/duels.png) |
| Bans with full history | 1v1s with locked terms |
| ![Debts and deals](./Screenshots/debts-deals.png) | ![Transactions](./Screenshots/transactions.png) |
| Debts that double when they go unpaid | Every point, every reason |
| ![League of Legends rules](./Screenshots/rules-league.png) | ![Fonts](./Screenshots/settings-fonts.png) |
| League of Legends rules, ready to apply | A different font for every part of the app |

Declare a bounty before you engage, then settle it with proof:

<p align="center">
  <img src="./Screenshots/declare-bounty.png" alt="Declaring a bounty" width="480">
</p>

## Download

Grab the latest installer from the [Releases page](../../releases/latest).

| Platform | Formats |
|----------|---------|
| Windows 10 / 11 (64-bit) | `KillEconomy-Setup.exe` (per user, no admin), standalone `KillEconomy.exe` |

Nothing else to install: no Python, no Excel, everything the app needs is bundled in. On first run you pick who you are and start a fresh ledger at zero, or import an existing ledger workbook. From then on Kill Economy updates itself straight from this page's releases (**Settings → App updates**).

## Features

- **The ledger:** shared kill-point balances for the whole squad, with an append-only history of every change and why it happened. Mistakes are reversed, never deleted. Balances can go negative, so debt is real.
- **One ledger for the whole squad (new in 3.3.0):** one PC hosts and everyone else joins with a code. Balances, rules, bounties, bans, trades and history match on every PC, and every change is saved on the host. It works on the same network, or across the internet through a VPN such as Tailscale. The host picks which of its addresses goes in the join code from a list that names each adapter. Since 3.4.1 it never picks a privacy VPN such as NordVPN, whose address other PCs cannot reach.
- **Automatic Tarkov kills:** after extraction, Kill Economy reads the RAID STATISTICS screen with Windows' built-in OCR and credits your kills once per raid. It needs three matching reads and never touches game memory.
- **Every game you play:** Tarkov, MK1, Street Fighter 6, Valorant, League of Legends and GTA 5 come built in, and Tarkov, MK1, Valorant, Street Fighter 6 and League of Legends start with their house rules. **Add Game** adds any other game, with its own theme, rules, shop and photo. A game's photo also fills the Overview banner (new in 3.4.0).
- **Rules of engagement:** your house rules as priced, editable entries for teamkills, loot theft, trolling, insurance trolling, Squad Savior (numbered rescues with a killed player, kit savior and AAR since 3.5.0), Zero to Hero, NVG usage, singing callouts and more. The BRA singing callout is in every game, including games you add (since 3.6.0). Price changes only apply going forward; anything already paid keeps the price it was paid at.
- **League of Legends rules (new in 3.6.2):** standard result (+10), high-exploit builds (+5), rage quit, smart surrender and IRL surrender awards, setup-error bonuses and the intentional wrong runes penalty, all ready for **Apply Rule**. Match objective, remakes, setup errors and next-match bans are listed as reference rules, and the full written rules sit in **Previous rules reference**.
- **Fonts your way (new in 3.7.0):** set a different font for body text, buttons, the sidebar, titles, balances, labels, table rows, table headings and reference text in **Settings → Fonts**. Type an installed font name, `google:Font Name` to pull one from [Google Fonts](https://fonts.google.com), or browse for a `.ttf` or `.otf` file. Google fonts download once and then work offline, and nothing is installed into Windows. Each PC keeps its own fonts.
- **The full written Tarkov ruleset (new in 3.2.0):** the squad's complete rulebook, word for word, sits in the Tarkov **Previous rules reference**. It covers loot claims, cultist rules, bounties, Squad Savior eligibility, 1v1s and the Kill Shop. Live prices are still whatever you've set in Rules and Shop.
- **Bounties:** declare a boss before you engage, pull in helpers, then settle with proof or a witness. The payout split works off actual boss and guard kills plus agreed support shares, in whole points with nothing lost to rounding. Outcomes include Success, Boss not found and Failure. There's also fraud clawback with a 7-day ban, and Sektant, Full and Boss tabs (Factory night cultists included).
- **Written bounty rules:** the full bounty rulebook covers helpers, help calls, splits, Sanitar, Boss not found, proof, fraud and Squad Savior. It sits right under **Edit bounty prices** and behind the **Bounty rules** button. Its values list is read from your current prices, so the rules and the prices always agree.
- **1v1s:** agree terms and wagers up front, start from a standing start, and settle the series. Terms lock when both fighters agree.
- **Shop and redemptions:** a priced shop per game, plus free-text redemptions where you name the reward and the price. Pay player to player, player to SYSTEM, or SYSTEM to player.
- **Trades:** one global trade book for items, game time and favours across games, with partial delivery ("30 of 120 minutes"), cancellations and full history.
- **Bans:** game-scoped bans on weapons, fighters, Kameos, agents and more, with paid unbans and clear-all. Bans are kept in history rather than deleted.
- **Debts and deals:** track who owes what. Unpaid Tarkov debts double at the deadline and again every full week after.
- **Discord:** a live kill feed scoreboard, bans board, shop board and trade posts, each edited in place instead of spamming the channel. Every webhook is separate and optional.
- **Safe by default:** backups before every update, one-click ledger backup and Excel export, and a tray agent that keeps tracking with the window closed. It can also start silently when you log in.
- **Automatic updates:** checks this repo's latest release at startup and every six hours, with no setup. Each update has its size and SHA-256 verified and is test-started before it replaces anything. Your ledger is backed up first, and if the new version won't start, the previous one comes back. You can install with one click, or let it download and restart on its own.

## Privacy

Your ledger lives in a SQLite file on your PC (`%LOCALAPPDATA%\KillEconomy`) and goes nowhere else. No account, no analytics, no server. Kill Economy only goes online for things you turn on: Discord webhooks you paste in, the update check, the shared squad ledger, and Google Fonts when you ask for a `google:` font. When you host, your squad's PCs talk directly to yours. Every request is signed with your join code's secret, but traffic is not encrypted, so keep it to your own network or a VPN. Webhook addresses are encrypted with Windows' own data protection and never shown again after you save them. Raid capture uses the OCR built into Windows, on your PC.

## Bugs

**"Cannot reach the host" when joining a shared ledger?** Make sure both PCs run the same version and the host app is open. If the host uses a VPN app such as NordVPN, update to 3.4.1 or later and have the host click **Copy join code** again, because older codes could carry the VPN's address. A connected VPN can also block local traffic, so turn on its LAN access option or disconnect it while you play.

Open an [issue](../../issues/new/choose) with what you were doing, what happened, and your version (**Settings → App updates**). A screenshot helps. Never paste a Discord webhook address into an issue.

## Credits

Built on [Python](https://www.python.org) and Tkinter, [SQLite](https://sqlite.org), [Pillow](https://python-pillow.org), [mss](https://github.com/BoboTiG/python-mss), [pystray](https://github.com/moses-palmer/pystray), [Requests](https://requests.readthedocs.io), [openpyxl](https://openpyxl.readthedocs.io), Windows OCR via [PyWinRT](https://github.com/pywinrt/pywinrt), and [PyInstaller](https://pyinstaller.org). Boss and escort guidance links to the [Escape from Tarkov Wiki](https://escapefromtarkov.fandom.com). Optional fonts come from [Google Fonts](https://fonts.google.com) under their own open licenses. Much of the code was written with AI assistance, directed, reviewed and tested by the squad.

Kill Economy is a fan-made tool and is not affiliated with Battlestate Games, NetherRealm Studios, Capcom, Riot Games, Rockstar Games, Discord, Google or any of the projects above.
