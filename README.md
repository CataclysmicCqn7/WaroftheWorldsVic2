# War of the Worlds

This Victoria 2 mod that brings H. G. Wells' *The War of the Worlds* to the Victorian world, bringing down the martian tripods to rein chaos upon the earth. In 1896, Martian cylinders begin falling on Earth. Fighting machines rise from the pits, the people around them are herded into pens, and humanity has to hold on until something stops the invaders. The contents of this mod are mostly based off the book, albeit the original inspiration to make this came from a friend, who in turn got it from the movie. For me this has been a long in development project, as I first started upon it a few months ago, but hit a pit stop when I both lost interest in vic2 and couldn't properly implement some features I wanted - but alas, I have suceeded! So now I'll try and bring this to fruition and make something that will be, very hopefully, at least playable.

> **Prototype.** As stated above, the mod is in prototype, playable but veeeery unbalanced and unfinished, and most art is placeholder.

## Requirements

- Victoria 2: Heart of Darkness (Duh)
- Runs on the base game, replaces some vanilla files (see [Compatibility](#compatibility)), so it doesn't combine with mods that change the same files.

## Installation

1. Download or clone this repository.
2. Put the `War of the Worlds` folder and `War of the Worlds.mod` into `Victoria 2/mod/`.
3. Enable **War of the Worlds** in the launcher.

## Features

### The invasion
- **Flashes on Mars (1894):** astronomers around the world notice strange flashes on the planet. (Options to add different times of appearance will be added later)
- **The first cylinder (1896):** it lands near Oxford, west of London. Britain can storm the pit before it opens, or send a deputation under a white flag. (Will have to change this, since it's very easy to preemptively crush the Martians)
- **The pit:** the cylinder unscrews, the crew emerges, and the first fighting machines are assembled. If humans take the pit in time, the landing is crushed. (Does the job, will probably tweak it a lot)
- **More cylinders** fall at every opposition of Mars, about every 26 months, at random places around the world (see [LANDING_SITES.md](LANDING_SITES.md)).

### The Martians
- **A new nation, the Martians,** with their own culture, religion and government. They fight without generals. (for now?)
- **Martian Tripod:** a heavily armed and armoured fighting machine.
- **Martian Amphibious Carrier and Martian Sea Strider:** a fighting transport and its escort, so the invasion can reach across water.
- **The Black Smoke:** the Martians use gas in battle, and can blanket nearby provinces with poison. (Gas attack defence lines up very nicely in 1900, so they don't become too overpowered)
- **No economy:** Martian units cost next to nothing; production is limited by time.

### Martian rule
- People in Martian lands are penned as slaves, and their land stops producing. (No RGOs and everyone becomes slaves)
- Provinces the Martians hold for long enough become theirs. (In lieu of being able to annex nations normally)
- The Martians attack every neighbour they aren't already at war with.
- The pens are culled to feed the Martians. (Mass pop death, yay)
- The Red Weed spreads out from Martian territory. (Reminder to declare wars on islands too)
- Nations that lose their capital for too long are swallowed whole. (May get rid of this)

### Humanity's response
- **The Great Truce:** human wars end when the Martians land. (Will definitely have to rethink how this exactly works, since it doesn't feel very natural?)
- **A Common Enemy:** great powers mobilise more easily, and can join a coalition against Mars. (To be tweaked)
- **Panic** spreads along the front, and London may have to be evacuated. (To be tweaked)
- **Captured Heat-Ray fragments** teach human armies to fight back. (To be tweaked)
- **Gas defence** becomes much easier to discover once the Black Smoke has been used. (As stated above)

### The end
Earth's bacteria slowly kill the Martians. Their armies weaken in four stages until the Martian empire collapses. The conquered lands return to their nations, and the rest falls to whoever holds the Martian capital. Human medicine speeds the end.

## Trying it out quickly

Start a game as the United Kingdom, open the console (`~`) and type `event 777110` to land the first cylinder immediately. Type `tag MAR` to play as the Martians. An option to normally play as them will definitely be added later, but this is a prototype for now so womp womp.

## Compatibility

The mod replaces these vanilla files with extended copies:

- `common/countries.txt`, `cultures.txt`, `religion.txt`, `governments.txt`, `cb_types.txt`, `event_modifiers.txt`, `issues.txt`
- `inventions/army_inventions.txt`
- `interface/buildunit.gui`, `interface/unitpanel.gfx`
- `gfx/interface/unit_strip.dds`

## Credits

Based on *The War of the Worlds* by H. G. Wells (1898). The Greater Flavor Mod (GFM) was used as a scripting reference.
