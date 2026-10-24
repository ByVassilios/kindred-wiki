# Settings and FAQ

## Mod settings

Options → Mod settings → The Rim by Night: Kindred.

Three pages: Rules, Display, and World and events. **Reset to defaults** sits at the bottom, and
with a game loaded so does **Remove Kindred from this game**.

| Setting | What it does |
|---|---|
| **Vampires** | |
| Sunlight damage | How hard the sun burns a vampire caught outside by day. At 0% it does no harm at all. |
| Blood used each night | The blood a vampire burns to wake each evening. Lower it if feeding takes up too much of the colony's time. At 0% they only need blood for healing and powers. |
| Experience gained | How fast vampires earn experience for new Discipline dots, Attributes and Virtues. |
| Frenzy checks | Added to the difficulty of every frenzy and Rötschreck roll. Above zero the Beast gets loose more often, below zero less. |
| Soften clan weaknesses | Each clan's weakness still applies, in a milder form. |
| **The Masquerade** | |
| Breaches have consequences | Outsiders who see a vampire at work carry the story away, and the world reacts: warier visitors, then hunters, then the Society of Leopold. Turn off to play without any of it. |
| How much a breach counts | How much each sighting adds to the colony's Masquerade breach score. |
| How fast breaches fade | How quickly the world forgets what it saw. Higher numbers bring the breach score down sooner. |
| **Interface** | |
| Discipline tiles | Put a vampire's powers on one small tile per Discipline. Turn it off to give every power its own full-size button, as vanilla does. |
| Kindred right-click submenu | Gather feeding, staking, the Embrace and the other vampire orders under one "Kindred" entry in the right-click menu. Turn it off to list them with vanilla's orders. |
| Power timers in the inspect pane | List a selected vampire's running powers and the time each has left in the bottom-left inspect pane, so you don't have to open the health tab. |
| Effects on the Kindred tab | Keep a vampire's buffs, powers that are switched on and other harmless effects off the health tab. They are listed under Active effects on the Kindred tab's Character page. Wounds and anything harmful stay on the health tab. |
| **Effects** | |
| Fighting motion | Blurred vampires dash at their foes, Potence knocks people back, and Kindred blows show on screen. Turn it off for plain vanilla melee. |
| Power auras | A faint glow around a vampire while a buff lasts, with a trail and a mark on its blows. |
| Bared fangs | Show fangs on a vampire's face when drafted, fighting, feeding or in frenzy. |
| Gore | How much blood a fight with a vampire spills, and whether cut-off hands, limbs and heads fly off and lie where they land. At 0 there are no sprays and a lost part is simply gone, as in vanilla. |
| **The world** | |
| NPC Kindred | How often vampires from outside the colony turn up: in the dark at night, in cryptosleep caskets, in rogue bands. 0% turns them off. |
| Extra courts in a new world | Every world gets one court of each sect and a haven for each Independent clan. This many more courts go to sects at random. Read when a world is made, or when the mod is added to a save. |
| Sleepers in ancient dangers | The chance that one casket in a new map's ancient danger holds a Kindred instead of a soldier. Also scaled by the NPC Kindred setting. |
| Background world | Courts changing by themselves while you play: coups, rival schemes, blood hunts and cities changing sect. Switched off, the courts stay as they are. |
| Sire calls | A sire out in the world calling on its childe with demands. |
| Wights come back | A vampire lost to the Beast who escapes the map returns now and then as a night threat. |
| **Events** | |
| Hunters | Hunters and investigators who come because of Masquerade breaches, and hunter raids. |
| Sect politics | Archons, Sabbat packs and Anarch gangs sent against the colony, infiltrators, thralls of outside Kindred, Anarch unrest, Assamite contracts, Setite corruption and Tremere hit teams. |
| Kindred attacks | Rogue bands, elder raids, and the angry dead coming back to haunt the colony. |
| Kindred visitors | Kindred at the door, Path mentors, the occult trader, the ghoul black market, the anonymous benefactor and revenants asking to join. |

## FAQ

**Can I add this to an existing save?**
Yes. Nothing changes until someone becomes Kindred. Courts are placed when the mod is first
loaded into the save.

**Can I remove it from a save?**
Yes, with the button made for it. Load the game, open the mod settings and press **Remove Kindred
from this game**. Every vampire and ghoul becomes mortal again, the mod's items, buildings,
creatures, factions, quests and sites are deleted, and the game is saved under a new name and
taken back to the main menu. Then turn the mod off and load that save. Removing the mod without
doing this first leaves the save broken.

**Do I need any DLC?**
No. It runs on Core alone and gets along with all the DLCs.

**Does it work with modded races?**
Yes, if the race is humanlike and has blood. The Kindred tab and recipes are added to every
humanlike race at startup, and nothing assumes a human body layout. A pawn with no teeth gets no
bite, and one with no heart can't be staked.

**What about other mods?**
The mod uses Harmony postfixes where it can, prefixed def names, and narrow XML patches. The full
patch list is in the mod's repository. Mods that cure or block mental states also work on frenzies.

**Will it slow my game down?**
It shouldn't. Non-vampires cost nothing per tick, and nothing scans every pawn on the map.

**My vampire won't eat / won't go to bed / won't let the doctor tend it.**
Kindred don't need food or rest the normal way, and only blood heals them. See
[Being Kindred](Being-Kindred.md).

**My vampire burned to death at dawn.**
Check the dawn alert, give every vampire a roof within reach, and build coffins. Vampires caught
outside try to dig in on soft ground, but rock and floors can't be dug.

**A colonist tried to kill my vampire in its sleep.**
That was a hateful mortal's "slay the monster" break. Watch for the warning thought and deal with
them early. See [Feeding](Feeding.md#how-mortals-feel-about-it).

**Hunters keep showing up.**
Your breach score is high. Stop making witnesses and wait for it to fade, or silence the
witnesses before they leave. See [The Masquerade and hunters](Masquerade-and-Hunters.md).

**My tavern shelf has no prices button.**
Build a tavern counter on the map. The prices are kept on the counter, so a shelf only shows the
button while a counter stands there, and a tavern area with no counter gets no guests. See
[The tavern](Tavern.md#prices).

**Does it work with Combat Extended?**
Yes. With CE loaded, the fangs and the mod's weapons become CE weapons, armour and the powers'
projectiles hit in CE's units, and the hunters' guns are CE guns that need no ammo.

## Dev mode

With dev mode on, the debug actions menu has a "Vampires" category. **Make vampire** turns a
colonist into a Kindred with rolled defaults, and **Open making menu** lets you choose instead.
The full list:

- Make vampire
- Hunting trip letter
- Slide pawn 4 cells east
- Throw item 6 cells east
- Sever a limb
- Sever every limb
- Spawn unidentified relic...
- Reveal torpor crypt
- Breach +10
- Breach -10
- Spawn hunter's notebook (a recent breach)
- Make investigator (hunter visitor)
- Benefactor: start, or next step
- Host Elysium now (skips the cooldown and night checks)
- Overt act here (witness scan)
- True Faith +1
- Make enemy thrall (outing soon)
- Make hunter infiltrator (strikes by day)
- Learn every court
- Earn a boon
- Send a shelter guest
- Send a sanctuary guest
- Reset court favours
- Fill court mission offers
- Start Elysium everywhere
- Open making menu
- Set clan
- Set Discipline dots
- Add Merit or Flaw
- Make 100 years older
- Make mortal
- Fill blood
- Empty blood
- Generation -1 (stronger)
- Generation +1 (weaker)
- Upkeep now
- Enter torpor
- End torpor
- Humanity -1
- Humanity +1
- Set morality (rating 5)
- Take the Path test now
- Golconda: ready for the Suspire
- Commit a sin (degeneration roll)
- Frenzy test (difficulty 6)
- Rötschreck test (difficulty 8)
- Add random derangement
- Derangement episodes now
- Clan weakness checks now
- Regard -0.2 (towards hateful)
- Regard +0.2 (towards devoted)
- Give 20 experience
- Restore willpower
- Log character sheet
- Run self-tests
- Log dice odds
- Bond step toward selected
- Vitae craving +1 stage
- Give vitae from selected
- Ghoul: skip 14 days
- Make revenant
- Diablerie by selected
- Ask for the Embrace

## Reporting a bug

Open an issue with:

1. what you did and what happened;
2. your `Player.log` (on Windows, in
   `%USERPROFILE%\AppData\LocalLow\Ludeon Studios\RimWorld by Ludeon Studios\`);
3. your mod list.

[← Contents](README.md)

---

<img src="img/dark-pack-logo.png" width="160" alt="Dark Pack logo">

This is not official World of Darkness material. Portions of the materials are the copyrights
and trademarks of Paradox Interactive AB, and are used with permission. All rights reserved. For
more information please visit worldofdarkness.com.
