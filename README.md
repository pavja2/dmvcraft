# Server Guide
## The Basics
### Joining the Server
The server operates based on a whitelist. Email me or ask someone already on the server if you'd like to be added. The server was built with the Rhodes community in mind but friends and family from beyond are 100% welcome, just let me know their usernames and I will add them.
### First Time Players
Never played minecraft before? That's alright. The server is designed to be very close to vanilla minecraft with a few basic quality-of-life features and plugins to improve player interactions. It's a great environment for first time players!

To issue commands or say things in chat, press the 't' key in game. Commands start with a '/' character and can have many arguments separated by spaces.

Everything on the server is free - when you see prices in game or in this guide those refer to in-game currency, not real money. I'm paying to host it on my own right now and there are no donor tiers or pay-to-win perks or anything like that, if hosting costs get too high I might solicit voluntary donations but for a small number of users but it should always be free for people who just want to play!

That said, minecraft itself is not free. You can buy it from https://www.minecraft.net/ for around $25. This server will only work with the "Java Edition." That means you should not buy the mobile or console editions or the "Windows 10 Edition" (also sold as the "Bedrock" edition). The Java Edition will work on most modern versions of Mac, Linux, and Windows.
### Rules
An up to date list of rules for the server can be found with the ``/rules`` command in game. The list boils down to no cheating and be nice to people. If people break the rules they can be warned or banned but I'd really rather not do any moderation if possible, so be excellent to each other!
### PVP
PVP combat is disabled by default but players can opt-in to pvp using the ``/pvp toggle`` command. You will have to wait at least 120 seconds to leave PVP mode so don't start a fight you're unwilling to finish!
### The Environment
Please try to keep the server looking nice / natural. This means avoid flattening vast areas of the map for no reason or only partially cutting down trees (leaving them floating in the air). A little care in designing your builds goes a really long way.
### Lag Management
I'm paying for hosting out of pocket and it's a **very** cheap box as game servers go. This means that you should avoid building massive mob-spawners, automatic farms or redstone clocks. Automating is half the fun of minecraft so I don't want to ban it outright but if a certain build causes trouble, it may have to be deleted.
### Chatting
You will default in the global chat channel which is where everyone can hear you. There are a few other chat options available. Simply type the commands below to switch chat modes:

``/g`` - default, global channel everyone can here

``/tc`` - town chat, everyone in your town can hear you

``/lc`` - local chat, players nearby (a few dozen blocks) can hear you

``/pc`` - party chat, players in your MCMMO party (see below) can hear you

If you wish to change your display name from whatever embarrassing username middle-school you picked when joining minecraft. You can use the `/nick <new name>` command to change it. Your real username will still appear on shops that you create though.
### Teleporting
The best way to get places is to walk, but if you're in a rush it is possible to teleport. There are a few commands to let you zip around the server faster.

#### Homes
First, you can set custom homes - these are points in the world that you can warp to at anytime. You can have up to three warps configured.

To set a home location, stand where you want to set the home and use the command: ``/sethome <homename>``\
To go to a home location, use the command: ``/home <homename>``
To remove a home location, use the command: ``/delhome <homename>``

Warping home costs $5 to incentivze transport infrastructure around towns.

#### Server Warps
You can always warp to the server spawn with ``/spawn`` and to the server marketplace with ``/market`` for free.

#### Town Warps
You can warp to your town spawn with ``/town spawn`` for $5 of in-game currency. If your town has joined a nation, you can warp to other towns in the nation with ``/town spawn [town_name]`` for $5 of in-game currency.

#### Player Warps
You can teleport to players for free to socialize or meet up anywhere on the server.

To invite a player to teleport to your location: ``/tphere <playername>``
To ask a player to let you teleport to their location: ``/tpa <playername>``

#### 
## The Economy
The economy operates off a gold standard. Ten units of currency can be traded at any time for one gold ingot and one gold ingot can be sold to the server at any time for ten units of currency.
To sell gold to the server, hold a stack of ingots in your hand and use the following command:
```
/sell hand
```
To buy gold from the server, head to the bank inside the main spawn building and purchase gold ingots from one of the shops inside.

Since the server will purchase an infinite quantity of gold at a fixed price, one way to make money is prospecting for gold. The ore generation settings have been adjusted so that gold occurs with greater frequency and in bigger clumps than in default minecraft so this is a viable option.
### Trading Goods
Mining for gold gets boring. You can sell goods to other players using the quickshop plugin. This allows you to operate shops which people can buy from even when you're offline / away. There is a nominal tax on all shop transactions (5%) to help keep the economy balanced / manage the money supply.

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

You can warp directly to the market with ``/warp market``.

### Trading Services
In addition to shop-based trading, you can send currency to other players with the ``/pay <playername> <amount>`` command. This is a good way to pay for other services (e.g. construction help).

## Towns and Protection
Block protection is offered by the Towny plugin which allows players to group together and form towns and settlements in which they can control who is allowed to build and where.

### Creating a town
Anyone is allowed to start a town but you will have to save up some money to do so! Right now, founding a town costs $400 (or the equivalent of 40 gold ingots traded at the server bank). As the server matures, this price may go up while the economy settles / inflation stabilizes.

To found a town run the command ``/town new <townname>`` and you will be mayor of your own little settlement. To check if where you are standing belongs to a town type ``/town here``

### Growing your town
Towns consists of chunks measuring 16x16 blocks and stretch from the bottom of the map to the top. When you start your town, it will have one chunk (where you're standing). You can buy additional chunks from the server with the command ``/town claim`` but these chunks must be adjacent to one you already own.

An easy way to visualize chunks is to press the F3+G keys at the same time. To disable this view, press them again.

The number of chunks you are able to buy depends on the number of other players who live in your town. To invite new residents use ``/town add <playername>`` to send people invites to your town.

As mayor you can sell (or give) plots to your residents by standing in a claimed chunk and using the command ``/ plot forsale <price>``. Residents can claim plots for sale by standing in them and using the command ``/plot claim``.

### Other town features
You can easily get back to your town's homeblock (the first block claimed) with ``/town spawn``. There are tons of other towny features as well, such as the ability to join up with other towns and form nations (allowing your residents to teleport between towns within the nation). For more detailed documentation check out: https://github.com/TownyAdvanced/Towny/wiki

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
## Privacy Notes
Anything you type on the server is logged along with your minecraft username and connection information. This information is visible to server administrators and potentially our VPS hosting provider. Be mindful that any personal information you share (even in /msg mesages to other players) is not guaranteed to remain private. I'll refer to logs if I have to moderate any disputes.

