---
title: pvpstats_players
description: 
published: true
date: 2021-08-30T22:00:42.141Z
tags: database, 3.3.5, 3.3.5a, 335, 335a, wotlk, characters
editor: markdown
dateCreated: 2021-08-30T06:00:00.000Z
---

<a href="https://dev.trinitycore.info/en/database/335/characters/pvpstats_battlegrounds" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'pvpstats_battlegrounds'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/335/characters/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to characters</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/335/characters/quest_tracker" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'quest_tracker'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [battleground_id](#battleground_id) | bigint(20) | unsigned | PRI | NO |  |  |  |
| [character_guid](#character_guid) | int(10) | unsigned | PRI | NO |  |  |  |
| [winner](#winner) | bit(1) |  |  | NO |  |  |  |
| [score_killing_blows](#score_killing_blows) | mediumint(8) | unsigned |  | NO |  |  |  |
| [score_deaths](#score_deaths) | mediumint(8) | unsigned |  | NO |  |  |  |
| [score_honorable_kills](#score_honorable_kills) | mediumint(8) | unsigned |  | NO |  |  |  |
| [score_bonus_honor](#score_bonus_honor) | mediumint(8) | unsigned |  | NO |  |  |  |
| [score_damage_done](#score_damage_done) | mediumint(8) | unsigned |  | NO |  |  |  |
| [score_healing_done](#score_healing_done) | mediumint(8) | unsigned |  | NO |  |  |  |
| [attr_1](#attr_1) | mediumint(8) | unsigned |  | NO | 0 |  |  |
| [attr_2](#attr_2) | mediumint(8) | unsigned |  | NO | 0 |  |  |
| [attr_3](#attr_3) | mediumint(8) | unsigned |  | NO | 0 |  |  |
| [attr_4](#attr_4) | mediumint(8) | unsigned |  | NO | 0 |  |  |
| [attr_5](#attr_5) | mediumint(8) | unsigned |  | NO | 0 |  |  |
&nbsp;
## Description of fields

### battleground_id
*- no description -*
&nbsp;

### character_guid
*- no description -*
&nbsp;

### winner
*- no description -*
&nbsp;

### score_killing_blows
*- no description -*
&nbsp;

### score_deaths
*- no description -*
&nbsp;

### score_honorable_kills
*- no description -*
&nbsp;

### score_bonus_honor
*- no description -*
&nbsp;

### score_damage_done
*- no description -*
&nbsp;

### score_healing_done
*- no description -*
&nbsp;

### attr_1
*- no description -*
&nbsp;

### attr_2
*- no description -*
&nbsp;

### attr_3
*- no description -*
&nbsp;

### attr_4
*- no description -*
&nbsp;

### attr_5
*- no description -*
&nbsp;

<a href="https://dev.trinitycore.info/en/database/335/characters/pvpstats_battlegrounds" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'pvpstats_battlegrounds'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/335/characters/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to characters</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/335/characters/quest_tracker" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'quest_tracker'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

