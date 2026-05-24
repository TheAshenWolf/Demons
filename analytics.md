# Analytics

> ⚠️ Analytics are currently being reworked and this list may not represent everything with 100% accuracy.
> - 2026-05-23

> ### Disclaimer
> 
> This game uses Analytics. All data collected is related to performance, gameplay, and compatibility. We do not collect any personal data that could be traced back to you.
> If you want to know the details of what is being collected, the comprehensive list can be found in the #news channel on Discord (post about getting access).


This is a comprehensive list of all analytic data that is being collected.
Please note that this list may change at any time as the development progresses.
Data collected will be used for game balance and performance optimizations.

Along with analytics comprised of the following list, Player.log is also attached. This file contains the engine log.

## Hardware
- OS family
- OS version
- OS Architecture (x32/x64)
- Screen resolution
- Screen refresh rate
- Maximum available RAM
- CPU name/model
- CPU frequency
- CPU logical core count
- GPU name/model
- GPU available VRAM
- GPU API version
- GPU shader level
- GPU supports multithreaded rendering

## General
- Session ID (this ID is generated in a format \[unix timestamp\]-\[random GUID\], used to connect different analytic events)
- DLCs loaded
- Game version

## Player death
- Time alive
- Amount of hits taken
- Amount of raw damage taken
- Time since previous hit
- Last hit damage
- Last hit raw damage
- Damage taken since max health
- Killed by (NPC)
- Killed by (Attack)
- Killed by (Attack Type)
- Direction of the fatal blow
- Last grounded position
- Last grounded time
- Player rotation
- Player position
- Player velocity
- Can revive

## End of run
- Is loaded game
- Rng seed
- Start time (since game startup)
- End time (since game startup)
- Success
- Rooms cleared
- Enemies killed
- Minibosses killed
- Bosses killed
- Chests opened
- Damage dealt
- Damage taken
- Currency collected
- Skip currency accumulated
- Run end currency
- Green items collected
- Blue items collected
- Red items collected
- Chests skipped
- Items collected (complete inventory)
- Item tags
- Total healing

## Chest opened
- Time opened (since game startup)
- Loot seed
- First item
- Second item
- Third item
- Skip currency amount
- Chosen reward

## Shop left
- Time spent in shop
- Items bought
- Money when entered
- Money when left
- Reroll count
- Reroll money spent

## NPC too far
- NPC name
- NPC state
- Room name

## NPC Killed
- Name
- Game Difficulty
- Damage dealt to player
- Damage dealt to other NPCs
- Amounts of hits caused by different attack types
- Damage dealt per attack type
- Gold reward
- Amount of hits received
- Amount of hits scored
- Room name
- Coordinates of the spawnpoint
- Death coordinates
- Causer of the final blow
- First engagement time
- Death time
- Raw damage taken
- True damage taken
