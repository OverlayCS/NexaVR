Joining a Private Room Is As Simple As Writning This Code

The First Part Is The Room Name You Want To Join 
The Second Part Is The Max Players (Up To 100 if you pay for it) 
The Last Part Is The Game Mode Dont Worry About It To Much Just Keep It In Shared

```Csharp
NexaVRManger.ConnectToRoom("OverlayCS", 10, GameMode.Shared);
```
How To Enable A Cosmetic
```Csharp
NexaVRManager.EnableCosmetic("TopHat", CosmeticType.Head);
```
If name is blank it will disable the current active cosmetic in the type you picked
Example:
```Csharp
NexaVRManager.EnableCosmetic("", CosmeticType.Head);
```

How to spawn a networked object that the position or roataion can be networked and set if they are or not
example:
```Csharp
NexaVRManager.SpawnRoomObject(string ObjectName, vector3 spawnpostion, Quaternion startRotation, bool NetworkPosition, bool networkRotation);
```
