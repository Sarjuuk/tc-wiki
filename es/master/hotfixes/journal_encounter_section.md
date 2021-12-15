---
title: journal_encounter_section
description: 
published: true
date: 2021-11-14T19:41:35.129Z
tags: database, master, hotfixes
editor: markdown
dateCreated: 2021-08-30T06:00:00.000Z
---

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/journal_encounter_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'journal_encounter_locale'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/journal_encounter_section_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'journal_encounter_section_locale'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [ID](#id) | int(10) | unsigned | PRI | NO | 0 |  |  |
| [Title](#title) | text |  |  | YES | NULL |  |  |
| [BodyText](#bodytext) | text |  |  | YES | NULL |  |  |
| [JournalEncounterID](#journalencounterid) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [OrderIndex](#orderindex) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [ParentSectionID](#parentsectionid) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [FirstChildSectionID](#firstchildsectionid) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [NextSiblingSectionID](#nextsiblingsectionid) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [Type](#type) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [IconCreatureDisplayInfoID](#iconcreaturedisplayinfoid) | int(10) | unsigned |  | NO | 0 |  |  |
| [UiModelSceneID](#uimodelsceneid) | int(11) | signed |  | NO | 0 |  |  |
| [SpellID](#spellid) | int(11) | signed |  | NO | 0 |  |  |
| [IconFileDataID](#iconfiledataid) | int(11) | signed |  | NO | 0 |  |  |
| [Flags](#flags) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [IconFlags](#iconflags) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [DifficultyMask](#difficultymask) | tinyint(4) | signed |  | NO | 0 |  |  |
| [VerifiedBuild](#verifiedbuild) | int(11) | signed | PRI | NO | 0 |  |  |
&nbsp;
## Description of fields

### ID
*- no description -*
&nbsp;

### Title
*- no description -*
&nbsp;

### BodyText
*- no description -*
&nbsp;

### JournalEncounterID
*- no description -*
&nbsp;

### OrderIndex
*- no description -*
&nbsp;

### ParentSectionID
*- no description -*
&nbsp;

### FirstChildSectionID
*- no description -*
&nbsp;

### NextSiblingSectionID
*- no description -*
&nbsp;

### Type
*- no description -*
&nbsp;

### IconCreatureDisplayInfoID
*- no description -*
&nbsp;

### UiModelSceneID
*- no description -*
&nbsp;

### SpellID
*- no description -*
&nbsp;

### IconFileDataID
*- no description -*
&nbsp;

### Flags
*- no description -*
&nbsp;

### IconFlags
*- no description -*
&nbsp;

### DifficultyMask
*- no description -*
&nbsp;

### VerifiedBuild
This field is used by the TrinityDB Team to determine whether a template has been verified from WDB files.

If value is 0 then it has not been parsed yet.

If value is above 0 then it has been parsed with WDB files from that specific client build.

If value is -1 then it is just a place holder until proper data are found on WDBs.

If value is -Client Build then it was parsed with WDB files from that specific client build and manually edited later for some special necessity.

&nbsp;

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/journal_encounter_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'journal_encounter_locale'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/journal_encounter_section_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'journal_encounter_section_locale'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

