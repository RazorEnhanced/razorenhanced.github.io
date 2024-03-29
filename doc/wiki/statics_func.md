
====== Scripting - Statics data and function ======

Here can find some information about Enhanced Scripting function and data for Statics and Map Information.



===== Land Information =====



{|style="font-size:85%; border:solid 2px; width: 50%;"

|style="font-size:150%;  padding: 2px" colspan="2" | **Get Land ID**

|- style="background-color:#f0f0f0;"

|**Syntax**

|style="width: 90%" | Statics.GetLandID(int, int, int)

|-

|colspan="2" |**Description:**

|-

|colspan="2" |Get ID of tile in X, Y coordinates and specific map.

|- style="background-color:#f0f0f0;"

|**Returns**

|Int

|-

|**In Object:**

|Statics

|- style="background-color:#f0f0f0;"

|**Parameters:**

|mapID



|}





{|style="font-size:85%; border:solid 2px; width: 50%;"

|style="font-size:150%;  padding: 2px" colspan="2" | **Get Land Name**

|- style="background-color:#f0f0f0;"

|**Syntax**

|style="width: 90%" | Statics.GetLandName(int LandID)

|-

|colspan="2" |**Description:**

|-

|colspan="2" |Get Name of the land identified by LandID.

|- style="background-color:#f0f0f0;"

|**Returns**

|Int

|-

|**In Object:**

|Statics

|- style="background-color:#f0f0f0;"

|**Parameters:**

|LandID



|}









{|style="font-size:85%; border:solid 2px; width: 50%;"

|style="font-size:150%;  padding: 2px" colspan="2" | **Get Land X Level**

|- style="background-color:#f0f0f0;"

|**Syntax**

|style="width: 90%" | Statics.GetLandZ(int, int, int)

|-

|colspan="2" |**Description:**

|-

|colspan="2" |Get Z Level of tile in X, Y coordinates and specific map.

|- style="background-color:#f0f0f0;"

|**Returns**

|Int

|-

|**In Object:**

|Statics

|- style="background-color:#f0f0f0;"

|**Parameters:**

|mapID



|}





{|style="font-size:85%; border:solid 2px; width: 50%;"

|style="font-size:150%;  padding: 2px" colspan="2" | **Get Land tile flag information**

|- style="background-color:#f0f0f0;"

|**Syntax**

|style="width: 90%" | Statics.GetLandFlag(int, string)

|-

|colspan="2" |**Description:**

|-

|colspan="2" |Get true or false if flag is present for specific land itemID.

|- style="background-color:#f0f0f0;"

|**Returns**

|bool

|-

|**In Object:**

|Statics

|- style="background-color:#f0f0f0;"

|**Parameters:**

|int itemid, string flagname

|-

|**Possible flag to check:**

|

  * None

  * Translucent

  * Wall

  * Damaging

  * Impassable

  * Surface

  * Bridge

  * Window

  * NoShoot

  * Foliage

  * HoverOver

  * Roof

  * Door

  * Wet



|}



===== Statics Information =====





{|style="font-size:85%; border:solid 2px; width: 50%;"

|style="font-size:150%;  padding: 2px" colspan="2" | **Get Static information on tile**

|- style="background-color:#f0f0f0;"

|**Syntax**

|style="width: 90%" | Statics.GetStaticsTileInfo(int, int, int)

|-

|colspan="2" |**Description:**

|-

|colspan="2" |Get tiles info in a certain map at X, Y coordinates.

Tileinfo list contain all static item in specific tile whit this information: StaticID (Static item Grapics), StaticHue (Static item color), StaticZ (Static item Z Level).



|- style="background-color:#f0f0f0;"

|**Returns**

|List(TileInfo)

|-

|**In Object:**

|Statics

|- style="background-color:#f0f0f0;"

|**Parameters:**

|int coordX, int coordY, int mapID



|}









{|style="font-size:85%; border:solid 2px; width: 50%;"

|style="font-size:150%;  padding: 2px" colspan="2" | **Get Static tile name**

|- style="background-color:#f0f0f0;"

|**Syntax**

|style="width: 90%" | Statics.GetTileName(int)

|-

|colspan="2" |**Description:**

|-

|colspan="2" |Get a tile name.

Tileinfo list contain all static item in specific tile with this information: StaticID (Static item Graphics), StaticHue (Static item color), StaticZ (Static item Z Level).



|- style="background-color:#f0f0f0;"

|**Returns**

|string

|-

|**In Object:**

|Statics

|- style="background-color:#f0f0f0;"

|**Parameters:**

|int TileID



|}



























{|style="font-size:85%; border:solid 2px; width: 50%;"

|style="font-size:150%;  padding: 2px" colspan="2" | **Get Static tile flag information**

|- style="background-color:#f0f0f0;"

|**Syntax**

|style="width: 90%" | Statics.GetTileFlag(int, string)

|-

|colspan="2" |**Description:**

|-

|colspan="2" |Get true or false if flag is present for specific itemID.

|- style="background-color:#f0f0f0;"

|**Returns**

|bool

|-

|**In Object:**

|Statics

|- style="background-color:#f0f0f0;"

|**Parameters:**

|int itemid, string flagname

|-

|**Possible flag to check:**

|

  * None

  * Translucent

  * Wall

  * Damaging

  * Impassable

  * Surface

  * Bridge

  * Window

  * NoShoot

  * Foliage

  * HoverOver

  * Roof

  * Door

  * Wet



|}



===== Deed Information =====



{|style="font-size:85%; border:solid 2px; width: 50%;"

|style="font-size:150%;  padding: 2px" colspan="2" | **Check if exist deed house**

|- style="background-color:#f0f0f0;"

|**Syntax**

|style="width: 90%" | Statics.CheckDeedHouse(int, int)

|-

|colspan="2" |**Description:**

|-

|colspan="2" |Get true or false if exist deed house in specific X, Y.

|- style="background-color:#f0f0f0;"

|**Returns**

|Bool

|-

|**In Object:**

|Statics

|- style="background-color:#f0f0f0;"

|**Parameters:**

|coordY



|}

