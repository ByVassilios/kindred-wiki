# The tavern

A tavern earns silver and brings mortals in after dark. For the colony's Kindred that means
vessels who walk in on their own, and more for the Masquerade to worry about. It works in any
colony, with or without vampires.

## Setting one up

1. Build a **tavern counter** (Furniture tab, no research). It is also storage, set to drinks,
   drugs and meals.
2. Stock the counter, and any shelves in the tavern, with what you want to sell.
3. Optionally, paint a **tavern area** from the zone tab. The tavern is the counter's room (or the
   ground within 6 cells of it out in the open), plus any painted tavern area joined to that room,
   such as a patio through the door. Paint the door too, or the patio isn't joined. A counter
   standing on painted area out in the open makes that whole patch of area its tavern.
4. Optionally, mark beds **For guests** (any humanlike bed or coffin, modded beds too: with Ideology it is in the bed's For colonists / prisoners / slaves menu, without it a button of its own). Vampires staying with the colony, such as a fostered childe, sleep the day in these beds for free.

There is no barkeep. Guests serve themselves and leave the silver on the counter, and haulers
carry it off.

Each counter is its own tavern, with its own prices, guests and night. A map can have several.

## Prices

The counter's **Prices** button sets the price for everything, from 75% to 300% of market value
(125% to start), or opens **By ware...**, a list of everything in the tavern where you can type
a price in silver for each ware. A ware with no price of its own sells at the counter's. Every
shelf in the tavern shows the same button, but only while a counter stands on the map, since the
prices belong to the counter.

Guests pay a fair price without thinking twice. Above it, fewer of them buy, and none at all once
the price is a full market value over fair. Fair starts at 125% and rises:

- with an impressive tavern room, half a percent per point;
- by up to 25 points for a friendly faction;
- by 25 points once the guest is drunk;
- by 50 points while a vampire's Awe is in the tavern.

A guest who turns a ware down shows "Too dear" over its head.

## The guests

Most evenings (every 0.7 to 1.5 days) four to ten guests come from the factions that aren't
hostile, with one more for every 15 points of the tavern room's impressiveness. One night in five
is a busy night with twice the crowd, up to 20. They come one to three at a time through the
evening, each party from its own faction, so the room fills with a mix. They buy a round, then sit
at the tables, stand about talking or wander the tavern, buying another round now and then. They
toast each other, boast and tell stories of the road, which shows over their heads and in the
social log. Drinks, drugs and meals are used on the spot. Anything else goes home with them. Each
party goes home after three to ten hours, or after the night's sleep if it rented a bed. Once you
have a vampire and know a friendly court, one or two of its Kindred mix with them. They buy only
blood, feed on herd in the tavern and leave two hours before dawn.

Friendly visitors and a trade caravan's guards already on the map drop in after dark too, one or
two at a time. The trader and its pack animals stay put.

### Who may come

The counter's **Guests** button opens a window with every kind of guest the loaded mods know, as a
tree of checkboxes: mortals, then Kindred by sect, and with the other mods the Garou by tribe and
their Kinfolk, mages by Path, and hunters. A new counter, and any counter from an older save, lets in
mortals and Kindred of every sect, which is what the tavern always did: only the sect of the nearest
friendly court actually comes. **Only Kindred** at the top of the list turns the counter into a
Kindred-only room.

The window also shows who of the kinds let in hates whom, the odds of a fight on a night, your other
taverns side by side, and how many guests a night here brings and about what they spend. A row
dimmed grey can't come right now; its tooltip says why. A guest let in at more than one of your
taverns goes to the one without anyone it hates in it, and failing that the emptiest.

### Fights

Guests who hate each other can come to blows, but only once one of them knows what the other is.
Mortals are plain to see. A vampire passes for mortal until something gives it away: Auspex (Aura
Perception), a Garou's nose, a hunter's second sight, Mage Sight, a power used where your colonists
can see, or a kind your colony already has.

Each hour both are inside, such a pair can roll. The roll is in the roll log: Temper dice, one more
for drink and one for a crowded room, two fewer on neutral ground, one fewer for each bouncer and
for a host with a calming power such as Awe. One or two successes are words and a shove, three a
brawl (vanilla's social fight), five a killing: the two fight and the winner finishes the loser.

- **Neutral ground.** A toggle on the counter: an Elysium, the Litany's truce, the Consilium's
  peace. Guests are slower to fight, but a vampire who kills under Elysium is blood hunted, and a
  Garou who breaks the truce leaves for the sept's judgment.
- **Bouncers.** Pick one or two colonists on the counter. Each one in the tavern counts fully; any
  other drafted colonist there counts half.
- A guest killed in the tavern costs regard with its sworn home, if you have one with its people,
  and its home hears of it. The loser of a brawl costs a little too.
- Sabbat Kindred see the mortals around them as prey. Let both in and expect trouble.

### Regulars

A guest who bought something or rented a bed, and left without finding a price too dear, getting
into a fight or running off, becomes one of the tavern's **regulars**. The tavern keeps six, and the
oldest makes room for a new one. Regulars come back now and then with friends from their faction,
and a message tells you who is back.

### What happens on a night

Up to two of these happen on a night, about three hours apart while guests are inside:

- **A brawl.** A drunk guest picks a fist fight with another. Neither comes back as a regular.
- **A traveller's tale.** Once a night at most, a guest tells of a trade caravan on its way, of
  raiders asking the road to the colony (both arrive in one to four days), or of a stash out in
  the wilds, which is offered as a quest.
- **Passed out.** A drunk falls asleep in a free guest bed or on the floor, and leaves 10 to 40
  silver for the trouble on waking.
- **A round for the room.** A guest buys for everyone. For the next hour every guest inside buys
  one more drink whatever the price.
- **Dice with the house.** A guest bets 20 to 60 silver. Half the time the stake lands on the
  counter, half the time the guest takes it from the silver lying in the tavern.
- **A drifter.** Rarely, a guest tired of its own people asks to stay. Take it in and it joins the
  colony.

Some things come on their own:

- **A minstrel.** About one night in three, a party brings a minstrel. It plays an instrument
  standing in the tavern (Royalty or Ideology) or sings. While it plays, the other guests stay
  past their time and buy another round twice as often.
- **Dine and dash.** Now and then a guest, twice as often a drunk one, takes a ware without paying
  and runs for the road. Arrest it to get the ware back, though its faction won't like it.

The **Open** toggle on the counter closes the tavern. Guests already inside finish their visit,
and no new ones come.

## Guest beds

A bed marked for tavern guests is rented for 15 silver a night, plus a little for an impressive
bedroom. The guest goes to bed in the small hours and leaves after it wakes. Keep the bed
unowned, or a colonist with no bed of its own may claim it. With no beds marked, no rooms are
let.

If the Hospitality mod is loaded, its
guest beds stay its own and our guests use only beds marked here.

## Guests as vessels

- A guest asleep in a rented bed can be fed on. Whether it sleeps through is a roll, see
  [feeding on a sleeper](Feeding.md#feeding-on-a-sleeper). A drunk guest makes that roll easier.
- A drunk guest who is awake doesn't remember a careful feeding and isn't a witness. Anyone else
  who sees it still is.
- Under the "animals and willing" feeding policy or looser, the feeding AI takes such guests by
  itself, and it still won't feed where an outsider can see.
- A guest's drug high passes to the vampire who drinks from it, as with any vessel.

Now and then a Society investigator comes in with the guests, more often the worse the breach
score. See [The Masquerade and hunters](Masquerade-and-Hunters.md).

## The Kindred club

The tavern's night twin. In a newer colony, pick **Only Kindred** in a counter's Guests window
instead. A map that already has a **Kindred club** area keeps it, and its zone buttons; a counter
inside it works as below.

- Once you have a vampire and know a friendly court, two to five of the nearest such court's
  Kindred come one or two at a time through the night and stay until two hours before dawn. A finer room brings them more often.
- The club's shelves sell only blood: vials, Kindred vitae and hemogen, at the blood market's price
  plus your markup.
- **Herd.** Prisoners and slaves get a Herd toggle. Guests feed on herd standing in the club and
  leave silver on the counter, more for a healthy vessel and a finer room. Nobody is fed on past
  the safe line.
- **Rumours.** Now and then the guests' talk becomes a letter with something real in it: a sept
  (with Werewolf) or hunter cell (with Hunter) you didn't know, a raid that will come in so many
  days, or a plot at a court you know. A finer club talks more, and it never tells you the same
  thing twice.
- Mortal tavern guests never step into the club, and a second counter outside it runs an ordinary
  tavern.

[← Contents](README.md)

---

<img src="img/dark-pack-logo.png" width="160" alt="Dark Pack logo">

This is not official World of Darkness material. Portions of the materials are the copyrights
and trademarks of Paradox Interactive AB, and are used with permission. All rights reserved. For
more information please visit worldofdarkness.com.
