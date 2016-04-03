---
layout: page
title: Commands
---

Commands are essential to EconomyLite. Here is a list of commands and what they do:

### User Commands

`/balance [<player>]` **-** Shows the balance of your account. Include a player name to get the balance of that player.

**Permissions:** `economylite.balance` : `economylite.admin.balanceothers`

`/pay <player> <amount>` **-** Pays another player.

**Permission:** `economylite.pay`

`/baltop` **-** Shows the balance of the top three players.

**Permission:** `economylite.baltop`

### Administrative Commands

`/econ set | add | remove <player> <amount>` **-** Adds, sets or removes currency from a player.

**Permissions:** `economylite.admin.econ.set` : `economylite.admin.econ.add` : `economylite.admin.econ.remove`

`/currency set | delete <currency>` **-**  Sets the current currency, deletes a currency, or or displays the currency currently being used by the server.

**Permissions:** `economylite.admin.currency` : `economylite.admin.currency.set` : `economylite.admin.currency.delete`

`/currency create <singular> <plural> <symbol>` **-**  Creates a new currency with the given information.

**Permission:** `economylite.admin.currency.create`

`/vbalance <account>` **-** Gets the balance of a virtual account.

**Permission:** `economylite.admin.virtual.balance`

`/vset <account> <amount>` **-** Sets the balance of a virtual account.

**Permission:** `economylite.admin.virtual.set`

`/migrate [<confirm>]` **-** Migrates EconomyLite data from `v1.X.X` to `v2.X.X`. Requires the old data files (`data.conf` and `businesses.conf` to exist).

**Permission:** `economylite.admin.migrate`
