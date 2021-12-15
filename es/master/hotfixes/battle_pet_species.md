---
title: battle_pet_species
description: 
published: true
date: 2021-11-14T19:41:35.077Z
tags: database, master, hotfixes
editor: markdown
dateCreated: 2021-08-30T06:00:00.000Z
---

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/battle_pet_breed_state" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'battle_pet_breed_state'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/battle_pet_species_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'battle_pet_species_locale'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [Description](#description) | text |  |  | YES | NULL |  |  |
| [SourceText](#sourcetext) | text |  |  | YES | NULL |  |  |
| [ID](#id) | int(10) | unsigned | PRI | NO | 0 |  |  |
| [CreatureID](#creatureid) | int(11) | signed |  | NO | 0 |  |  |
| [SummonSpellID](#summonspellid) | int(11) | signed |  | NO | 0 |  |  |
| [IconFileDataID](#iconfiledataid) | int(11) | signed |  | NO | 0 |  |  |
| [PetTypeEnum](#pettypeenum) | tinyint(11) | signed |  | NO | 0 |  |  |
| [Flags](#flags) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [SourceTypeEnum](#sourcetypeenum) | tinyint(4) | signed |  | NO | 0 |  |  |
| [CardUIModelSceneID](#carduimodelsceneid) | int(11) | signed |  | NO | 0 |  |  |
| [LoadoutUIModelSceneID](#loadoutuimodelsceneid) | int(11) | signed |  | NO | 0 |  |  |
| [CovenantID](#covenantid) | int(11) | signed |  | NO | 0 |  |  |
| [VerifiedBuild](#verifiedbuild) | int(11) | signed | PRI | NO | 0 |  |  |
&nbsp;
## Description of fields

### Description
*- no description -*
&nbsp;

### SourceText
*- no description -*
&nbsp;

### ID
*- no description -*
&nbsp;

### CreatureID
*- no description -*
&nbsp;

### SummonSpellID
*- no description -*
&nbsp;

### IconFileDataID
*- no description -*
&nbsp;

### PetTypeEnum
*- no description -*
&nbsp;

### Flags
*- no description -*
&nbsp;

### SourceTypeEnum
*- no description -*
&nbsp;

### CardUIModelSceneID
*- no description -*
&nbsp;

### LoadoutUIModelSceneID
*- no description -*
&nbsp;

### CovenantID
*- no description -*
&nbsp;

### VerifiedBuild
This field is used by the TrinityDB Team to determine whether a template has been verified from WDB files.

If value is 0 then it has not been parsed yet.

If value is above 0 then it has been parsed with WDB files from that specific client build.

If value is -1 then it is just a place holder until proper data are found on WDBs.

If value is -Client Build then it was parsed with WDB files from that specific client build and manually edited later for some special necessity.

&nbsp;

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/battle_pet_breed_state" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'battle_pet_breed_state'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/battle_pet_species_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'battle_pet_species_locale'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

