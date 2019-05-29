# Kirby & The Amazing Mirror (JP) Randomizer
This is a multi-feature randomizer for the Japanese release of Kirby &amp; The Amazing Mirror. It currently allows for the randomization of rooms, items and chests, spray paint palettes, ability stands, and the music.

# Setup
Here is what you need in order to play a randomized KatAM ROM:
- This randomizer, which comes with a folder of JSON files, the readme (this!), credits, and the licence info.
- A Gameboy Advance emulator of your choice.
- A Japanese version of Kirby & The Amazing Mirror (This randomizer will eventually be updated to work with all three releases of the game, but currently only the Japanese version works because each version stores data in the ROM in different spots).

After you've got what you need, simply start the EXE, set the paths to your ROM and where you want the randomized ROM to be created, select your settings, and hit generate!

# Options
Currently you're able to randomize these settings:
- Seed number: This number sets the RNG seed. The RNG seed gets reset to this number after every task of the randomizer, so if you randomize mirros and items with seed number 12, you'll have the same randomized item layout if you make another ROM with seed 12 and just randomize the items and leave the mirrors alone.
- Randomize the mirrors: Randomizes where the mirrors take you. The mirrors are randomized in a way so you can beat all 8 bosses and get to the credits. Enabling this presents further options:
  - Total Random mode: By default, mirror are only randomized with mirrors of a similar type, e.g. two-way mirrors (mirrors that have a big star above them) and one-way mirrors (mirros that have a smaller star above them). Enabing Total Random turns this off, and shuffles everything together.
  - Randomize hub mirrors: The hub mirrors are not randomized by default, allowing them to act as checkpoints back to the main hub. You can randomize these as well if you want to *really* hate yourself. This option is not available if you're playing on total random mode.
- Randomize items and chests: This makes it so all the overworld 1UP, health items, batteries, candies, and chests are scrambled with one another. This mode changes all big chests to small chests (they'll still have the same contents, it's just an aesthetic change).
- Randomize ability stands: Feel like having wheel and smash in the first Peppermint Palace switch room? You might if you're lucky enough.
- Randomize spray palletes: This changes how each of the spray paint colours look. It can lead to some particularily...funky looks for Kirby.
- Randomize music: Nothing screams "final boss showdown" lounder than the main menu loop.

Once you've checked off what you want to randomize, hit the Generate button, and play your ROM!

# In Closing...
If you enounter any problems running the randomizer, please please please report it to the Randomizer GitHub page (either the master branch if you're using a release version, or the test-branch if you're testing out one of the new features slated for next release). It can't be fixed if I don't know about it!

I hope you have fun playing!
