---
description: handles data from server
---

# Extremo\_fnc\_database\_client

### Syntax

Syntax: \[table, action, param1, param2, param3...] call Extremo\_fnc\_database\_client;

Parameters:

1. [string](https://community.bistudio.com/wiki/String) - table
2. [string](https://community.bistudio.com/wiki/String) - action
3. varies see [examples](extremo\_fnc\_database\_client.md#examples)

Return: [boolen](https://community.bistudio.com/wiki/Boolean)

### Examples

1. `["characters", "update"] call extremo_fnc_database_client;` // sync character to database
2. `["characters", "update", false] call extremo_fnc_database_client;`  // sync character to database (Also displays [stackable notifaction](../gui/extremo\_fnc\_gui\_toasterscreen.md) to the player)
3.
