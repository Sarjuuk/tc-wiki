---
title: instance_encounters
description: 
published: true
date: 2021-08-30T20:38:02.282Z
tags: database, master, world
editor: markdown
dateCreated: 2021-08-30T06:00:00.000Z
---

<a href="https://dev.trinitycore.info/en/database/master/world/guild_rewards_req_achievements" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'guild_rewards_req_achievements'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to world</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/instance_spawn_groups" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'instance_spawn_groups'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [entry](#entry) | int(10) | unsigned | PRI | NO |  |  | Unique entry from DungeonEncounter.dbc |
| [creditType](#credittype) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [creditEntry](#creditentry) | int(10) | unsigned |  | NO | 0 |  |  |
| [lastEncounterDungeon](#lastencounterdungeon) | smallint(5) | unsigned |  | NO | 0 |  | If not 0, LfgDungeon.dbc entry for the instance it is last encounter in |
| [comment](#comment) | varchar(255) | signed |  | NO | '' |  |  |
&nbsp;
## Description of fields

### entry
*- no description -*
&nbsp;

### creditType
*- no description -*
&nbsp;

### creditEntry
*- no description -*
&nbsp;

### lastEncounterDungeon
*- no description -*
&nbsp;

### comment
*- no description -*
&nbsp;

<a href="https://dev.trinitycore.info/en/database/master/world/guild_rewards_req_achievements" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'guild_rewards_req_achievements'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to world</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/instance_spawn_groups" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'instance_spawn_groups'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

