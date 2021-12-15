---
title: gameobjects
description: 
published: true
date: 2021-11-14T19:41:35.102Z
tags: database, master, hotfixes
editor: markdown
dateCreated: 2021-08-30T06:00:00.000Z
---

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/gameobject_display_info" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'gameobject_display_info'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/gameobjects_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'gameobjects_locale'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [Name](#name) | text |  |  | YES | NULL |  |  |
| [PosX](#posx) | float |  |  | NO | 0 |  |  |
| [PosY](#posy) | float |  |  | NO | 0 |  |  |
| [PosZ](#posz) | float |  |  | NO | 0 |  |  |
| [Rot1](#rot1) | float |  |  | NO | 0 |  |  |
| [Rot2](#rot2) | float |  |  | NO | 0 |  |  |
| [Rot3](#rot3) | float |  |  | NO | 0 |  |  |
| [Rot4](#rot4) | float |  |  | NO | 0 |  |  |
| [ID](#id) | int(10) | unsigned | PRI | NO | 0 |  |  |
| [OwnerID](#ownerid) | int(11) | signed |  | NO | 0 |  |  |
| [DisplayID](#displayid) | int(11) | signed |  | NO | 0 |  |  |
| [Scale](#scale) | float |  |  | NO | 0 |  |  |
| [TypeID](#typeid) | int(11) | signed |  | NO | 0 |  |  |
| [PhaseUseFlags](#phaseuseflags) | int(11) | signed |  | NO | 0 |  |  |
| [PhaseID](#phaseid) | int(11) | signed |  | NO | 0 |  |  |
| [PhaseGroupID](#phasegroupid) | int(11) | signed |  | NO | 0 |  |  |
| [PropValue1](#propvalue1) | int(11) | signed |  | NO | 0 |  |  |
| [PropValue2](#propvalue2) | int(11) | signed |  | NO | 0 |  |  |
| [PropValue3](#propvalue3) | int(11) | signed |  | NO | 0 |  |  |
| [PropValue4](#propvalue4) | int(11) | signed |  | NO | 0 |  |  |
| [PropValue5](#propvalue5) | int(11) | signed |  | NO | 0 |  |  |
| [PropValue6](#propvalue6) | int(11) | signed |  | NO | 0 |  |  |
| [PropValue7](#propvalue7) | int(11) | signed |  | NO | 0 |  |  |
| [PropValue8](#propvalue8) | int(11) | signed |  | NO | 0 |  |  |
| [VerifiedBuild](#verifiedbuild) | int(11) | signed | PRI | NO | 0 |  |  |
&nbsp;
## Description of fields

### Name
*- no description -*
&nbsp;

### PosX
*- no description -*
&nbsp;

### PosY
*- no description -*
&nbsp;

### PosZ
*- no description -*
&nbsp;

### Rot1
*- no description -*
&nbsp;

### Rot2
*- no description -*
&nbsp;

### Rot3
*- no description -*
&nbsp;

### Rot4
*- no description -*
&nbsp;

### ID
*- no description -*
&nbsp;

### OwnerID
*- no description -*
&nbsp;

### DisplayID
*- no description -*
&nbsp;

### Scale
*- no description -*
&nbsp;

### TypeID
*- no description -*
&nbsp;

### PhaseUseFlags
*- no description -*
&nbsp;

### PhaseID
*- no description -*
&nbsp;

### PhaseGroupID
*- no description -*
&nbsp;

### PropValue1
*- no description -*
&nbsp;

### PropValue2
*- no description -*
&nbsp;

### PropValue3
*- no description -*
&nbsp;

### PropValue4
*- no description -*
&nbsp;

### PropValue5
*- no description -*
&nbsp;

### PropValue6
*- no description -*
&nbsp;

### PropValue7
*- no description -*
&nbsp;

### PropValue8
*- no description -*
&nbsp;

### VerifiedBuild
This field is used by the TrinityDB Team to determine whether a template has been verified from WDB files.

If value is 0 then it has not been parsed yet.

If value is above 0 then it has been parsed with WDB files from that specific client build.

If value is -1 then it is just a place holder until proper data are found on WDBs.

If value is -Client Build then it was parsed with WDB files from that specific client build and manually edited later for some special necessity.

&nbsp;

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/gameobject_display_info" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'gameobject_display_info'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/gameobjects_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'gameobjects_locale'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

