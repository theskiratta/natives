---
ns: PED
aliases: ["0xF2385935BFFD4D92"]
---
## IS_CURRENT_HEAD_PROP_A_HELMET

```c
// 0xF2385935BFFD4D92 0xFFF149FE
BOOL IS_CURRENT_HEAD_PROP_A_HELMET(Ped ped);
```

Checks if the specified peds head prop is a helmet.

## Parameters
* **ped**: Ped whose head prop should be checked.

## Return value
Returns true if the specified peds head prop is helmet, otherwise returns false.

```c
// Head prop Flags
enum ePedCompFlags
{
    PV_FLAG_NONE
	PV_FLAG_BULKY
	PV_FLAG_JOB
	PV_FLAG_SUNNY
	PV_FLAG_WET
	PV_FLAG_COLD
	PV_FLAG_NOT_IN_CAR
	PV_FLAG_BIKE_ONLY
	PV_FLAG_NOT_INDOORS
	PV_FLAG_FIRE_RETARDENT
	PV_FLAG_ARMOURED
	PV_FLAG_LIGHTLY_ARMOURED
	PV_FLAG_HIGH_DETAIL
	PV_FLAG_DEFAULT_HELMET
	PV_FLAG_RANDOM_HELMET
	PV_FLAG_SCRIPT_HELMET
	PV_FLAG_FLIGHT_HELMET
	PV_FLAG_HIDE_IN_FIRST_PERSON
	PV_FLAG_USE_PHYSICS_HAT_2
	PV_FLAG_PILOT_HELMET
	PV_FLAG_WET_MORE_WET
	PV_FLAG_WET_LESS_WET
}
```