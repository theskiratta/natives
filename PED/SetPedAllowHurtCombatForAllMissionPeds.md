---
ns: PED
aliases: ["0xF2BEBCDFAFDAA19E"]
---
## SET_PED_ALLOW_HURT_COMBAT_FOR_ALL_MISSION_PEDS

```c
// 0xF2BEBCDFAFDAA19E 0x6CD58238
void SET_PED_ALLOW_HURT_COMBAT_FOR_ALL_MISSION_PEDS(BOOL allowHurtCombat);
```

Allows or disallows hurt combat for all mission peds.

```
toggle was always false except in one instance (b678).
The one time this is set to true seems to do with when you fail the mission.
```

## Parameters
* **allowHurtCombat**: Whether to allow hurt combat for all mission peds.
