# Release History

Reconstructed chronology and content of TeamFortress Quake releases.

The goal is ascertain exactly what was released and when.

Related: see [releases on cds](research_cds.txt), [homepages](research_homepages.md), [resources](resources.md)

## v1.0

Released as `fortv1_0.zip`.

Uploaded to `ftp.cdrom.com` in the directory `/pub/idgames2/quakec/teamplay/`:

```text
fortv1_0.txt           22-Aug-96 06:10     8k
fortv1_0.zip           23-Aug-96 19:05    69k
```

-- [http://www.cdrom.com/pub/idgames2/quakec/teamplay/](https://web.archive.org/web/19961225222656/http://www.cdrom.com/pub/idgames2/quakec/teamplay/) (archived)

Robin Walker (programmer) announced the release on USENET in `rec.games.computer.quake.announce`:

```text
Multiple PlayerClasses QuakeC Patch.
Robin
22 Aug 1996

Announcing TeamFortress v1.0: (Excerpt from readme)

*==============================================================*
* TeamFortress v1.0 *
*==============================================================*
Introduction
------------

TeamFortress is a new QuakeC patch which radically changes
team games. It provides far more incentive for teams to
actually work as a team. Each member of the team has unique
weapons, items, and abilities.

Player Classes
--------------

TeamFortress uses multiple player classes. Whenever a new map is
loaded,
all players start as an Undefined class. This class has 1 health, an
axe,
and cannot pick up anything. Once a player class is chosen, you cannot
change class for the rest of that level. To choose a class, just use
the
appropriate impulse. (See Impulse Summary)
The classes implemented so far are as follows:
SCOUT: Fastest moving class. Can only wear a small amount of the
lowest absorption armor. Limited to the 2 Shotguns and Nailgun.
Low ammo levels.
Carries a Motion Detector, 2 grenades, 3 concussion grenades.

SNIPER: Medium speed. Wears only small amount of armor, upto medium
absorption level. Limited to Nailgun and Sniper's rifle. Medium
ammo levels.
Carries 2 grenades.

SOLDIER: Slowest moving class. Wears large amount of armor, at all
absorption levels. All normal weapons except Grenade Launcher.
High ammo levels.
Carries 4 grenades, 4 nail grenades.

DEMOLITION MAN: Medium speed. Wears medium amount of armor, upto
medium absorption level. Uses the ShotGun and Grenade/Pipebomb
Launcher. Carries 1 DetPack, 6 grenades, 4 Mirv Grenades.

COMBAT MEDIC: Medium speed. Wears medium amount of armor, upto medium
absorption level. Uses both Shotguns and the Super Nailgun.
Carries Medikit, 3 grenades, 2 concussion grenades.
Regenerates slowly.

==================================================================

Uploaded to ftp,cdrom.com and ftp.stomped.com
Source included, no progs.dat.

This is a _team_ patch. It is a lot of fun to play single player, or
deathmatch, (especially the sniper's rifle :), but it is designed for
team games.
If you've got a bunch of friends and play games regularly on a LAN,
this is the patch you've been looking for.

(If I may say so myself :)
---
Robin. (Bro in Quake)
wal...@netspace.net.au
Robin.
wal...@netspace.net.au
"Can you help me remember how to smile? Make it somehow all seem worthwhile?
How on earth did I get so jaded? Life's mysteries seem so faded..."
```

-- [rec.games.computer.quake.announce](https://groups.google.com/g/rec.games.computer.quake.announce/c/-LVYmqQGn1o/m/WoufJcw3PZAJ)


The file timestamp suggests that `fortv1_0.txt` was uploaded early on August 22nd 1996 and that `fortv1_0.zip` was uploaded later the next day.

```text
-rw-rw-r--  0 0      0        3262 10 Aug  1996 QUAKE/FORTRESS/SOUND/WEAPONS/SNIPER.WAV
-rw-rw-r--  0 0      0       12429 17 Aug  1996 QUAKE/FORTRESS/SOURCE/BOSS.QC
-rw-rw-r--  0 0      0       34596 21 Aug  1996 QUAKE/FORTRESS/SOURCE/CLIENT.QC
-rw-rw-r--  0 0      0        6221 18 Aug  1996 QUAKE/FORTRESS/SOURCE/COMBAT.QC
-rw-rw-r--  0 0      0       31290 21 Aug  1996 QUAKE/FORTRESS/SOURCE/DEFS.QC
-rw-rw-r--  0 0      0       18316 17 Aug  1996 QUAKE/FORTRESS/SOURCE/HKNIGHT.QC
-rw-rw-r--  0 0      0       29795 15 Aug  1996 QUAKE/FORTRESS/SOURCE/ITEMS.QC
-rw-rw-r--  0 0      0       15094 17 Aug  1996 QUAKE/FORTRESS/SOURCE/MISC.QC
-rw-rw-r--  0 0      0       18282 21 Aug  1996 QUAKE/FORTRESS/SOURCE/PLAYER.QC
-rw-rw-r--  0 0      0         437 21 Aug  1996 QUAKE/FORTRESS/SOURCE/PROGS.SRC
-rw-rw-r--  0 0      0        9094 22 Aug  1996 QUAKE/FORTRESS/SOURCE/README.TXT
-rw-rw-r--  0 0      0       43706 22 Aug  1996 QUAKE/FORTRESS/SOURCE/TFORT.QC
-rw-rw-r--  0 0      0       34956 17 Aug  1996 QUAKE/FORTRESS/SOURCE/WEAPONS.QC
-rw-rw-r--  0 0      0       10681 17 Aug  1996 QUAKE/FORTRESS/SOURCE/WIZARD.QC
-rw-rw-r--  0 0      0       11059 17 Aug  1996 QUAKE/FORTRESS/SOURCE/WORLD.QC
```

The timestamps of files in the archive suggest the last modification was made on August 22nd.

## v1.1

Released as `tf1_1src.zip`.

It was likely uploaded to `ftp.cdrom.com`.

Robin Walker (programmer) announced the release on USENET in `rec.games.computer.quake.announce`:

```text
[UPDATE] TeamFortress Version 1.1
Robin
2 Sept 1996

Snipped from the readme.txt:
*==============================================================*
* TeamFortress v1.1 readme.txt *
*==============================================================*
Introduction
------------
TeamFortress is a new QuakeC patch which radically changes
team games. It provides far more incentive for teams to
actually work as a team. Each member of the team has unique
weapons, items, and abilities.

Player Classes
--------------
The classes implemented so far are as follows:
SCOUT: Fastest moving class. Can only wear a small amount of the
lowest absorption armor. Limited to the 2 Shotguns and Nailgun.
Low ammo levels.
Carries a Motion Detector, 2 grenades, 3 concussion grenades.

SNIPER: Medium speed. Wears only small amount of armor, upto medium
absorption level. Limited to Nailgun and Sniper's rifle. Medium
ammo levels.
Carries 2 grenades.

SOLDIER: Slow moving class. Wears large amount of armor, at all
absorption levels. All normal weapons except Grenade Launcher.
High ammo levels.
Carries 4 grenades, 4 nail grenades.

DEMOLITION MAN: Medium speed. Wears medium amount of armor, upto
medium absorption level. Uses the ShotGun and Grenade/Pipebomb
Launcher. Carries 1 DetPack, 6 grenades, 4 Mirv Grenades.

COMBAT MEDIC: Medium speed. Wears medium amount of armor, upto medium
absorption level. Uses both Shotguns and the Super Nailgun.
Carries Medikit, 3 grenades, 2 concussion grenades.
Regenerates slowly.

HEAVY WEAPONS GUY: The slowest moving class of all. Lotsa armor, high
absorption levels. Uses both Shotguns, the Nailgun, and
the Assault Cannon (yeah!)
Carries 4 grenades and 1 Mirv Grenade.

New Weapons
-----------
Sniper Rifle:
Assault Cannon:

Grenades
--------
The grenade types are as follows:
Normal
Concussion
Nail
Mirv

New Items
---------
Motion Detector:
Medikit:
Detpack:

New Rules
---------
Reloading:

ToggleAble Game Settings
------------------------
The options are:
Multiskin/Classkin
Class Persistence On/Off
Cheat Checking On/Off
FortressMap On/Off

Copyright and Distribution
--------------------------------------
Authors may use this code for the basis of other freeware quakec
code, but not for any for-profit code.

You may distribute this patch in any electronic format as long as this

textfile remains unmodified and all of the files in the archive are
present, and as long as no charge is made for it.

Quake Servers are free to run this patch, but it'd be nice in
you mailed us and mentioned that you are.

Availability
------------
The latest version of this patch can always be found at the
TeamFortress WWW page - http://minyos.its.rmit.edu.au/~cookj

The latest version should also be on the following locations:
ftp.cdrom.com/pub/quake/ <- check incoming, newstuff or
quakec/multiplayer
The Quake Stomping Grounds - http://www.stomped.com/files.shtml

Other things:
Advanced Team Support.
FortressMap support with Team spawnpoints.
NetServer Mode, which uses only standard Quake files.
Aliases for all commands.

------------
I'm happy to help with any questions about the source you have.
One thing that we took pains to do was to make almost _everything_
#defined.
You can 'tweak' 90% the game details just by editing the defs.qc

Robin. (Bro in Quake)
wal...@netspace.net.au
Quake TeamFortress WWW page - http://minyos.its.rmit.edu.au/~cookj

=======
Version info for those that interested:

-----------
Version 1.1
-----------
Features added:
- Help revamped.
- Aliases for Help, Detpacks, and Scanners added.
- Multiple Player skin support added.
- Added World Toggleables handling.
- Classkin and Multiskin Toggle added.
- Class persistence between levels Toggle added.
- Cheatchecking Toggle added.
- TeamFortressMap Toggle added.
- Detpack CountDown added.
- Scanner now gives directions of blips
- NetServer setting which uses no non-standard quake files
- TeamFortress Map Support (Yeah!!)

Classes: Scout, Sniper, Soldier, Demolitions Man, Combat Medic,
Heavy Weapons Guy.

Changes:
- Undefined players are now invincible, but can't move.

Bugs Removed:
- Detpack was spawning two objects.
- Gibbed while Reloading bug fixed.
- Dying while concussed bug fixed.

-----------
Version 1.0
-----------
Initial Release
Classes: Scout, Sniper, Soldier, Demolitions Man, Combat Medic


Robin.
wal...@netspace.net.au
"Can you help me remember how to smile? Make it somehow all seem worthwhile?
How on earth did I get so jaded? Life's mysteries seem so faded..."
```

-- [rec.games.computer.quake.announce](https://groups.google.com/g/rec.games.computer.quake.announce/c/Fzk7vCmp7MI/m/piBQXsNygawJ)


It appears on the `stomped.com` file area.

> TeamFortress v1.1	9/8/96	87K	TeamFortress is a new QuakeC patch which radically changes team games. It provides far more incentive for teams to actually work as a team. Each member of the team has unique weapons, items, and abilities. Also adds lots of weapons patches and misc stuff. Robin Walker and John Cook

-- [http://www.stomped.com/files.html](https://web.archive.org/web/19961219003113/http://www.stomped.com/files.html) (archived)

Link:

* ftp://ftp.stomped.com/pub/quake/quakec/multiplayer/tf1_1src.zip

The date suggests the release was September 8th 1996, this could be the date the file was added to the file area.

```text
-rw-rw-r--  0 0      0        3262 10 Aug  1996 QUAKE/FORTRESS/SOUND/WEAPONS/SNIPER.WAV
-rw-rw-r--  0 0      0       12429 17 Aug  1996 QUAKE/FORTRESS/SOURCE/BOSS.QC
-rw-rw-r--  0 0      0       37247 30 Aug  1996 QUAKE/FORTRESS/SOURCE/CLIENT.QC
-rw-rw-r--  0 0      0        6217 29 Aug  1996 QUAKE/FORTRESS/SOURCE/COMBAT.QC
-rw-rw-r--  0 0      0       35951 30 Aug  1996 QUAKE/FORTRESS/SOURCE/DEFS.QC
-rw-rw-r--  0 0      0       18316 17 Aug  1996 QUAKE/FORTRESS/SOURCE/HKNIGHT.QC
-rw-rw-r--  0 0      0       29795 27 Aug  1996 QUAKE/FORTRESS/SOURCE/ITEMS.QC
-rw-rw-r--  0 0      0       15094 17 Aug  1996 QUAKE/FORTRESS/SOURCE/MISC.QC
-rw-rw-r--  0 0      0        1713 30 Aug  1996 QUAKE/FORTRESS/SOURCE/MSKIN.QC
-rw-rw-r--  0 0      0       20424 30 Aug  1996 QUAKE/FORTRESS/SOURCE/PLAYER.QC
-rw-rw-r--  0 0      0        2598 27 Aug  1996 QUAKE/FORTRESS/SOURCE/PROGDEFS.QC
-rw-rw-r--  0 0      0         575 28 Aug  1996 QUAKE/FORTRESS/SOURCE/PROGS.SRC
-rw-rw-r--  0 0      0       21748 31 Aug  1996 QUAKE/FORTRESS/SOURCE/README.TXT
-rw-rw-r--  0 0      0       54741 31 Aug  1996 QUAKE/FORTRESS/SOURCE/TFORT.QC
-rw-rw-r--  0 0      0       11899 30 Aug  1996 QUAKE/FORTRESS/SOURCE/TFORTHLP.QC
-rw-rw-r--  0 0      0        2288 30 Aug  1996 QUAKE/FORTRESS/SOURCE/TFORTMAP.TXT
-rw-rw-r--  0 0      0        4548 30 Aug  1996 QUAKE/FORTRESS/SOURCE/TFORTTM.QC
-rw-rw-r--  0 0      0       38721 30 Aug  1996 QUAKE/FORTRESS/SOURCE/WEAPONS.QC
-rw-rw-r--  0 0      0       10681 17 Aug  1996 QUAKE/FORTRESS/SOURCE/WIZARD.QC
-rw-rw-r--  0 0      0       11059 17 Aug  1996 QUAKE/FORTRESS/SOURCE/WORLD.QC
```

The timestamps suggest the archive may have been created on August 31st.


## v1.2

Released as `tf1_2src.zip`.

The release was announced by John Cook on USENET:

```text
TeamFortress v1.2 released
John
10 Sept 1996

TeamFortress v1.2 has been released, check it out at
http://minyos.its.rmit.edu.au/~cookj/index.htm
or
ftp.cdrom.com/quake/quakec
Features:
Multiple player classes, each with own weapons and abilities.
Soldier, scout, combat medic, heavy weapons guy, demolitions man, sniper.
Enhanced teamplay functions. (after all, it is TeamFortress!)
New random class, player becomes a different class with each respawn.
Player is an observer until they choose a class.
Lots of new map handling features:
Autodetection of TeamFortress maps, different spawn points
for different teams, the map 'decides' how many different teams
are supported, highly functional goal entities with team goals,
goal groups, and lots of different stuff.
And lots more...

Cheers,
John

--
john cook co...@yallara.cs.rmit.edu.au
```

-- [rec.games.computer.quake.announce](https://groups.google.com/g/rec.games.computer.quake.announce/c/TM3wc_lgKUA/m/yNir0zxKZbwJ)

Contents of `tf1_2src.zip`:

```text
-rw-rw-r--  0 0      0         182  1 Oct  1996 FILE_ID.DIZ
drwxrwxr-x  0 0      0           0 27 Dec  1996 QUAKE/
-rw-rw-r--  0 0      0        1461 31 Dec  1995 ARSENAL.96
drwxrwxr-x  0 0      0           0 27 Dec  1996 QUAKE/FORTRESS/
drwxrwxr-x  0 0      0           0 27 Dec  1996 QUAKE/FORTRESS/SOUND/
drwxrwxr-x  0 0      0           0 27 Dec  1996 QUAKE/FORTRESS/SOURCE/
drwxrwxr-x  0 0      0           0 27 Dec  1996 QUAKE/FORTRESS/SOUND/WEAPONS/
-rw-rw-r--  0 0      0        3262 10 Aug  1996 QUAKE/FORTRESS/SOUND/WEAPONS/SNIPER.WAV
-rw-rw-r--  0 0      0       11059 17 Aug  1996 QUAKE/FORTRESS/SOURCE/WORLD.QC
-rw-rw-r--  0 0      0       12429 17 Aug  1996 QUAKE/FORTRESS/SOURCE/BOSS.QC
-rw-rw-r--  0 0      0       18316 17 Aug  1996 QUAKE/FORTRESS/SOURCE/HKNIGHT.QC
-rw-rw-r--  0 0      0       15094 17 Aug  1996 QUAKE/FORTRESS/SOURCE/MISC.QC
-rw-rw-r--  0 0      0       10681 17 Aug  1996 QUAKE/FORTRESS/SOURCE/WIZARD.QC
-rw-rw-r--  0 0      0        2598 27 Aug  1996 QUAKE/FORTRESS/SOURCE/PROGDEFS.QC
-rw-rw-r--  0 0      0         625  4 Sep  1996 QUAKE/FORTRESS/SOURCE/PROGS.SRC
-rw-rw-r--  0 0      0       30308  8 Sep  1996 QUAKE/FORTRESS/SOURCE/ITEMS.QC
-rw-rw-r--  0 0      0       14739  8 Sep  1996 QUAKE/FORTRESS/SOURCE/TRIGGERS.QC
-rw-rw-r--  0 0      0       10414  9 Sep  1996 QUAKE/FORTRESS/SOURCE/COMBAT.QC
-rw-rw-r--  0 0      0       40267  9 Sep  1996 QUAKE/FORTRESS/SOURCE/CLIENT.QC
-rw-rw-r--  0 0      0       41141  9 Sep  1996 QUAKE/FORTRESS/SOURCE/DEFS.QC
-rw-rw-r--  0 0      0       29557 10 Sep  1996 QUAKE/FORTRESS/SOURCE/TFORTMAP.QC
-rw-rw-r--  0 0      0       23908 10 Sep  1996 QUAKE/FORTRESS/SOURCE/PLAYER.QC
-rw-rw-r--  0 0      0       46829 10 Sep  1996 QUAKE/FORTRESS/SOURCE/WEAPONS.QC
-rw-rw-r--  0 0      0       64938 10 Sep  1996 QUAKE/FORTRESS/SOURCE/TFORT.QC
-rw-rw-r--  0 0      0        1712 10 Sep  1996 QUAKE/FORTRESS/SOURCE/MSKIN.QC
-rw-rw-r--  0 0      0       24713 10 Sep  1996 QUAKE/FORTRESS/SOURCE/README.TXT
-rw-rw-r--  0 0      0       14262 10 Sep  1996 QUAKE/FORTRESS/SOURCE/TFORTHLP.QC
-rw-rw-r--  0 0      0        9817 10 Sep  1996 QUAKE/FORTRESS/SOURCE/TFORTTM.QC
-rw-rw-r--  0 0      0       23632 10 Sep  1996 QUAKE/FORTRESS/SOURCE/TFORTMAP.TXT
```

The version we've acquired is a re-pack for distribution on BBS and then a magazine CD. The timestamps suggest the archive was created September 10th.

The readme in this release includes release dates for this and prior releases:

```text
...
--------------------------------
Version 1.2	- Released 11/9/96
--------------------------------
...
--------------------------------
Version 1.1	- Released 31/8/96
--------------------------------
...
--------------------------------
Version 1.1	- Released 24/8/96
--------------------------------
```

Version v1.0 is mistakenly listed as v1.1 (i.e. v1.1 is listed twice). The dates are close to what can be derived.

## v1.21

Released as the files, a binary and source release:

* `tf1_21pr.zip`
* `tf1_21sc.zip`


The versions of these release were repacked for BBS distribution and include additional `FILE_ID.DIZ`, `!WOHER!.TXT`, and `ARSENAL.96` files.

Content of `tf1_21pr.zip`:

```text
-rw-rw-r--  0 0      0       23632 10 Sep  1996 TFORTMAP.TXT
-rw-rw-r--  0 0      0       25730 17 Sep  1996 README.TXT
-rw-rw-r--  0 0      0      538572 17 Sep  1996 PROGS.DAT
-rw-rw-r--  0 0      0         169  1 Oct  1996 FILE_ID.DIZ
drwxrwxr-x  0 0      0           0 27 Dec  1996 SOUND/
-rw-rw-r--  0 0      0        1461 31 Dec  1995 ARSENAL.96
drwxrwxr-x  0 0      0           0 27 Dec  1996 SOUND/WEAPONS/
-rw-rw-r--  0 0      0        3262 10 Aug  1996 SOUND/WEAPONS/SNIPER.WAV
```

Content of `tf1_21sc.zip`

```text
-rw-rw-r--  0 0      0        7208 25 Jul  1996 FIGHT.QC
-rw-rw-r--  0 0      0         222 25 Jul  1996 JCTEST.QC
-rw-rw-r--  0 0      0        7892 25 Jul  1996 SHALRATH.QC
-rw-rw-r--  0 0      0        9554 25 Jul  1996 DOG.QC
-rw-rw-r--  0 0      0        9788 25 Jul  1996 MODELS.QC
-rw-rw-r--  0 0      0        4798 25 Jul  1996 MONSTERS.QC
-rw-rw-r--  0 0      0        9696 25 Jul  1996 KNIGHT.QC
-rw-rw-r--  0 0      0        7693 25 Jul  1996 PLATS.QC
-rw-rw-r--  0 0      0        2910 25 Jul  1996 BUTTONS.QC
-rw-rw-r--  0 0      0       16997 25 Jul  1996 DOORS.QC
-rw-rw-r--  0 0      0       14521 25 Jul  1996 AI.QC
-rw-rw-r--  0 0      0        9400 25 Jul  1996 OLDONE.QC
-rw-rw-r--  0 0      0       10739 25 Jul  1996 ENFORCER.QC
-rw-rw-r--  0 0      0        1697 25 Jul  1996 AMTEST.QC
-rw-rw-r--  0 0      0        9916 25 Jul  1996 DEMON.QC
-rw-rw-r--  0 0      0        7759 25 Jul  1996 FISH.QC
-rw-rw-r--  0 0      0        6062 25 Jul  1996 SUBS.QC
-rw-rw-r--  0 0      0        9837 25 Jul  1996 SOLDIER.QC
-rw-rw-r--  0 0      0        7128 25 Jul  1996 TARBABY.QC
-rw-rw-r--  0 0      0       12737 25 Jul  1996 SHAMBLER.QC
-rw-rw-r--  0 0      0         486 25 Jul  1996 SPRITES.QC
-rw-rw-r--  0 0      0       20120 25 Jul  1996 ZOMBIE.QC
-rw-rw-r--  0 0      0        3262 10 Aug  1996 SNIPER.WAV
-rw-rw-r--  0 0      0       11059 17 Aug  1996 WORLD.QC
-rw-rw-r--  0 0      0       12429 17 Aug  1996 BOSS.QC
-rw-rw-r--  0 0      0       18316 17 Aug  1996 HKNIGHT.QC
-rw-rw-r--  0 0      0       15094 17 Aug  1996 MISC.QC
-rw-rw-r--  0 0      0       10681 17 Aug  1996 WIZARD.QC
-rw-rw-r--  0 0      0        2598 27 Aug  1996 PROGDEFS.QC
-rw-rw-r--  0 0      0         625  4 Sep  1996 PROGS.SRC
-rw-rw-r--  0 0      0       10414  9 Sep  1996 COMBAT.QC
-rw-rw-r--  0 0      0       23632 10 Sep  1996 TFORTMAP.TXT
-rw-rw-r--  0 0      0         492 28 Oct  1996 FREE_EPC.TXT
-rw-rw-r--  0 0      0       14671 10 Sep  1996 OGRE.QC
-rw-rw-r--  0 0      0       14816 15 Sep  1996 TRIGGERS.QC
-rw-rw-r--  0 0      0       30572 17 Sep  1996 ITEMS.QC
-rw-rw-r--  0 0      0        2598 17 Sep  1996 PROGDEFS.H
-rw-rw-r--  0 0      0       23909 17 Sep  1996 PLAYER.QC
-rw-rw-r--  0 0      0       29557 17 Sep  1996 TFORTMAP.QC
-rw-rw-r--  0 0      0       14264 17 Sep  1996 TFORTHLP.QC
-rw-rw-r--  0 0      0       65015 17 Sep  1996 TFORT.QC
-rw-rw-r--  0 0      0        9818 17 Sep  1996 TFORTTM.QC
-rw-rw-r--  0 0      0        1713 17 Sep  1996 MSKIN.QC
-rw-rw-r--  0 0      0       46922 17 Sep  1996 WEAPONS.QC
-rw-rw-r--  0 0      0       41410 17 Sep  1996 DEFS.QC
-rw-rw-r--  0 0      0       40636 17 Sep  1996 CLIENT.QC
-rw-rw-r--  0 0      0       25730 17 Sep  1996 README.TXT
-rw-rw-r--  0 0      0         325  3 Nov  1996 FILE_ID.DIZ
-rw-rw-r--  0 0      0        1543 28 Oct  1996 !WOHER!.TXT
-rw-rw-r--  0 0      0        1461 31 Dec  1995 ARSENAL.96
```

The file timestamps suggest a release on September 17th.

This matches the date in the changelog:

```text
--------------------------------
Version 1.21 - Released 17/9/96
--------------------------------
Bugs Removed:
    - Assault Cannon backpack/cooling bug fixed.
    - BioWeapon not infecting monsters bug fixed.
    - Megahealth always curing infection bug fixed.
    - Detpack stuffcmd failure bug fixed.
    - Medikit non-precached sound bug fixed.
    - Deathmatch Everyone-respawn-in-the-same-place bug fixed.
    - Heavy Weapon Guy's weapons cleaned up.
```

-- tf1_21sc.zip/README.TXT

After this release, there is mention that the TeamFortress homepage was updated on BluesNews on September 21st:

> Go check out the Team Fortress Page which has been completely redone to make it easier to learn about their new concept for teamplay

-- [https://www.bluesnews.com/archives/sept96-4.html](https://www.bluesnews.com/archives/sept96-4.html)

Link:

* http://minyos.its.rmit.edu.au/~cookj/

This suggests that `bluesnews.com` was aware of TeamFortress, but no mention of the mod appears prior to this date (as far as I can tell).

## v1.22

The filename for this release is not known. It was probably released as `tf_v122.zip`.

The changelog from v1.3 does not include mention of v1.22, it jumps from v1.21 to v1.3

This version was mentioned in the online version of the changelog:

```text
------------
Version 1.22
------------
Features added:
	Class skins
	One all-inclusive PAK file.
```

-- [http://minyos.its.rmit.edu.au/~cookj/pages/version.htm](https://web.archive.org/web/19970121054854/http://minyos.its.rmit.edu.au/~cookj/pages/version.htm) (archived)

A copy of the release was found unzipped on the "[Phenomenon](https://discmaster.textfiles.com/browse/34043)" Addon Quake CD.

```text
drwxr-xr-x  0 501    20          0 28 Nov  1996 TF_V122/
-rw-r--r--  0 501    20      23632 10 Sep  1996 TF_V122/TFORTMAP.TXT
-rw-r--r--  0 501    20        306 18 Oct  1996 TF_V122/INSTALL.TXT
-rw-r--r--  0 501    20        365 18 Oct  1996 TF_V122/CHANGES.TXT
-rw-r--r--  0 501    20      24836 18 Oct  1996 TF_V122/README.TXT
-rw-r--r--  0 501    20    1078522 18 Oct  1996 TF_V122/PAK0.PAK
```

The changelog from the readme suggest the release was October 19th

```text
--------------------------------
Version 1.22 - Released 19/10/96
--------------------------------
        - Added new class skins
        - PAK file only
```

-- TF_V122/README.TXT

The `changes.txt` file in the release suggests it was a minor release:

```text
*==============================================================*
* TeamFortress v1.22                               changes.txt *
*==============================================================*

Changes
=======

Skins!

 This release is almost identical to v1.21, but includes the new player
skins. Everything you need is contained within the .pak file.
```

-- TF_V122/CHANGES.TXT



## v1.3

This version was released as `tf1_3.zip`.

The release as mentioned on the TeamFortress homepage:

> 31/10/96\
> Released v1.3 last night. It seems to be virtually bug-free, thanks to our beta-testers. Though i am still worried about the problem where the game would sometimes crash when a grenade was thrown. I think it is fixed, but if happens to anyone, please mail me.
TF v1.4 is already started! It will feature two new classes, the Spy and the Assassin. It will also include gun turrets, auto-turrets, and team bots.

-- [http://minyos.its.rmit.edu.au/~cookj/pages/working.htm](https://web.archive.org/web/19970121054840/http://minyos.its.rmit.edu.au/~cookj/pages/working.htm) (archived)

The release was mentioned on Blues News:

> October 30th
>
> TeamFortress 1.3\
> Version 1.3 of TeamFortress, a multiplayer patch that allows different character classes, and offers several goal-oriented team play modes (like CTF) has been released on the TeamFortress homepage.

-- [https://www.bluesnews.com/archives/oct96-4.html](https://www.bluesnews.com/archives/oct96-4.html)

Links:

* http://minyos.its.rmit.edu.au/~cookj/index.htm

The release was mentioned on Redwood's News:

> ==November 1== 11:15p.m. CST\
> ...
> Team Fortress 1.3 is out.

-- [http://redwood.stomped.com/1196.html](https://web.archive.org/web/20011031110024/http://redwood.stomped.com/1196.html) (archived)

Link:

* http://minyos.its.rmit.edu.au/~cookj/index.htm

The release in this archive is a repack for distribution on BBSs and includes an additional `FILE_ID.DIZ` file:

```text
-rw-rw-r--  0 0      0       48596 27 Oct  1996 TFORTMAP.TXT
-rw-rw-r--  0 0      0       28360 31 Oct  1996 README.TXT
-rw-rw-r--  0 0      0     1406674 31 Oct  1996 PAK0.PAK
-rw-rw-r--  0 0      0          28 20 Nov  1996 FILE_ID.DIZ
```

The timestamps suggest a release on October 31.


## v1.31

The filename for this release is not known.

This version is mentioned on the TeamFortress news page:

> 4/11/96\
> Released v1.31 today. Fixed some known bugs, and some previously unknown bugs too. Added some other features.
>
> 3/11/96\
> I plan on releasing v1.31 tomorrow with some bug fixes and some changes to the Pyro; we played a lot today, and decided that he was too tough.
>
> 1/11/96\
> I've been working on a pre-processor for the quakeC compiler today, but it looks like there will be a TF v1.31 coming out soon. The bugs that have been found are:\
> - the server crashing because of a grenade being thrown (doesn't happen often)
> - pipebomb problems.\
> These problems will be fixed soon. Just go easy on the grenades and pipebombs :)

-- [http://minyos.its.rmit.edu.au/~cookj/pages/working.htm](https://web.archive.org/web/19970121054840/http://minyos.its.rmit.edu.au/~cookj/pages/working.htm) (archived)

This suggests that v1.31 was released on November 4th 1996.

This matches the date in the changelog from the v1.35 release:

```text
--------------------------------
Version 1.31 - Released 4/11/96
--------------------------------
Features added:
	- Class choices are announced to Team Members.

Changes:
	- Pyro Class made a little weaker, as follows:
		- Flames on Players burn for half as long.
		- Incendiary Cannon has a smaller radius.

Bugs Removed:
	- Pipebomb's crashing the server.
		"I just commented out the debug!" John cried :)
	- Grenade names in inventory fixed.
	- Updating of Current Ammo fixed.
	- Weapon firing in air fixed.
		"Who the hell is DeMorgan?!?!" Robin screams :)
	- Speed resetting when a GoalItem is removed corrected.
	- Detpack activation of Goals fixed.
```

-- README.TXT

**A copy of this release has not yet been acquired for this archive.**


## v1.32

The filename for this release is not known.

This version is mentioned on the TeamFortress news page:

> 10/11/96\
> v1.32 has been released, and we have started work on v1.4. The Spy and Scuba Commando have been designed, the assassin scraped and'merged' with the spy. So far, the spy will be able to:
Disguise: can change skin and team colors. Takes 5 seconds to change.
Backstab: Has a knife which does 30 damage normally, or 120 damage if he strikes from behind (backstab!).
Caltrops: Little spiky things that get stuck in peoples feet, doing small amounts of damage and slowing them down.
And some other suprises...
>
> 9/11/96\
> The preprocessor is finished, so our code will look a little different from now on. We are planning on releasing v1.32 in a few days, with some small changes (mainly for net play).

-- [http://minyos.its.rmit.edu.au/~cookj/pages/working.htm](https://web.archive.org/web/19970121054840/http://minyos.its.rmit.edu.au/~cookj/pages/working.htm) (archived)

This suggests that v1.32 was released on November 10th 1996.

This matches the date in the changelog from the v1.35 release:

```text
--------------------------------
Version 1.32 - Released 10/11/96
--------------------------------
Features added:
	- Nextlevel command.
		Players can use the "Nextlevel" command to cycle through the
		v1.3 FortressMaps and choose which one will be played when the
		current one ends.
	- Deathmatch 3 setting.
		When in deathmatch 3, players can choose the class they will
		respawn as.

Changes:
	- Removed all pre-impulses.
	  	We used these in LAN games and they're fine. But on the net,
	  	the lag can cause problems with them. So they're gone. We
	  	have left in the pre-impulses for Detpacks and Scanners so
	  	players can still define their own time settings/energy levels.
	- Detpack setting changed.
	  	Instead of stopping you for 4 seconds when you set a detpack,
	  	now you have to hold down the Detpack-Set key for 4 seconds
	  	without moving, and you can stop and run at any time.
	 	The old method is still there if you want to use it instead.
	- Sniper Rifle changed.
		It takes a little longer to build up the damage now, so snap-shots
		won't kill so much. Aiming still builds up the damage.
		Also, the Sniper must stop moving before he can start to aim.
	- Team Color Checking
		Now it doesn't penalise the player in any way for changing colors,
		it just sets them back. Players with lag on servers would get
		penalised before they're colors had been set when they joined a
		team. :)

Bugs Removed:
	- Announcing of class choices when deathmatching.
	- Sniper aiming not incrementing damage.
	- Teamfrags not keeping correct count.
	- Team 4 wasn't working.
```

-- README.TXT

**A copy of this release has not yet been acquired for this archive.**

## v1.33

This version was released as `tf1_33.zip` and/or `v1_33pak.zip`.

This version is mentioned on the TeamFortress news page:

> 12/11/96\
> We've made the detpack exposion more impressive (and dangerous). We've fixed a small bug in v1.32, i will put v1.33 up soon.

-- [http://minyos.its.rmit.edu.au/~cookj/pages/working.htm](https://web.archive.org/web/19970121054840/http://minyos.its.rmit.edu.au/~cookj/pages/working.htm) (archived)

This release was later announced on BluesNews:

> November 17th
>
> New TeamFortress\
> There's a new release of the TeamFortress teamplay patch (version 1.33) on the TeamFortress Homepage. Thank you to Tim Scott for letting me know.

-- [https://www.bluesnews.com/archives/nov96-3.html](https://www.bluesnews.com/archives/nov96-3.html)

Links:

* http://minyos.its.rmit.edu.au/~cookj/

Evidence suggests that v1.33 was released around November 12th 1996.

This is close to the release date mentioned in the changelog from the v1.35 release:

```text
--------------------------------
Version 1.33 - Released 11/11/96
--------------------------------
Bugs Removed:
	- Nextlevel command not working.
```

-- README.TXT

A copy of this release is linked on Stomped:

```text
ftp://ftp.stomped.com/pub/quake/quakec/multiplayer/tf1_33.zip
ftp://ftp.stomped.com/pub/quake/quakec/multiplayer/tf1_33.txt
```

A copy of this release appears on this news page:

> Team Fortress 1.33, New server patch from Team Fortress, includes charactor skins and a new charactor class.

-- [http://web.ukonline.co.uk/Members/jc.burton/quakec.htm](https://web.archive.org/web/19970618165530/http://web.ukonline.co.uk:80/Members/jc.burton/quakec.htm) (archived)

Link:

* http://web.ukonline.co.uk:80/Members/jc.burton/v1_33pak.zip

**A copy of this release has not yet been acquired for this archive.**

## v1.34

There's no mention of this release on the TeamFortress news page.

This version is not mentioned in the online version of the release history:

* [http://minyos.its.rmit.edu.au/~cookj/pages/version.htm](https://web.archive.org/web/19970121054854/http://minyos.its.rmit.edu.au/~cookj/pages/version.htm) (archived)

The changelog from v1.35 suggests there was no public v1.34:

```text
Changes TeamFortress v1.35 from v1.33
======================================
```

-- v1_35pak.zip/CHANGES.TXT

The readme for the 1.35 release suggests that v1.34 was an internal release:

```text
--------------------------------
Version 1.34 - Internal Version
--------------------------------
Features added:
	- Monster's put back in.
	- Co-Op version implemented.
```

-- v1_35pak.zip/README.TXT

**A copy of this release has not yet been acquired for this archive.**

After this release, a call for TeamFortress map makers was shared on BluesNews:

> November 21st
>
> TeamFortress Map Makers Needed\
> I got word from Robin, one of the creators of the TeamFortress patch, who would like experienced map authors who are interested in creating maps for use with the add-on to contact him. More info on what is involved in adding TF entities to a map are available on the TeamFortress Page.

-- [https://www.bluesnews.com/archives/nov96-3.html](https://www.bluesnews.com/archives/nov96-3.html)

Links:

* http://minyos.its.rmit.edu.au/~cookj/


## v1.35

This version was released as five files:

* `v1_35pak.zip`
* `net1_35.zip`
* `coop1_35.zip`
* `v1_35src.zip`
* `1_35nopr.zip`

This version is mentioned on the TeamFortress news page:

> 30/11/96\
> I've put v1.35 on the web page now, along with the Net and Coop versions. Only the server needs the special version. The Coop version is kindof a beta, so any comments or suggestions about it are very welcome.
>
> 27/11/96\
> Sorry about the delay, but v1.35 won't be released until tomorrow. This is because i've decided to add in a menu system for choosing teams/classes.
>
> 26/11/96\
> I'm planning on releasing TF v1.35, TF coop beta, and a net server version of TF later today. I'll also be releasing the precompiler (preqcc).\
> I better get to work...

-- [http://minyos.its.rmit.edu.au/~cookj/pages/working.htm](https://web.archive.org/web/19970121054840/http://minyos.its.rmit.edu.au/~cookj/pages/working.htm) (archived)

This release was listed on the TeamFortress download page:

```text
Team Fortress v1.35
TF v1.35 pak file .
Just unzip this file into your quake\fortress directory and run quake with the -game fortress parameter. With this you can connect to any TF server.

TF Net server v1.35 pak file
This version is designed for net servers only.

TF Coop server v1.35 pak file
This version is designed for cooperative and single player games.
TF v1.35 source code only .
TF v1.35 extra files only (no progs.dat)
```

-- [http://minyos.its.rmit.edu.au/~cookj/pages/download.htm](https://web.archive.org/web/19970121054832/http://minyos.its.rmit.edu.au/~cookj/pages/download.htm) (archived)

A comment at the top of the page suggests that perhaps this and prior releases were uploaded to cdrom.com:

> A lot of these files can also be found on ftp.cdrom.com., or on: The Quake Toybox, QuakeEthereal, Mordor

Links:

* http://minyos.its.rmit.edu.au/~cookj/files/v1_35pak.zip
* http://minyos.its.rmit.edu.au/~cookj/files/net1_35.zip
* http://minyos.its.rmit.edu.au/~cookj/files/coop1_35.zip
* http://minyos.its.rmit.edu.au/~cookj/files/v1_35src.zip
* http://minyos.its.rmit.edu.au/~cookj/files/1_35nopr.zip

This release was mentioned on BluesNews:

> November 30, 1996
>
> TeamFortress Update\
> Version 1.35 of the TeamFortress QuakeC patch, as well as a special net server version and a coop-version have been released. On the TeamFortress Page. The authors are also looking for some net servers to run the patch.

-- [https://www.bluesnews.com/archives/nov96-5.html](https://www.bluesnews.com/archives/nov96-5.html)

Links:

* http://minyos.its.rmit.edu.au/~cookj/

This release was also mentioned on Telefragged:

> 11/30/96
>
> There's a new TeamFortress patch out. It now has menus to pick your class. If you don't know what TeamFortress is or you want the file go to minyos.its.rmit. edu.au/~cookj.

-- [http://www.telefragged.com/oldnews/old1.shtml](https://web.archive.org/web/19980114112105/http://www.telefragged.com/oldnews/old1.shtml) (archived)


Content of `v1_35pak.zip`:

```text
-rw-rw-r--  0 0      0         596 29 Nov  1996 CHANGES.TXT
-rw-rw-r--  0 0      0         493 30 Nov  1996 FORTRESS.CFG
-rw-rw-r--  0 0      0     1685403 30 Nov  1996 PAK0.PAK
-rw-rw-r--  0 0      0       29069 30 Nov  1996 README.TXT
-rw-rw-r--  0 0      0       48599 30 Nov  1996 TFORTMAP.TXT
```

Content of `net1_35.zip`:

```text
-rw-rw-r--  0 0      0         596 29 Nov  1996 CHANGES.TXT
-rw-rw-r--  0 0      0         493 30 Nov  1996 FORTRESS.CFG
-rw-rw-r--  0 0      0     1685495 30 Nov  1996 PAK0.PAK
-rw-rw-r--  0 0      0       29069 30 Nov  1996 README.TXT
-rw-rw-r--  0 0      0       48599 30 Nov  1996 TFORTMAP.TXT
```

Content of `coop1_35.zip`:

```text
-rw-rw-r--  0 0      0         596 29 Nov  1996 CHANGES.TXT
-rw-rw-r--  0 0      0         493 30 Nov  1996 FORTRESS.CFG
-rw-rw-r--  0 0      0     1916607 30 Nov  1996 PAK0.PAK
-rw-rw-r--  0 0      0       29069 30 Nov  1996 README.TXT
-rw-rw-r--  0 0      0       48599 30 Nov  1996 TFORTMAP.TXT
```

Content of `v1_35src.zip`:

```text
-rw-rw-r--  0 0      0         829 11 Nov  1996 ADMIN.QC
-rw-rw-r--  0 0      0       15082 21 Nov  1996 AI.QC
-rw-rw-r--  0 0      0        1697 25 Jul  1996 AMTEST.QC
-rw-rw-r--  0 0      0       12867 20 Nov  1996 BOSS.QC
-rw-rw-r--  0 0      0        3829 30 Oct  1996 BOT.QC
-rw-rw-r--  0 0      0       16945 30 Oct  1996 BOTAI.QC
-rw-rw-r--  0 0      0        3168  9 Nov  1996 BUTTONS.QC
-rw-rw-r--  0 0      0         596 29 Nov  1996 CHANGES.TXT
-rw-rw-r--  0 0      0       48363 30 Nov  1996 CLIENT.QC
-rw-rw-r--  0 0      0       12475 21 Nov  1996 COMBAT.QC
-rw-rw-r--  0 0      0         749 30 Oct  1996 COMBOT.QC
-rw-rw-r--  0 0      0        2668 30 Nov  1996 COOP.QC
-rw-rw-r--  0 0      0       47263 30 Nov  1996 DEFS.QC
-rw-rw-r--  0 0      0       11227 28 Nov  1996 DEMON.QC
-rw-rw-r--  0 0      0       10475 28 Nov  1996 DOG.QC
-rw-rw-r--  0 0      0       18050 30 Nov  1996 DOORS.QC
-rw-rw-r--  0 0      0       12119 28 Nov  1996 ENFORCER.QC
-rw-rw-r--  0 0      0        7199 20 Nov  1996 FIGHT.QC
-rw-rw-r--  0 0      0        7956 20 Nov  1996 FISH.QC
-rw-rw-r--  0 0      0        1738  9 Nov  1996 FLARE.QC
-rw-rw-r--  0 0      0       19702 28 Nov  1996 HKNIGHT.QC
-rw-rw-r--  0 0      0       34171 29 Nov  1996 ITEMS.QC
-rw-rw-r--  0 0      0         222 25 Jul  1996 JCTEST.QC
-rw-rw-r--  0 0      0       10898 28 Nov  1996 KNIGHT.QC
-rw-rw-r--  0 0      0        3290 30 Nov  1996 MENU.QC
-rw-rw-r--  0 0      0       17395 20 Nov  1996 MISC.QC
-rw-rw-r--  0 0      0        9788 25 Jul  1996 MODELS.QC
-rw-rw-r--  0 0      0       10826 30 Nov  1996 MONSTERS.QC
-rw-rw-r--  0 0      0        1356 29 Nov  1996 MSKIN.QC
-rw-rw-r--  0 0      0       16078 28 Nov  1996 OGRE.QC
-rw-rw-r--  0 0      0       11561 30 Oct  1996 OLDBOT.QC
-rw-rw-r--  0 0      0        9707 20 Nov  1996 OLDONE.QC
-rw-rw-r--  0 0      0         473 29 Nov  1996 OPTIONS.QC
-rw-rw-r--  0 0      0        8279  9 Nov  1996 PLATS.QC
-rw-rw-r--  0 0      0       24744 20 Nov  1996 PLAYER.QC
-rw-rw-r--  0 0      0         362 29 Nov  1996 PREPROGS.SRC
-rw-rw-r--  0 0      0        2598 27 Aug  1996 PROGDEFS.QC
-rw-rw-r--  0 0      0         495 30 Nov  1996 PROGS.SRC
-rw-rw-r--  0 0      0       17961  9 Nov  1996 PYRO.QC
-rw-rw-r--  0 0      0       29069 30 Nov  1996 README.TXT
-rw-rw-r--  0 0      0        9067 28 Nov  1996 SHALRATH.QC
-rw-rw-r--  0 0      0       14085 28 Nov  1996 SHAMBLER.QC
-rw-rw-r--  0 0      0       11217 28 Nov  1996 SOLDIER.QC
-rw-rw-r--  0 0      0         486 25 Jul  1996 SPRITES.QC
-rw-rw-r--  0 0      0        6378 21 Nov  1996 SUBS.QC
-rw-rw-r--  0 0      0        7374 20 Nov  1996 TARBABY.QC
-rw-rw-r--  0 0      0       85664 30 Nov  1996 TFORT.QC
-rw-rw-r--  0 0      0       14691 30 Nov  1996 TFORTHLP.QC
-rw-rw-r--  0 0      0       38070 29 Nov  1996 TFORTMAP.QC
-rw-rw-r--  0 0      0       48599 30 Nov  1996 TFORTMAP.TXT
-rw-rw-r--  0 0      0       11104 10 Nov  1996 TFORTTM.QC
-rw-rw-r--  0 0      0       16147 28 Nov  1996 TRIGGERS.QC
-rw-rw-r--  0 0      0        3079 29 Oct  1996 TURRET.QC
-rw-rw-r--  0 0      0       60197 30 Nov  1996 WEAPONS.QC
-rw-rw-r--  0 0      0       12051 28 Nov  1996 WIZARD.QC
-rw-rw-r--  0 0      0       11801  9 Nov  1996 WORLD.QC
-rw-rw-r--  0 0      0       20678 20 Nov  1996 ZOMBIE.QC
```

Content of `1_35nopr.zip`:

```text
-rw-rw-r--  0 0      0         596 29 Nov  1996 CHANGES.TXT
-rw-rw-r--  0 0      0         493 30 Nov  1996 FORTRESS.CFG
-rw-rw-r--  0 0      0         277 30 Nov  1996 QUAKE.RC
-rw-rw-r--  0 0      0       29069 30 Nov  1996 README.TXT
-rw-rw-r--  0 0      0       48599 30 Nov  1996 TFORTMAP.TXT
-rw-rw-r--  0 0      0       64008 28 Nov  1996 GFX/CONBACK.LMP
-rw-rw-r--  0 0      0       64008  9 Nov  1996 GFX/HELP0.LMP
-rw-rw-r--  0 0      0       64008  9 Nov  1996 GFX/HELP1.LMP
-rw-rw-r--  0 0      0       64008 30 Nov  1996 GFX/HELP2.LMP
-rw-rw-r--  0 0      0       64008 29 Nov  1996 GFX/HELP3.LMP
-rw-rw-r--  0 0      0       64008 29 Nov  1996 GFX/HELP4.LMP
-rw-rw-r--  0 0      0       64008 29 Nov  1996 GFX/HELP5.LMP
-rw-rw-r--  0 0      0       26888  8 Nov  1996 GFX/MAINMENU.LMP
-rw-rw-r--  0 0      0        5864  9 Nov  1996 GFX/P_MULTI.LMP
-rw-rw-r--  0 0      0       49560 19 Sep  1996 PROGS/CROSS1.MDL
-rw-rw-r--  0 0      0       26532 28 Nov  1996 PROGS/HANDGREN.MDL
-rw-rw-r--  0 0      0      593848 31 Oct  1996 PROGS/PLAYER.MDL
-rw-rw-r--  0 0      0       57908 24 Oct  1996 PROGS/V_BIO.MDL
-rw-rw-r--  0 0      0       57908 24 Oct  1996 PROGS/V_MEDI.MDL
-rw-rw-r--  0 0      0        7482 12 Sep  1996 SOUND/MISC/VAPEUR2.WAV
-rw-rw-r--  0 0      0       21286  8 Jul  1994 SOUND/WEAPONS/FLMFIRE.WAV
-rw-rw-r--  0 0      0        7508 25 Sep  1996 SOUND/WEAPONS/FLMFIRE2.WAV
-rw-rw-r--  0 0      0        7710 25 Sep  1996 SOUND/WEAPONS/FLMGREXP.WAV
-rw-rw-r--  0 0      0        5124  7 Sep  1996 SOUND/WEAPONS/HIS.WAV
-rw-rw-r--  0 0      0        3262 10 Aug  1996 SOUND/WEAPONS/SNIPER.WAV
-rw-rw-r--  0 0      0        2714 16 Oct  1996 SOUND/WEAPONS/SNIPRLD2.WAV
```

The timestamps suggest the archives were created November 30th.

This matches the changelog from the readme file:

```text
--------------------------------
Version 1.35 - Released 30/11/96
--------------------------------
Features added:
    - Menu for teams and classes.
    - Rocket ammo boxes sometimes give grenades
    - Ammo dropping.
    - Key dropping.
    - Toggleflag added:
        - Manual-Color. If it's not on, team colors are automatically assigned.

Changes:
    - Quake's autoaiming put back in for sniper rifle
    - Console commands now usable while dead

Multiple Compile Modes:
    - Coop mode version, with:
        - monsters included
        - enhanced skill levels
        - coop mode 2 added, with:
            - Doors which all players must open.
    - Net server version, with:
        - Max. number of flames in world reduced
        - Sniper rifle beefed up
        - Sniper rifle autozoom defaults to OFF
        - General alterations to reduce net traffic
```

-- README.TXT

## v1.36

Robin Walker (programmer) announced testing of this version on USENET:

```text
TeamFortress 1.36 Beta on Netspace server
Robin
7 Dec 1996

Bored of CTF?
Experience some _real_ teamplay!
Over the next few days, we're doing testing of the new TeamFortress
v1.36 Beta on the Netspace Quake Server. It'll be running CTF v3
maps, so make sure you've got the CTF maps.
The server _may_ go down occasionally if bugs are found, but it'll
only be for a few minutes at a time.
Also, the Netspace server has recently undergone an ip change,
so if you can't connect to quake.netspace.net.au, try:
203.17.103.34

This new version has CTF map support, the long awaited Grappling
Hook, a new user interface, and a few other surprises.

For those who are new to TeamFortress, it's a Teamplay oriented
patch with 7 Player Classes:
Scout, Sniper, Soldier, Demolitions Man, Combat Medic,
Heavy Weapons Guy, and Pyromaniac

It has new weapons, new items, new graphics, new rules, etc.
You can find out all about it at:
http://minyos.its.rmit.edu.au/~cookj

Hope to see you there.

Robin. (Bro in Quake)


------
wal...@netspace.net.au
TeamFortress QuakeC Patch Version 1.35 is out!
7 Player Classes! Map support! New Weapons! Armor! Grenades!
Download it from the WWW page: http://minyos.its.rmit.edu.au/~cookj
```

-- [rec.games.computer.quake.servers](https://groups.google.com/g/rec.games.computer.quake.servers/c/jA96ia2irCQ/m/3tOES33tZ5QJ)

This release was mentioned on the TeamFortress homepage:

> Last Updated 10/12/96
> ...
> TeamFortress v1.36 will be released soon

-- [http://minyos.its.rmit.edu.au/~cookj/](https://web.archive.org/web/19970121054942/http://minyos.its.rmit.edu.au/~cookj/) (archived)

And the news page:

> 7/12/96\
> We got lotsa stuff done over the past few days, including:\
> - Added in CTF map support\
> - Added in grappling hook as a compilable option\
> - Intro screens for each class\
> - Cleaned up a lot of the code\
> - Fixed spawning problems\
> - Automatic level cycling\
> - Net version no longer requires players to have TF to join (no extra files)
>
> All this will be released in v1.36 in a couple of days.\
> Rob has almost completed his EntEd user manual, with complete worked examples.\
> Bots probably won't be released with v1.4; you'll just have to wait longer.\
> We got C&C; Red Alert, but found it so boring that we worked on TF instead :).\

-- [http://minyos.its.rmit.edu.au/~cookj/pages/working.htm](https://web.archive.org/web/19970121054840/http://minyos.its.rmit.edu.au/~cookj/pages/working.htm) (archived)

There is mention of beta testing of a release on BluesNews:

> December 7, 1996
>
> TeamFortress Beta\
> There's beta testing of TeamFortress on the Netspace server. The new version has, among other things, Threewave CTF map support and includes the Grappling Hook (so bring your marshmallows for the campfire). The server is 203.17.103.34, running CTF 3 maps.

-- [https://www.bluesnews.com/archives/dec96-1.html](bin/https://www.bluesnews.com/archives/dec96-1.html)

Links:

* http://minyos.its.rmit.edu.au/~cookj/

Beta testing was mentioned on Telefragged:

> 12/7/96
>
> They are beta testing a new version of TeamFortress. It is suppose to have a grappling hook and stuff.

-- [http://www.telefragged.com/oldnews/old1.shtml](https://web.archive.org/web/19980114112105/http://www.telefragged.com/oldnews/old1.shtml) (archived)

Links:

* http://minyos.its.rmit.edu.au/~cookj/

It does not appear in the changelog in version 1.37.

This may have been another internal release like v1.24 or a minor release like 1.22.

**A copy of this release has not yet been acquired for this archive.**

## v1.37

Released as 5 files:

* `tf1_37_cl.zip`
* `tf1_37_coop.zip`
* `tf1_37_lan.zip `
* `tf1_37_net.zip `
* `tf1_37_src.zip `

This version is mentioned on the TeamFortress news page:

> 12/12/96\
> Lots of work is being done, to make v1.37 run better on the net. We've had to make a few small sacrificies to reduce player lag, but only in the net server version. There's been a lot of small improvements, and we're continuing beta-testing on these servers:
quake2.tassie.net.au will always be running the latest beta version.
quake.netspace.net.au will swap between running CTF and the v1.37 beta.
> We don't really want to release it until it's perfect, but you can beg for it if you want :)
>
> 10/12/96\
> We've fixed the problems with v1.36 now, with big thanks going to Nige. It should be released tomorrow sometime.

-- [http://minyos.its.rmit.edu.au/~cookj/pages/working.htm](https://web.archive.org/web/19970121054840/http://minyos.its.rmit.edu.au/~cookj/pages/working.htm) (archived)

Beta testing of this release was announced on USENET:

```text
TeamFortress now at Netspace
cc1...@mail.oaks.com.au
11 Dec 1996

We are now testing a BETA of Team Fortress at quake.netspace.net.au.
Expect it to be either on port 26001 or 26000, depending on the time
of day. The IP address is 203.17.103.34.
This is a specially-enhanced version of TF that uses CTF3 maps ! So
all you need to play is the same map and -game setup that you use for
CTF3.

To quote from the web page,

'TeamFortress is a new QuakeC patch which radically changes normal and
team games. It provides far more incentive for teams to actually work
as a team. Each member of the team has unique weapons, items, and abilities.

There are seven different classes for players to choose from, each
specialising in their own field. To make it even better, there is extra
teamplay and map functionality, with team-specific spawn points, resupply
area's, and special goals for each team to complete. Some example objectives
are hold the enemy base, capture the flag, defend an area, infilitrate a
fort, and many others.'

In the version of TF that we are running, the goals are the same as CTF 3.
Special player classes include sniper (has deadly sniper rifle), demo man
(has lotsa explosives :), pyro (sets things on fire), soldier (has RL),
heavy weapons guy (slow but well-armoured ; has very deadly chain cannon),
scout (VERY fast and light), and medic (can heal and give health to team
members, can give deadly and very infectious disease to enemy).

For more information see http://minyos.its.rmit.edu.au/~cookj/index.htm

If you can't connect to the quake.netspace.net.au server, make sure your
name server is resolving it to the above IP address as our IP changed
recently.
```

-- [rec.games.computer.quake.servers](https://groups.google.com/g/rec.games.computer.quake.servers/c/tE7RzugwCSw/m/nYd6Dyf1UbMJ)


The release was mentioned on Redwood's News:

> =December 12==\
> ...
> Look into the Team Fortress 1.37 beta.

-- [http://redwood.stomped.com/1296.html](https://web.archive.org/web/20011121183249/http://redwood.stomped.com/1296.html) (archived)

Link:

* http://minyos.its.rmit.edu.au/~cookj/

This early date suggests multiple beta versions of 1.37 may have been released.

The final release was mentioned on BluesNews:

> December 17, 1996
>
> TeamFortress Updated\
Version 1.37 of the TeamFortress patch has been released. This is described as the first version designed for Internet servers. More details on the TeamFortress Homepage.

-- [https://www.bluesnews.com/archives/dec96-2.html](https://www.bluesnews.com/archives/dec96-2.html)

Links:

* http://www.bluesnews.com/files/tf137cl.zip
* http://yallara.cs.rmit.edu.au/~cookj/

This release was mentioned on Telefragged:

> 12/17/96 6:50 a.m.
>
> * A new team fortress patch is out. A link is on my links page. See ya. Got to go to school quick.

-- [http://www.telefragged.com/oldnews/old1.shtml](https://web.archive.org/web/19980114112105/http://www.telefragged.com/oldnews/old1.shtml) (archived)

The release was uploaded to `cdrom.com`:

```text
tf1_37_cl.txt          17-Dec-96 02:23    28k
tf1_37_cl.zip          17-Dec-96 02:26   411k
tf1_37_coop.txt        17-Dec-96 02:26    28k
tf1_37_coop.zip        17-Dec-96 02:27   224k
tf1_37_lan.txt         17-Dec-96 02:27    28k
tf1_37_lan.zip         17-Dec-96 02:28   164k
tf1_37_net.txt         17-Dec-96 02:29    28k
tf1_37_net.zip         17-Dec-96 02:30   164k
tf1_37_src.txt         17-Dec-96 02:30    14k
tf1_37_src.zip         17-Dec-96 02:31   195k
```

-- [http://www.cdrom.com/pub/idgames2/quakec/teamplay/](https://web.archive.org/web/19961225222656/http://www.cdrom.com/pub/idgames2/quakec/teamplay/) (archived)

A copy of some of this release was found on BluesNews:

```text
http://www.bluesnews.com/files/tf137cl.zip
http://www.bluesnews.com/files/tf137src.zip
```

Content of `tf137cl.zip`:

```text
-rw-rw-r--  0 0      0         431 16 Dec  1996 CTF.TXT
-rw-rw-r--  0 0      0         493 30 Nov  1996 FORTRESS.CFG
-rw-rw-r--  0 0      0     1323378 16 Dec  1996 PAK0.PAK
-rw-rw-r--  0 0      0       29093 16 Dec  1996 README.TXT
-rw-rw-r--  0 0      0       48599 30 Nov  1996 TFORTMAP.TXT
```

Content of `tf137src.zip`:

```text
-rw-rw-r--  0 0      0        2523 11 Dec  1996 ADMIN.QC
-rw-rw-r--  0 0      0       15082 21 Nov  1996 AI.QC
-rw-rw-r--  0 0      0        1697 25 Jul  1996 AMTEST.QC
-rw-rw-r--  0 0      0         295 13 Dec  1996 AUTOEXEC.CFG
-rw-rw-r--  0 0      0       12867 20 Nov  1996 BOSS.QC
-rw-rw-r--  0 0      0        2202  6 Dec  1996 BOT.QC
-rw-rw-r--  0 0      0       15371 13 Dec  1996 BOTAI.QC
-rw-rw-r--  0 0      0         166  3 Dec  1996 BOTS.QC
-rw-rw-r--  0 0      0        3168  9 Nov  1996 BUTTONS.QC
-rw-rw-r--  0 0      0       50832 14 Dec  1996 CLIENT.QC
-rw-rw-r--  0 0      0       13396 13 Dec  1996 COMBAT.QC
-rw-rw-r--  0 0      0         873 13 Dec  1996 COMBOT.QC
-rw-rw-r--  0 0      0        2668 30 Nov  1996 COOP.QC
-rw-rw-r--  0 0      0        1735 11 Dec  1996 CTF.QC
-rw-rw-r--  0 0      0       47908 14 Dec  1996 DEFS.QC
-rw-rw-r--  0 0      0       11227 28 Nov  1996 DEMON.QC
-rw-rw-r--  0 0      0       10475 28 Nov  1996 DOG.QC
-rw-rw-r--  0 0      0       18050 30 Nov  1996 DOORS.QC
-rw-rw-r--  0 0      0       12119 28 Nov  1996 ENFORCER.QC
-rw-rw-r--  0 0      0        7199 20 Nov  1996 FIGHT.QC
-rw-rw-r--  0 0      0        7956 20 Nov  1996 FISH.QC
-rw-rw-r--  0 0      0        1738  9 Nov  1996 FLARE.QC
-rw-rw-r--  0 0      0       14512 17 Dec  1996 FORTRESS.TXT
-rw-rw-r--  0 0      0       19702 28 Nov  1996 HKNIGHT.QC
-rw-rw-r--  0 0      0        5483 14 Dec  1996 HOOK.QC
-rw-rw-r--  0 0      0       34327 13 Dec  1996 ITEMS.QC
-rw-rw-r--  0 0      0         222 25 Jul  1996 JCTEST.QC
-rw-rw-r--  0 0      0       10898 28 Nov  1996 KNIGHT.QC
-rw-rw-r--  0 0      0       14684 14 Dec  1996 MENU.QC
-rw-rw-r--  0 0      0         978 14 Dec  1996 MESSAGES.QC
-rw-rw-r--  0 0      0       17395 20 Nov  1996 MISC.QC
-rw-rw-r--  0 0      0        9788 25 Jul  1996 MODELS.QC
-rw-rw-r--  0 0      0       10826 30 Nov  1996 MONSTERS.QC
-rw-rw-r--  0 0      0        1356 11 Dec  1996 MSKIN.QC
-rw-rw-r--  0 0      0       16078 28 Nov  1996 OGRE.QC
-rw-rw-r--  0 0      0       11561 30 Oct  1996 OLDBOT.QC
-rw-rw-r--  0 0      0        9707 20 Nov  1996 OLDONE.QC
-rw-rw-r--  0 0      0        2187 16 Dec  1996 OPTIONS.QC
-rw-rw-r--  0 0      0        8279  9 Nov  1996 PLATS.QC
-rw-rw-r--  0 0      0       26745 14 Dec  1996 PLAYER.QC
-rw-rw-r--  0 0      0         915  7 Dec  1996 PREOPDEF.QC
-rw-rw-r--  0 0      0         405 11 Dec  1996 PREPROGS.SRC
-rw-rw-r--  0 0      0        2598 27 Aug  1996 PROGDEFS.QC
-rw-rw-r--  0 0      0       19526 13 Dec  1996 PYRO.QC
-rw-rw-r--  0 0      0        9067 28 Nov  1996 SHALRATH.QC
-rw-rw-r--  0 0      0       14085 28 Nov  1996 SHAMBLER.QC
-rw-rw-r--  0 0      0       11217 28 Nov  1996 SOLDIER.QC
-rw-rw-r--  0 0      0         486 25 Jul  1996 SPRITES.QC
-rw-rw-r--  0 0      0        6378 21 Nov  1996 SUBS.QC
-rw-rw-r--  0 0      0        7374 20 Nov  1996 TARBABY.QC
-rw-rw-r--  0 0      0       86905 15 Dec  1996 TFORT.QC
-rw-rw-r--  0 0      0       15148 11 Dec  1996 TFORTHLP.QC
-rw-rw-r--  0 0      0       49923 14 Dec  1996 TFORTMAP.QC
-rw-rw-r--  0 0      0       16103 14 Dec  1996 TFORTTM.QC
-rw-rw-r--  0 0      0       15685 14 Dec  1996 TRIGGERS.QC
-rw-rw-r--  0 0      0        3079 29 Oct  1996 TURRET.QC
-rw-rw-r--  0 0      0       67069 15 Dec  1996 WEAPONS.QC
-rw-rw-r--  0 0      0       12051 28 Nov  1996 WIZARD.QC
-rw-rw-r--  0 0      0       11847 14 Dec  1996 WORLD.QC
-rw-rw-r--  0 0      0       20678 20 Nov  1996 ZOMBIE.QC
```

The timestamps suggest a release on December 16th.

The header of the readme file suggests multiple, perhaps up to four beta versions of this release:

```text
*==============================================================*
* TeamFortress v1.37 beta 4                         readme.txt *
* Written by Robin Walker, John Cook, Ian Caughley         *
*==============================================================*
```

The changelog in the readme for this release does not include any details of this release.

A changelog for this release does appear in the next available release (e.g v2.0), but does not include a date:

```text
--------------------------------
Version 1.37 - Beta Released
--------------------------------
So many changes, so here are just a few of them:
    - Pipebombs completely cleaned up. Now there's a
      limit defined in options.qc, default 10, and
      this is divided out between teams.
      e.g. in CTF both teams can have upto 5.
    - "reload" fixed.
    - "dropammo" fixed.
    - Concussion gren healing fixed.
    - Teamplay options are much better.
    - Temp1 variable now hold Toggleflags, so they
      persist over maps.
    - maxammo for all ammo increased for each
      class, so that scouts can carry rockets,
      but still not use them. This way they can
      carry them to team members.
    - BioWeapon and Medikit can be merged into
      one weapon if MEDIKIT_IS_BIOWEAPON is defined.
      It heals if you hit a teammember and infects
      if you hit an enemy.
    - Dropammo menu appears faster
    - Spawn blood when curing concussion
    - Prevented infections attacking your own team,
      if teamplay options prevent it doing damage
    - telefragged players respawn a couple of seconds
      later, so we don't get that telefrag crap.
    - autoteam kicks in after 30 seconds into a map.
      So teams can be restructured when people enter
      a new map, and then after 30 seconds, people will
      be assigned automatically.
    - Firing removes help now, and prints the "8 to see..."
    - People can now ask for bindings to be done for them,
      with a selection of keys for mouse and key players.
    - Player's push each other, and flag carrying players
      have a bigger weight.
```

-- qwtf2.zip/README.TXT

**Some files for this release have not yet been acquired for this archive.**


## v1.4

This version is mentioned as being under development on the TeamFortress homepage:

> TeamFortress v1.4 is under construction

-- [http://minyos.its.rmit.edu.au/~cookj/pages/working.htm](https://web.archive.org/web/19970121054840/http://minyos.its.rmit.edu.au/~cookj/pages/working.htm) (archived)

And in an update:

> 8/12/96\
> We're going to get a lot done today. TF v1.4 maybe be closer than you think...

-- [http://minyos.its.rmit.edu.au/~cookj/pages/working.htm](https://web.archive.org/web/19970121054840/http://minyos.its.rmit.edu.au/~cookj/pages/working.htm) (archived)

This version was also mentioned in the online FAQ:

> Version 1.4-
>
> -Well, I'm really not going to do much with the FAQ. I'll probably go over the grenades section, because of new info on aliases I've gotten from John. Otherwise, I've kinda scrapped the idea of definition charts and stuff. I'm working on my TF map right now, so the next revision will be in a week, or until I get some more questions or news.

-- [http://minyos.its.rmit.edu.au/~cookj/faq.html](https://web.archive.org/web/19970121054908/http://minyos.its.rmit.edu.au/~cookj/faq.html) (archived)

This version does not appear in the changelog for the next release, e.g. v2.0.

**A copy of this release has not yet been acquired for this archive.**

## v2.0

Released as:

* `qwtf2.zip`
* `qwtf2nnf.zip`

Two additional files were distributed for this release that may or may not be official (from [Jord's Files page](https://web.archive.org/web/19980111040233/http://jord.sbc.edu/files.htm) circa December 1996):

* `tf2files.zip`
* `tf2src.zip`

This version was announced on BluesNews:

> December 22, 1996
>
> QuakeWorld TeamFortress Quake\
> Robin of TeamFortess Quake (also take note of the new homepage address) sends along word that they've released a beta of Quake TeamFortress 2.0, which is designed for QuakeWorld. They are now looking for server operators who are interesting in testing it out. There are two versions: one is the patch that doesn't download anything other than skins, the other is the patch which uses some new graphics and sounds.

-- [http://bluesnews.com/](https://web.archive.org/web/19961226231646/http://bluesnews.com/) (archived) and <https://www.bluesnews.com/archives/dec96-3.html>

Links:

* http://yallara.cs.rmit.edu.au/~cookj/
* http://bluesnews.com/files/qwtf2nnf.zip
* http://bluesnews.com/files/qwtf2.zip

This version was mentioned on Telefragged:

> 12/22/96 11:00 a.m.\
> ...\
> Also, I learned from Blue's that TeamFortress 2 is out for QuakeWorld and that they are looking for some QW servers now. Also they have a new address which is http://yallara.cs.rmit.edu.au/~cookj/.

-- [http://www.telefragged.com/oldnews/old1.shtml](https://web.archive.org/web/19980114112105/http://www.telefragged.com/oldnews/old1.shtml) (archived)

This version was mentioned on Jord's:

> Sunday December 22, 1996
>
> Team Fortress update 07:49 PM\
> Started work on setting up a TF server. I'm building the machine from the ground up so I'm waiting for Windows 95 to install. (I tend to do this to computers alot, reformat them that is, makes em run better) So I went to read the documentation on TF.
> YOU DO NOT NEED TO DOWNLOAD THE CLIENT SIDE FOR TF! This is great news. According to the guys at TF the dynamic download from a Quake server is a heck of a lot simpler and it takes about the same amount of time. Plus you don't have to start QWCL with any paramiters. VERY COOL
> You can now move as an observer. Its slow but its better than being stuck like you were in the regular Quake version
If you are getting random "ACK" messages from the master not to worry its the server trying to get some info about you and can't be helped.
> The "serverinfo" command doesn't work from within a TF server.
> And over all. I just can't wait to get this thing running!
> Please remember this is still a beta version so their are likely to be bugs.
>
> Team Fortress Quake World mod goes into beta! 04:03 PM\
> Oh cool man! I love this mod to begin with. Been working on getting each sequential update working for quite some time. Now I can carry it with me to Quake World.

-- [http://jord.sbc.edu/archives/news/dec18th.htm](https://web.archive.org/web/19980216153039/http://jord.sbc.edu/archives/news/dec18th.htm) (archived)


Content of `qwtf2.zip`:

```text
-rw-rw-r--  0 0      0      405088 22 Dec  1996 PROGS.DAT
-rw-rw-r--  0 0      0       33203 22 Dec  1996 README.TXT
-rw-rw-r--  0 0      0        6776 22 Dec  1996 SERVER.TXT
-rw-rw-r--  0 0      0       49560 19 Sep  1996 PROGS/CROSS1.MDL
-rw-rw-r--  0 0      0       26532 28 Nov  1996 PROGS/HANDGREN.MDL
-rw-rw-r--  0 0      0      593848 31 Oct  1996 PROGS/PLAYER.MDL
-rw-rw-r--  0 0      0       57908 24 Oct  1996 PROGS/V_BIO.MDL
-rw-rw-r--  0 0      0       57908 24 Oct  1996 PROGS/V_MEDI.MDL
-rw-rw-r--  0 0      0       31503 22 Dec  1996 SKINS/TF_DEMO.PCX
-rw-rw-r--  0 0      0       33445 22 Dec  1996 SKINS/TF_HWGUY.PCX
-rw-rw-r--  0 0      0       27813 22 Dec  1996 SKINS/TF_MEDIC.PCX
-rw-rw-r--  0 0      0       30499 22 Dec  1996 SKINS/TF_PYRO.PCX
-rw-rw-r--  0 0      0       31515 22 Dec  1996 SKINS/TF_SCOUT.PCX
-rw-rw-r--  0 0      0       28098 22 Dec  1996 SKINS/TF_SNIPE.PCX
-rw-rw-r--  0 0      0       30579 22 Dec  1996 SKINS/TF_SOLD.PCX
-rw-rw-r--  0 0      0        7482 12 Sep  1996 SOUND/MISC/VAPEUR2.WAV
-rw-rw-r--  0 0      0       21286  8 Jul  1994 SOUND/WEAPONS/FLMFIRE.WAV
-rw-rw-r--  0 0      0        7508 25 Sep  1996 SOUND/WEAPONS/FLMFIRE2.WAV
-rw-rw-r--  0 0      0        7710 25 Sep  1996 SOUND/WEAPONS/FLMGREXP.WAV
-rw-rw-r--  0 0      0        5124  7 Sep  1996 SOUND/WEAPONS/HIS.WAV
-rw-rw-r--  0 0      0        3262 10 Aug  1996 SOUND/WEAPONS/SNIPER.WAV
-rw-rw-r--  0 0      0        2714 16 Oct  1996 SOUND/WEAPONS/SNIPRLD2.WAV
```

Content of `qwtf2nnf.zip`

```text
-rw-rw-r--  0 0      0      402792 22 Dec  1996 PROGS.DAT
-rw-rw-r--  0 0      0       33203 22 Dec  1996 README.TXT
-rw-rw-r--  0 0      0        6776 22 Dec  1996 SERVER.TXT
-rw-rw-r--  0 0      0       31503 22 Dec  1996 SKINS/TF_DEMO.PCX
-rw-rw-r--  0 0      0       33445 22 Dec  1996 SKINS/TF_HWGUY.PCX
-rw-rw-r--  0 0      0       27813 22 Dec  1996 SKINS/TF_MEDIC.PCX
-rw-rw-r--  0 0      0       30499 22 Dec  1996 SKINS/TF_PYRO.PCX
-rw-rw-r--  0 0      0       31515 22 Dec  1996 SKINS/TF_SCOUT.PCX
-rw-rw-r--  0 0      0       28098 22 Dec  1996 SKINS/TF_SNIPE.PCX
-rw-rw-r--  0 0      0       30579 22 Dec  1996 SKINS/TF_SOLD.PCX
```

The file timestamps suggest the archives were created on December 22nd.

This matches the date in the changelog:

```text
-------------------------------------
Version 2.0  - Beta Released 22/12/96
-------------------------------------
    QUAKEWORLD
```

-- qwtf2.zip/README.TXT

**Not all files from this release have been acquired for this archive.**

## v2.01

The filename for this release is not known, although it was probably `tf201src.zip`

This release was mentioned on Telefragged:

> 12/24/96 10:51 a.m.\
> ...\
> Wait, just saw that there is a new version of TeamFortress for QW out. Version 2.01 just for QW. Go play it. Gotta go shovel snow

-- [http://www.telefragged.com/oldnews/old1.shtml](https://web.archive.org/web/19980114112105/http://www.telefragged.com/oldnews/old1.shtml) (archived)

This release is mentioned on Jord's:

> Tuesday December 24, 1996
>
> TF update 10:01 AM\
> Looks like the guys at TF have a bug fix version out for QW TF. I'll Check it out.

-- [http://jord.sbc.edu/archives/news/dec18th.htm](https://web.archive.org/web/19980216153039/http://jord.sbc.edu/archives/news/dec18th.htm) (archived)

This version does not appear in the changelog for v2.1.

**A copy of this release has not yet been acquired for this archive.**


## v2.02

The filename for this release is not known, although it was probably `tf202src.zip`

This release may have been mentioned on Telefragged:

> Fri Dec 27 08:35:53 CST 1996\
> ...\
> There is also a new beta of QW Team Fortress out. Go to the TeamFortress HomePage

-- [http://www.telefragged.com/oldnews/old1.shtml](https://web.archive.org/web/19980114112105/http://www.telefragged.com/oldnews/old1.shtml) (archived)

Links:

* http://yallara.cs.rmit.edu.au/~cookj/

This release is mentioned on Jord's:

> Friday December 27, 1996
>
> Team Fortress updates 05:33 AM\
> There is a new beta of the TF source for both Quake and Quake World. You can compile it for each by changing one line in the options.qc file.\
> It look pretty good. I've had the server running for over an hour now and none of the problems that we were seeing before have cropped up.\
> I seem to have developed a cult following on that server. No sooner do I start it up than I have at least three people connected. Its pretty impressive.

-- [http://jord.sbc.edu/archives/news/dec27.htm](https://web.archive.org/web/19980216153116/http://jord.sbc.edu/archives/news/dec27.htm) (archived)

This suggests it was just a source code release.

This version does not appear in the changelog for v2.1.

**A copy of this release has not yet been acquired for this archive.**

## v2.03

Released as `tf203src.zip`.

This release is mentioned on Jord's:

> Saturday December 28, 1996
>
> Team Fortress Update 03:37 PM\
> There is another version of the Team Fortress server. Here is the word straight from the team.
>
>> Ok guys, here's the beta release for version 2.03\
>> It's getting pretty stable now, since we've got hold
of a master server which runs on a LAN.
>> We can now test the code a lot more extensively
>> before we release it, which is good news for you
>> and good news for us.
>> This version has the following fixes:
>>
>> - Items falling through world\
>> - Burning players not being able to move\
>> - Teamplay settings fixed\
>> - Quake Triggers activating TF Goals fixed\
>> - Level Cycling fixed
>
> Thanks to Robin for sending that along.
> I'm going to go compile it now and should be running it on my TF server within the hour.

-- [http://jord.sbc.edu/archives/news/dec27.htm](https://web.archive.org/web/19980216153116/http://jord.sbc.edu/archives/news/dec27.htm) (archived)

Links:

* http://yallara.cs.rmit.edu.au/~cookj/

And again later:

> Wendsday January 1, 1997
>
> Team Fortress 2.03 Beta is running at 198.28.62.30:27501

-- [http://jord.sbc.edu/archives/news/0101_0107.htm](https://web.archive.org/web/19980216153158/http://jord.sbc.edu/archives/news/0101_0107.htm) (archived)

It was also linked on Jord's Files page:

> tf203src.zip  The latest version of the TF source code.

-- [http://jord.sbc.edu/files.htm](https://web.archive.org/web/19980111040233/http://jord.sbc.edu/files.htm) (archived)

This release may have been mentioned on Telefragged:

> Sat Dec 28 11:28:34 CST 1996
>
> TeamFortress for QW 2.03 beta is out. It is suppose to be the last beta till the official release is out. Go check it out.

-- [http://www.telefragged.com/oldnews/old1.shtml](https://web.archive.org/web/19980114112105/http://www.telefragged.com/oldnews/old1.shtml) (archived)

Links:

* http://yallara.cs.rmit.edu.au/~cookj/

This version appears in the changelog for v2.1:

```text
-------------------------------------
Version 2.03  - Beta Released 28/12/96
-------------------------------------
Bugs Fixed:
    - Items falling through world
    - Burning players not being able to move
    - Teamplay settings fixed
    - Quake Triggers activating TF Goals fixed
    - Level Cycling fixed
```

-- tf21_cl.zip/README.TXT

**A copy of this release has not yet been acquired for this archive.**


## v2.1

Released as `tf21_cl.zip`.

This version was mentioned on BluesBews as well as the moved website:

> January 23, 1997
>
> TeamFortress\
> TeamFortress has moved (thanks sbloyd), to http://www.telefragged.com/teamfortress/ where they have, as promised, made version 2.1 of the TF patch available.

-- [https://www.bluesnews.com/archives/jan97-3.html](https://www.bluesnews.com/archives/jan97-3.html)

Links:

* http://www.telefragged.com/teamfortress/

This version is mentioned in a message signature by Robin Walker on USNET:

```text
...
Robin.

------
wal...@netspace.net.au
TeamFortress Version 2.12 is out.
Download it from the WWW page: http://www.telefragged.com/teamfortress
```

-- [rec.games.computer.quake.misc](https://groups.google.com/g/rec.games.computer.quake.misc/c/16b42SBX5uI/m/6Iotij72U6oJ)


This release was reviewed on QCArchive:

> The Team Fortress patch is a team based mod that lets you choose from 8 different charecter types. The object of this mod is to kick the other teams ass into the next time zone by killing them the ol fassion way or capturing the other teams key. Even though you try to capture the other team's key TeamFortress is not a lame CTF rippoff. It has totally new gameplay with the character classes, this patch rivals ctf. This mod work on both normal quake servers and QuakeWorld servers. This is an awsome mod and everyone should get it.

-- [http://www.planetquake.com/qca/patch131.htm](https://web.archive.org/web/19970611065419/http://www.planetquake.com/qca/patch131.htm) (archived)

Links:

* http://www.planetquake.com/qca/patch131.txt
* http://www.planetquake.com/qca/files/tf21_cl.zip

The release was mentioned on Jord's:

> Thursday January 23, 1997 01:49 PM
>
> New Version 11:26 AM\
> Well the guys down at Team Fortress have released version 2.1.
It includes new maps and options such as redone 2fort and havoc maps and 3 team CTF.
I can't wait to get a look at this but I'm at work now. :-(
>
> Move 11:31 AM\
> Well they did get around to moving. Team Fortress is now located at http://www.telefragged.com/teamfortress/

-- [http://jord.sbc.edu/archives/news/011797_012397.htm](https://web.archive.org/web/19980216153314/http://jord.sbc.edu/archives/news/011797_012397.htm) (archived)


Content of `tf21_cl.zip`:

```text
-rw-rw-r--  0 0      0         416 23 Jan  1997 CTF.TXT
-rw-rw-r--  0 0      0       14225 23 Jan  1997 FORTRESS.TXT
-rw-rw-r--  0 0      0     1594438 23 Jan  1997 PAK0.PAK
-rw-rw-r--  0 0      0      662032 23 Jan  1997 PROGS.DAT
-rw-rw-r--  0 0      0       40935 23 Jan  1997 README.TXT
-rw-rw-r--  0 0      0       33188 23 Jan  1997 TFMAPS.TXT
-rw-rw-r--  0 0      0       59176 23 Jan  1997 TFORTMAP.TXT
```

The file timestamps suggest a release on January 23rd 1998.

This is close to the date in the changelog:

```text
-------------------------------------
Version 2.1  - Released 22/1/97
-------------------------------------
Features Added:
    - "maphelp" alias which gives you a short description of the
      map you're playing, if it's a TF map and a description has
      been supplied by the map creator.
    - "flaginfo" alias which gives you a display of the status
      of the flags on any map which the map creator provides a
      flag info section in the Detection entity.
      Works for all CTF maps as well.
    - Civilian Class. Sorry, you can't play this one by choice. It is
      only used on special maps.

Bugs Fixed:
    - Quake Plats and Doors AP checking fixed
    - Quake Trigger reverse-AP-criteria fixed
    - Spawncode fixed and enhanced
    - Level Cycling removed, rewritten, and hopefully fixed!
      N.B. You can't use nextlevel anymore to pick your next level.
           Instead, the server admin chooses the levels he/she wants
           the patch to cycle through.

Changes:
    - Speed Cheat Checking has been updated, so those cheating soldiers
      out there won't be moving so fast.
    - Finally updated this doc!

Map Code Enhancements:
    - Goals can specify a team they belong to
    - Goals can specify a starting state
    - Activation Criteria can check other Goal's states
    - Can Centerprint to members on/not-on AP's team
    - Detection entity can specify a custom Team Menu message
    - Detection entity can specify a Map Help message
    - Entities can specify whether they exist for different "skill" settings
    - TeamSpawn points can remove themselves after being spawned on
    - GoalItems can glow when not being carried
    - Detection entity can restrict available classes for each team
    - All Goals can specify an 'else' goal, which is activated if this isn't
    - Detection entity can now specify a maximum number of players in each team
    - All Goals can display the status of upto 2 GoalItems when activated
    - GoalItems can centerprint messages to players when they return
    - Detection entity can restrict teams to the Civilian class for fancy maps
    - Can Centerprint to owners of a Goal/Item when it's activated
    - Any Goal/Item can force an item to return
    - Any Goal check whether any GoalItem is at its origin in it's Criteria
    - Goals that give out GoalItems can specify whether they want to the Item
      itself to apply results.
    - Detection entity can specify that the Grappling Hook cannot be used
    - Any Goal can remove/restore Team Spawnpoints
    - GoalItems can specify console item's they'd like to light up when carried

Map Code Changes:
    - "Personal Message" is now centerprinted to AP
    - "Broadcast Message" is now centerprinted to everyone else
    - Goals activated by others now check their Criteria before activating
    - GoalItems don't restore a goal when they return, now they activate it

Map Code breakages (Old maps won't work if you used these)
    - Detection entity can now make Pyro class illegal.
      It replaces the Random PC prevention.
      This will only cause a problem if you have a map which
      prevented players from playing Random PC.
    - GoalItems don't restore a goal when they return, now they activate it.
      If you had any GoalItems using the "impulse" variable to restore a Goal
      when the GoalItem returns, you'll need to redo the Goalwork.
      My suggestion: Say a GoalItem was restoring Goal A when it returned.
                     Make a Goal B. Make the GoalItem activate Goal B when
                     it returns. Make Goal B restore Goal A.
      If you're wondering why I did this, it's because an activating goal
      can restore a goal, and do much more. This way, you're not limited in
      what you want to do when a GoalItem is returned.
```

-- tf21_cl.zip/README.TXT

## v2.11


todo

A bug is mentioned in this version on Jord's:

> Tuesday January 28, 1997 04:50 PM
>
> TeamFortress 03:35 PM\
> Class Changing Bug 03:26 PM\
> OK version 2.11 of TeamFortress has a bug in it. The cheat checking has been improved greatly but as a side effect of this there are times when the TF server to which you are connected sends the command to the master to change your skin and because of the load on the masters some times they don't get the command instantly. Next time the cheat check looks at you you have the wrong skin and get kicked off the server (they don't actually log twenty frags against you)
> I talked to the guys at TF and they are going to have the cheat checking just reset your skin to what it should be instead of kicking players. In the mean time they sent me these instructions on how to recompile your server without skin checking

-- [http://jord.sbc.edu/archives/news/012497_013097.htm](https://web.archive.org/web/19980216153351/http://jord.sbc.edu/archives/news/012497_013097.htm) (archived)

This version is mentioned BluesNews:

> January 28, 1997
>
> TeamFortress\
> There are two new patches on the TeamFortress page (thanks DiabloZ). Also, there's info on a workaround for a bug in version 2.11 of TeamFortress on Jord's Quake World.

-- [https://www.bluesnews.com/archives/jan97-4.html](https://www.bluesnews.com/archives/jan97-4.html)

Links:

* http://www.telefragged.com/teamfortress/

The changelog from version 2.14 suggests a release on January 27th.

```text
-------------------------------------
Version 2.11  - Released 27/1/97
-------------------------------------
Features Added:
    - Speed checking is now much more efficient, and will catch
      them everytime.
    - Suiciders now have a respawn delay, and cannot re-suicide for 10
      seconds. This prevents them from crashing servers.
    - Skin and color checking has been fixed, and players who are
      caught are kicked.

Changes:
    - Teamfrags option changed. Servers now have the option to
      never use teamfrags. This is now the default.
```

-- qwwf214.zip/README.TXT

**A copy of this release has not yet been acquired for this archive.**

## v2.12

todo

This version is mentioned on BluesNews:

> February 4, 1997
>
> New TeamFortress\
> Version 2.12 of the TeamFortress patch is out, featuring a few bug fixes. Thanks DiabloZ.

-- https://www.bluesnews.com/archives/feb97-1.html

Links:

* http://www.telefragged.com/teamfortress/

This version is mentioned on Jord's:

> Tuesday February 04, 1997 07:49 PM
>
> Version 2.12 12:23 PM\
> Well here it is. The guys down at TeamFortress have finally gotten version 2.12 out.
Improvements and bug fixes include.
> Map Code Enhancements\
> Skin checking no longer disconnects the player, just sets the skin back.\
> Sniper laser sight and autozoom changed.\
> CHEAT_WARNINGS option that you can use to turn off the cheat display and have the checking run only in the background.

-- [http://jord.sbc.edu/archives/news/013197_020697.htm](https://web.archive.org/web/19980216153427/http://jord.sbc.edu/archives/news/013197_020697.htm) (archived)

This version is mentioned in a message signature by Robin Walker on USNET:

```text
...
Robin.

------
wal...@netspace.net.au
TeamFortress Version 2.12 is out.
Download it from the WWW page: http://www.telefragged.com/teamfortress
```

-- [rec.games.computer.quake.misc](https://groups.google.com/g/rec.games.computer.quake.misc/c/16b42SBX5uI/m/6Iotij72U6oJ)


This version is mentioned as being installed on a server on USENET (translated):

```text
Team Fortress v. 2.12 juz jest!
KraQs
13 Feb 1997

Hey.

I installed version 2.12 of the Team Fortress server on VAVEL – the latest version currently available. It doesn't require installing a new client (2.11 works correctly). Several bugs have been fixed, mainly related to color changes, the grappling hook, and the sniper's shotgun. Version 2.2 with bots is coming! By the way – a day earlier than I announced – I've added the Cascade and Hedge 5 maps to the game.
```

-- [pl.rec.gry.komputerowe](https://groups.google.com/g/pl.rec.gry.komputerowe/c/_DoaAF1R8S4/m/mvu_RlfBcvgJ)

The changelog from version 2.14 suggests a release on February 4th.

```text
-------------------------------------
Version 2.12  - Released 4/2/97
-------------------------------------
Map Code Enhancements:
    - Goals can do more intelligent broadcasting with netname.(Happy Network? ;)

Changes:
    - Skin checking no longer disconnects the player, just sets the skin back.
    - Sniper laser sight and autozoom.
```

-- qwwf214.zip/README.TXT

**A copy of this release has not yet been acquired for this archive.**

## v2.13

Released as `qwwf213.zip`.

This version is mentioned on Jord's:

> Monday February 17, 1997 11:59 PM EST
>
> Team Fortress 11:32 PM\
> The guys on the TF team have yet another update to the popular TeamFortress mod. Version 2.13 is now out.
> Changes include
> Better prevention of cheating with mouse movement.\
> Medic gets a frag for curing infection and concussion.\
> Level cycling is now sensitive to the number of Players in the game.\
> Sniper Reload time #defined for accessibility. (Heh I had already done that on my server)\
> Medic max_armor and max_nails lowered.\
> Assault Cannon's damage increased. (evil grin, this could be fun)\
> Flame-thrower and Incendiary Cannon damage increased in the net version. This is because the Pyro is a weaker character on net, due to the fact he cannot spread fires. (Its about time)\
> All damage done by players is now reduced by 10%. (Probably not a bad idea)\
> The TF people are also planing to have an new full version out soon. With new classes and other improvements.

-- [http://jord.sbc.edu/archives/news/021697_021897.htm](https://web.archive.org/web/19980216153555/http://jord.sbc.edu/archives/news/021697_021897.htm) (archived)

Links:

* http://www.telefragged.com/teamfortress/

This version is mentioned on USENET:

```text
...
Starting with TF 2.13, mouse movement was disabled at the server level.
There's nothing you can do on the Client to get around it.
Unfortunately it was necessary in order to fix a sometimes-intentional,
sometimes-not "cheating" problem. By using the mouse, the HWGuy and
Soldier were able to run practically as fast as the Scout. That
defeated one of the main balancing features between the various
different player classes.

We play a lot of LAN games of TF on Saturday nights, and we had a friend
figure this out back with version 2.12. We didn't bother to mention it
to the TF guys, but they apparently discovered it themselves. Only
about a week or two later, version 2.13 was out with the fix.
...
```

-- [rec.games.computer.quake.misc](https://groups.google.com/g/rec.games.computer.quake.misc/c/F7XDBOUCmA0/m/qY0flW5tOW4J)

This version is listed on QUTA:

> Quakeworld Team Fortress Server files (687k) These do not require the client side files, so if you can use TCP/IP, this is for you

-- [http://web.ukonline.co.uk/Members/dr.stebbings/clubshop.htm](https://web.archive.org/web/19970615012732/http://web.ukonline.co.uk:80/Members/dr.stebbings/clubshop.htm) (archived)

Links:

* http://web.ukonline.co.uk/Members/dr.stebbings/ZIPFILES/qwwf213.zip

The changelog from version 2.14 suggests a release on February 17th.

```text
-------------------------------------
Version 2.13  - Released 17/02/97
-------------------------------------
Features Added:
    - Better prevention of cheating with mouse movement.
    - Medic gets a frag for curing infection and concussion.
    - Level cycling is now sensitive to the number of Players in the game.

Map Code Enhancements:
    - GoalItems can centerprint messages to players when they're dropped by
      a dying player.

Changes:
    - Method of counting players adjusted so we count people with a fancy
      character as the first letter in their name. This will fix team
      imbalances in the autoteam assignment.
    - Sniper Reload time #defined for accessability.
    - Medic max_armor and max_nails lowered.
    - Assault Cannon's damage increased.
    - Flamethrower and Incendiary Cannon damage increased in the net version.
      This is because the Pyro is a weaker character on net, due to the fact
      he cannot spread fires.
    - All damage done by players is now reduced by 10%.

Bug Fixes:
    - Fixed a killtarget problem which prevented TF Goals from using
      killtarget and target effectively (Thanks Jeremy!)
    - Fixed a problem with the Class-Persistence in non-Coop Mode play.
```

-- qwwf214.zip/README.TXT

**A copy of this release has not yet been acquired for this archive.**

## v2.14

Released as five files:

* `lanwf214.zip`
* `netnf214.zip`
* `netwf214.zip`
* `qwwf214.zip`
* `tf214src.zip`

Files for this release were listed on the Time2Quake files area:

```text
lanwf214.zip           03-Apr-97 22:09   686k
netnf214.zip           03-Apr-97 22:09   183k
netwf214.zip           03-Apr-97 22:10   686k
qwwf214.zip            03-Apr-97 22:11   686k
tf214src.zip           03-Apr-97 22:12   328k
```

-- [http://www.time2quake.com/filez/teamfortress/](https://web.archive.org/web/19970706053450/http://www.time2quake.com/filez/teamfortress/) (archived)

Content of `lanwf214.zip`:

```text
-rw-rw-r--  0 0      0         215 23 Jan  1997 AUTOEXEC.CFG
-rw-rw-r--  0 0      0         175 11 Mar  1997 CHANGES.TXT
-rw-rw-r--  0 0      0         416 23 Jan  1997 CTF.TXT
-rw-rw-r--  0 0      0     1594438 23 Jan  1997 PAK0.PAK
-rw-rw-r--  0 0      0      436092 11 Mar  1997 PROGS.DAT
-rw-rw-r--  0 0      0       43235 11 Mar  1997 README.TXT
-rw-rw-r--  0 0      0        7121 11 Mar  1997 SERVER.TXT
-rw-rw-r--  0 0      0       19092 21 Feb  1997 TFENTREF.TXT
-rw-rw-r--  0 0      0       61103 11 Mar  1997 TFORTMAP.TXT
```

Content of `netnf214.zip`:

```text
-rw-rw-r--  0 0      0         232 23 Jan  1997 AUTOEXEC.CFG
-rw-rw-r--  0 0      0         175 11 Mar  1997 CHANGES.TXT
-rw-rw-r--  0 0      0         416 23 Jan  1997 CTF.TXT
-rw-rw-r--  0 0      0      436408 11 Mar  1997 PROGS.DAT
-rw-rw-r--  0 0      0       43235 11 Mar  1997 README.TXT
-rw-rw-r--  0 0      0        7121 11 Mar  1997 SERVER.TXT
-rw-rw-r--  0 0      0       19092 21 Feb  1997 TFENTREF.TXT
-rw-rw-r--  0 0      0       61103 11 Mar  1997 TFORTMAP.TXT
```

Content of `netwf214.zip`:

```text
-rw-rw-r--  0 0      0         232 23 Jan  1997 AUTOEXEC.CFG
-rw-rw-r--  0 0      0         175 11 Mar  1997 CHANGES.TXT
-rw-rw-r--  0 0      0         416 23 Jan  1997 CTF.TXT
-rw-rw-r--  0 0      0     1594438 23 Jan  1997 PAK0.PAK
-rw-rw-r--  0 0      0      436748 11 Mar  1997 PROGS.DAT
-rw-rw-r--  0 0      0       43235 11 Mar  1997 README.TXT
-rw-rw-r--  0 0      0        7121 11 Mar  1997 SERVER.TXT
-rw-rw-r--  0 0      0       19092 21 Feb  1997 TFENTREF.TXT
-rw-rw-r--  0 0      0       61103 11 Mar  1997 TFORTMAP.TXT
```

Content of `qwwf214.zip`:

```text
-rw-rw-r--  0 0      0         175 11 Mar  1997 CHANGES.TXT
-rw-rw-r--  0 0      0         416 23 Jan  1997 CTF.TXT
-rw-rw-r--  0 0      0     1594438 23 Jan  1997 PAK0.PAK
-rw-rw-r--  0 0      0      438328 11 Mar  1997 PROGS.DAT
-rw-rw-r--  0 0      0       43235 11 Mar  1997 README.TXT
-rw-rw-r--  0 0      0         160 23 Jan  1997 SERVER.CFG
-rw-rw-r--  0 0      0        7121 11 Mar  1997 SERVER.TXT
-rw-rw-r--  0 0      0       19092 21 Feb  1997 TFENTREF.TXT
-rw-rw-r--  0 0      0       61103 11 Mar  1997 TFORTMAP.TXT
```

Content of `tf214src.zip`:

```text
-rw-rw-r--  0 0      0       12676 14 Feb  1997 ADMIN.QC
-rw-rw-r--  0 0      0       15150 29 Dec  1996 AI.QC
-rw-rw-r--  0 0      0       77312 22 Oct  1996 ALEXQCC.EXE
-rw-rw-r--  0 0      0        1833 29 Dec  1996 AMTEST.QC
-rw-rw-r--  0 0      0       12936 29 Dec  1996 BOSS.QC
-rw-rw-r--  0 0      0        2202  6 Dec  1996 BOT.QC
-rw-rw-r--  0 0      0       15307 20 Dec  1996 BOTAI.QC
-rw-rw-r--  0 0      0         166  3 Dec  1996 BOTS.QC
-rw-rw-r--  0 0      0        3875  5 Mar  1997 BUTTONS.QC
-rw-rw-r--  0 0      0         175 11 Mar  1997 CHANGES.TXT
-rw-rw-r--  0 0      0       62326 17 Feb  1997 CLIENT.QC
-rw-rw-r--  0 0      0       15083 17 Feb  1997 COMBAT.QC
-rw-rw-r--  0 0      0         874 20 Dec  1996 COMBOT.QC
-rw-rw-r--  0 0      0        2739 24 Dec  1996 COOP.QC
-rw-rw-r--  0 0      0        3326 23 Jan  1997 CTF.QC
-rw-rw-r--  0 0      0        1072 23 Jan  1997 DEBUG.QC
-rw-rw-r--  0 0      0       54513 11 Mar  1997 DEFS.QC
-rw-rw-r--  0 0      0       11297 29 Dec  1996 DEMON.QC
-rw-rw-r--  0 0      0       10545 29 Dec  1996 DOG.QC
-rw-rw-r--  0 0      0       20211 21 Feb  1997 DOORS.QC
-rw-rw-r--  0 0      0       12159 29 Dec  1996 ENFORCER.QC
-rw-rw-r--  0 0      0        7199 20 Nov  1996 FIGHT.QC
-rw-rw-r--  0 0      0        8025 29 Dec  1996 FISH.QC
-rw-rw-r--  0 0      0        1739 29 Dec  1996 FLARE.QC
-rw-rw-r--  0 0      0       19772 29 Dec  1996 HKNIGHT.QC
-rw-rw-r--  0 0      0       18918 23 Jan  1997 HOOK.QC
-rw-rw-r--  0 0      0       37812 29 Dec  1996 ITEMS.QC
-rw-rw-r--  0 0      0         290 29 Dec  1996 JCTEST.QC
-rw-rw-r--  0 0      0       10968 29 Dec  1996 KNIGHT.QC
-rw-rw-r--  0 0      0        2456 17 Feb  1997 LEVELS.QC
-rw-rw-r--  0 0      0          61 11 Mar  1997 MAKE.BAT
-rw-rw-r--  0 0      0       15722 23 Jan  1997 MENU.QC
-rw-rw-r--  0 0      0         950 11 Mar  1997 MESSAGES.QC
-rw-rw-r--  0 0      0       19738 29 Dec  1996 MISC.QC
-rw-rw-r--  0 0      0        9788 25 Jul  1996 MODELS.QC
-rw-rw-r--  0 0      0       10851 23 Jan  1997 MONSTERS.QC
-rw-rw-r--  0 0      0        1518 23 Jan  1997 MSKIN.QC
-rw-rw-r--  0 0      0       16116 29 Dec  1996 OGRE.QC
-rw-rw-r--  0 0      0       11561 30 Oct  1996 OLDBOT.QC
-rw-rw-r--  0 0      0        9776 29 Dec  1996 OLDONE.QC
-rw-rw-r--  0 0      0        3169 11 Mar  1997 OPTIONS.QC
-rw-rw-r--  0 0      0        9984 29 Dec  1996 PLATS.QC
-rw-rw-r--  0 0      0       28952 25 Jan  1997 PLAYER.QC
-rw-rw-r--  0 0      0         915  7 Dec  1996 PREOPDEF.QC
-rw-rw-r--  0 0      0         426 27 Dec  1996 PREPROGS.SRC
-rw-rw-r--  0 0      0       93649 19 Dec  1996 PREQCC.EXE
-rw-rw-r--  0 0      0        2598 27 Aug  1996 PROGDEFS.QC
-rw-rw-r--  0 0      0       20782 10 Feb  1997 PYRO.QC
-rw-rw-r--  0 0      0       43235 11 Mar  1997 README.TXT
-rw-rw-r--  0 0      0        7121 11 Mar  1997 SERVER.TXT
-rw-rw-r--  0 0      0        9106 29 Dec  1996 SHALRATH.QC
-rw-rw-r--  0 0      0       14030 29 Dec  1996 SHAMBLER.QC
-rw-rw-r--  0 0      0       11255 29 Dec  1996 SOLDIER.QC
-rw-rw-r--  0 0      0         486 25 Jul  1996 SPRITES.QC
-rw-rw-r--  0 0      0        6746 28 Dec  1996 SUBS.QC
-rw-rw-r--  0 0      0        7498 29 Dec  1996 TARBABY.QC
-rw-rw-r--  0 0      0       19092 21 Feb  1997 TFENTREF.TXT
-rw-rw-r--  0 0      0      101560 10 Feb  1997 TFORT.QC
-rw-rw-r--  0 0      0       15322 11 Mar  1997 TFORTHLP.QC
-rw-rw-r--  0 0      0       70371 21 Feb  1997 TFORTMAP.QC
-rw-rw-r--  0 0      0       61103 11 Mar  1997 TFORTMAP.TXT
-rw-rw-r--  0 0      0       21952 17 Feb  1997 TFORTTM.QC
-rw-rw-r--  0 0      0       19235 21 Jan  1997 TRIGGERS.QC
-rw-rw-r--  0 0      0        3057 20 Dec  1996 TURRET.QC
-rw-rw-r--  0 0      0       73467 14 Feb  1997 WEAPONS.QC
-rw-rw-r--  0 0      0       12077 29 Dec  1996 WIZARD.QC
-rw-rw-r--  0 0      0       11928 24 Dec  1996 WORLD.QC
-rw-rw-r--  0 0      0       20747 29 Dec  1996 ZOMBIE.QC
```

The file timestamps suggest a release on March 11th 1997.

This matches the date in the changelog:

```text
-------------------------------------
Version 2.14  - Released 11/03/97
-------------------------------------
Bug Fixes:
    - Various small bugs in the map code fixed.
```

-- qwwf214.zip/README.TXT


## v2.15

Released as `qwwf215.zip`.

Mentioned on the TeamFortress homepage:

> 8-4-97\
> Well, you can get version 2.15 from the Downloads section. This version is a simple port of 2.14 for QuakeWorld 1.5. It has NO new features, so unless you want to run a QW 1.5 TF server, don't bother downloading it. Sorry it took so long... we lost our net access for 2 days because we moved houses, which made it fairly difficult to upload the patch. Please Note : This version has 1 or 2 known bugs in it... they're non-fatal, but we wanted to get this version out ASAP. It only has to last for 5 days... we're still committed to getting a beta of 2.5 out by the end of this week.
>
> If you're going to run 2.15, be careful about the map you use. QuakeWorld 1.5 seems to have a lower maximum entity/static count than the previous version, so maps with too many of them will crash the server when it tries to load them. At the moment, I know that 2fort4 has too many, and other TF maps may. To fix it, edit the .bsp file and change all "light_torch_small_walltorch" entities to "light", and then qbsp it with the -onlyent parameter. That should lower the entity count.
>
> We'd like to wave farewell to Nate and Thank him for all he did for TF... he'll be missed.
At the same time, we'd like to welcome Tyr to the TF group. He's working on a revamped version of 2fort, which is looking fantastic.

-- [http://www.planetquake.com/teamfortress/working.htm](https://web.archive.org/web/19970607150217fw_/http://www.planetquake.com/teamfortress/working.htm) (archived)

Mentioned on BluesNews:

> April 7, 1997
>
> QW TeamFortress\
> TeamFortress Server 2.15, essentially a QW 1.5 port, is out on the TeamFortress page. Thanks to [UN]Falc[MOB], who's mail contained this amusing message:
>
>> NO new features are included (yes, we're still waiting on the spy, and hallucination grenades, and backstabbing, etc...<g>). Now that we'll be getting our servers back, those of us in the TF community would like to invite all you death matchers to drop by for your very own personal head wound. <g> (yes, I'm a sniper, and damn proud of it!!)

-- https://www.bluesnews.com/archives/april97-1.html

Links:

* http://www.planetquake.com/teamfortress/

Mentioned on Redwood's:

> April 7, 1997
>
> Saw on sCary's that QuakeWorld 1.5 TeamFortress (v2.15) is available.

-- [http://redwood.stomped.com/497.html](https://web.archive.org/web/20011031111944/http://redwood.stomped.com/497.html) (archived)

Links:

* http://www.planetquake.com/teamfortress/

Files for this release were listed on the Time2Quake files area:

```text
qwwf215.zip            07-Apr-97 11:29   685k
```

-- [http://www.time2quake.com/filez/teamfortress/](https://web.archive.org/web/19970706053450/http://www.time2quake.com/filez/teamfortress/) (archived)

Content of `qwwf215.zip`:

```text
-rw-rw-r--  0 0      0         175 11 Mar  1997 CHANGES.TXT
-rw-rw-r--  0 0      0         416 23 Jan  1997 CTF.TXT
-rw-rw-r--  0 0      0     1594438 23 Jan  1997 PAK0.PAK
-rw-rw-r--  0 0      0      440096  7 Apr  1997 PROGS.DAT
-rw-rw-r--  0 0      0       43235 11 Mar  1997 README.TXT
-rw-rw-r--  0 0      0         160 23 Jan  1997 SERVER.CFG
-rw-rw-r--  0 0      0        7121 11 Mar  1997 SERVER.TXT
-rw-rw-r--  0 0      0       19092 21 Feb  1997 TFENTREF.TXT
-rw-rw-r--  0 0      0       61103 11 Mar  1997 TFORTMAP.TXT
```

The file timestamps suggest a release on April 7th.

The changes and readme files were not updated for the release, suggesting it was a small bug fix release.

## v2.5 Beta A

Released as `25betaf.zip`.

Mentioned on the TeamFortress homepage:

> Last Updated 15/4/97\
> Current version: TF v2.5 Beta A, 15/4/97

-- [http://www.planetquake.com/teamfortress/](https://web.archive.org/web/19970414103937/http://www.planetquake.com/teamfortress/) (archived)

And:

14-4-97
> Yes, finally, we've released the first beta of TeamFortress Version 2.5. It's NOT a public beta... for a couple of reasons. We don't want 500 people mailing us a report of the same bug, and since we'll quite likely be releasing a few new versions over the next few days, it makes it easier for us if its in a controlled environment.
The beta is currently running on all the servers in CTSnet. Just connect to one and you'll d/l all the relevant files. We don't have a client pak here because it isn't assembled yet... we'll be adding in a few new files over the next couple of days. You can download a zip containing the current models/sounds being used right here. Unzip them in your quake\qw directory, and make sure you keep the directory structure.
>
> ...
>
> Well, there's lots more in there than that, but you'll just have to find out for yourself. We'll keep running it like this until we're happy with it's stability, and then we'll release it here, along with the client pak.

-- [http://www.planetquake.com/teamfortress/working.htm](https://web.archive.org/web/19970607150217fw_/http://www.planetquake.com/teamfortress/working.htm) (archived)

Links:

* http://www.planetquake.com/teamfortress/files/25betaf.zip

A changelog is listed on the TeamFortress homepage:

```text
--------------------------------------
Version 2.5 Beta A  - Released 13/4/97
--------------------------------------
Classes: Scout, Sniper, Soldier, Demolitions Man, Combat Medic,
         Heavy Weapons Guy, Spy, Engineer.

Features Added:
    - New, improved, and just plain nastier cheat checking.
    - Concussed ppl make bubbles.
    - Sniper rifle now has locational damage, like TF-Sniper.
    - Support for skins for each class for each team. Good for Clan battles.
    - A new alias called "special", which does the primary
      ability of your class.

Models/Sounds:
    - Assault Cannon redone with no cooling. Looks and sounds fantastic now.
    - Grenade models for all types.
    - Detpack model.
    - Ammobox model.

Quakeworld Additions:
    - QuakeWorld servers can use various Keys to set options. Keys are:
      "autoteam", "grapple", "teamfrags", etc. See QW.TXT for details.

Changes:
    - Major code cleanup. A lot of redundant code/features removed.
    - Demomen can't fire while setting detpacks.
    - Demomen can't set detpacks while in the air or hanging from a hook.
    - Scout scanner is more user friendly now.
    - Coop Mode Door/Key behaviour is much more user friendly now.
    - Assault Cannon doesn't need cooling after really short bursts.
    - Grapple cannot hurt players.
    - Snipers have flare grenades.
    - All lasting effects (concussion/hallucination/tranquilisation) can
      affect team members, but Medics only get frags for curing effects
      caused by enemy teams.

Bug Fixes:
    - Fixed a loophole in the non_team and owners_team Goal Broadcasting.
    - Fixed a bug in the map code governing items given by goals.
    - Powerups don't remove Dimlight caused by GoalItems, and vice versa.
    - Detpacks exploding outside maps.
    - Some Weapons not "kicking" your view fixed.
    - Ammoboxes are counted like pipebombs now. e.g. limited number of
      them in existence at any one time.
    - Fixed bug in pipebomb counting in deathmatch.

Map Code Enhancements:
    - Goals can use the "delay" variable now to delay their activation for a
      specific amount of time.
    - Goals can check to see if the player is carrying any items from
      a particular group in it's criteria using "has_item_from_group".
    - Goals can use the "remove_item_group" to remove all the items
      in a particular group from any player affected by its activation.
    - A new Bit was added to the "goal_results" variable for Goals/Items
      which allows them to remove a Spy's disguise.
    - A new Bit was added to the "goal_activation" of GoalItems.
      See the tfortmap.txt for details.
    - Team Spawnpoints can now use Criteria exactly the same as Goals.
      Players can only spawn at spawnpoints that they match the Criteria of.
    - Team Spawnpoints can activate a goal when someone spawns on them,
      using the "activate_goal_no" variable.

Map Code Changes:
    - Items given by Goals are not set to Active state anymore, so they
      can be given out multiple times.

Map Code Bug Fixes (Thanks Jim!) :
    - Goal/Groups being removed/returned fixed.
    - Fixed Goals applying bonuses to players through other Goals.
    - Use of the "all_active" and "last_impulse" variables is now fixed.
    - Fixed a bug with the "t_length" variable.
    - Fixed the problem of Goals using the "wait" variable never inactivating.
    - Fixed the behaviour of the "wait" variable in Goals. It used to
      remove Goals for the period of time in the "wait" variable. Now
      they stay active for that time... like the readme says they do.
```

-- [http://www.planetquake.com/teamfortress/version.htm](https://web.archive.org/web/19970607150255fw/http://www.planetquake.com/teamfortress/version.htm) (archived)

**A copy of this release has not yet been acquired.**

## v2.5 Beta B

Mentioned on the TeamFortress homepage:

> 16-4-97\
> Ok, Beta B of version 2.5 has just been mailed to CTSnet. I also sent it to Kinlord and Gudlyf, who run the BraveHeart server. It fixes various bugs, including the Spy's color changing ability, so hopefully we'll see a server or two running in that mode... personally, I find invisibility boring compared to color/skin changing :)
> If you're bored, read the version info.

-- [http://www.planetquake.com/teamfortress/working.htm](https://web.archive.org/web/19970607150217fw/http://www.planetquake.com/teamfortress/working.htm) (archived)

This suggests it is a private beta.


Mentioned on Redwoods:

> April 17, 1997
>
> The TeamFortress page has v2.5 beta available for download.

-- [http://redwood.stomped.com/497.html](https://web.archive.org/web/20011031111944/http://redwood.stomped.com/497.html) (archived)

Links:

* http://www.planetquake.com/teamfortress/

Mentioned on BluesNews:

> April 18, 1997
>
> TeamFortress 2.5 Beta Is Available?\
> I've gotten a lot more email about the TeamFortress beta... apparently there is a 2.5 beta available for download. It's just not marked on the website(?), and the beta running on some test servers.

-- https://www.bluesnews.com/archives/april97-2.html

Links:

* http://www.planetquake.com/teamfortress/

A changelog is listed on the TeamFortress homepage:

```text
--------------------------------------
Version 2.5 Beta B  - Released 16/4/97
--------------------------------------
Changes:
    - Engineers can only have 1 dispenser at a time.
    - Dispenser health lowered.
    - SentryGuns can only be activated by their owners.
    - Player's can't hurt turrets/dispensers made by their teammembers.

Bugs Fixed:
    - CycleWeapon crashing servers fixed.
    - Spy Color changing fixed.
    - Building/Stop-Building/Build loophole fixed.
    - Buildings are destroyed if the Engineer who built them changes class.
```

-- [http://www.planetquake.com/teamfortress/version.htm](https://web.archive.org/web/19970607150255fw/http://www.planetquake.com/teamfortress/version.htm) (archived)

**A copy of this release has not yet been acquired.**

## v2.5 Beta C

Mentioned on the TeamFortress homepage:

> 21-4-97\
> Ok, big update now to clear some more confusion.
> First, we're releasing beta C now. It wasn't released 2 days ago, like we hoped. Basically, we decided it wasn't ready, so we went back at kept working on it. And it was worth it.
>
>>    Features Added:
>>        - "Help!!!" impulse implemented. Any player can do issue just do it
>>          using the "saveme" command. Any medic/engineer on the same team as
>>          that person will see a lightning bolt effect around that player.
>>          Use it to signal you need help.
>>          Spy's can see anyone of any team doing it.
>>        - Spies and Scouts who touch any undercover enemy Spy remove the
>>          enemy's disguise.
>>        - Spy now has a knife model.
>>        - Engineers can remotely detonate their buildings.
>>
>>    Changes:
>>        - QW Serverinfo keys shortened to fit 256 char keyspace.
>>        - QW "temp1" key can be used like the temp1 var in normal quake.
>>        - Assault Cannon winds up in 1/2 the time.
>>        - Since the new cheat checking is tougher, moving with the mouse
>>          has been allowed again.
>>
>>    Bugs Fixed:
>>        - Snipers changing weapons while aiming fixed.
>>        - Sentries won't shoot at feigning spies now.
>>        - Healing infection from your team fixed.
>>        - Building code rewritten. It should be more robust now.
>>        - Players being unable to respawn fixed.
>>        - Color/Skin cheat checking shouldn't kick non-cheaters now.
>>        - Players with no weapon being hit by an EMP grenade won't cause problems now.
>>        - Players being prevented from moving shouldn't be kicked for speed
>>          cheating straight away.
>
> It should be on various servers soon. Unless some major bugs are found, this will probably be the last private beta. The source will then be released, etc.
> Second, just a note on the Engineer's building problems. We rewrote 90% of the code, so that it now operates in a quite different manner. It's a lot more robust in this version, but it's still not 100% perfect. We will probably try a clean it up a bit more... but basically we're resigned to the fact that we may never be able to ahve it completely foolproof.
> One of the main reasons for this is simply that Quake was not designed with this in mind. Quake rarely (if ever?) spawns a new solid entity anywhere. Instead, it teleports them in from hidden sections in the map, and it teleports them to specific places on the map, that were created with the knowledge that something would be teleported there.
> There are many traps and pitfalls that you run across when you're trying to spawn a solid entity somewhere while making sure it doesn't end up inside something else.
> We've done the best we can.
>
> Third, it seems id is not happy with the concept of us accepting donations. So, unless something changes, do not send us any money. (We will bill you ;)
This is disappointing... but thanks to all of you who mailed us to say they would have.
>
> Fourth, people have been getting confused, and leading poor Blue astray ;). The 2.5 beta F is not available on our site. You can download all the mdls/sounds that TF 2.5 beta C needs right here, but it doesn't contain the source code or the progs.dat.
We will release the source code, but not until we're happy with it's stability.
>
> Finally, some troubleshooting.
> If you get a "HunkAlloc" error when trying to connect to a TF server, then you've somehow managed to get an invalid TF mdl. I'm not sure how this happens... perhaps if the server crashes/changes-level while you're downloading it. You can fix it by downloading all the mdls & sounds here. Unzip the files into the directory where you've stored TF, or quake\qw if you haven't created a TF directory.

-- [http://www.planetquake.com/teamfortress/working.htm](https://web.archive.org/web/19970607150217fw/http://www.planetquake.com/teamfortress/working.htm) (archived)

Links:

* http://www.planetquake.com/teamfortress/files/25betaf.zip

This suggests that it is a private beta.

Mentioned on BluesNews:

> April 21, 1997
>
> TeamFortress 2.5 Beta C\
> TeamFortress 2.5 Beta C has been released on the TeamFortress homepage (I saw the link in the news section with my own two eyes--I'm not crazy, I tell you!!) you can download all the mdls/sounds that TF 2.5 beta C needs, but it doesn't contain the source code or the progs.dat. Also, apparently the concept of donateware is off the boards, because id wasn't into it.

-- https://www.bluesnews.com/archives/april97-3.html

The changelog is listed on the TeamFortress homepage:

```text
--------------------------------------
Version 2.5 Beta C  - Released 21/4/87
--------------------------------------
Features Added:
    - "Help!!!" impulse implemented. Any player can do issue just do it
      using the "saveme" command. Any medic/engineer on the same team as
      that person will see a lightning bolt effect around that player.
      Use it to signal you need help.
      Spy's can see anyone of any team doing it.
    - Spies and Scouts who touch any undercover enemy Spy remove the
      enemy's disguise.
    - Spy now has a knife model.
    - Demomen can remotely detonate their buildings.

Changes:
    - QW Serverinfo keys shortened to fit 256 char keyspace.
    - QW "temp1" key can be used like the temp1 var in normal quake.
    - Assault Cannon winds up in 1/2 the time.
    - Since the new cheat checking is tougher, moving with the mouse
      has been allowed again.

Bugs Fixed:
    - Snipers changing weapons while aiming fixed.
    - Sentries won't shoot at feigning spies now.
    - Healing infection from your team fixed.
    - Building code rewritten. It should be more robust now.
    - Players being unable to respawn fixed.
    - Color/Skin cheat checking shouldn't kick non-cheaters now.
    - Players with no weapon being hit by an EMP grenade won't cause problems now.
    - Players being prevented from moving shouldn't be kicked for speed
      cheating straight away.
```

-- [http://www.planetquake.com/teamfortress/version.htm](https://web.archive.org/web/19970607150255fw/http://www.planetquake.com/teamfortress/version.htm) (archived)

**A copy of this release has not yet been acquired.**

## v2.5 Beta D

Mentioned on the TeamFortress homepage:

> 22-4-97\
> Ok, I've released beta D, which should be up on servers soon. It fixes the sentrygun bug, the serverinfo problems, and should kill the spy's skin/color kicking bug once and for all... (touch wood;)
Oh, btw, the Demoman doesn't have the ability to remotely detonate his buildings... it's the Engineer who can. After you've built something, just use the "build" alias to bring up the menu again, and you'll see you have the option to do it there.

-- [http://www.planetquake.com/teamfortress/working.htm](https://web.archive.org/web/19970607150217fw/http://www.planetquake.com/teamfortress/working.htm) (archived)

This suggests that it is a private beta.

Mentioned on BluesNews:

> April 22, 1997
>
> TeamFortress 2.5 Beta D\
> There is an updated Beta of version 2.5 up on the TeamFortress page.

-- https://www.bluesnews.com/archives/april97-3.html

Mentioned on Redwood's:

> April 22, 1997
>
> TeamFortress Beta D\
> The recent trend of releasing slow, agonizing beta releases continues its legacy, TeamFortress has gone to beta D.

-- [http://redwood.stomped.com/497.html](https://web.archive.org/web/20011031111944/http://redwood.stomped.com/497.html) (archived)

Links:

* http://www.planetquake.com/teamfortress/

The changelog is listed on the TeamFortress homepage:

```text
--------------------------------------
Version 2.5 Beta D  - Released 22/4/87
--------------------------------------
Bugs Fixed:
    - Sentryguns not targeting the right people. And they
      target faster now.
    - Toggleflag defines fixed, so serverinfo keys are working again.
```

-- [http://www.planetquake.com/teamfortress/version.htm](https://web.archive.org/web/19970607150255fw/http://www.planetquake.com/teamfortress/version.htm) (archived)

**A copy of this release has not yet been acquired.**

## v2.5 Beta E

Released as `qw25bte.zip`.

Mentioned on the TeamFortress homepage:

> 25-4-97\
> Ok, I've released Beta E. It is the first public release of 2.5. IT IS QW ONLY. If you can't run a QW TF server, then this is useless to you. It contains the qwprogs.dat, a sample server.cfg file, and a txt file explaining the new server keys. You can download it here.
It simply fixes a couple of bugs and cleans up some other stuff. Read the full details in the version info.
> We're finally reaching what looks like a fairly stable version, so the full release shouldn't be too far away. In terms of additions, there's still a few more to go in yet. Some of these are:
>
> - A Discard alias to drop all unneeded ammo.\
> - Something extra for the Pyro class.\
> - A voting system, for various things (Exit, etc).\
> - Some more models.\
> None of these are promised... they're simply ones we'd like to get done. And there'll be some more custom stuff... graphics, maps, etc.

-- [http://www.planetquake.com/teamfortress/working.htm](https://web.archive.org/web/19970607150217fw/http://www.planetquake.com/teamfortress/working.htm) (archived)

Links:

* http://www.planetquake.com/teamfortress/files/qw25bte.zip
* http://www.planetquake.com/teamfortress/version.htm

Mentioned on BluesNews:

> April 25, 1997
>
> TeamFortress Beta E\
> TeamFortress Beta E has been released on the TeamFortress page. Contrary to previous reports, this is the first actual publicly available beta of version 2.5. It is, as pointed out, useless to you unless you can run a QuakeWorld TeamFortress server. Thanks Pat Mccomack.

-- https://www.bluesnews.com/archives/april97-3.html

The changelog is listed on the TeamFortress homepage:

```text
--------------------------------------
Version 2.5 Beta E  - Released 25/4/97
--------------------------------------
Features Added:
    - Spy disguising is more user-friendly.

Bugs Fixed:
    - Engineers can't build more than one of each building by suiciding.
    - Scouts getting removed fixed.
    - Spy disguise being removed by enemies is better.
```

-- [http://www.planetquake.com/teamfortress/version.htm](https://web.archive.org/web/19970607150255fw/http://www.planetquake.com/teamfortress/version.htm) (archived)

**A copy of this release has not yet been acquired.**

## v2.5 Beta F

Released as:

* `qw25btf.zip`
* `nq25btf.zip`
* `newfiles.zip`
* `25files.zip`

Mentioned on the TeamFortress homepage:

> 17-5-97\
> Ok, Beta F is done.
> You can download the QW Version or the Normal Quake Version.
> Note that the Normal Quake Versions has been compiled for LAN... you can run it on a net server, but it'll be badly lagged by pyros and demomen.
> It's got the usual bug fixes, and a few new features, which you can read about in the version info.
Also, player's should know about the following:
>
>> STATUS BAR
>> There's now a status bar which displays various player details, such as the team scores and the number of shots left in your clip, as well as specific class details, such as your current skin/color if you're a spy.
It works much like CTF's status bar, with a few refinements. The commands to use it are:
>>
>> sbar_on
>> This turns the status bar on. If it's already on, it cycles the status bar through three positions. The three positions are designed to put the status bar at the very bottom of your screen. If you play with no console, you want position 3, half console position 2, and full console position 1.
>> sbar_off
>> Turns the status bar off.
>>
>> sbar_200 sbar_240 sbar_300 sbar_350 sbar_384 sbar_400 sbar_480 sbar_600 sbar_768
>> These commands tell the status bar which screen resolution you're running in, so it knows where to put itself. The res you want to use is the one that corresponds to the Y value in the res you run quake in.
e.g. if you run quake in 320x200, use sbar_200
>>
>> But, there's a much better way to set your status bar position. Edit the config.cfg file in your quake\fortress directory and put in the following lines:
>> setinfo sbar_size position
>> setinfo sbar_res resolution
>> Where:
>> position is either 1, 2, or 3. The position you should use depends on how much of a console you use:
>> 1 : Full Console
>> 2 : Half Console
>> 3 : No Console
>> resolution is either 200, 240, 300, 350, 384, 400, 480, 600, or 768. It should correspond to the Y value of the res you run quake in.
Then, whenever you connect to a TF server, it'll automatically turn on the status bar with these settings.
>>
>> For example, I run quake in 320x240, with half the console up. In my config.cfg, I've got these two lines:
>>
>> setinfo sbar_size 2
>> setinfo sbar_res 240
>> DISCARD
>> This command drops a single backpack containing all the ammo your class cannot use. Great for helping teammates.
>>
>> FLASH GRENADE
>> Replaces the scouts normal grenades. It works exactly like you'd expect one to work. :)
>>
>> SPY DISABLING
>> QW Servers can now elect to disable the spy class completely. Do this by setting the "spy" infokey to "off".
>> e.g. setinfo spy off
>
>The new version also contains some new models. You can get these in two ways. The easiest way is to simply connect to a server running Beta F, and it will promptly send them to you. The faster way is to download just the new models from here. If you haven't got any of the TF 2.5 files, you can download all the TF 2.5 files.

-- [http://www.planetquake.com/teamfortress/working.htm](https://web.archive.org/web/19970607150217fw/http://www.planetquake.com/teamfortress/working.htm) (archived)

Links:

* http://www.planetquake.com/teamfortress/files/qw25btf.zip
* http://www.planetquake.com/teamfortress/files/nq25btf.zip
* http://www.planetquake.com/teamfortress/files/newfiles.zip
* http://www.planetquake.com/teamfortress/files/25files.zip

Mentioned on BluesNews:

> Saturday, May 17, 1997
>
> TeamFortress 2.5 Beta F\
> Thanks to my pal SirLiam for the word that TeamFortress 2.5 Beta F has been released on the TeamFortress Page (and very easy to find on the page this time around, I might add).

-- https://www.bluesnews.com/archives/may97-3.html

Some of these files are listed on Time2Quake:

```text
25files.zip            03-Jun-97 11:43   787k
newfiles.zip           03-Jun-97 11:44   223k
nq25btf.zip            17-May-97 10:13   209k
```

-- [http://www.time2quake.com/filez/teamfortress/](https://web.archive.org/web/19970706053450/http://www.time2quake.com/filez/teamfortress/) (archived)

Contents of `nq25btf.zip`:

```text
-rw-rw-r--  0 0      0        2453 17 May  1997 CHANGES.TXT
-rw-rw-r--  0 0      0      653600 17 May  1997 PROGS.DAT
-rw-rw-r--  0 0      0         170 17 May  1997 SERVER.CFG
```

Contents of `25files.zip`:

```text
-rw-rw-r--  0 0      0       59200 29 Nov  1996 PROGS/AMMOBOX.MDL
-rw-rw-r--  0 0      0      162084 23 Mar  1997 PROGS/BIGGREN.MDL
-rw-rw-r--  0 0      0       49560 19 Sep  1996 PROGS/CROSS1.MDL
-rw-rw-r--  0 0      0       52196 30 Mar  1997 PROGS/DETPACK.MDL
-rw-rw-r--  0 0      0       12845 26 May  1997 PROGS/DGIB1.MDL
-rw-rw-r--  0 0      0        4533 26 May  1997 PROGS/DGIB2.MDL
-rw-rw-r--  0 0      0        4869 26 May  1997 PROGS/DGIB3.MDL
-rw-rw-r--  0 0      0       59089 26 May  1997 PROGS/DISP.MDL
-rw-rw-r--  0 0      0        1967 22 Mar  1997 PROGS/E_SPIKE1.MDL
-rw-rw-r--  0 0      0        1967 22 Mar  1997 PROGS/E_SPIKE2.MDL
-rw-rw-r--  0 0      0       22264  9 Nov  1996 PROGS/FLARE.MDL
-rw-rw-r--  0 0      0        9627 12 Apr  1997 PROGS/GRENADE2.MDL
-rw-rw-r--  0 0      0      611926 17 May  1997 PROGS/HEADLESS.MDL
-rw-rw-r--  0 0      0      116992 21 Mar  1997 PROGS/HGREN2.MDL
-rw-rw-r--  0 0      0       37912 17 May  1997 PROGS/HOOK.MDL
-rw-rw-r--  0 0      0         312  5 Mar  1997 PROGS/SIGHT.SPR
-rw-rw-r--  0 0      0       12131 24 Mar  1997 PROGS/TGIB1.MDL
-rw-rw-r--  0 0      0       10491 24 Mar  1997 PROGS/TGIB2.MDL
-rw-rw-r--  0 0      0       14655 24 Mar  1997 PROGS/TGIB3.MDL
-rw-rw-r--  0 0      0       54408 26 Mar  1997 PROGS/TURRBASE.MDL
-rw-rw-r--  0 0      0       84224 28 Mar  1997 PROGS/TURRGUN.MDL
-rw-rw-r--  0 0      0       64760 29 Mar  1997 PROGS/V_ASSCAN.MDL
-rw-rw-r--  0 0      0       57908 24 Oct  1996 PROGS/V_BIO.MDL
-rw-rw-r--  0 0      0      104349  9 May  1997 PROGS/V_GRAP.MDL
-rw-rw-r--  0 0      0       62015 21 Apr  1997 PROGS/V_KNIFE.MDL
-rw-rw-r--  0 0      0       62015 21 Apr  1997 PROGS/V_KNIFE2.MDL
-rw-rw-r--  0 0      0       57908 24 Oct  1996 PROGS/V_MEDI.MDL
-rw-rw-r--  0 0      0      160272 13 Apr  1997 PROGS/V_RAIL.MDL
-rw-rw-r--  0 0      0       58735  3 Apr  1997 PROGS/V_SPAN.MDL
-rw-rw-r--  0 0      0       47071 29 Mar  1997 PROGS/V_SRIFLE.MDL
-rw-rw-r--  0 0      0       31503 22 Dec  1996 SKINS/TF_DEMO.PCX
-rw-rw-r--  0 0      0       26073 13 Apr  1997 SKINS/TF_ENG.PCX
-rw-rw-r--  0 0      0       33445 22 Dec  1996 SKINS/TF_HWGUY.PCX
-rw-rw-r--  0 0      0       27813 22 Dec  1996 SKINS/TF_MEDIC.PCX
-rw-rw-r--  0 0      0       30499 22 Dec  1996 SKINS/TF_PYRO.PCX
-rw-rw-r--  0 0      0       31515 22 Dec  1996 SKINS/TF_SCOUT.PCX
-rw-rw-r--  0 0      0       28098 22 Dec  1996 SKINS/TF_SNIPE.PCX
-rw-rw-r--  0 0      0       30579 22 Dec  1996 SKINS/TF_SOLD.PCX
-rw-rw-r--  0 0      0       27211 13 Apr  1997 SKINS/TF_SPY.PCX
-rw-rw-r--  0 0      0        7482 12 Sep  1996 SOUND/MISC/VAPEUR2.WAV
-rw-rw-r--  0 0      0        6100 21 May  1997 SOUND/SPEECH/SAVEME1.WAV
-rw-rw-r--  0 0      0       23194 21 May  1997 SOUND/SPEECH/SAVEME2.WAV
-rw-rw-r--  0 0      0       11108 31 Mar  1997 SOUND/WEAPONS/ASSCAN1.WAV
-rw-rw-r--  0 0      0        4558 31 Mar  1997 SOUND/WEAPONS/ASSCAN2.WAV
-rw-rw-r--  0 0      0       28090 31 Mar  1997 SOUND/WEAPONS/ASSCAN3.WAV
-rw-rw-r--  0 0      0        2638 13 Apr  1997 SOUND/WEAPONS/DARTGUN.WAV
-rw-rw-r--  0 0      0       27970  3 Apr  1997 SOUND/WEAPONS/DETPACK.WAV
-rw-rw-r--  0 0      0        7508 25 Sep  1996 SOUND/WEAPONS/FLMFIRE2.WAV
-rw-rw-r--  0 0      0        7710 25 Sep  1996 SOUND/WEAPONS/FLMGREXP.WAV
-rw-rw-r--  0 0      0       13338 12 Apr  1997 SOUND/WEAPONS/RAILGUN.WAV
-rw-rw-r--  0 0      0        3262 10 Aug  1996 SOUND/WEAPONS/SNIPER.WAV
-rw-rw-r--  0 0      0       32866 26 Mar  1997 SOUND/WEAPONS/TURRIDLE.WAV
-rw-rw-r--  0 0      0       18330 26 Mar  1997 SOUND/WEAPONS/TURRSET.WAV
-rw-rw-r--  0 0      0        5802 26 Mar  1997 SOUND/WEAPONS/TURRSPOT.WAV
```

Contents of `newfiles.zip`:

```text
-rw-rw-r--  0 0      0      708704  5 Apr  1997 PROGS/PLAYER.MDL
```

The file timestamps suggest a release on May 17th, at least for the server release. Perhaps a May 26th release for the additional client files.

The release date matches the date in the changelog:

```text
--------------------------------------
Version 2.5 Beta F  - Released 17/5/97
--------------------------------------
Features Added:
    - Much more powerful and admin-friendly map cycling method.
    - Decapitation.
    - Status Bar, showing team scores, as well as various details
      depending on the class you're playing.
    - Engineer is alerted when his/her sentry is destroyed.
    - Completely new user-friendly map cycling method.
    - Scout now has a flash grenade.
    - "fortress" gamedir is enforced.
    - "discard" alias, which drops all ammo your carrying that
      can't be used by your class in a single backpack.
    - Some new models, including a new grapple-gun, hook, and
      a headless player.

Changes:
    - Assault Cannon's damage increased.
    - Gas Grenades that explode underwater don't make gas.
    - Sniper's cannot jump and fire the sniper rifle.

Bugs Fixed:
    - Engineers can't build more than one of each building.
    - Kicked for color cheating in co-op fixed.
    - Class help corrected.
    - Engineers can't repair armor on players with no armor.
    - Spies can't feign on top of other spies.
    - Illegal Classes & Deathmatch 3 fixed.
    - Shub death by gunfire fixed.

Map Code Enhancements:
    - Buttons can use bit 4(8) of the "goal_activation" variable
      to make them only activated when hit by an engineer's spanner.

Map Code Bug Fixes:
    - Various centerprinted messages have been fixed.

Map Code Changes:
    - "delay" variable used for delaying goal results has been changed
      to "delay_time", to allow for better backwards compatability.

Map Code breakages (Old maps won't work if you used these)
    - Way back in version 1.3 the "goal_effects" variable was introduced,
      to allow goals to affect more than one player. In version 1.21 you
      didn't have to specify a "goal_effects" variable... instead, any
      goal simply affected it's AP. To allow for backwards compatability,
      in all versions since 1.3, any Goal that did not specify a "goal_effects"
      field automatically had it's "goal_effects" set to 1, which is affect
      AP only. This has become a problem now, since it prevents map-makers
      from having goals that have a "goal_effects" of 0.
      From this version onwards, the "goal_effects" variable will be left
      as it is in the .map file. So, if you have a map which contains any
      Goals/Items that do _not_ have a "goal_effects" variable specified,
      add it in and set it to 1.
```

-- nq25btf.zip/CHANGES.TXT

**The file `qw25btf.zip` has not yet been acquired.**

## v2.5 Beta G

Released as `tf25btg.zip` and an updated `25files.zip`.

Mentioned on the TeamFortress homepage:

> 21-5-97
> Beta G\
> Ok, Beta G is finished. You can download the QW And Lan Version, the New Files needed for it, or all the TF 2.5 files.
> The patch is now in the one zip, since QW uses qwprogs.dat and LAN uses progs.dat.
> This version is simply a bunch of bug fixes and tweaks, as follows:
>
>> Features Added:
>>     - Players using the "saveme" impulse now yell "Medic!"
>>
>> Changes:
>>     - Detpack's explosion size lowered.
>>     - Frag for killing an enemy sentry gun.
>>     - Engineer's Railgun used nails instead of metal.
>>
>> Bugs Fixed:
>>     - Detpacks exploding outside the map in QW fixed.
>>     - Number of Special Grenades limited to 4 of each type.
>>     - Number of Detpacks limited to 1.
>>     - Napalm grenades not removing themselves underwater.
>>     - Pipebomb counting tweaked.
>>     - Server's not being able to enable the grapple with the
>>       "serverinfo g on" method fixed.
>>     - Grenades exploding in player's hands hurting teammates
>>       when teamplay is on.
>>
>> Map Code Bug Fixes:
>>     - Dead Players getting GoalItems fixed.
>>
>> Map Code Changes:
>>     - Goals can now affects players who are dead, allowing dead players
>>       to get teamscores when their team captures flags, etc.

-- [http://www.planetquake.com/teamfortress/working.htm](https://web.archive.org/web/19970607150217fw/http://www.planetquake.com/teamfortress/working.htm) (archived)

Links:

* http://www.planetquake.com/teamfortress/files/tf25btg.zip
* http://www.planetquake.com/teamfortress/files/newfiles.zip
* http://www.planetquake.com/teamfortress/files/25files.zip

Mentioned on BluesNews:

> Wednesday, May 21, 1997
>
> TeamFortress 2.5 Beta G\
> TeamFortress 2.5 Beta G is available on the TeamFortress page. Thanks Klerck.

-- https://www.bluesnews.com/archives/may97-3.html

Announced on Jord's News:

> Team Fortress 17:58 EST\
> Version 2.5 beta G is now out. Changes, and bug fixes include a frag for killing enemy sentry guns. That one has been over due. Several other things have been changed some of which I don't like but then when the final release is out with the source I'll fix for my server. <evil grin>
>
> tf25btg.zip (www.planetquake.com) - server files
>
> 25files.zip (www.planetquake.com) - client and server files
>
> Team Fortress

-- [http://jord.sbc.edu/main.htm](https://web.archive.org/web/19980111035532/http://jord.sbc.edu/main.htm)

Links:

* http://www.planetquake.com/teamfortress/files/tf25btg.zip
* http://www.planetquake.com/teamfortress/files/25files.zip
* http://www.planetquake.com/teamfortress/

**A copy if this release has not yet been acquired.**

## v2.5 Beta H

Released as `tf25bth.zip`.

Mentioned on the TeamFortress homepage:

> 22-5-97\
> Ok, Beta H is finished. You can download the QW And Lan Version, the New Files needed for it, or all the TF 2.5 files.\
> There's no new files essentially, but the dispenser's size has been changed, and we've got a new mdl to suit it. If you don't get the new model, you'll still be able to play, but dispenser's won't look quite right.\
> ...

-- [http://www.planetquake.com/teamfortress/working.htm](https://web.archive.org/web/19970607150217fw/http://www.planetquake.com/teamfortress/working.htm) (archived)

Links:

* http://www.cdrom.com/pub/idgames2/planetquake/teamfortress/tf25bth.zip
* http://www.cdrom.com/pub/idgames2/planetquake/teamfortress/newfiles.zip
* http://www.cdrom.com/pub/idgames2/planetquake/teamfortress/25files.zip

Mentioned on BluesNews:

> Tuesday, May 27, 1997
>
> TeamFortress Beta H\
> Thanks Bethune for word that TeamFortress Beta H is out. Speaking of TeamFortress, Falconeer's Sniper Tactics can teach budding Lee Harveys what's up with "that darn sniper rifle".

-- https://www.bluesnews.com/archives/may97-4.html

Listed on Time2Quake:

```text
tf25bth.zip            26-May-97 23:56   427k
```

-- [http://www.time2quake.com/filez/teamfortress/](https://web.archive.org/web/19970706053450/http://www.time2quake.com/filez/teamfortress/) (archived)

Content of `tf25bth.zip`:

```text
-rw-rw-r--  0 0      0        2669 27 May  1997 CHANGES.TXT
-rw-rw-r--  0 0      0      660920 27 May  1997 PROGS.DAT
-rw-rw-r--  0 0      0        5892 27 May  1997 QW.TXT
-rw-rw-r--  0 0      0      669284 27 May  1997 QWPROGS.DAT
-rw-rw-r--  0 0      0         199 27 May  1997 SERVER.CFG
-rw-rw-r--  0 0      0          13 17 May  1997 QWMCYCLE/MAP1.CFG
-rw-rw-r--  0 0      0          15 18 May  1997 QWMCYCLE/MAP2.CFG
-rw-rw-r--  0 0      0          36 17 May  1997 QWMCYCLE/MAP3.CFG
-rw-rw-r--  0 0      0          27 17 May  1997 QWMCYCLE/MAP4.CFG
-rw-rw-r--  0 0      0          15 27 May  1997 QWMCYCLE/MAP5.CFG
```

The file timestamps suggest a release on May 27th.

This matches the date in the changelog:

```text
--------------------------------------
Version 2.5 Beta H  - Released 27/5/97
--------------------------------------
Features Added:
    - Demomen can select pipebomb launcher with impulse 7, and 6
      always selects normal grenades.

Changes:
    - Medic's now heal teammates fully in one hit with the medikit, and
      it doesn't use any medikit ammo.
    - If a Medic hits a teammate with the medikit, and the teammate is already
      fully healed, then the Medic will add 5 megahealth to the teammate,
      upto 50 megahealth over the teammates max health. This uses up 1 medikit
      ammo per 5 megahealth.
    - Medic's now use 1 medikit ammo per 1 health regenerated.
    - Engineer's repair 4 armor for every 1 metal now.
    - New Dispenser mdl by Jim Kaufman. It's now smaller, and can be jumped.
    - Players can't shoot for 0.4s after spawning, to prevent ppl dying in a
      fight from accidently shooting teammates.
    - The use of "samelevel" restored, and we now use the serverinfo key "n"
      to store the current level number in the cycle. Read the qw.txt file
      for full details.

Bugs Fixed:
    - Demomen "bouncing" as they set detpacks.
    - "trigger_hurt" entities only gibbing a player once.
    - Engineer's building cleaned up. No more build-sentry-change-class,
      or build-sentry-reconnect.

Map Code Changes:
    - Goals that injure players they affect never gib the player. This should
      stop Jim Kaufman's Rock map crashing.

Map Code Enhancements:
    - There are now abbreviations for many of the mapcode entity's strings.
      This should help for those of you having trouble with Quake's limit on
      a map's entity details.
      The Abbreviations are as follows:
        Classnames
            "i_p_t"   for   "info_player_teamspawn"
            "i_t_g"   for   "info_tfgoal"
            "i_t_t"   for   "info_tfgoal_timer"

        Common Variables
            "g_a"     for   "goal_activation"
            "g_e"     for   "goal_effects"

        String Variables
            "t_s_h"   for   "team_str_home"
            "t_s_m"   for   "team_str_moved"
            "t_s_c"   for   "team_str_carried"
            "n_s_h"   for   "non_team_str_home"
            "n_s_m"   for   "non_team_str_moved"
            "n_s_c"   for   "non_team_str_carried"

            "b_b"     for   "broadcast"
            "b_t"     for   "team_broadcast"
            "b_n"     for   "non_team_broadcast"
            "b_o"     for   "owners_team_broadcast"
            "n_b"     for   "netname_broadcast"
            "n_t"     for   "netname_team_broadcast"
            "n_n"     for   "netname_non_team_broadcast"
            "n_o"     for   "netname_owners_team_broadcast"

            "d_t"     for   "team_drop"
            "d_n"     for   "non_team_drop"
            "d_n_t"   for   "netname_team_drop"
            "d_n_n"   for   "netname_non_team_drop"
```

-- tf25bth.zip/CHANGES.TXT

## v2.5 Beta I

Released as `tf25bti.zip`

Mentioned on the TeamFortress homepage:

> Last Updated 3/6/97\
> Current version: TF v2.5 Beta I, 3/6/97

-- [http://www.planetquake.com:80/teamfortress](https://web.archive.org/web/19970607133107/http://www.planetquake.com:80/teamfortress/) (archived)

And:

> 3-6-97\
> Beta I\
> Ok, here at Betas-R-Us we've released Beta I. Thanks must go to GudlyF for his beta testing help, and thanks to everyone on the BraveHeart servers who put up with the constant server crashes while we searched for the problem.
> You can download the QW And Lan Version, the New Files needed for it, or all the TF 2.5 files.
> The only new file is the player.mdl with the Spy and Engineer skins, which is useless if you play QW only. If you play Normal/Lan TF, then you want this.
> ...

-- [http://www.planetquake.com/teamfortress/working.htm](https://web.archive.org/web/19970607150217fw/http://www.planetquake.com/teamfortress/working.htm) (archived)

Links:

* http://www.cdrom.com/pub/idgames2/planetquake/teamfortress/tf25bti.zip
* http://www.cdrom.com/pub/idgames2/planetquake/teamfortress/newfiles.zip
* http://www.cdrom.com/pub/idgames2/planetquake/teamfortress/25files.zip

Mentioned on BluesNews:

> Tuesday, June 3, 1997
>
> New TeamFortress\
> Beta I of TeamFortress 2.5 is now available on the TeamFortress Page (thanks SirLiam).

-- https://www.bluesnews.com/archives/may97-5.html

Mentioned on Time2Quake:

> June 03, 1997
>
> TeamFortress Beta I\
>Team Fortress Beta 1 is out so go the Team Fortress home page and get news/info/download.

-- [http://www.time2quake.com/scarecrow/scqold.htm](https://web.archive.org/web/19970706050533/http://www.time2quake.com/scarecrow/scqold.htm) (archive)

Links:

* http://www.planetquake.com/teamfortress/

Listed on Time2Quake:

```text
tf25bti.zip            03-Jun-97 15:12   435k
```

-- [http://www.time2quake.com/filez/teamfortress/](https://web.archive.org/web/19970706053450/http://www.time2quake.com/filez/teamfortress/) (archived)

Content of `tf25bti.zip`:

```text
-rw-rw-r--  0 0      0        3363  4 Jun  1997 CHANGES.TXT
-rw-rw-r--  0 0      0      665764  4 Jun  1997 PROGS.DAT
-rw-rw-r--  0 0      0      674532  4 Jun  1997 QWPROGS.DAT
-rw-rw-r--  0 0      0        7517  3 Jun  1997 QWSERVER.TXT
-rw-rw-r--  0 0      0         201  4 Jun  1997 SERVER.CFG
-rw-rw-r--  0 0      0        4910  3 Jun  1997 SERVER.TXT
-rw-rw-r--  0 0      0          21  4 Jun  1997 MCYCLE/MAP1.CFG
-rw-rw-r--  0 0      0          23  4 Jun  1997 MCYCLE/MAP2.CFG
-rw-rw-r--  0 0      0          44  4 Jun  1997 MCYCLE/MAP3.CFG
-rw-rw-r--  0 0      0          35  4 Jun  1997 MCYCLE/MAP4.CFG
-rw-rw-r--  0 0      0          12  4 Jun  1997 MCYCLE/MAP5.CFG
-rw-rw-r--  0 0      0          13 17 May  1997 QWMCYCLE/MAP1.CFG
-rw-rw-r--  0 0      0          15 18 May  1997 QWMCYCLE/MAP2.CFG
-rw-rw-r--  0 0      0          36 17 May  1997 QWMCYCLE/MAP3.CFG
-rw-rw-r--  0 0      0          27 17 May  1997 QWMCYCLE/MAP4.CFG
-rw-rw-r--  0 0      0          15 27 May  1997 QWMCYCLE/MAP5.CFG
```

The timestamps suggest a release on June 4th.

This is close to the date in the changelog:

```text
--------------------------------------
Version 2.5 Beta I  - Released  3/6/97
--------------------------------------
Features Added:
    - Respawn Delay code fixed. QW servers can set a respawn delay by
      using the serverinfo key "respawn_delay" to set a time in seconds.
      LAN servers have a set Respawn Delay of 5 seconds by using the
      "temp1" variable.
      Suiciding players cannot respawn for an extra 5 seconds.
    - EMP Grenades detonate pipebombs and ammoboxes/discard-backpacks.
    - Forced Reloading time is now proportional to the number of empty
      spaces in the clip.
    - Dispensers create ammo inside themselves at a rate of
      20 shells, 30 nails, 15 rockets, 20 cells, & 25 armor every 10 seconds.
    - Player suiciding or killing themselves while infected now
      give the medic a frag.
    - IDing sentries/dispensers tells you who built them.
    - Direct selection impulse for Axe added. The impulse is 40.
      It will select the axe equivalent for your current class.
      e.g. Knife for Spy, Spanner for Engineer, BioWeapon for Medic,
           Axe for everyone else.

Changes:
    - When a player gets ammo/armor from a dispenser, he/she attempts to
      get as much as they can carry in one go.
    - Drop Ammo amount and Dispenser Ammo Retrieval amount doubled.
    - Detpacks can't be set with fuses shorter than 5 seconds.
    - Nail Grenade's nails don't knock players around.
    - Nail Grenade's nails damage decrease to by a 1/3.
    - Heavy Weapons Man is not knocked around by the damage he takes.
    - Tweaked Soldier and Medic.

Bug Fixes:
    - Bug in alias creation fixed. ZMalloc should occur less frequently now.
    - Pyro rockets/flames hurting teammates fixed.
    - Demomen retrieving detpacks being unable to move fixed.
    - Sentry Gun's not using rocket ammo fixed.
    - Sentry Gun's taking double damage from explosions fixed.
    - Sentry Gun's not shooting anyone in DM fixed.
    - Team Centerprinting in DM fixed.
    - Detpack blocking fixed.
    - Engineer getting other class's weapons fixed. Sorry ;)
    - Railgun weapon selection fixed.
    - Detpack countdown being removed if setter dies fixed.
    - Armor picture being incorrectly updated fixed.
    - Status Bar crashing in Size 3 (No Console) fixed.
      There is only two Statusbar sizes now: Full Console and Half Console.

Map Code Changes:
    - "armortype" variable for Goals used to be added to player's current
      armortype. Now, the player's armortype is set to the Goals "armortype".
      Armortypes are:
            0.3 : Green
            0.6 : Yellow
            0.8 : Red

Map Code Bug Fixes:
    - Illegal Classes handling for Spy, Engineer, and RandomPC fixed.
    - Goals starting in Removed state being visible fixed.
    - GoalItem's Reverse activation bit working now.
    - Timer Goals not checking criteria properly fixed.
    - Abbreviations for "info_tfdetect" entities fixed.
    - Goal's giving armor not updating the picture fixed.

Map Code Enhancements:
    - A new bit (32) was added to the "goal_effects".
        32  :   If a player who fits one of the other "goal_effects" variables
                is not in the same environment as the Goal, don't affect him.
                Environments are air, water, slime, lava.
                e.g. If a Goal is above some water, and does a radius effect
                     with "t_length", and a player in the water is within the
                     radius, he won't be affected if this bit is set.
```

-- tf25bti.zip/CHANGES.TXT

## v2.5 Beta J

Released as `tf25btj.zip`

Mentioned on BluesNews:

> Tuesday, June 10, 1997
>
> TeamFortress Quake\
> The new beta of TeamFortress 2.5 that has been posted on the TeamFortress page, is promised to be the last beta before the final release of version 2.5. I received a well done demo that was kind of like a music video, to promote TF 2.5. The demo was pretty nifty, I presume it will be made publicly available eventually.

-- https://www.bluesnews.com/archives/june97-1.html

Listed on Time2Quake:

```text
TF25BTJ.ZIP            10-Jun-97 12:52   208k
```

-- [http://www.time2quake.com/filez/teamfortress/](https://web.archive.org/web/19970706053450/http://www.time2quake.com/filez/teamfortress/) (archived)

Contents of `tf25btj.zip`:

```text
-rw-rw-r--  0 0      0        1187 11 Jun  1997 CHANGES.TXT
-rw-rw-r--  0 0      0      665828 11 Jun  1997 PROGS.DAT
```

The file timestamps suggest a release on June 11th.

This is close to the date in the changelog:

```text
-----------------------------------------
Version 2.5 Final Beta - Released 10/6/97
-----------------------------------------
Changes:
    - Added support for QW "rj" key to allow RocketJump customisation.
    - Soldiers Rocket damage increased to 92 direct, 92+rnd(20) splash.
    - Demoman starts with Blast resistant armor.
    - Detpacks are removed if the demoman who set them disconnects.
    - Map Code mdl setting cleaned up.
    - Players in Observer mode have their skin set to base.
    - CTF support now uses the tf_flag.mdl
    - Decapitation removed in QW version, since we were exceeding QW's
      16 meg RAM limit.

Bugs Fixed:
    - Engineer out of shells being unable to select railgun fixed.
    - Special Armor types not updating correctly fixed.
    - Incendiary Rockets injuring teammates fixed.

Map Code Enhancements:
    - A new bit (64) was added to the "goal_effects".
        64 : If this bit is set, then instead of just applying this Goal's
             results to the group of players specified by the other
             "goal_effects" variable, this Goal checks it's criteria for
             each player in the group and then applies it's results
             invididually to any of them that pass.
```

-- tf25btj.zip/CHANGES.TXT


## v2.5 Final Beta

The filename for this release is not yet known.

This "final beta" may be one and the same as "v2.5 Beta J". I suspect this is the case, but the post on BluesNews make this confusing.

Mentioned on the TeamFortress homepage:

> Last Updated 10/6/97\
> Current version: TF v2.5 Final Beta, 10/6/97

-- [http://www.planetquake.com:80/teamfortress](https://web.archive.org/web/19970611032547/http://www.planetquake.com:80/teamfortress/) (archived)

Mentioned on BluesNews:

> Friday, June 13, 1997
>
> TeamFortress 2.5 Final Beta\
> The final beta of TeamFortress 2.5 has been released on the TeamFortress Page (thanks orangE-[CE]). The cool TF promo was supposed to be released simultaneously, but I can't find it posted yet.

-- https://www.bluesnews.com/archives/june97-1.html

This release is not mentioned in the changelog for the final v2.5 release.

**A copy of this release has not yet been acquired.**

## v2.5

Released as:

* `tf25rel.zip`
* `tf25src.zip`

Mentioned on the TeamFortress News page:

> 13.06.1997\
> Team Fortress Version 2.5 Final Release\
> Yes, it's finally here. Download TF 2.5.\
> The zip file contains all versions, normal and QW, client and server. And the promo.
>
> Well, we're going out to get absolutely legless, and we're not going to be back for 2 days.
> So if you find a bug, tell it to someone who cares.

-- [http://www.planetquake.com/teamfortress/news.html](https://web.archive.org/web/19970617153959/http://www.planetquake.com/teamfortress/news.html) (archived)

Links:

* ftp://ftp.cts.com/software/games/quakeworld/fortress/tf25rel.zip

Listed on the TeamFortress Downloads page:

> TF 2.5    \
> Team Fortress Version 2.5 Final Release  \
> Download TF 2.5\
> Contains all versions, normal and QW, client and server. And the promo.
>
> Download TF 2.5 Source Code\
> The code and everything needed to compile it.
>
> BTW, Team Fortress 2.5 is now donateware. Feel free to download it without donating, but if you would like to contribute, the details are here.

-- [http://www.planetquake.com/teamfortress/download.html](https://web.archive.org/web/19970617154012/http://www.planetquake.com/teamfortress/download.html) (archived)

Links:

* ftp://ftp.cts.com/software/games/quakeworld/fortress/tf25rel.zip
* http://www.teamfortress.com/files/teamfortress/tf25src.zip

Mentioned on BluesNews:

> Friday, June 13, 1997
>
> TeamFortress 2.5 Final!\
> Well that was a short beta period (see below). The final version of TeamFortress version 2.5 (3 MB) has been released. The package contains the whole deal: a normal and QuakeWorld version (both client and server), and the cool TF 2.5 promo. The new release is also (obviously) available on the newly redesigned TeamFortress page which looks great. There is also a description there of a TF demo competition, as well as the news that they have been allowed by id Software to accept donations (so all you TF fans, get your checkbooks ready...). Thanks for word on this from Rooks, who has revamped his TF Strategy Guide for the occasion.

-- https://www.bluesnews.com/archives/june97-1.html

Links:

* https://www.bluesnews.com/files/patches/teamfortress/tf25rel.zip

Mentioned on Telefragged:

> Fri Jun 13 17:28:34 CDT 1997
>
> TeamFortress\
> If you go to the awesomely remodeled TeamFortress Page, you will find that the final version of 2.5 has been released. Get both the server/client combined pack. Also, they have started a demo competition. Also, they are accepting donations from TeamFortress players, details are here.

-- [http://www.telefragged.com/oldnews/june.shtml](https://web.archive.org/web/19980114112029/http://www.telefragged.com/oldnews/june.shtml) (archived)

Links:

* http://www.planetquake.com/teamfortress
* ftp://ftp.telefragged.com/pub/quake/quakec/tf/tf25rel.zip
* http://www.teamfortress.com/democomp/
* http://www.teamfortress.com/register.html

This version was uploaded to `cdrom.com`:

```text
tf25rel.txt            06-Jul-97 18:02    44k
tf25rel.zip            06-Jul-97 18:02   3.1M
```

-- [http://www.cdrom.com/pub/idgames2/quakec/teamplay/](https://web.archive.org/web/19980210220428/http://www.cdrom.com:80/pub/idgames2/quakec/teamplay/) (archived)

This version was reviewed on QCArchive:

> One feature that I thoroughly enjoyed was the demo that came with TF 2.5. It's practically an opera. The demo really shows off the features found in TF. The demo has a fantastic finale which ends with a BOOM literally. This demo puts the great Ranger Gone Bad 2 to shame. That's how good it is.

-- [http://www.planetquake.com:80/qca/patch182.htm](https://web.archive.org/web/19970719012544/http://www.planetquake.com:80/qca/patch182.htm) (archived)

Links:

* http://www.planetquake.com/teamfortress/
* http://www.planetquake.com/qca/patch182.txt
* ftp://ftp.cts.com/software/games/quakeworld/fortress/tf25rel.zip
* ftp://ftp.cts.com/software/games/quakeworld/fortress/tf25fix.zip

This release may have been renamed `tf25_cl.zip` and redistributed with this name.

> Serwer oparty na Team Fortress 2.5. Pliki niezbędne do poprawnego działania to tf25_cl.zip i v-maps11.zip, dostępne oczywiście w QuakeToys, sekcja teamfort.

-- [http://riad.usk.pk.edu.pl/~pmj/quake/servers.shtml](https://web.archive.org/web/20040121081623/http://riad.usk.pk.edu.pl/~pmj/quake/servers.shtml) (archived)

Links:

* ftp://ftp.pk.edu.pl/pub/games/id/quaketoys/teamfort/tf25_cl.zip

Contents of `tf25rel.zip`:

```text
-rw-rw-r--  0 0      0     6965596 13 Jun  1997 PAK0.PAK
-rw-rw-r--  0 0      0      897292 13 Jun  1997 PROGS.DAT
-rw-rw-r--  0 0      0      690980 13 Jun  1997 QWPROGS.DAT
-rw-rw-r--  0 0      0        8863 13 Jun  1997 QWSERVER.HTM
-rw-rw-r--  0 0      0        7606 13 Jun  1997 QWSERVER.TXT
-rw-rw-r--  0 0      0       47041 13 Jun  1997 README.HTM
-rw-rw-r--  0 0      0       45264 13 Jun  1997 README.TXT
-rw-rw-r--  0 0      0        1972 13 Jun  1997 REGISTER.TXT
-rw-rw-r--  0 0      0         198 13 Jun  1997 SERVER.CFG
-rw-rw-r--  0 0      0        5771 13 Jun  1997 SERVER.HTM
-rw-rw-r--  0 0      0        4893 13 Jun  1997 SERVER.TXT
-rw-rw-r--  0 0      0       68779 13 Jun  1997 TFORTMAP.TXT
-rw-rw-r--  0 0      0       31543 13 Jun  1997 VERSIONS.HTM
-rw-rw-r--  0 0      0       31666 13 Jun  1997 VERSIONS.TXT
-rw-rw-r--  0 0      0      682260 13 Jun  1997 ALTPROGS/PROGS.DAT
-rw-rw-r--  0 0      0      690332 13 Jun  1997 ALTPROGS/QWPROGS.DAT
-rw-rw-r--  0 0      0       64008  2 Jun  1997 GFX/CONBACK.LMP
-rw-rw-r--  0 0      0          21  4 Jun  1997 MCYCLE/MAP1.CFG
-rw-rw-r--  0 0      0          23  4 Jun  1997 MCYCLE/MAP2.CFG
-rw-rw-r--  0 0      0          44  4 Jun  1997 MCYCLE/MAP3.CFG
-rw-rw-r--  0 0      0          35  4 Jun  1997 MCYCLE/MAP4.CFG
-rw-rw-r--  0 0      0          12  4 Jun  1997 MCYCLE/MAP5.CFG
-rw-rw-r--  0 0      0          13 17 May  1997 QWMCYCLE/MAP1.CFG
-rw-rw-r--  0 0      0          15 18 May  1997 QWMCYCLE/MAP2.CFG
-rw-rw-r--  0 0      0          36 17 May  1997 QWMCYCLE/MAP3.CFG
-rw-rw-r--  0 0      0          27 17 May  1997 QWMCYCLE/MAP4.CFG
-rw-rw-r--  0 0      0          15 27 May  1997 QWMCYCLE/MAP5.CFG
```

Content of `tf25src.zip`:

```text
-rw-rw-r--  0 0      0       13796  4 Jun  1997 ACTIONS.QC
-rw-rw-r--  0 0      0         162 10 May  1997 ADMIN.QC
-rw-rw-r--  0 0      0       15150 21 Mar  1997 AI.QC
-rw-rw-r--  0 0      0       77312 22 Oct  1996 ALEXQCC.EXE
-rw-rw-r--  0 0      0        1833 29 Dec  1996 AMTEST.QC
-rw-rw-r--  0 0      0       12930 12 Jun  1997 BOSS.QC
-rw-rw-r--  0 0      0        2202  6 Dec  1996 BOT.QC
-rw-rw-r--  0 0      0       15340 13 Apr  1997 BOTAI.QC
-rw-rw-r--  0 0      0         166  3 Dec  1996 BOTS.QC
-rw-rw-r--  0 0      0        3845 13 Jun  1997 BUTTONS.QC
-rw-rw-r--  0 0      0       10722 13 May  1997 CAMERA.QC
-rw-rw-r--  0 0      0       73973 12 Jun  1997 CLIENT.QC
-rw-rw-r--  0 0      0       15857 10 Jun  1997 COMBAT.QC
-rw-rw-r--  0 0      0         887 21 Mar  1997 COMBOT.QC
-rw-rw-r--  0 0      0        3731 21 Mar  1997 COOP.QC
-rw-rw-r--  0 0      0        1961 18 Apr  1997 CTF.QC
-rw-rw-r--  0 0      0        1099 18 Apr  1997 DEBUG.QC
-rw-rw-r--  0 0      0       66209 13 Jun  1997 DEFS.QC
-rw-rw-r--  0 0      0       11855 12 Jun  1997 DEMOMAN.QC
-rw-rw-r--  0 0      0       11297 29 Dec  1996 DEMON.QC
-rw-rw-r--  0 0      0       10545 29 Dec  1996 DOG.QC
-rw-rw-r--  0 0      0       19655 13 Jun  1997 DOORS.QC
-rw-rw-r--  0 0      0       12140 10 Apr  1997 ENFORCER.QC
-rw-rw-r--  0 0      0       24724 12 Jun  1997 ENGINEER.QC
-rw-rw-r--  0 0      0        7199 20 Nov  1996 FIGHT.QC
-rw-rw-r--  0 0      0        8025 29 Dec  1996 FISH.QC
-rw-rw-r--  0 0      0        1622  9 May  1997 FLARE.QC
-rw-rw-r--  0 0      0       19766 21 Feb  1997 HKNIGHT.QC
-rw-rw-r--  0 0      0       12101 17 May  1997 HOOK.QC
-rw-rw-r--  0 0      0       38815  3 Jun  1997 ITEMS.QC
-rw-rw-r--  0 0      0         290 29 Dec  1996 JCTEST.QC
-rw-rw-r--  0 0      0       10968 29 Dec  1996 KNIGHT.QC
-rw-rw-r--  0 0      0          11 10 May  1997 LEVELS.QC
-rw-rw-r--  0 0      0          61  7 Mar  1997 MAKE.BAT
-rw-rw-r--  0 0      0       39331 12 Jun  1997 MENU.QC
-rw-rw-r--  0 0      0         949 13 Jun  1997 MESSAGES.QC
-rw-rw-r--  0 0      0       19844 26 May  1997 MISC.QC
-rw-rw-r--  0 0      0        9788 25 Jul  1996 MODELS.QC
-rw-rw-r--  0 0      0       10793 12 Jun  1997 MONSTERS.QC
-rw-rw-r--  0 0      0        1376 18 Apr  1997 MSKIN.QC
-rw-rw-r--  0 0      0       16116 13 Apr  1997 OGRE.QC
-rw-rw-r--  0 0      0       11562 19 Mar  1997 OLDBOT.QC
-rw-rw-r--  0 0      0        9777 16 May  1997 OLDONE.QC
-rw-rw-r--  0 0      0        4246 13 Jun  1997 OPTIONS.QC
-rw-rw-r--  0 0      0        9620 12 Apr  1997 PLATS.QC
-rw-rw-r--  0 0      0       33687 12 Jun  1997 PLAYER.QC
-rw-rw-r--  0 0      0         997 21 May  1997 PREOPDEF.QC
-rw-rw-r--  0 0      0         558 12 Jun  1997 PREPROGS.SRC
-rw-rw-r--  0 0      0       93649 19 Dec  1996 PREQCC.EXE
-rw-rw-r--  0 0      0        2598 27 Aug  1996 PROGDEFS.QC
-rw-rw-r--  0 0      0       21469 10 Jun  1997 PYRO.QC
-rw-rw-r--  0 0      0        2581 10 May  1997 QW.QC
-rw-rw-r--  0 0      0        7606 13 Jun  1997 QWSERVER.TXT
-rw-rw-r--  0 0      0       45447 13 Jun  1997 README.TXT
-rw-rw-r--  0 0      0       14765 12 Jun  1997 SCOUT.QC
-rw-rw-r--  0 0      0        8953  4 Jun  1997 SENTRY.QC
-rw-rw-r--  0 0      0        4893 13 Jun  1997 SERVER.TXT
-rw-rw-r--  0 0      0        9106 29 Dec  1996 SHALRATH.QC
-rw-rw-r--  0 0      0       14030 29 Dec  1996 SHAMBLER.QC
-rw-rw-r--  0 0      0        1880 10 Apr  1997 SKINS.QC
-rw-rw-r--  0 0      0        3275 12 May  1997 SNIPER.QC
-rw-rw-r--  0 0      0       11256 25 Mar  1997 SOLDIER.QC
-rw-rw-r--  0 0      0         486 25 Jul  1996 SPRITES.QC
-rw-rw-r--  0 0      0       28349 21 May  1997 SPY.QC
-rw-rw-r--  0 0      0       83482  4 Jun  1997 STATUS.QC
-rw-rw-r--  0 0      0        6947 17 May  1997 SUBS.QC
-rw-rw-r--  0 0      0        7610 11 May  1997 TARBABY.QC
-rw-rw-r--  0 0      0       84592 12 Jun  1997 TFORT.QC
-rw-rw-r--  0 0      0        7118 13 Jun  1997 TFORTHLP.QC
-rw-rw-r--  0 0      0       78911 13 Jun  1997 TFORTMAP.QC
-rw-rw-r--  0 0      0       26167  4 Jun  1997 TFORTTM.QC
-rw-rw-r--  0 0      0       18147 13 Jun  1997 TRIGGERS.QC
-rw-rw-r--  0 0      0        2428 21 May  1997 TSOLDIER.QC
-rw-rw-r--  0 0      0        3057 20 Dec  1996 TURRET.QC
-rw-rw-r--  0 0      0       31666 13 Jun  1997 VERSIONS.TXT
-rw-rw-r--  0 0      0       86236 13 Jun  1997 WEAPONS.QC
-rw-rw-r--  0 0      0       12071 21 Feb  1997 WIZARD.QC
-rw-rw-r--  0 0      0       14109 12 Jun  1997 WORLD.QC
-rw-rw-r--  0 0      0       20747 29 Dec  1996 ZOMBIE.QC
```

The file timestamps suggest a release on June 13th.

This matches the date in the changelog.

```text
--------------------------------------------
Version 2.5 Final Release - Released 13/6/97
--------------------------------------------
Bugs Fixed:
    - Detpack countdown's being removed when an EMP grenade destroys the pack.
    - CTF emulation being broken by the tf_flag.mdl fixed.
    - Abbreviations not working for Quake Triggers fixed.
    - Button/Door handling with Engineer spanner fixed.
```

-- tf25rel.zip/VERSIONS.TXT


## v2.5 QuakeWorld Fix

Released as `tf25fix.zip`.

Mentioned on the TeamFortress News page:

> 15.06.1997\
> GLQuakeWorld fix for TF 2.5\
> Thanks to Jack "Morbid" Mathews, we've found the problems with the 2.5 mdls that caused GLQW to crash. We've fixed that, and also replaced the tf_flag.mdl with the correct one, so even if you don't run GLQW, it's worth downloading it anyway\
> You can download the fix here (33k)\
>
> Unzip the zip into your fortress directory, and you're ready to go.\

-- [http://www.planetquake.com/teamfortress/news.html](https://web.archive.org/web/19970617153959/http://www.planetquake.com/teamfortress/news.html) (archived)

Links:

* http://www.planetquake.com/teamfortress/files/tf25fix.zip

Listed on the TeamFortress Downloads page:

> Team Fortress 2.5 Fix\
> Download Fix (33k)\
> Fixes the GLQW crash problem, and the tf_flag.mdl having the wrong skins. Just unzip it into your fortress directory.

-- [http://www.planetquake.com/teamfortress/download.html](https://web.archive.org/web/19970617154012/http://www.planetquake.com/teamfortress/download.html) (archived)

Links:

* http://www.planetquake.com/teamfortress/files/tf25fix.zip

Mentioned on Redwoods:

> June 15, 1997
>
> TeamFortress Fix for QW 1.64\
Some of you may have noticed that TeamFortress 2.5 does not work correctly with the new QuakeWorld client. Here is the fix which will make it run properly, and also replaces the current flag with the correct one.

-- [http://redwood.stomped.com/697.html](https://web.archive.org/web/20010830150348/http://redwood.stomped.com/697.html) (archived)

Links:

* http://www.planetquake.com/teamfortress/news.html
* http://redwood.stomped.com/files2/tf25fix.zip

Mentioned on BluesNews:

> Monday, June 16, 1997
>
> GL TeamFortress Fix\
> There is a fix for using GL Quake with TeamFortress on the TeamFortress Page. Thanks MJollnir.

-- https://www.bluesnews.com/archives/june97-2.html

Mentioned on Telefragged:

> Sun Jun 15 20:52:31 CDT 1997
>
> TeamFortress\
> TeamFortress 2.5 doesn't work with the new version of QuakeWorld. You have to get a fix available on their page.

-- [http://www.telefragged.com/oldnews/june.shtml](https://web.archive.org/web/19980114112029/http://www.telefragged.com/oldnews/june.shtml) (archived)

Content of `tf25fix.zip`:

```text
-rw-rw-r--  0 0      0      335155 15 Jun  1997 PAK1.PAK
-rw-rw-r--  0 0      0         920 15 Jun  1997 README.TXT
```

The file timestamps suggest a release on June 15th.

This matches the date in the release notes:

```text
=------------------------------------------------------=
    TeamFortress v2.5 Fix       15/6/97
=------------------------------------------------------=

This is a quick fix to solve a couple of problems
in the TeamFortress 2.5 pak file.
```

-- tf25fix.zip/README.TXT


## v2.6 Final Beta (FB)

todo

This release was reviewed on QCArchive:

> Update: Recently Team Fortress 2.6 came out. This is the last version of TF that will be coming out. The Team Fortress team has started to focus their attention on Team Fortress for Quake 2. Team Fortress 2.6 was released and basically does one thing. TF 2.6 speeds up QuakeWorld games and works with GLQWCL. ...

-- [http://www.planetquake.com/qca/reviews/patch81.htm](https://web.archive.org/web/20000522141708/http://www.planetquake.com:80/qca/reviews/patch81.htm) (archived)

Links:

* http://www.planetquake.com/qca/reviews/patch81.txt
* ftp://ftp.cdrom.com/pub/quake/planetquake/teamfortress/tf26fb.zip



## v2.6

todo

```text
tf26fb.txt             14-Aug-97 15:14     1k
tf26fb.zip             14-Aug-97 15:22   1.1M
```

-- [http://www.cdrom.com/pub/idgames2/quakec/teamplay/](https://web.archive.org/web/19980210220428/http://www.cdrom.com:80/pub/idgames2/quakec/teamplay/) (archived)




