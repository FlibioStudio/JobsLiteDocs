---
layout: page
title: Configuration
---

JobsLite can be configured to meet your server's needs. All of the messages sent by the plugin can be customized.
The configuration files can be found in the `<config directory>/jobslite` folder. A list of configuration options can be found below.

### Main Configuration

The main configuration file is called `config.conf`. The options are described below.

`max-jobs` **-** The maximum amount of jobs a player can have at one time.

`virtual-draw` **-** If set to a value other than `none`, JobsLite will draw funds from this account, rather than simply giving the player money.

#### MySQL

`modules.mysql.enabled` **-** Sets if the MySQL module is enabled or not.

`modules.mysql.hostname` **-** The hostname of the MySQL server.

`modules.mysql.port` **-** The port of the MySQL server.

`modules.mysql.database` **-** The database on the MySQL server.

`modules.mysql.username` **-** The username used to connect to the MySQL server.

`modules.mysql.password` **-** The password used to connnect to the MySQL server.

### Message Configuration

The message configuration file is called `messages.conf`. It is used to customize every message sent be JobsLite. To
customize a message, simply replace the text found after the message name. Feel free to include colors in the message
using the `&` formatting code. (Example: `&c` is equal to red)
