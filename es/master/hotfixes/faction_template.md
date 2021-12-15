---
title: faction_template
description: 
published: true
date: 2021-11-14T19:41:35.100Z
tags: database, master, hotfixes
editor: markdown
dateCreated: 2021-08-30T06:00:00.000Z
---

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/faction_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'faction_locale'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/friendship_rep_reaction" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'friendship_rep_reaction'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [ID](#id) | int(10) | unsigned | PRI | NO | 0 |  |  |
| [Faction](#faction) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [Flags](#flags) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [FactionGroup](#factiongroup) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [FriendGroup](#friendgroup) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [EnemyGroup](#enemygroup) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [Enemies1](#enemies1) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [Enemies2](#enemies2) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [Enemies3](#enemies3) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [Enemies4](#enemies4) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [Friend1](#friend1) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [Friend2](#friend2) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [Friend3](#friend3) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [Friend4](#friend4) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [VerifiedBuild](#verifiedbuild) | int(11) | signed | PRI | NO | 0 |  |  |
&nbsp;
## Description of fields

### ID
*- no description -*
&nbsp;

### Faction
*- no description -*
&nbsp;

### Flags
*- no description -*
&nbsp;

### FactionGroup
*- no description -*
&nbsp;

### FriendGroup
*- no description -*
&nbsp;

### EnemyGroup
*- no description -*
&nbsp;

### Enemies1
*- no description -*
&nbsp;

### Enemies2
*- no description -*
&nbsp;

### Enemies3
*- no description -*
&nbsp;

### Enemies4
*- no description -*
&nbsp;

### Friend1
*- no description -*
&nbsp;

### Friend2
*- no description -*
&nbsp;

### Friend3
*- no description -*
&nbsp;

### Friend4
*- no description -*
&nbsp;

### VerifiedBuild
This field is used by the TrinityDB Team to determine whether a template has been verified from WDB files.

If value is 0 then it has not been parsed yet.

If value is above 0 then it has been parsed with WDB files from that specific client build.

If value is -1 then it is just a place holder until proper data are found on WDBs.

If value is -Client Build then it was parsed with WDB files from that specific client build and manually edited later for some special necessity.

&nbsp;

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/faction_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'faction_locale'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/friendship_rep_reaction" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'friendship_rep_reaction'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

