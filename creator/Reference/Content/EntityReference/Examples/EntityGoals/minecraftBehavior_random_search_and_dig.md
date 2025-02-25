---
author: mammerla
ms.author: v-jimseaman
title: Entity Documentation - minecraft:behavior.random_search_and_dig
ms.prod: gaming
---

# Entity Documentation - minecraft:behavior.random_search_and_dig

`minecraft:behavior.random_search_and_dig` compels an entity to locate a random target block that it can find a path towards. Once found, the entity will move towards the target block and dig up an item.

## Parameters

|Name |Default Value  |Type  |Description  |
|:----------|:----------|:----------|:----------|
|cooldown_range|[0.000000, 0.000000]|Range [a, b]|Goal cooldown range in seconds.|
|digging_duration_range|[0.000000, 0.000000]|Range [a, b]|Digging duration in seconds.|
|find_valid_position_retries|0.000000|Decimal|Amount of retries to find a valid target position within search range.|
|goal_radius|1.500000|Decimal|Distance in blocks within the entity to consider it has reached the target position.|
|item| *not set*| Item Description Properties| The item to spawn on a successful dig. Format: itemName:auxValue |
|on_digging_start|*not set*|Trigger|Event to run when the goal ends searching and digging begins.|
|on_fail_during_digging|*not set*|Trigger|Event to run when the goal failed while in the digging state.|
|on_fail_during_searching|*not set*|Trigger|Event to run when the goal failed while in the searching state.|
|on_item_found|*not set*|Trigger|Event to run when the goal finds an item.|
|on_searching_start|*not set*|Trigger|Event to run when the goal starts searching.|
|on_success|*not set*|Trigger|Event to run when searching and digging has ended.|
|search_range_xz|0.000000|Decimal|Width and length of the volume around the entity used to find a valid target position.|
|search_range_y|0.000000|Decimal|Height of the volume around the entity used to find a valid target position.|
|spawn_item_after_seconds|0.000000|Decimal|Digging duration before spawning item in seconds.|
|spawn_item_pos_offset|0.000000|Decimal|Distance to offset the item's spawn location in the direction the mob is facing.|
|speed_multiplier|0.000000|Decimal|Search movement speed multiplier.|