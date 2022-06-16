Donate me for new contents/custom features

[![DonateMe](https://raw.githubusercontent.com/aha999/DonateButtons/master/Paypal.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=EFV4JT97G462S&lc=GB&button_subtype=services&currency_code=USD&bn=PP%2dBuyNowBF%3atumblr_inline_mwkm8w4B1G1rxzg7g%2egif%3aNonHosted/)

# Current contents/features a head from Official rAthena
- Upgraded Source
  - Convex Mirror Work with multiple bosses in one map :white_check_mark:
- Instances
  - Old Glast Heim (Hard Mode) :white_check_mark: (thanks to [ref](https://github.com/llchrisll/rAthena-Scripts) without complete normal mode)
- Level 175+ Contents [ref](https://hazyforest.com/lv175_exp_quests)
  - Magma Dungeon Floor 3 :white_check_mark:
  - Glast Heim Abyss :white_check_mark:
  - Odin Past :construction:
  - Einbech Mines Floor 3 :construction:
  - Thanatos Tower :construction:
  - Abyss Lake Floor 4 :construction:
  - Niflheim Dungeon Floor 1 :construction:
  - Rudus Floor 4 :construction:
  - Amicitia Floor 1 :construction:
  - Amicitia Floor 2 :construction:
  - Niflheim Dungeon Floor 2 :construction:
- Eden new contents :construction: [ref](https://hazyforest.com/eden:map)

# You can look for implemented contents in "/import" folder of each categories (ie. db/npc/etc..) or compare "matao-ro" branch with official "master" branch
# ***Note*** These will be removed if Official rAthena catch-up
# This branch is normally merge with official branch to get issue fix commits and contents


<img src="doc/logo.png" align="right" height="90" />
# rAthena
[![Total alerts](https://img.shields.io/lgtm/alerts/g/rathena/rathena.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/rathena/rathena/alerts/) [![Language grade: C/C++](https://img.shields.io/lgtm/grade/cpp/g/rathena/rathena.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/rathena/rathena/context:cpp) ![GitHub](https://img.shields.io/github/license/rathena/rathena.svg) ![GitHub repo size](https://img.shields.io/github/repo-size/rathena/rathena.svg)
> rAthena is a collaborative software development project revolving around the creation of a robust massively multiplayer online role playing game (MMORPG) server package. Written in C, the program is very versatile and provides NPCs, warps and modifications. The project is jointly managed by a group of volunteers located around the world as well as a tremendous community providing QA and support. rAthena is a continuation of the eAthena project.

[Forum](https://rathena.org/board)|[Discord](https://rathena.org/discord)|[Wiki](https://github.com/rathena/rathena/wiki)|[FluxCP](https://github.com/rathena/FluxCP)|[Crowdfunding](https://rathena.org/board/crowdfunding/)|[Fork and Pull Request Q&A](https://rathena.org/board/topic/86913-pull-request-qa/)
--------|--------|--------|--------|--------|--------

### Table of Contents
1. [Prerequisites](#1-prerequisites)
2. [Installation](#2-installation)
3. [Troubleshooting](#3-troubleshooting)
4. [More Documentation](#4-more-documentation)
5. [How to Contribute](#5-how-to-contribute)
6. [License](#6-license)

## 1. Prerequisites
Before installing rAthena there are certain tools and applications you will need which
differs between the varying operating systems available.

### Hardware
Hardware Type | Minimum | Recommended
------|------|------
CPU | 1 Core | 2 Cores
RAM | 1 GB | 2 GB
Disk Space | 300 MB | 500 MB

### Operating System & Preferred Compiler
Operating System | Compiler
------|------
Linux  | [gcc-5 or newer](https://www.gnu.org/software/gcc/gcc-5/) / [Make](https://www.gnu.org/software/make/)
Windows | [MS Visual Studio 2013, 2015, 2017](https://www.visualstudio.com/downloads/)

### Required Applications
Application | Name
------|------
Database | [MySQL 5 or newer](https://www.mysql.com/downloads/) / [MariaDB 5 or newer](https://downloads.mariadb.org/)
Git | [Windows](https://gitforwindows.org/) / [Linux](https://git-scm.com/download/linux)

### Optional Applications
Application | Name
------|------
Database | [MySQL Workbench 5 or newer](http://www.mysql.com/downloads/workbench/)

## 2. Installation 

### Full Installation Instructions
  * [Windows](https://github.com/rathena/rathena/wiki/Install-on-Windows)
  * [CentOS](https://github.com/rathena/rathena/wiki/Install-on-Centos)
  * [Debian](https://github.com/rathena/rathena/wiki/Install-on-Debian)
  * [FreeBSD](https://github.com/rathena/rathena/wiki/Install-on-FreeBSD)

## 3. Troubleshooting

If you're having problems with starting your server, the first thing you should
do is check what's happening on your consoles. More often that not, all support issues
can be solved simply by looking at the error messages given. Check out the [wiki](https://github.com/rathena/rathena/wiki)
or [forums](https://rathena.org/forum) if you need more support on troubleshooting.

## 4. More Documentation
rAthena has a large collection of help files and sample NPC scripts located in the /doc/
directory. These include detailed explanations of NPC script commands, atcommands (@),
group permissions, item bonuses, and packet structures, among many other topics. We
recommend that all users take the time to look over this directory before asking for
assistance elsewhere.

## 5. How to Contribute
Details on how to contribute to rAthena can be found in [CONTRIBUTING.md](https://github.com/rathena/rathena/blob/master/.github/CONTRIBUTING.md)!

## 6. License
Copyright (c) rAthena Development Team - Licensed under [GNU General Public License v3.0](https://github.com/rathena/rathena/blob/master/LICENSE)
