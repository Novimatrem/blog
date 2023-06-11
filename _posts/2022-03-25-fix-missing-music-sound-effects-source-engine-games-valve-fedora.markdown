---
layout: post
title:  "Fix missing music/sound effects in Source Engine games (Valve games, etc.) on Fedora"
date:   2022-03-25 08:15:00 +0000
---
## Fix missing music/sound effects in Source Engine games (Valve games, etc.) on Fedora
#### by zoey Whitehat (novimatrem.uk)
*Released: 25/Mar/2022 at 08:15AM*

Hello- I've switched to using Fedora, kinda recently, and unfortunately, it has a bit of an issue regarding completely skipping playing certain audio files during Valve's games. None of this causes any crashing, but can lead to a worse gaming experience, confusion, and the appearance of buggyness- and generally isn't great. To work around this, please refer to the following steps, and all the games' audio will then work perfectly.

You need to open your Terminal emulator, either from the usual application menu place, or by using the keyboard shortcut Ctrl+Alt+T, or sometimes it's Super+T
AND THEN type the following into it, entering your password when it prompts you.

```

sudo su
sudo setsebool -P selinuxuser_execheap 1

```

That's it.
Your game will now function as intended, enjoy being able to hear the soundtracks, music, sound effects, etc! Especially 'Still Alive', and the banger that Half-Life 2's soundtrack is, amongst others.

valve pls fix

...

You can e-mail me with thoughts, feedback, etc. at [TheNovimatrem@protonmail.ch](mailto:TheNovimatrem@protonmail.ch)

...

![face2](https://gitlab.com/Novimatrem/blog/-/raw/master/face2.png)
