---
layout: page
title: Configuration
---

EconomyLite can be configured to meet your servers needs. All of the messages sent by the plugin can be customized.
The configuration files can be found in the `config/economylite` folder. A list of configuration options can be found below.

### Main Configuration

The main configuration file is called `config.conf`. The options are described below.

`debug-logging` **-** Sets whether or not EconomyLite will output debug log messages. The default value is `true`.

`default-balance` **-** The default balance a player receives when they first join the server. The default value is `0`.

`virt-default-balance` **-** The default balance a virtual account receives when it is created. The default value is `0`.

#### MySQL Module

`modules.mysql.enabled` **-** Sets if the MySQL module is enabled or not.

`modules.mysql.hostname` **-** The hostname of the MySQL server.

`modules.mysql.port` **-** The port of the MySQL server.

`modules.mysql.database` **-** The database on the MySQL server.

`modules.mysql.username` **-** The username used to connect to the MySQL server.

`modules.mysql.password` **-** The password used to connnect to the MySQL server.

#### Loan Module

`modules.loan.enabled` **-** Sets if the loan module is enabled or not.

`modules.loan.interest-rate` **-** The interest rate loans are taken out at. It must be greater than or equal to 1.

`modules.loan.max-loan-balance` **-** The maximum loan balance a player can have at any given time.

### Message Configuration

The message configuration file is called `messages.conf`. It is used to customize every message sent be EconomyLite. To
customize a message, simply replace the text found after the message name. Feel free to include colors in the message
using the `&` formatting code. (Example: `&c` is equal to red)
