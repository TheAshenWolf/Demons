# Analytics

> **Last updated:** 2026-05-30

> ### Disclaimer
> 
> This game uses Analytics. All data collected is related to performance, gameplay, and compatibility. We do not collect any personal data that could be traced back to you.
> If you want to know the details of what is being collected, the comprehensive list can be found in the #news channel on Discord (post about getting access).


This is a comprehensive list of all analytic data that is being collected.
Please note that this list may change at any time as the development progresses.
Data collected will be used for game balance and performance optimizations.

Along with analytics comprised of the following list, Player.log is also attached. This file contains the engine log.

## Hardware
- OperatingSystem
- OperatingSystemVersion
- OperatingSystemArchitecture
- Resolution
- RefreshRate
- AvailableMemory
- CpuModel
- CpuFrequency
- CpuCoreCount
- GpuModel
- GpuVram
- GpuApiVersion
- GpuShaderLevel
- GpuMultithreadedRendering
- SystemLanguage

## General
- Session ID (this ID is generated in a format \[unix timestamp\]-\[random GUID\], used to connect different analytic events)
- GameVersion
- UnityVersion

## Player death
- Alive Since
- LastHitTime
- LastHitDamage
- LastHitRawDamage
- DamageSinceMaxHealth
- KilledBy
- KilledByAttack
- AttackType
- PlayerRotation
- AttackDirection
- RevivesLeft
- RoomName

## End of run
- IsLoadedGame
- RunRngSeed
- StartupTime
- EndTime
- Success
- RoomsCleared
- EnemiesKilled
- MinibossesKilled
- BossesKilled
- ChestsOpened
- DamageDealt
- DamageTaken
- CurrencyCollected
- SkipCurrencyAccumulated
- EndCurrency
- GreenItemsCollected
- BlueItemsCollected
- RedItemsCollected
- OpenChestSkips
- ClosedChestSkips
- ItemsCollected
- TagDistribution
- TotalHealing
- HighestSingleHeal
- ItemsPurchased
- ShopRerolls
- HighestDamageDealt
- HighestDamageTaken
- HighestRawDamageDealt
- TotalRawDamageDealt
- HighestRawDamageTaken
- TotalRawDamageTaken

## Chest opened
- TimeOpened
- LootSeed
- Item1
- Item2
- Item3
- SkipRewardAmount
- RewardPicked
- OpenedManually
- RoomName

## Shop left
- TimeEntered
- TimeLeft
- ItemsBought
- MoneyWhenEntered
- MoneyWhenLeft
- RerollCount
- RerollCurrencySpent

## NPC too far
- NpcName
- State
- RoomName
- DespawnLocation
- TimeSinceStartup

## NPC Killed
- Name
- Difficulty
- DamageDealtToPlayer
- DamageDealtToNpcs
- HitTypeCounts
- DamageDealtPerType
- GoldReward
- HitsReceived
- HitsScored
- RoomName
- SpawnPointCoordinates
- DeathCoordinates
- DeathCauser
- FirstEngageTime
- DeathTime
- RawDamageTaken
- TrueDamageTaken
- KilledByAttackType

## Performance
- Time
- CpuFrameTimeMs
- CpuMainThreadFrameTimeMs
- CpuMainThreadPresentWaitTimeMs
- CpuRenderThreadFrameTimeMs
- GpuFrameTimeMs
- HeightScale
- WidthScale
- SyncInterval
- TotalAllocatedMemoryMb
- TotalReservedMemoryMb
- TotalUnusedReservedMemoryMb
- MonoUsedSizeMb
- MonoHeapSizeMb
- AllocatedGraphicsMemoryMb
- SmoothDeltaMs
- AverageFps
- AverageFpsOnePercent
- AverageFpsZeroOnePercent
