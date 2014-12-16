# Columns Review #
*   Author: Alberto Buffolino.

Columns Review is an add-on to read and copy items in a list column by column. It supports lists (see below) with a potentially infinite number of columns, and you can navigate them using keyboard or numpad digits. The column headers can be read but not copied, or vice versa.

## For developers and advanced users ##

List types supported are:

*   SysListView32;
*   DirectUIHWND (present in 64-bit systems);
*   WindowsForms10.SysListView32.app.0.x (applications that use .NET);
*   Mozilla list (tipically, Thunderbird message list).

All gestures are associated on and only on supported lists, when these are not empty.

## Key Commands ##

*   NVDA+control+digits from 1 to 0 (keyboard mode) or from 1 to 9 (numpad mode): pressed once, read the chosen column, pressed twice, copy it;
*   NVDA+control+numpadMinus (numpad mode): read or copy the 10th, 20th, etc column;
*   NVDA+control+- (default, EN-US layout, keyboard mode): in a list with 10+ columns, let you to change interval and read columns from 11 to 20, from 21 to 30, and so on; see settings to change last char according to your layout;
*   NVDA+control+numpadPlus (numpad mode): exactly as previous command.

## Changes for 1.0 ##
*   Initial release.
