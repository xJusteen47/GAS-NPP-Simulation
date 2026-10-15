> **UE 5.8 branch** (fork of Sabri-Kai/GAS-NPP-Simulation `GAS-NPP-Simulation-5.7`).
> Requires the forked plugins from https://github.com/xJusteen47/UnrealEngineNPP/tree/GAS-NPP-5.8 (GameplayAbilities,
> NetworkPrediction, NetworkPredictionExtras, NetworkPredictionInsights, ported to Unreal Engine 5.8.3).
> Changes for 5.8: tag overrides use `EGameplayTagReplicationState` (forced to `None`, tags are synced by NPP), the removed
> `Add/RemoveReplicatedLooseGameplayTag` overrides were dropped, debug-string replication is registered via reflection
> (members are private in 5.8), and the compiler context uses `Algo::Sort` for `TObjectPtr` arrays.

# GAS-NPP-Simulation

A Plugin that allows GAS to work with NPP and use its prediction system instead of its own.
This requires Forked engine plugin Gameplay Abilities and the 3 Network Prediction Plugins 
From this Repo https://github.com/Sabri-Kai/UnrealEngineNPP/tree/GAS-NPP-5.5 to be used.

If you have question here's a discord server invite, you are welcome to ask, i am the server admin
https://discord.gg/C4nvcG4bbG
