# X3FL-notoriety-hack
This cheat engine script allows direct notoriety modification of all races in X3FL including all major races, pirates, companies, Xenon and Kha'ak, without activating in-game script editor, thus leaving the game 'unmodified'.

Possible extended usage includes modifying relationship among races directly.

## Usage

Install cheat engine, launch and enter game, launch script, wait a few seconds until notoriety values are shown, double click to modify.

Notoriety points - level conversion can be found here.

## Limits

Tested on X3FL 1.2. Expected to work on all versions. Will not work properly / will need modification if relationship among races is different from current status as in X3FL 1.2 normal start.

## Motivation

[Agents diplomacy exploit](https://forum.egosoft.com/viewtopic.php?f=199&t=439741#p5062135) is fixed in 1.2. The dynamic relationship system, despite interesting, become too troublesome to deal with, and unrealistically strict compared to real life diplomacy such that it kills fun. Thus this script is written to save the trouble. Feel free to use or not, and at your own risk.

## Mechanism

Inspired by [X3TC_X3AP_Ranks_aob.CT](https://fearlessrevolution.com/viewtopic.php?t=4409) by Schnitzelmaker. Had difficulty locating static pointers so AOB scan is used. Observation of relevant memory address shows that relationship among races are stored as 4 bytes signed integer separated by 0x01. AOB strategy optimized. Rewritten in Lua.
Welcome to discuss.
