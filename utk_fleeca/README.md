# Fleeca Bank Heists by utku

Made by utku#9999

## Installation

Simply drag and drop this folder to you resources directory and give it a start on server.cfg

Don't forget to add the items to your database (sql file if you need)

## Configuration

You can add more banks to the script by copy pasting the previous ones. However you may need to test it a few times to fit the objects to the right places and similar stuff. Bank iformations are in "utk.lua"

You also need to edit this code:

```lua
-- line 4
Freeze = {F1 = 0, F2 = 0, F3 = 0, F4 = 0, F5 = 0, F6 = 0}
-- you need to add the bank here like this:
Freeze = {F1 = 0, F2 = 0, F3 = 0, F4 = 0, F5 = 0, F6 = 0, F7 = 0}

-- line 5
Check = {F1 = false, F2 = false, F3 = false, F4 = false, F5 = false, F6 = false}
-- you need to add the bank here like this:
Check = {F1 = false, F2 = false, F3 = false, F4 = false, F5 = false, F6 = false, F7 = false}

-- line 6
LootCheck = {
    F1 = {Stop = false, Loot1 = false, Loot2 = false, Loot3 = false},
    F2 = {Stop = false, Loot1 = false, Loot2 = false, Loot3 = false},
    F3 = {Stop = false, Loot1 = false, Loot2 = false, Loot3 = false},
    F4 = {Stop = false, Loot1 = false, Loot2 = false, Loot3 = false},
    F5 = {Stop = false, Loot1 = false, Loot2 = false, Loot3 = false},
    F6 = {Stop = false, Loot1 = false, Loot2 = false, Loot3 = false}
}
-- you need to add the bank here like this:
LootCheck = {
    F1 = {Stop = false, Loot1 = false, Loot2 = false, Loot3 = false},
    F2 = {Stop = false, Loot1 = false, Loot2 = false, Loot3 = false},
    F3 = {Stop = false, Loot1 = false, Loot2 = false, Loot3 = false},
    F4 = {Stop = false, Loot1 = false, Loot2 = false, Loot3 = false},
    F5 = {Stop = false, Loot1 = false, Loot2 = false, Loot3 = false},
    F6 = {Stop = false, Loot1 = false, Loot2 = false, Loot3 = false},
    F7 = {Stop = false, Loot1 = false, Loot2 = false, Loot3 = false}
}

--line 225
if Freeze.F1 > 3 and Freeze.F2 > 3 and Freeze.F3 > 3 and Freeze.F4 > 3 and Freeze.F5 > 3 and Freeze.F6 > 3 then
-- you need to add the bank here like this:
if Freeze.F1 > 3 and Freeze.F2 > 3 and Freeze.F3 > 3 and Freeze.F4 > 3 and Freeze.F5 > 3 and Freeze.F6 > 3 and Freeze.F7 > 3 then
```
