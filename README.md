I'm a big fan of Talandar99's Planet Pelagos mod. The concept is awesome and it looks beautiful, but the author is a very stubborn person who insists their mods are played exactly the way they want, rather than allowing users to find their own fun.



The main Pelagos mod changes recipes for Cargo Ships to require them to be crafted and researched on Pelagos, which causes trouble for people like me who were already using ships on Nauvis prior to installing the mod. Unhappy with the change, users requested it be made an option, and when Talandar refused a mod was created to change it back. Talandar, in a very petty move, marked this mod as incompatible. When users started using older versions of the mod to avoid this, Talandar deleted them all from the mod portal, which could cause issues for people loading older saves. Not content with this pettiness, Talandar then programmed a "sanity check", a script that prevented the game from loading if sealant was removed from Cargo Ships recipes. He even put calls to the script in the mod that would crash your game if the script was completely deleted.



This is where I come into the story, I was so offended by the pettiness that I worked out how to disable his prevention script and updated the mod to revert the recipes, and I gave Talandar an ultimatum: quit it with these anti-player practises or I'd release a fork of Pelagos with the script removed. Talandar responded by deleting my thread immediately and changing the license to prevent people forking the mod. I decided not to respond immediately and got distracted from Factorio for a while until recently when I saw the same series of events had played out with a mod called Autobarrelling for Pelagos, right down to deleting old versions of the mod when people realised they could bypass his arbitrary restrictions.



So, here we are. I didn't wanna do it, but its come to this. This repository contains a fork of Pelagos 0.55.1, the last version released under GPLv3. The prevention script has been disabled and the dependencies modified to allow using v0.1.2 of Barrelling Machines, the last version compatible with Autobarrelling for Pelagos. I've also made Diesel Cargo Ships optional, and added support for my own fork of that mod. As of the time of upload, this mod is compatible with the latest versions of most of Talandar's mods, barring those that are updated to 2.1 and Diesel Machines, however it's **extremely** likely that Talandar will blacklist this mod from all future versions as well as take down the older versions this mod is compatible with. As a result, included in this repo is a .rar containing all of the dependencies and recommended mods that I run in my current save, all of which are confirmed to work with Pelagos CF. (All assets released under CC licenses are presented without modifications.)



My goal with this fork is to listen to community suggestions and provide a stable, functional version of the mod that won't be suddenly updated to break people's saves because they dared to have fun. As I'm still learning lua, I welcome contributions from the community to make this a true collaborative effort.



(Although the rest of the mod is released as GPLv3, the sound and music is released under CC-BY-NC-ND 4.0, and is presented without modification.)

