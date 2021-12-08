![Morrowind Modding Essentials, Fixes, & Tools](https://media.discordapp.net/attachments/759128899338108940/917910527676645406/MMEFT-Thumbnail.png?width=1191&height=670)
<h1 align="center">MMEFT<br /><sup><sup align="center"><em><strong>M</strong>orrowind <strong>M</strong>odding <strong>E</strong>ssentials, <strong>F</strong>ixes, & <strong>T</strong>ools</em></sup></sup></h1>

A utility modlist for TES3 - Morrowind; your ultimate guide to getting started in the wonderful world of modding.

<h6 align="center">WARNING: THIS GUIDE IS STILL UNDER CONSTRUCTION</h6>

This list is set up as a guide, but is easily installable using the [Wabbajack](https://www.wabbajack.org) tool. I recommend going through the guide at least once, as it holds valuable lessons you will need along your journey. The Wabbajack install is intended for users who know what they are doing and want to get straight to modding. Skip to the end to install the list via Wabbajack.

## Table of Contents (WIP)
0. [Read me (this page!)]()
    - [Assumptions](#assumptions)
    - [Resources](#resources)
    - [Introduction](#introduction)
1. [Getting Started](https://github.com/RingComics/MMEFT/wiki/Getting-Started)
    - [Prerequisites](https://github.com/RingComics/MMEFT/wiki/Getting-Started#prerequisites)
    - [Setting up Morrowind](https://github.com/RingComics/MMEFT/wiki/Getting-Started#setting-up-morrowind)
    - [Setting up Mod Organizer](https://github.com/RingComics/MMEFT/wiki/Getting-Started#setting-up-mod-organizer)
    - [Setting up tools](https://github.com/RingComics/MMEFT/wiki/Getting-Started#setting-up-tools)
    - Setting up Wabbajack
2. Installing Mods
    - Where to get mods
    - Installing mods using MO2
    - Documentation
    - Testing
    - Conflict resolution
    - Wabbajack Best Practices
    - Cleaning, merging, and levelled lists
3. Tools
    - MGE XE
    - Morrowind Code Patch
    - Wrye Mash
    - Mod ORganizer 2
    - tes3cmd
    - tes3merge
    - tes3pcd
    - tes3view

### Assumptions

This guide makes the following assumptions for your modding journey:

1. **You plan on installing several hundred mods.** Many of these steps set you up for success for when your modlist becomes large and unweildy. If you don't plan on installing an ungodly amount of mods, you may not get the most out of MMEFT, but it certainly won't hurt.
2. **You plan on sharing your modlist on Wabbajack.** Making lists for Wabbajack, even just for sharing with a friend, requires special set up. If you don't want to use Wabbajack, there are several steps you may be able to skip.
3. **You have tried modding Morrowind at least once.** Some knowledge is accepted as common and may not be explained. If you run into any terminology or instructions you don't recognize, feel free to ask for help.

## Resources

Here are a list of reading material, communities, and other guides you may find useful along your journey.
#### Communities
- [RingComics' Discord](https://discord.gg/6wusMF6) - This is my personal Discord, where I host discussion and support for my various projects. Morrowind modding is a common topic here, check the `#modding` channel.
- [Morrowind Modding Community Discord](https://discord.gg//morrowindmoddingcommunity) - The central hub for all things Morrowind modding. If you have a question about Morrowind, there's a place to ask here. MMEFT has it's own channel for support and discussion.
- [Wabbajack Discord]() - News, support, and information regarding the Wabbajack tool. Great resource for people wanting to make their own Wabbajack list.

#### Sites
- [Danae's Journal](https://danaeplays.thenet.sk/) - Danae is a very active and talented member of the Morrowind modding community, and regularly posts useful, interesting, and thorough articles on her blog about Morrowind modding.
- [Morrowind Modding Hall](https://mw.moddinghall.com/) - MMH is a modding forum specifically for Morrowind, run by STiX. Here you can find discussion threads, mod downloads, community events, and more!
- [Nexus Mods]() - Nexus Mods has become the main repository for Morrowind Mods. Most of your mods will likely be sourced from here, especially if you want to make a Wabbajack list.
- [Morrowind Modding History]() and [Great House Fliggerty]() - These used to be the main spot for mods and discussion for the community, and many great mods can still be found here. These sites are prone to going down, and therefore unfortunately unsupported by Wabbajack.

#### Accounts to Follow
- ***Danae*** - Danae does modded playthroughs and tutorials for Morrowind, and is one of our leaders in the MMC. She has also created many mods, including Friends & Foes and Wares, two must have mods! Danae also hosts most of our community events on her Twitch channel!
  - [Twitch](https://www.twitch.tv/danaeplays)
  - [YouTube](https://www.youtube.com/user/terdanae)
  - [NexusMods](https://www.nexusmods.com/morrowind/users/1233897?tab=user+files)
- ***RingComics*** *<sub>(das me)</sub>* - I'm the Wabbajack guy in the Morrowind community. I created YAJAN (plus a few other lists, including this one!), modding tools like Azura's Star, and I  have a few mods, most notably is "What Are My Attributes?". I also host events occasionally.
  - [Twitch](https://www.twitch.tv/ringcomics)
  - [YouTube](https://www.youtube.com/channel/UCif_YWnOGA1HLlkH_4rvIwA)
  - [NexusMods](https://www.nexusmods.com/morrowind/users/42343935?tab=user+files)
- ***[DarkElfGuy](https://www.youtube.com/c/MorrowindModdingShowcases)*** - DarkElfGuy's YouTube channel is a gold mine of wonderful mod showcases, and is beloved by the community.
- ***[MickyD](https://www.youtube.com/c/MickyD)*** - Just a stand up lad who breathed new life into Morrowind's online presence. He makes comedic videos about a variety of video games, but mainly TES, with a focus on modding the game to death.

#### Guides and Modlists
- [Morrowind# by Sigourn](https://github.com/Sigourn/morrowind-sharp) - Morrowind# (pronounced *sharp*) is a highly compatible, highly stable, vanilla-friendly game focused on enhanced gameplay and a vanilla+ aesthetic. 
- [Morrowind Graphics Guide by DassiD](https://wiki.nexusmods.com/index.php/Morrowind_graphics_guide) - Previously known as the S.T.E.P. guide, the Morrowind Graphics Guide (MGG for short) is all about improving the game's visuals while still maintainting the vanilla game's aesthetics.
- [Morrowind 2020: Thastus Edition](https://github.com/Tyler799/Morrowind-2020/blob/master/Morrowind_2020.md) - This is an updated, revised and re-written version of Cynderal's guide (Morrowind 2017), which was an updated version of Guideanon's 2016 guide, which is apparently a revised version of the Morrowind 2015 guide.
- [Morrowind Immersive Overhaul by /u/MorrowindNostalgia](https://docs.google.com/document/d/19n-4coZka9hcvzaufWSuv-SVbwHplXyhCE7BAhuzxUA/edit) - With Morrowind Immersive Overhaul, the goal was to create a simple and elegant overhaul that retains the feel of vanilla Morrowind, while still offering a variety of fresh features that breathe new life into the game world. 
- [An Alternative to Morrowind Rebirth by RandomPal](https://www.nexusmods.com/morrowind/mods/48812) - This guide's purpose is to provide a relatively small list of mods that when used together will replace what Morrowind Rebirth has to offer and with more modularity.
- [You Are Just An N'wah](https://github.com/RingComics/yajan) - A Morrowind survival overhaul modlist focused on bringing Morrowind to 2020 in gameplay and graphics, downloadable using Wabbajack.
- [MOISE](https://www.fgsmodlists.com/moise/readme/) - Morrowind Overall Improvement Suite Enhanced (MOISE) is a basic, primarily graphical overhaul for Morrowind GOTY edition. It includes all of the necessities required to begin a Morrowind modding adventure. Download using Wabbajack.

## Introduction

You want to learn to mod Morrowind but don't know where to start. The guides online are helpful, but you find yourself having to read several of them to grasp a single concept. The issue lies not with the quality of these guides but the scope. Many of these guides give you a roadmap to reaching the end goal of replicating their modlist, but often fail to teach the methods needed when creating one's own load order.

I found myself in this situation a little over a year ago when I started work on YAJAN. I hadn't modded for Morrowind in years, a lot had changed, and the popular guides available online weren't updated. The information I needed was scattered, buried in Discord channels and web archives and Nexus comments. This is an attempt to collect all of that information into one constantly updated guide. MMEFT is not a modlist just like a fishing pole is not a fish; it is the means of getting your own. The initial set up is fine as it is as a basic Morrowind modlist, one for purists perhaps. But its intention is to built upon. 

You may use this guide as you please. This is simply a collection of public knowledge (and a few tricks I've discovered) and belongs to no one. If you find a mistake within the guide, please submit a request with a fix. I will be granting permissions to several prominent modders in the Morrowind modding community to make sure MMEFT does not fade with my own lease on list maintenance, and I ask if the community is locked out of this repository, ownership will be given to anyone willing to keep it alive.

<h3 align="Center"><a href="https://github.com/RingComics/MMEFT/wiki/Getting-Started">Click here to get started</a></h3>
