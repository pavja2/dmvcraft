# Server Guide
## The Basics
### Joining the Server
The server operates based on an allowlist. Email me or ask someone already on the server if you'd like to be added. 

Friends and family are 100% welcome, just let me know their usernames and I will add them. Only caveat is that you're vouching for the folks you invite, so if your 12 year-old cousin who loves minecraft wants to play, great - they're absolutely welcome! But if they turn out to be hacking/cheating/bullying folks in chat, you may get banned along with them.

### First Time Players
Never played minecraft before? That's alright. The server is designed to be very close to vanilla minecraft with a few basic quality-of-life features and plugins to improve player interactions. It's a great environment for first time players!

To issue commands or say things in chat, press the 't' key in game. Commands start with a '/' character and can have many arguments separated by spaces.

Everything on the server is free - when you see prices in game or in this guide those refer to in-game currency, not real money. I'm paying to host it on my own right now and there are no donor tiers or pay-to-win perks or anything like that. If hosting costs get too high I might solicit voluntary donations but it should always be free for people who just want to play!

That said, minecraft itself is not free. You can buy it from https://www.minecraft.net/ for around $25. This server will only work with the "Java Edition." That means you should not buy the mobile or console editions or the "Windows 10 Edition" (also sold as the "Bedrock" edition). The Java Edition will work on most modern versions of Mac, Linux, and Windows.\

### Rules
TLDR; No cheating and be nice to people. 

If people break rules they can be warned or banned, but I'd really rather not do any moderation if possible, so be excellent to each other!

1. **Respect others**.

2. **No cheating or hacking:** Fair play only. No mods which give unfair advantage. If you wanna use `Litematica` or similar client side mods for planning or replicating your builds - that is fine though!

3. **Keep the environment clean:** Try and cut down your trees all the way and don't leave gaping craters all over the map.

4. **Don't exploit bugs:** If you see a server plugin bug (e.g. the ability to get infinite money or duplicate items) let me know so I can fix it and keep the server balanced and fun for everyone.

### PVP
PVP combat is disabled by default but players can opt-in to pvp using the ``/pvptoggle`` command. You will have to wait at least 120 seconds to leave PVP mode so don't start a fight you're unwilling to finish!

### The Environment
Please try to keep the server looking nice / natural. This means avoid flattening vast areas of the map for no reason or only partially cutting down trees (leaving them floating in the air). A little care in designing your builds goes a really long way.

### Chatting
You will default in the global chat channel which is where everyone can hear you. There are a few other chat options available. Simply type the commands below to switch chat modes:

You may wish to change your display name from whatever embarrassing username middle-school you picked when joining minecraft. You can use the `/nick <new name>` command to change it. Your real username will still appear on shops that you create though.

### Teleporting
The best way to get places is to walk, but if you're in a rush it is possible to teleport. 
There are a few commands to let you zip around the server faster. Teleporting typically costs `$1` or the equivalent of one raw copper nugget.

#### Homes
First, you can set custom homes - these are points in the world that you can warp to at anytime. You can have up to three warps configured.

To set a home location, stand where you want to set the home and use the command: ``/sethome <homename>``\
To go to a home location, use the command: ``/home <homename>``
To remove a home location, use the command: ``/delhome <homename>``
#### Server Warps
You can always warp to the server spawn with ``/spawn``.

#### Player Warps
You can teleport to players for free to socialize or meet up anywhere on the server.

To invite a player to teleport to your location: ``/tphere <playername>``

To ask a player to let you teleport to their location: ``/tpa <playername>``
### Lag Management
I'm paying for hosting out of pocket and it's a **very** cheap box as game servers go. This means that you should avoid building massive mob-spawners, automatic farms or redstone clocks. Automating is half the fun of minecraft so I don't want to ban it outright but if a certain build causes trouble, it may have to be deleted.

### Bugs/Issues
Contact James in game, in the server discord, or via e-mail if you run into any weird bugs with the server and I'll try to fix them as fast as I can! Feel free to ask in the game chat for any help using various features or just playing minecraft if you've never played, someone will probably be able to help you.

## The Economy
The economy operates off a copper standard. 1 unit of currency can be traded any time for a raw copper and a raw copper can be sold to the server at any time for 1 unit of currency.

To sell copper to the server, hold a stack of ingots in your hand and use the following command:
```
/sell hand
```
To buy copper from the server, head to the shop on the second floor of the main spawn building and purchase copper ingots from one of the shops inside.

Since the server will purchase an infinite quantity of copper at a fixed price, one way to make money is prospecting for copper.

### Trading Goods
Mining for copper gets boring. You can sell goods to other players using the quickshop plugin. This allows you to operate shops which people can buy from even when you're offline / away. There is a nominal tax on all shop transactions (5%) to help keep the economy balanced / manage the money supply.

Creating a shop is really easy:
1) Place a chest on the ground
2) Hold the item you want to sell in your hand and hit the chest.
3) Type in the price for the item in the chat (follow the prompts)
4) Fill the chest with the item you wish to sell

There are other settings for more advanced shops (e.g. shops which buy items). To change these just right click a shop you own and follow the prompts.

Buying from a shop is also really easy. Just punch the sign on a shop (left click) and enter the quantity of the items you want to buy in chat. If you're looking for a shop nearby but can't remember quite where it is you can use the ``/qs find <itemname>`` command to find shops selling an item within a few dozen blocks of you. For example ``/qs find diamond`` will face you towards the nearest diamond shop.

### The  Marketplace
There is a small marketplace outside of the main spawn building with stalls available for purchase by players. You are allowed to put whatever you want in your stalls but stalls must contain at least one quickshop selling or buying products. Stalls which are abandoned (either out of stock for multiple days, or belonging to an owner who has been inactive for 2 weeks) will be reset and placed back on the market.

Feel free to build shops in your own towns/homes as well. You don't have to build in the market but its a convenient central spot for everyone.

### Trading Services
In addition to shop-based trading, you can send currency to other players with the ``/pay <playername> <amount>`` command. This is a good way to pay for other services (e.g. construction help).

## Block Protection
Block protection is offered using the protection stones plugin. You can buy protection stones at the server spawn shop and then place them to protect a 32x32 area centered on the stone!

You can learn more about how to share access to your protection stones, manage protections, and merge regions with the ``/ps help`` command.

## Character Development
The server has the popular McMMO plugin installed. This allows you to level your character according to many different RPG mechanics and unlock special perks and abilities as you progress. This happens more or less in the background and will impact things like mining, farming, combat and so forth as you rank up.

### Skills and Abilities
The skills are: Acrobatics, Archery, Axes, Swords, Unarmed, Excavation, Fishing, Herbalism, Mining, Woodcutting, Alchemy, Repair, Taming, Salvage, and Smelting.

Certain special abilities can be unlocked and will be executed when you right click with particular tools or type commands in chat. Type ``/stats`` to see a basic summary of your character and ``/<skillname>`` to see information about a particular skill (e.g. ``/fishing``).

### EXP Sharing
You can team up with other players to cooperate and earn experience using party commands. The basic party commands are:

``/party`` - shows information about your party

``/party create <name>`` - creates a new party

``/party join <name>`` - joins an existing party

``/party q`` - leaves the party you are in

``/party invite <player name>`` - invites a player to your party

### Advanced Enchantments
The server sells customized enchantments beyond those which can be found in vanilla minecraft at the server shop, along with some special items which can be added to further enhance your enchantments (such as the ability to increase the number of enchantment slots available on an item). Use `/enchanter` to learn more about these features! These enchantments offer a powerful late game progression objective and place for you to spend your hard-earned copper! A full list of available enchantments can be found [here](https://ae.advancedplugins.net/enchantments/list-of-enchantments/default-enchants-200+).

## Locked Chests
Chest and other containers you place automatically lock. You can manage access to these chests using the `/bolt` commands.

## Convencience Functions
You can use /chestsort to automatically sort your chests and inventory.
You can use /disposal to easily dispose of items from your inventory wherever you are standing.
You can use /condense to automatically turn blockable items in your inventory (e.g. iron ingots) into blocks


## Privacy Notes
Anything you type on the server is logged along with your minecraft username and connection information. This information is visible to server administrators and potentially our VPS hosting provider. Be mindful that any personal information you share (even in /msg mesages to other players) is not guaranteed to remain private. I'll refer to logs if I have to moderate any disputes.

