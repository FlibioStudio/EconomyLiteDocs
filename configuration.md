---
layout: page
title: Configuration
---

Commands are essential to EconomyLite. Here is a list of commands and what they do:

### Balance Commands

`/balance` **-** Shows the balance of your account.

**Permission:** `None`

`/balance {business name}` **-** Shows the balance of a business. You must an owner of the business to use this command.

 **Permission:** `econ.business.balance`

`/playerbalance {player name}` **-** Gets the balance of another player. Works in the console.

 **Permission:** `econ.playerbalance`

### Administrative Commands

`/econ add|remove {amount} {player name}` **-** Add or removes currency from a player.

**Permission:** `econ.admin`

`/econ set {player name} {amount}` **-** Sets the balance of a player.

**Permission:** `econ.admin`

### Pay Commands

`/pay {amount} {player or business name}` - Pays a player/business from your account

**Permission:** `econ.pay`

`/paySpecified {type} {amount} {player or business name}` - Used solely by EconomyLite to detect when a player clicks on an option in chat.

**Permission:** `econ.pay`

### Business Commands

`/business register {business name}` - Registers a new business under the specified name. Business names are allowed to have spaces in them.
 
**Permission:** `econ.business.register`

`/business delete {business name}` - Deletes a business from EconomyLite. Upon deletion, the balance of the business will be split evenly among it's owners.
 
**Permission:** `econ.business.delete`

`/business leave {business name}` - Allows a player to leave a business as an owner. If you are the sole owner the business will be deleted.
 
**Permission:** `econ.business.leave`

`/business invite {player name} {business name}` - Invite someone to join your business as an owner. The player will receive a clickable  message in chat that will allow them to accept your invitation. 
 
**Permission:** `econ.business.invite`

`/business inviteAccept {business name}` - This command is used solely by EconomyLite to detect when a player accepts an invite to a business.
 
**Permission:** `econ.business.invite`

`/business transfer {amount} {business name}` - Used to transfer money from a business to a player. You must be an owner of the business to run this command.

**Permission:** `econ.business.transfer`

`/business owners {business name}` - Used to view the owners of a business. You must be an owner of the business to run this command.
 
**Permission:** `econ.business.owners`
