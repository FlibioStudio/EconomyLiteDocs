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

`/payv <account> <amount>` **-** Pays a virtual account.

**Permission:** `economylite.virtual.pay`

`/baltop [<page>]` **-** Shows the balance of the top three players. Include a page number to navigate between pages.

**Permission:** `economylite.baltop`

#### Loan Module Commands

`/loan` **-** The base loan command.

**Permission:** `economylite.loan`

`/loan balance` **-** Displays your current loan balance.

**Permission:** `economylite.loan.balance`

`/loan take <amount>` **-** Takes out a loan for the specified amount.

**Permission:** `economylite.loan.take`

`/loan pay <amount>` **-** Pays the given amount towards your loan balance.

**Permission:** `economylite.loan.pay`

`/loan accept` **-** Accepts a loan offer.

**Permission:** `economylite.loan.accept`

`/loan deny` **-** Denies a loan offer.

**Permission:** `economylite.loan.deny`

### Administrative Commands

`/econ set | add | remove <player> <amount>` **-** Adds, sets or removes currency from a player.

**Permissions:** `economylite.admin.econ.set` : `economylite.admin.econ.add` : `economylite.admin.econ.remove`

`/currency set | delete <currency>` **-**  Sets the current currency, deletes a currency, or or displays the currency currently being used by the server.

**Permissions:** `economylite.admin.currency` : `economylite.admin.currency.set` : `economylite.admin.currency.delete`

`/currency create <singular> <plural> <symbol>` **-**  Creates a new currency with the given information.

**Permission:** `economylite.admin.currency.create`

`/vbalance <account>` **-** Gets the balance of a virtual account.

**Permission:** `economylite.admin.virtual.balance`

`/vecon set | add | remove <account> <amount>` **-** Adds, sets or removes currency from a virtual account.

**Permissions:** `economylite.admin.virtual.set` : `economylite.admin.virtual.add` : `economylite.admin.virtual.remove`

`/vpay <player> <amount>` **-** Pays a player from a virtual account.

**Permissions:** `economylite.admin.virtual.pay`

`/migrate <mode> [<confirm>]` **-** Migrates data to EconomyLite.

**Modes:**

 - `economylite1` **-** EconomyLite data from `v1.X.X` to `v2.X.X`. Requires the old data files (`data.conf` and `businesses.conf`) to be in the `config/EconomyLite` folder.
 - `totaleconomy` **-** TotalEconomy data to EconomyLite.

**Permission:** `economylite.admin.migrate`
