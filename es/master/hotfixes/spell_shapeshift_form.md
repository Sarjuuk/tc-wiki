---
title: spell_shapeshift_form
description: 
published: true
date: 2021-11-14T19:41:35.170Z
tags: database, master, hotfixes
editor: markdown
dateCreated: 2021-08-30T06:00:00.000Z
---

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/spell_shapeshift" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'spell_shapeshift'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/spell_shapeshift_form_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'spell_shapeshift_form_locale'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [ID](#id) | int(10) | unsigned | PRI | NO | 0 |  |  |
| [Name](#name) | text |  |  | YES | NULL |  |  |
| [CreatureType](#creaturetype) | tinyint(4) | signed |  | NO | 0 |  |  |
| [Flags](#flags) | int(11) | signed |  | NO | 0 |  |  |
| [AttackIconFileID](#attackiconfileid) | int(11) | signed |  | NO | 0 |  |  |
| [BonusActionBar](#bonusactionbar) | tinyint(4) | signed |  | NO | 0 |  |  |
| [CombatRoundTime](#combatroundtime) | smallint(6) | signed |  | NO | 0 |  |  |
| [DamageVariance](#damagevariance) | float |  |  | NO | 0 |  |  |
| [MountTypeID](#mounttypeid) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [CreatureDisplayID1](#creaturedisplayid1) | int(10) | unsigned |  | NO | 0 |  |  |
| [CreatureDisplayID2](#creaturedisplayid2) | int(10) | unsigned |  | NO | 0 |  |  |
| [CreatureDisplayID3](#creaturedisplayid3) | int(10) | unsigned |  | NO | 0 |  |  |
| [CreatureDisplayID4](#creaturedisplayid4) | int(10) | unsigned |  | NO | 0 |  |  |
| [PresetSpellID1](#presetspellid1) | int(10) | unsigned |  | NO | 0 |  |  |
| [PresetSpellID2](#presetspellid2) | int(10) | unsigned |  | NO | 0 |  |  |
| [PresetSpellID3](#presetspellid3) | int(10) | unsigned |  | NO | 0 |  |  |
| [PresetSpellID4](#presetspellid4) | int(10) | unsigned |  | NO | 0 |  |  |
| [PresetSpellID5](#presetspellid5) | int(10) | unsigned |  | NO | 0 |  |  |
| [PresetSpellID6](#presetspellid6) | int(10) | unsigned |  | NO | 0 |  |  |
| [PresetSpellID7](#presetspellid7) | int(10) | unsigned |  | NO | 0 |  |  |
| [PresetSpellID8](#presetspellid8) | int(10) | unsigned |  | NO | 0 |  |  |
| [VerifiedBuild](#verifiedbuild) | int(11) | signed | PRI | NO | 0 |  |  |
&nbsp;
## Description of fields

### ID
*- no description -*
&nbsp;

### Name
*- no description -*
&nbsp;

### CreatureType
*- no description -*
&nbsp;

### Flags
*- no description -*
&nbsp;

### AttackIconFileID
*- no description -*
&nbsp;

### BonusActionBar
*- no description -*
&nbsp;

### CombatRoundTime
*- no description -*
&nbsp;

### DamageVariance
*- no description -*
&nbsp;

### MountTypeID
*- no description -*
&nbsp;

### CreatureDisplayID1
*- no description -*
&nbsp;

### CreatureDisplayID2
*- no description -*
&nbsp;

### CreatureDisplayID3
*- no description -*
&nbsp;

### CreatureDisplayID4
*- no description -*
&nbsp;

### PresetSpellID1
*- no description -*
&nbsp;

### PresetSpellID2
*- no description -*
&nbsp;

### PresetSpellID3
*- no description -*
&nbsp;

### PresetSpellID4
*- no description -*
&nbsp;

### PresetSpellID5
*- no description -*
&nbsp;

### PresetSpellID6
*- no description -*
&nbsp;

### PresetSpellID7
*- no description -*
&nbsp;

### PresetSpellID8
*- no description -*
&nbsp;

### VerifiedBuild
This field is used by the TrinityDB Team to determine whether a template has been verified from WDB files.

If value is 0 then it has not been parsed yet.

If value is above 0 then it has been parsed with WDB files from that specific client build.

If value is -1 then it is just a place holder until proper data are found on WDBs.

If value is -Client Build then it was parsed with WDB files from that specific client build and manually edited later for some special necessity.

&nbsp;

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/spell_shapeshift" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'spell_shapeshift'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/spell_shapeshift_form_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'spell_shapeshift_form_locale'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

