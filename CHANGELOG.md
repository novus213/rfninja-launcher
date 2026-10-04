*[Français](CHANGELOG.fr.md) · **English***

# Changelog

Changes made to the server and the client, newest first. The launcher applies
client updates automatically on startup.

## 4 October 2026

**The cure potion was wiping debuffs instead of shortening them.**
A player reported this, we told him it was working as intended, and he came
back a second time to say it was not. He was right. Using it now halves the
remaining duration of what is on you, rather than clearing it outright. The
description was never the thing that was wrong.

**Two new sort options at the auction house.**
You can now sort listings by *Ends soon* and by *Newest*, alongside the price
and level options that were already there. If you used the level sorts, check
them once and tell us if anything looks off.

**Archon-grade armour for levels 60, 65 and 70 is now on sale.**
The three hero merchants were stocking these sets up to level 55 and no
further, even though the higher pieces existed in full. All three tiers are
now available at the same counters.

**Chip wars last longer.**
The war crystals now take considerably more punishment before going down.
The intent is to give a race that loses the opening push the time to actually
mount a counter-attack, instead of the war being decided in the first
minutes.

**Six MAU ammunition types did nothing.**
They could be loaded and fired, and they were not linked to any weapon, so
they simply had no effect. They work now.

**Three different helmets all called "White Dragon Bone Head".**
They are a full helm, a pair of goggles and an amice, and they now say so.

**Archon helmets no longer show on male Bellato and Cora characters.**
This one is deliberate, and it is a step backwards that we chose on purpose.
These helmets had no artwork of their own for male characters — the original
developers never made any. What we had been doing was borrowing the look of
other helmets, which meant your Archon helmet looked like somebody else's
gear, and at some tiers like a beginner's headband. The official game does
not show them at all, so neither do we now. The helmets still work and still
give their stats; they are just not drawn.

**Two character texture packs.**
Updated default textures for female Cora and female Bellato.

## 2-3 October 2026

**The banker refused deposits that should have fit.**
The gold ceiling the banker checked against was out of date, so perfectly
valid deposits were being turned away.

**The auction house now works across all three races**, and it announces
notable listings in-game.

**A cash-shop grenade that did no damage at all.**
It fired, it was consumed, and it dealt nothing — while being on sale. Fixed.

**Craft recipes at the level 67 tier have been brought in line with the
official game.** A few dedicated recipes were a large shortcut around the
normal crafting odds; the official game does not have them, and now neither
do we. The standard recipes for those items are untouched.

**Armour appearance aligned with the official game** on a large batch of
sets. Only the 3D model changed — stats, effects and defence are identical.

**Female Archon helmets** now show the right model at every tier.

## 1 October 2026

**Daily quest rewards you could not actually use.**
Several daily quests handed out an experience potion locked to a level range
below the quest's own. If you were at the top of the bracket, the potion simply
refused to be drunk — you had earned a reward you could not touch. Thirty
quests were affected. They now give the potion that matches their own level
range, the six highest-tier quests give one at all (they gave none), and the
quantities now match what the quests were meant to hand out. Several of them
also hand out a travel scroll and a crystal shard they were supposed to include
and did not.

**The Sympathy Charm did nothing at all.**
A player reported it, ran the comparisons himself, and he was right: the charm
had no effect on an animus whatsoever. This was not a value set too low — the
bonus it was designed to give had simply stopped being read by this version of
the game. We have reimplemented it. It now adds to your animus's attack while
the charm is in your inventory, it stacks up to a ceiling, and it is not
consumed. The charms are also on sale again at the Cora merchants, where they
had quietly stopped being stocked.

**Trade your hunting time for a Premium Pass.**
A new option at the premium NPC: if you are not premium, the time you spend
actually hunting can be exchanged for a pass. Five hours of hunting buys one
day of premium, so thirty-five hours for the seven-day pass. The counter
follows your account rather than a single character, it survives relogging, and
only time with real activity counts — standing still does not accumulate.

**Guard towers can no longer be placed almost on top of each other.**
We had loosened the minimum distance between two towers some weeks ago, after
it proved frustratingly large. Players pointed out it had gone too far the
other way. It is back to the original rule: a tower has to be placed clear of
another one's own radius.

**The server was stuttering, briefly but constantly.**
Short freezes, a fraction of a second, repeating. Everyone felt them at the
same moment because they came from the server itself, not from anyone's
connection. The cause was a setting on the machine that nobody had chosen — it
came from a default. Fixed, and measured before and after.


**A technical component of the client has been brought up to the current
official version.**
Nothing changes in how the game looks or plays — this is a background piece the
client loads at startup, and it is now the version shipped by the engine's
authors rather than the slightly older one we had been carrying. The launcher
applies it on its own; you do not need to reinstall anything.

Worth mentioning rather than leaving silent: this component sits close to the
graphics layer, and it is the first time we have updated it through the
launcher. It has been tested here and the game runs normally — but if you
notice anything odd at startup, or any display behaviour that was not there
before, please tell us on Discord or open an issue. We would rather hear about
it quickly than have someone struggle in silence.

## 29 September 2026

**Clicking a high-level crafting recipe could close the game.**
Opening the workbench was fine, but clicking certain recipes from levels 65 and
above shut the client down on the spot -- no message, no warning. It happened to
anyone who tried, not just a few people. It is fixed.

**Some crafting piece names are a little shorter.**
The pieces you combine into recipes now read, for example, "Lv.65 Type B Weapon
Piece" instead of the longer name they had. Same items, same recipes, nothing
else changed -- only the label.

## 28 September 2026

**Crafting above level 55 finally shows up at the workbench.**
The high-level recipes had been in the game for weeks, and nobody could see
them. The list stopped at level 55 no matter what you were carrying. The
workbench now goes all the way to level 75.

**Forty-seven new high-grade recipes come with it.**
They sit alongside the existing ones, in their own weapon and armour families.

**Several monsters have been rebalanced.**
Their health has been brought in line with the official values. Some are
tougher than they were here, some are easier.

**Boss rewards match the official rates again.**
A handful of the highest bosses were handing out their better grades far more
often than they should. That is corrected.

**Two new world bosses now appear.**
Huge Beacon and Stocker Lava show up on their own, and **their loot is open to
everyone** -- whoever lands the kill, anyone nearby can pick it up.
## 27 September 2026

**The Mid-Autumn skewers can be crafted again.**
The premium pork could not be split off a stack, so the combination was
impossible — the whole stack went in and the craft was refused. The pork carried
a time limit, and an item with a time limit cannot be split. The limit is gone.
Nothing was ever lost in the attempts: the server only removed one piece each
time, however the screen looked.

**Crafting a shield now raises the right mastery.**
It was crediting armour instead. Anyone who crafted shields was building a bar
that had nothing to do with what they were making.

**Mastery now rises in a straight line.**
The first craft used to jump you a long way and then progress crawled to a stop.
Every craft now advances you by the same amount, all the way to the top. Nobody
loses anything: those already at maximum stay at maximum.

**Chip war crystals last much longer.**
Wars were being decided in well under ten minutes on average. The crystals are
substantially tougher now, which should put a war in the half-hour range. We
will adjust again once we have seen a few real ones — tell us if it swings too
far the other way.

**Gold boxes were giving nothing at all.**
Opening one very often produced an error and no reward. The box was not consumed,
so nothing was lost, but nothing was gained either. That is fixed. The reward
list has also been widened: a gold box now draws from ten possible outcomes
instead of two.

**The rare gold-ore reward is rarer.**
It was coming up far more often than intended.

**Two discount coupons were worth almost nothing.**
They sold for a token amount, and did nothing else. They now carry a real value.

**Cash shop prices match the reference version.**
A large batch of prices had drifted; they are aligned again.

**The Ether return ticket can be bought at the level the map admits you.**
Entry was allowed several levels before the ticket could be purchased, which left
a gap where you could get in but not buy your way back.

**A jewel exchange ticket did nothing.**
The exchange its description promised was simply missing from our data. It has
been restored. Two lower-grade versions of the same ticket are still pending —
no source records what they were meant to hand back, and we would rather leave
them than invent a reward.

**The ghost at the accretia outpost should be visible again.**
It was declared twice in our data, and anything declared twice stops being drawn.
It also had no appearance files of its own; it now has them. Please tell us if
you still cannot see it.

**Changing class grants a different craft bonus.**
The free mastery levels given at a class change have been rebalanced. **This is
not retroactive** — characters who already changed class keep what they were
given.

## 19 September 2026

**The premium reward coupon is live.**
An NPC hands it out, and six exchange recipes let you convert it.

**Dungeon briefings are no longer blank.**
The eighty step-by-step instructions came up empty. They are now written, in
English.

**Six teleport scrolls can finally be bought.**
The Sky Battleground access scrolls were sold nowhere — not at a counter, not in
the shop. They are now on sale at the relevant merchants. A duplicate entry that
showed up at three vendors has been removed, and access to the central area,
which is high-level only, now costs considerably more in game currency.

**Incident fixed the same day: NPC buttons.**
For a while no NPC button responded at all — ingot changer, buff shop,
everything. The cause was a file deployed that morning; it was found and fixed
the same day.

**Server announcements are back.**
Announcement messages, including the red banner everyone sees, had stopped
showing.

## 15 September 2026

**Three dedicated buff NPCs, one per race.**
They are in place in the bases and working.

**A high-level training map is reachable.**
Bringing it online caused a server outage on the first attempt; service was
restored the same day.

**Evening fixes.**
The level boundaries of one training tier were wrong. Some monsters showed
neither a full body nor a full head. A boss princess had no loot. Two maps were
claiming the same index. And the buff button moved from a merchant to a
dedicated NPC.

## 13 September 2026

**Server-wide loot outage — two hours.**
For about two hours no monster in the game dropped anything at all, except the
event pigs. Cause found, service restored.

**Mid-Autumn event and assorted fixes.**
The skewer crafting chain broke at the second tier: repaired. Eight high-tier
gems added, twenty-nine ammunition types put on sale in the shop, three items
put back on sale and nineteen switched back on. One MAU consumable had its
duration shortened.

## 12 September 2026

**The gold cap in your inventory is raised substantially.**

**Crafting.**
668 recipe prices realigned, 573 recipes made available according to the item's
race, and 1,846 recipes added.

## 11 September 2026

**Morning outage.**
A batch deployed in the morning stopped the server from opening its login port:
nobody could get in. It was rolled back and service restored the same day.

**Afternoon fixes.**
Sixty-three set bonuses realigned. Six dungeon entry items finally show their
duration. Three boxes could return nothing at all. Twelve counter purchases can
again be paid in currency alone. One NPC had a misspelled name, and twelve NPC
dialogues still quoted prices that no longer applied: all rewritten, in all
three languages.

## 10 September 2026

**Crafting and the autumn event.**
2,438 crafting recipes added, 53 component groups, and the autumn event loot
placed on 42 lines. The crystal cost of 63 NPC-menu purchases was brought back
to reference values.

**One recipe granted a free tier upgrade**: removed.

**Two monsters were summoning up to ten and fifteen escorts**: brought down to
five.

**Loyalty loot on one boss**: twelve shields added.

## 9 September 2026

**Two bosses on a high-level map were invisible.**
They show up now.

## 8 September 2026

**One item crashed the game just by hovering over it in your inventory.**
Its description was longer than the window can render. 477 descriptions were
shortened.

**Invisible monsters on the neutral maps.**
Sixty-three monsters were hitting players without being visible. Fixed.

**109 potions had no effect at all**: repaired.

**Box contents.**
Two inverted probabilities, one wrong item handed out, and one wrong quantity:
fixed. Two event boxes are now dropped by nineteen monsters each.

**Fifteen item names in a high-level family** corrected.

## 7 September 2026

**The wrong monster was spawning at 412 spawn points.**
An index drift: repaired.

**Nineteen monsters on a new map were invisible**, with malformed names. Fixed,
and their official loot placed.

**Two dead portals crashed the game on click**: neutralised.
Portal labels were wrong on seventeen maps: corrected.

**Any level could use the restricted teleport scrolls**: the level cap is back.

**Appearance.**
105 armour models made visible, six guard towers got their effects back, 61
effect files reattached, and the Baphomet MAU parts recovered their original
grey. A high-level map had been deployed without its textures or lighting —
transparent ground — it is now complete.

**Descriptions.**
Some were printing their colour tags literally on screen. Some scrolls were
called "item 255". Fixed.

**Content.**
The 61-70 training school is open. The dragon tower gets its map, its boss and
its loot. The hit points of 119 monsters are realigned. Six cloak recipes turn
five parts into a cloak every time. 480 weapon recipes at the +4 tier and 93
potions whose effect was dead are now in. MAU secondary ammunition is repaired.

## 6 September 2026

**The client could not update — several hours.**
The update chain was broken. Repaired.

**Ten bosses were respawning in a loop.**
They were destroyed and recreated the moment they took a step, producing a
stream of spawn announcements with no matching death. Fixed.

**Content.**
A new gate leads to a relic area from a neutral map. Twelve bosses placed. Six
new daily quests, and the reset time moved earlier.

## 5 September 2026

**Sixty premium items were purchasable nowhere**: they are in the shop — premium
pass, jades, charms, generators. PC-Bang rewards were enriched, with nothing
taken away.

**Forty-three merchants sell 318 more items**, with nothing removed.

**242 item models had no visual effect at all**, including eleven high-tier
weapons. Rendered now. The twenty-two weapons of the top tier, which had none,
get one.

**Sixty-nine boxes returned nothing**: they are filled, and the same fix turns
on twelve cloaks and 201 guaranteed-content boxes.

**Animus: the eight curves are aligned on the reference version.**
Your animus becomes markedly stronger at level 80, gains its elemental
affinities and keeps progressing to the cap instead of flattening out around
64-65. In exchange, it is more fragile at intermediate levels.

## 4 September 2026

**196 crafting recipes for levels 63 to 75** are added, craftable by race.

**862 set bonuses were missing**: set effects now show on imported pieces.

## 3 September 2026

**A quarter of the weapon catalogue was invisible in hand.**
2,725 original pieces did not render once equipped — and never had. All
repaired. Forty recently added weapons also get their model.

**3,742 armour pieces were invisible once worn**: they render now.

**Armour: stats realigned on the reference version**, 3,588 descriptions added,
and the displayed defence of 713 pieces, which was wrong, corrected. Buy and
sell prices changed on roughly 5,100 pieces.

**1,170 weapons had no description at all**, or showed an internal label: they
are described now.

**Two items had picked up their neighbour's stats** — an event sword that had
become sellable and droppable, and a staff with an absurd resale price.
Restored.

## 2 September 2026

**The new guard towers were not appearing.**
They appear, animate, play their sound and deal their damage.

## 1 September 2026

**584 rings and amulets are added.**
Six of them were showing their internal code instead of their name, and their
icons were missing: fixed.

**The two Baphomet MAU arms could not be bought at the tuning shop.**
The purchase window never went through. It works now.

**The game froze while loading effects**: fixed.

## 31 August 2026

**The upgrade window shows up again.**
Right-clicking an item to upgrade opened an invisible window: nothing appeared,
but the game seemed frozen — you could no longer click on the world, and only
Escape gave control back. The window was in fact opening, but its background was
never drawn, because one graphics file sat in the wrong folder. Fixed.

## 30 August 2026 — evening

**Dragon armour is available.**
Two complete sets, **Fire Dragon** and **Aqua Dragon**, five pieces each —
helmet, tunic, leggings, gauntlets, boots — for all three races. The items had
always existed in the game but never had a 3D model, so they could not be worn.
That is now fixed.

## 30 August 2026

**The transport ship is visible at dock again.**
It did arrive at HQ and at the Ether Platform — the announcements said so, the
portal worked — but its hull stayed invisible during the stop. You would see it
take off and vanish right away: that was not an early departure, it was the
docked model failing to render. Fixed on both sides.

**MAU services available at the Ether Platform.**
Repair, tuning and ammunition refill now respond at the counter. Previously the
button opened but nothing went through, without any error message.

**Two clients per machine.**
You can now run two games at once from the same computer.

**Gold Points active.**
Capsules that convert into Gold Points now work. The total is capped at 999,999
points.

**Scenery.**
A few missing elements in the Forrest03 areas have been restored.
