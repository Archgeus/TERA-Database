# TERA Database
Simple winforms application used as "Portable" item database of TERA

![1](https://i.ibb.co/r6QCXJr/Screenshot-294.png)

I created this tool for personal usage but i tought that it would be very useful for all, so i'm releasing it.

# Current features.

Shows item icons / names in a datagrid and values when any icon grid is selected, sorted by the coincidences in the search bar. Currently search by item name is supported. Search by ItemId is not supported (yet).

The tool uses a Sqlite as database in order to make it more portable.

# It shows the following values,

ItemID
ItemString
ToolTip
RareGrade
Level
MaxStack
Destroyable
Dismantlable
StoreSellable
Tradable
WarehouseStorable

The tool comes with 71.03 database by default, but it can generate a new database placing ItemData and StrSheet_Item folders from any client (I guess, only tested v3x.xx, 71.03 and 92.04) to the root application folder. (Remember to rename or delete the existing index.db file in order to force the app to recreate it, also move or delete the existing ItemData and StrSheet_Item folders to avoid incongruences).

Cheers.
