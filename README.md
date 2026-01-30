 This is a repository that will help you create your own mod! All images, videos, and even scenes are loaded from here! All you need to do is fork this repository and enter the link to your mod in the Friday Night Funkin AI Engine, specifically: `https://raw.githubusercontent.com/<Your Github nickname>/<Repository name>/refs/heads/main`

# How to add songs from mods or the original FNF?

1. Copy the `Chart` folder from `FNF GAME/assets/data/songs/<song>` to `GITHUB/songs`
2. Copy the instrumental and vocal audio files from `FNF GAME/assets/songs/<song>` to `GITHUB/songs/<song>`
3. Done. The song should work if you load it manually by name.

# Cool, we've figured out songs. What about characters?

1. Copy the JSON file from `FNF GAME/assets/data/characters/<CHARACTER NAME>` to `GITHUB/assets/characters`
2. Copy the XML file from `FNF GAME/assets/shared/images/characters/<CHARACTER NAME>.xml` to `GITHUB/assets/characters`
3. Copy the PNG file from `FNF GAME/assets/shared/images/characters/<CHARACTER NAME>.png` to `GITHUB/assets/characters`
4. Done, BUT... *read the text below*

# Characters from FNF >1.0.0 are harder to import!

FNF >1.0.0 splits sprites into multiple PNG files. For example, for Pico you need to copy not only `Pico_Playable.png`, but also `Pico_Censored.png`, `Pico_Shooting.png`, `Pico_Death.png`, `pico-cheer.png`, `pico-yeah.png`, `Pico_Intro.png`, and `Pico_Burps.png`. Unfortunately, you can only tell which PNG files need to be downloaded after you examine the character's JSON file.