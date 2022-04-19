---
description: Writes RPT log entry
---

# Extremo\_fnc\_client\_log

### Syntax

Syntax: \[message, isServerLog] call Extremo\_fnc\_client\_log;

Parameters:&#x20;

1. [string](https://community.bistudio.com/wiki/String) - message
2. [boolen](https://community.bistudio.com/wiki/Boolean) - isServerLog

Return: none

### Examples

1. `["Example Client RPT Message"] call Extremo_fnc_client_log;` // Write [RPT](https://community.bistudio.com/wiki/arma.RPT) log entry on the client function was executed on
2. `["Example Client & Server RPT Message", true] call Extremo_fnc_client_log;` // Write [RPT](https://community.bistudio.com/wiki/arma.RPT) log entry on the client function was executed on & Write [RPT](https://community.bistudio.com/wiki/arma.RPT) log entry on the server
