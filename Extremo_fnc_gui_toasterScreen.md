# Extremo_fnc_gui_toasterScreen
## Displays stackable notification to the client that the function is executed on

# Syntax
Syntax: [template, [placeholder,placeholder2,placeholder3,placeholder...]] call Extremo_fnc_gui_toasterScreen

Parameters:
- template classname 
- placeholders 

Return: Nothing

# Examples
Example 1: `["ErrorTitleAndText",["Whoops!","Something went really wrong. Please tell a server admin that you have having issues"]] call Extremo_fnc_gui_toasterScreen;`
<br/>
<br/>
Example 2: `["SuccessTitleAndText", ["Item purchased!", format ["-%1", 1000]]] call Extremo_fnc_gui_toasterScreen;`
<br/>
<br/>
Example 3: `["ErrorTitleAndText",["Whoops!","Something went really wrong. Please tell a server admin that you have having issues purchasing this vehicle "]] remoteExecCall ["Extremo_fnc_guitoasterScreen", 4];`
