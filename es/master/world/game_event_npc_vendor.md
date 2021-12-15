---
title: game_event_npc_vendor
description: 
published: true
date: 2021-08-30T20:38:02.274Z
tags: database, master, world
editor: markdown
dateCreated: 2021-08-30T06:00:00.000Z
---

<a href="https://dev.trinitycore.info/en/database/master/world/game_event_model_equip" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'game_event_model_equip'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to world</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/game_event_npcflag" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'game_event_npcflag'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [eventEntry](#evententry) | tinyint(4) | signed |  | NO |  |  | Entry of the game event. |
| [guid](#guid) | bigint(20) | unsigned | PRI | NO | 0 |  |  |
| [slot](#slot) | smallint(6) | signed | MUL | NO | 0 |  |  |
| [item](#item) | mediumint(8) | unsigned | PRI | NO | 0 |  |  |
| [maxcount](#maxcount) | mediumint(8) | unsigned |  | NO | 0 |  |  |
| [incrtime](#incrtime) | mediumint(8) | unsigned |  | NO | 0 |  |  |
| [ExtendedCost](#extendedcost) | mediumint(8) | unsigned | PRI | NO | 0 |  |  |
| [type](#type) | tinyint(3) | unsigned | PRI | NO | 1 |  |  |
| [BonusListIDs](#bonuslistids) | text |  |  | YES | NULL |  |  |
| [PlayerConditionID](#playerconditionid) | int(10) | unsigned |  | NO | 0 |  |  |
| [IgnoreFiltering](#ignorefiltering) | tinyint(3) | unsigned |  | NO | 0 |  |  |
&nbsp;
## Description of fields

### eventEntry
*- no description -*
&nbsp;

### guid
*- no description -*
&nbsp;

### slot
*- no description -*
&nbsp;

### item
*- no description -*
&nbsp;

### maxcount
*- no description -*
&nbsp;

### incrtime
*- no description -*
&nbsp;

### ExtendedCost
*- no description -*
&nbsp;

### type
*- no description -*
&nbsp;

### BonusListIDs
*- no description -*
&nbsp;

### PlayerConditionID
*- no description -*
&nbsp;

### IgnoreFiltering
*- no description -*
&nbsp;

<a href="https://dev.trinitycore.info/en/database/master/world/game_event_model_equip" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'game_event_model_equip'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to world</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/game_event_npcflag" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'game_event_npcflag'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

