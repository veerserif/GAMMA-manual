# Inventory

The inventory is a vital element of the game and you'll be staring at it a lot. Since progression in G.A.M.M.A. is largely dictated by the gear you have equipped, you will be staring a lot at the stuff you have - or don't.

[<img src="https://github.com/cwylo/GAMMA-manual/blob/main/images/inventory/inventory.jpg" alt="A screenshot of the G.A.M.M.A. inventory." width=800px>](https://github.com/cwylo/GAMMA-manual/blob/main/images/inventory/inventory.jpg)

The inventory displays your stalker's name, current faction, rank, amount of money (in rubles &#x20bd;), max carry weight, and all the items currently on you. It also displays currently-equipped items, resistances to damage, and the state of your health, hunger, thirst and tiredness meters. It is also the central place from which you can interact with items and access the crafting interface in G.A.M.M.A.

## Inventory-specific keybinds

Certain keybinds function differently on the inventory screen. By holding down certain modifier keys and mousing over items, players can perform certain quick actions. These keys are marked as `(on hover)`, meaning that they only work if players hover over an item then press that key.

| Key | Action |
|---|---|
| Right click | Open action menu |
| Shift (on hover) | Quick transfer |
| L Ctrl (on hover) | Show stats at 100% condition |
| L Alt (on hover) | Disassembly safety (disabled by default) |

## Items

All items are displayed on the right hand pane. Individual items cannot be reordered, but they can be interacted with by either right-clicking them to open up an action menu, or double-clicking them to perform the default action (e.g. equipping gear, using toolkits).

Usable items include consumables (meds, food, drinks, cigarettes), repair items, repair kits and maps or PDAs. Double-clicking them or selecting "Use" after right clicking will allow you to look at, consume, or open up the crafting menu depending on the chosen item.

Some items can be stacked. Stacks of items can be selected and opened by left-clicking on them. The stack will be then displayed in the center pane, where resistances are normally shown. Some items that have "charges" or multiple uses can be combined together if in a stack - for example, you could combine two matchboxes that each have one use left to make one matchbox with two uses. Since item weight is dependent on the _number_ of items, and not the _number of uses_ of each item, combining items can be an effective way to save weight.

Items can also be favourited through the right-click menu. A favourited item is pinned to the top of the inventory. It will also be pinned to the top of any trader's inventory, allowing you to view and buy favourited items more easily.

Junk items are the inverse of favourited items. Items marked as "junk" are always sorted last and therefore declutter the rest of your inventory.

### Sorting

Items are [sorted from top to bottom](https://www.moddb.com/mods/stalker-anomaly/addons/sorting-plus):

* Favourited items
* Loadout items (if enabled)
* Magazines (if playing with Mags Redux)
* Weapons (guns, melee weapons, explosives)
* Suits and helmets
* Artifacts (in or out of containers)
* Devices (receivers, detectors etc.)
* Tools, repair kits and other kits
* Medical items
* Food and drink
* Quest items and letters
* Ammunition
* Mutant parts
* Upgrade kits
* Crafting parts and broken items
* Faction patches
* Items set as junk

You can also quick-scroll to these categories by pressing the number keys or clicking the icons at the bottom of the center pane. 

## Equipment

[<img src="https://github.com/cwylo/GAMMA-manual/blob/main/images/inventory/equip.jpg" alt="A close-up of the G.A.M.M.A. inventory's equipment section." height=680px>](https://github.com/cwylo/GAMMA-manual/blob/main/images/inventory/equip.jpg)

Equipped gear is displayed in the center pane. Each piece of equipped gear must fit in one of the visible slots, which only take certain types of items. 

The body slot is for suits. If the equipped suit has available belt slots, they will be displayed just above the resistances pane - in the above image, no belt slots are available, so there are lock icons on all five possible belt slots. Belt slots can be used to equip armor frames, ballistic plates, or artifacts that are in suitable wearable containers.

The head slot is for helmets and respirators. These provide the majority of your radiation and psy resistance. Different models of masks will have different vision overlays, and may be cleaned if wet or otherwise dirty with the `T` key.

The back slot is for backpacks. Backpacks increase your maximum carry weight. Better backpacks can be crafted, or bought as a last resort. Backpacks in your inventory can also be dropped to create a stash on demand.

Weapons can be slotted into one of four slots: primary, secondary, melee or vision. Despite the names of the slots, pistols, certain SMGs and melee weapons and binoculars ("one handed weapons") can be equipped to any of the four slots. Guns that need two hands to wield can only be equipped in the primary or secondary weapon slot.

The B6 slot corresponds to the `5` key by default, and is generally kept for bolts or spent shells. These can be thrown to trigger anomalies, enabling players to find safe routes through anomaly fields or trigger anomalies on purpose.

The G4 slot is for grenades and other throwables. Press the `G` key to quick-throw the item in this slot.

The head gear slot is used for headlamps and night-vision goggles. Headlamps are toggled with `L` and night-vision goggles with `N`.

The detector slot is used for RF receivers, anomaly detectors, glowsticks, and flashlights. Detectors can be dual-wielded with one-handed weapons - that is to say, knives, pistols, and bolts/shells.

The PDA slot is only used to equip PDAs.

There are four quick-item slots, F1 to F4. By dragging items to these slots, pressing the associated key will use that item. This is particularly helpful for healing items and other meds. A transparent icon means that there is nothing currently equipped to that slot. By default, F1 uses first-aid kits, F2 for bandages, F3 for army medkits and F4 for morphine.

## Resistances and meters

[<img src="https://github.com/cwylo/GAMMA-manual/blob/main/images/inventory/resistances.jpg" alt="A close-up of the G.A.M.M.A. inventory's resistances and meters section.">](https://github.com/cwylo/GAMMA-manual/blob/main/images/inventory/resistances.jpg)

Underneath the equipment pane and belt slots are bars representing various resistances and meters. In G.A.M.M.A., much like base S.T.A.L.K.E.R., there are seven types of damage (left to right, top to bottom):

* Radiation
* Psy or psychic damage 
* Acid damage
* Impact damage
* Electric damage
* Rupture damage
* Fire damage

Radiation damage is caused by radiation fields and certain artifacts (usually more powerful ones). 

Psy damage comes from psy fields and certain mutants, as well as a certain anomaly. 

Acid, electrical and fire damage are caused by different kinds of anomalies. Specifically:

* Burners and Comets cause fire damage.
* Fruit Punch, Gas and Gas Clouds cause acid damage.
* Electro and Tesla anomalies cause electric damage.

Impact damage comes from certain mutant attacks (anything that looks like a bodyslam, headbutt or charge), certain anomalies, and fall damage. Think of it as similar to "blunt force trauma".

Rupture damage comes from bullets, slashing attacks, and certain anomalies. For example, a boar's tusk swipe would do rupture damage. Any attack that looks like it would cut or draw blood should do rupture damage.

Hunger, health, thirst and tiredness meters are in the same pane as resistances. The health meter is the one with the heart icon, and can be increased by using certain medical items, most commonly medkits. Going to a medic NPC (found in certain faction bases) and paying them to heal you can also completely fix your health. Standing next to a campfire also provides a very small health regen effect.

Hunger is represented by the fork and spoon icon. Increase this by eating foods. Thirst is represented by the water drop, and can be increased with (non-alcoholic) drinks. Unlike other modern survival games, it is important to keep this full or close to full - even losing one or two bars out of five can already cause noticeable effects. A good rule of thumb is that if you can see the [[icon on your HUD|Keybinds-and-HUD#4-icons]], it's time to eat or drink.

Similarly, tiredness is represented by the bed icon.

## Trade and stash screens

Both of these screens operate similarly to the inventory, with minor differences.

# PDA