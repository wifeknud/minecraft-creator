---
author: mammerla
ms.author: v-jimseaman
title: Entity Documentation - target_distance
ms.prod: gaming
---

# Entity Documentation - target_distance

Tests the distance between the calling entity and its target.


### subject

| Options| Description |
|:-----------|:-----------|
| block| The block involved with the interaction. |
| damager| The damaging actor involved with the interaction. |
| other| The other member of an interaction, not the caller. |
| parent| The caller's current parent. |
| player| The player involved with the interaction. |
| self| The entity or object calling the test |
| target| The caller's current target. |

### operator

| Options| Description |
|:-----------|:-----------|
| !=| Test for inequality. |
| <| Test for less-than the value. |
| <=| Test for less-than or equal to the value. |
| <>| Test for inequality. |
| =| Test for equality. |
| ==| Test for equality. |
| >| Test for greater-than the value. |
| >=| Test for greater-than or equal to the value. |
| equals| Test for equality. |
| not| Test for inequality. |

### value

|Name |Default Value  |Type  |Description  |
|---------|---------|---------|---------|
|value |-- |Decimal |A floating point value. |

## Examples

### Full

```json
{ "test": "target_distance", "subject": "self", "operator": "equals", "value": 0.00}
```

### Short (using Defaults)

```json
{ "test": "target_distance", "value": "0.00" }
```

