<p align="center">
    <img src="https://cdn.discordapp.com/attachments/377284586326982666/548680013453590548/GitHubLogo.png"/>
</p>

# Hacknet-VSCode
## Forget about the docs - welcome to the lazy way.

---

Table Of Contents
* [About](#about)
* [How To Use](#how-to-use)
    * [Templates](#predefined-templates)
    * [Support](#support)
* [Examples](#examples)
* [Installation](#installing)
* [Building](#building-from-source)

---

# About
Hacknet Extension development is a long process. Ask anybody who makes them. This Visual Studio Code extension aims to change that, and make Hacknet Extension development a much shorter and easier process.

## The Motivation
The official extension development guide is great, but it's also confusing. This VSC extension will streamline the process and make it much easier and much more understandable. I hope this will convince more people to try their hand at making extensions. It's no Extension Creator, but it's a step forward!

# How To Use
Simply [install the extension](#installing), then open up an XML file for Extension development, or a TXT file for HackerScript development.
While editing, use TAB to go to the next placeholder. If something isn't a placeholder, then you should probably leave it be!
If an entire tag/attribute is highlighted, then that means you can safely delete it. Don't wanna delete it? You don't need to! Just press TAB again, and it'll continue with the placeholders.

## Predefined Templates
1. [SequencerAction](#sequencer-example)
2. [HacknetMisssion](#mission-example)
3. StartingAction
4. SabotagedPacemaker
5. SequencerMission

Anything not listed here is likely not large enough to be considered a "template". Anything in the [official guide](https://steamcommunity.com/sharedfiles/filedetails/?id=914587661) is supported by this extension, along with some extras not included in the guide!

## Support
If you're still not getting the hang of this, that's okay! Join the [official Hacknet Discord](https://discord.gg/hacknet) and I'll do my best to help. It'll be hard to miss me.

# Examples
Note to self: add new examples here.

# Installing
1. [Download the latest release](https://www.github.com/SmartieCodes/hacknet-vscode/releases)
2. Follow this handy visual guide:
![](https://cdn.discordapp.com/attachments/377284586326982666/549048572545335296/InstallationExample.gif)

If you don't like doing it maunally, [you can also install it within VSCode!](https://marketplace.visualstudio.com/items?itemName=Smartie.hacknet-vscode)

# Building From Source
1. Clone the repo.
2. Install `vsce` if you haven't already
3. If you are going to add anything, remember to add it to the `package.json`!
4. Run `vsce package` in the root folder
5. Name the VSIX file whatever you'd like.