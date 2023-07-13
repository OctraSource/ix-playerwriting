# ix-playerwriting
Utilizes [Helix](https://gethelix.co/), a community-made gamemode framework for [Garry's Mod](https://store.steampowered.com/app/4000/Garrys_Mod/).
<br>
<br>
Adds a new type of [item](https://docs.gethelix.co/classes/item/): a writable.
<br>
Writables are notebook-like items that players can write onto. They can have multiple pages and can be seen by other players.
# functionality
"**Reading**" a writable pops a [Derma](https://wiki.facepunch.com/gmod/Derma_Basic_Guide) menu, which is a client-side popup (pausing in a multiplayer game allows you to see a menu, but nobody else sees it and it doesn't disrupt their game), which contains *pages* number of text boxes within it.
When creating your own item, you can modify *pages* to specify how many text boxes you want in a writable item, [here](https://github.com/OctraSource/ix-playerwriting/blob/main/playerwriting/items/base/sh_writables.lua).
If the item is not signed by any player, then whenever you read an item, you can also type into them and modify them.
<br>
<br>
"**Signing**" a writable disallows any further edits from any player, including yourself. If you're the signer of a writable, you can "**Unsign**" a writable to allow edits once again. Keep in mind, however, other players can now sign your writable!
