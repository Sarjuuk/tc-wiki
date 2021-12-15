---
title: ui_splash_screen
description: 
published: true
date: 2021-11-14T19:41:35.180Z
tags: database, master, hotfixes
editor: markdown
dateCreated: 2021-08-30T06:00:00.000Z
---

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/ui_map_x_map_art" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'ui_map_x_map_art'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/ui_splash_screen_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'ui_splash_screen_locale'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [ID](#id) | int(10) | unsigned | PRI | NO | 0 |  |  |
| [Header](#header) | text |  |  | YES | NULL |  |  |
| [TopLeftFeatureTitle](#topleftfeaturetitle) | text |  |  | YES | NULL |  |  |
| [TopLeftFeatureDesc](#topleftfeaturedesc) | text |  |  | YES | NULL |  |  |
| [BottomLeftFeatureTitle](#bottomleftfeaturetitle) | text |  |  | YES | NULL |  |  |
| [BottomLeftFeatureDesc](#bottomleftfeaturedesc) | text |  |  | YES | NULL |  |  |
| [RightFeatureTitle](#rightfeaturetitle) | text |  |  | YES | NULL |  |  |
| [RightFeatureDesc](#rightfeaturedesc) | text |  |  | YES | NULL |  |  |
| [AllianceQuestID](#alliancequestid) | int(11) | signed |  | NO | 0 |  |  |
| [HordeQuestID](#hordequestid) | int(11) | signed |  | NO | 0 |  |  |
| [ScreenType](#screentype) | tinyint(4) | signed |  | NO | 0 |  |  |
| [TextureKitID](#texturekitid) | int(11) | signed |  | NO | 0 |  |  |
| [SoundKitID](#soundkitid) | int(11) | signed |  | NO | 0 |  |  |
| [PlayerConditionID](#playerconditionid) | int(11) | signed |  | NO | 0 |  |  |
| [CharLevelConditionID](#charlevelconditionid) | int(11) | signed |  | NO | 0 |  |  |
| [RequiredTimeEventPassed](#requiredtimeeventpassed) | int(11) | signed |  | NO | 0 |  |  |
| [VerifiedBuild](#verifiedbuild) | int(11) | signed | PRI | NO | 0 |  |  |
&nbsp;
## Description of fields

### ID
*- no description -*
&nbsp;

### Header
*- no description -*
&nbsp;

### TopLeftFeatureTitle
*- no description -*
&nbsp;

### TopLeftFeatureDesc
*- no description -*
&nbsp;

### BottomLeftFeatureTitle
*- no description -*
&nbsp;

### BottomLeftFeatureDesc
*- no description -*
&nbsp;

### RightFeatureTitle
*- no description -*
&nbsp;

### RightFeatureDesc
*- no description -*
&nbsp;

### AllianceQuestID
*- no description -*
&nbsp;

### HordeQuestID
*- no description -*
&nbsp;

### ScreenType
*- no description -*
&nbsp;

### TextureKitID
*- no description -*
&nbsp;

### SoundKitID
*- no description -*
&nbsp;

### PlayerConditionID
*- no description -*
&nbsp;

### CharLevelConditionID
*- no description -*
&nbsp;

### RequiredTimeEventPassed
*- no description -*
&nbsp;

### VerifiedBuild
This field is used by the TrinityDB Team to determine whether a template has been verified from WDB files.

If value is 0 then it has not been parsed yet.

If value is above 0 then it has been parsed with WDB files from that specific client build.

If value is -1 then it is just a place holder until proper data are found on WDBs.

If value is -Client Build then it was parsed with WDB files from that specific client build and manually edited later for some special necessity.

&nbsp;

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/ui_map_x_map_art" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'ui_map_x_map_art'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/ui_splash_screen_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'ui_splash_screen_locale'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

