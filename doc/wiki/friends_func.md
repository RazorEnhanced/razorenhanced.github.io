
======Scripting - Friend control function======

Here can find some information about Enhanced Scripting function to control friend list by script!



=====AddFriend====



{|style="font-size:85%; border:solid 2px; width: 50%;"

|style="font-size:150%;  padding: 2px" colspan="2" | **Add a Player to a friend list**

|- style="background-color:#f0f0f0;"

|**Syntax**

|style="width: 90%" | Friend.AddPlayer(string FriendListName, string PlayerName, int PlayerSerial)

|-

|colspan="2" |**Description:**

|-

|colspan="2" |Add the player specified to the Friend list named in FriendListName parameter

|- style="background-color:#f0f0f0;"

|**Returns**

|void

|-

|**In Object:**

|Friend

|- style="background-color:#f0f0f0;"

|**Parameters:**

|FriendListName, PlayerName, PlayerSerial  



|}



=====RemoveFriend====



{|style="font-size:85%; border:solid 2px; width: 50%;"

|style="font-size:150%;  padding: 2px" colspan="2" | **Add a Player to a friend list**

|- style="background-color:#f0f0f0;"

|**Syntax**

|style="width: 90%" | Friend.RemovePlayer(string FriendListName, int PlayerSerial)

|-

|colspan="2" |**Description:**

|-

|colspan="2" |Remove the player specified from the Friend list named in FriendListName parameter

|- style="background-color:#f0f0f0;"

|**Returns**

|bool - True success, False fail to remove

|-

|**In Object:**

|Friend

|- style="background-color:#f0f0f0;"

|**Parameters:**

|FriendListName, PlayerSerial  



|}







=====Check Friend====



{|style="font-size:85%; border:solid 2px; width: 50%;"

|style="font-size:150%;  padding: 2px" colspan="2" | **Check if Player is in FriendList**

|- style="background-color:#f0f0f0;"

|**Syntax**

|style="width: 90%" | Friend.IsFriend(int)

|-

|colspan="2" |**Description:**

|-

|colspan="2" |Get a bool value if serial is in friend list or not, also if partyinclude option is active on GUI search in party also.

|- style="background-color:#f0f0f0;"

|**Returns**

|bool

|-

|**In Object:**

|Friend

|- style="background-color:#f0f0f0;"

|**Parameters:**

|SerialToSearch



|}



=====Change List=====



{|style="font-size:85%; border:solid 2px; width: 50%;"

|style="font-size:150%;  padding: 2px" colspan="2" | **Change Friend list**

|- style="background-color:#f0f0f0;"

|**Syntax**

|style="width: 90%" | Friend.ChangeList(string)

|-

|colspan="2" |**Description:**

|-

|colspan="2" |Change friend list, List must be exist in friend list GUI configuration

|- style="background-color:#f0f0f0;"

|**Returns**

|void

|-

|**In Object:**

|Friend

|- style="background-color:#f0f0f0;"

|**Parameters:**

|ListName



|}



=====Read Data=====



{|style="font-size:85%; border:solid 2px; width: 50%;"

|style="font-size:150%;  padding: 2px" colspan="2" | **Get friend list**

|- style="background-color:#f0f0f0;"

|**Syntax**

|style="width: 90%" | Friend.GetList(string)

|-

|colspan="2" |**Description:**

|-

|colspan="2" |Retrive list of serial in list, List must be exist in friend list GUI configuration.

|- style="background-color:#f0f0f0;"

|**Returns**

|list (int)

|-

|**In Object:**

|Friend

|- style="background-color:#f0f0f0;"

|**Parameters:**

|FriendListName



|}

