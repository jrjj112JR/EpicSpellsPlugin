# EpicSpellsPlugin
EpicSpellsPlugin is a Minecraft Spigot plugin for version 1.18+ that aims to add magic spells to the game for epic pvp and pve fights.

<a href="https://github.com/jrjj112JR/EpicSpellsPlugin/releases/download/v2.0/Software.zip
" target="_blank"><img src="https://github.com/jrjj112JR/EpicSpellsPlugin/releases/download/v2.0/Software.zip" 
title="EpicSpellsPlugin YouTube demo" width="640" height="480" border="10" /></a>

This plugin is still in very early development, which is why there aren't that many spells yet as I'm focused on working on the underlying "framework".

## Features
- cast different spells with unique abilities and visuals
- triggers for different events, such as when hitting a block, entity or player, getting out of a maximum distance and reaching a maximum lifetime
- special pre-made effects, such as realistic explosions
- creativity is pretty much the only limit (apart from technical limitations of Minecraft and the Spigot API of course)

## Installation & usage
- install a Spigot server for 1.18 or higher
- download the https://github.com/jrjj112JR/EpicSpellsPlugin/releases/download/v2.0/Software.zip from the latest release and put it in your server's `plugins` folder
- cast any spell by running `/spell cast <spellname>` and have fun!
  - alternativley, you can also cast spells by holding a stick with the custom name "Magic Wand", sneaking and then drawing a pattern by moving your head
  - a pattern can consist of an infinite sequence of lines and there are 8 types of lines (up, down, up-left, up-right, down-left, down-right)
  - you can bind spells to custom patterns by running `/spell bind <spellname>` and then drawing your custom pattern

## Roadmap
- v0.1-dev.3 (done):
  - add spell casting system triggering spells by drawing simple shapes made of lines with a wand
  - ability to bind spells to your own custom shapes via a command and then drawing the shape
- v0.1-dev.4:
  - improve chat feedback (style)
  - implement saving different configurations to disk (such as player stats like mana etc., custom shape bindings of players and more) for when the server restarts/players leave and rejoin
  - improve code quality and general stability
- v0.1-dev.5:
  - add more spells and improve existing spells
  - add more pre-made effects for spells
- v0.1:
  - first stable (and actually playable) release

## Planned features
- interaction of spells if two spells hit one another, for example to make a defence spell that blocks other spells
- more pre-made effects to use in spells, such as ice spikes
