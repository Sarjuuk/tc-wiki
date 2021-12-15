---
title: gameobject
description: 
published: true
date: 2021-08-30T22:01:28.032Z
tags: database, 3.3.5, 3.3.5a, 335, 335a, wotlk, world
editor: markdown
dateCreated: 2021-08-30T06:00:00.000Z
---

<a href="https://dev.trinitycore.info/en/database/335/world/game_weather" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'game_weather'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/335/world/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to world</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/335/world/gameobject_addon" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'gameobject_addon'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [guid](#guid) | int(10) | unsigned | PRI | NO |  | auto_increment | Global Unique Identifier |
| [id](#id) | mediumint(8) | unsigned |  | NO | 0 |  | Gameobject Identifier |
| [map](#map) | smallint(5) | unsigned |  | NO | 0 |  | Map Identifier |
| [zoneId](#zoneid) | smallint(5) | unsigned |  | NO | 0 |  | Zone Identifier |
| [areaId](#areaid) | smallint(5) | unsigned |  | NO | 0 |  | Area Identifier |
| [spawnMask](#spawnmask) | tinyint(3) | unsigned |  | NO | 1 |  |  |
| [phaseMask](#phasemask) | int(10) | unsigned |  | NO | 1 |  |  |
| [position_x](#position_x) | float |  |  | NO | 0 |  |  |
| [position_y](#position_y) | float |  |  | NO | 0 |  |  |
| [position_z](#position_z) | float |  |  | NO | 0 |  |  |
| [orientation](#orientation) | float |  |  | NO | 0 |  |  |
| [rotation0](#rotation0) | float |  |  | NO | 0 |  |  |
| [rotation1](#rotation1) | float |  |  | NO | 0 |  |  |
| [rotation2](#rotation2) | float |  |  | NO | 0 |  |  |
| [rotation3](#rotation3) | float |  |  | NO | 0 |  |  |
| [spawntimesecs](#spawntimesecs) | int(11) | signed |  | NO | 0 |  |  |
| [animprogress](#animprogress) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [state](#state) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [ScriptName](#scriptname) | char(64) | signed |  | YES | '' |  |  |
| [VerifiedBuild](#verifiedbuild) | smallint(5) | signed |  | YES | 0 |  |  |
&nbsp;
## Description of fields

### guid
*- no description -*
&nbsp;

### id
*- no description -*
&nbsp;

### map
*- no description -*
&nbsp;

### zoneId
*- no description -*
&nbsp;

### areaId
*- no description -*
&nbsp;

### spawnMask
*- no description -*
&nbsp;

### phaseMask
*- no description -*
&nbsp;

### position_x
*- no description -*
&nbsp;

### position_y
*- no description -*
&nbsp;

### position_z
*- no description -*
&nbsp;

### orientation
*- no description -*
&nbsp;

### rotation0
*- no description -*
&nbsp;

### rotation1
*- no description -*
&nbsp;

### rotation2
*- no description -*
&nbsp;

### rotation3
*- no description -*
&nbsp;

### spawntimesecs
*- no description -*
&nbsp;

### animprogress
*- no description -*
&nbsp;

### state
*- no description -*
&nbsp;

### ScriptName
*- no description -*
&nbsp;

### VerifiedBuild
*- no description -*
&nbsp;

<a href="https://dev.trinitycore.info/en/database/335/world/game_weather" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'game_weather'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/335/world/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to world</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/335/world/gameobject_addon" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'gameobject_addon'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

