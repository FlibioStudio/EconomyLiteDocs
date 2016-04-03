---
layout: page
title: Configuration
---

EconomyLite can be configured to meet your servers needs. All of the messages sent by the plugin can be customized.
The configuration files can be found in the `config/economylite` folder. A list of configuration options can be found below.

### Main Configuration

The main configuration file is called `config.conf`. The options are described below.

`default-balance` **-** The default balance a player receives when they first join the server. The default value is `0`.

`virt-default-balance` **-** The default balance a virtual account receives when it is created. The default value is `0`.

`modules.mysql` **-** Contains all of the configuration options for the MySQL module.

`modules.mysql.enabled` **-** Sets if the MySQL module is enabled or not.

`modules.mysql.hostname` **-** The hostname of the MySQL server.

`modules.mysql.port` **-** The port of the MySQL server.

`modules.mysql.database` **-** The database on the MySQL server.

`modules.mysql.username` **-** The username used to connect to the MySQL server.

`modules.mysql.password` **-** The password used to connnect to the MySQL server.

### Message Configuration

The message configuration file is called `messages.conf`. It is used to customize every message sent be EconomyLite. To
customize a message, simply replace the text found after the message name. Feel free to include colors in the message
using the `&` formatting code. (Example: `&c` is equal to red)
