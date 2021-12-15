---
title: wmo_area_table
description: 
published: true
date: 2021-11-14T19:41:35.183Z
tags: database, master, hotfixes
editor: markdown
dateCreated: 2021-08-30T06:00:00.000Z
---

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/vehicle_seat" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'vehicle_seat'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/wmo_area_table_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'wmo_area_table_locale'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [AreaName](#areaname) | text |  |  | YES | NULL |  |  |
| [ID](#id) | int(10) | unsigned | PRI | NO | 0 |  |  |
| [WmoID](#wmoid) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [NameSetID](#namesetid) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [WmoGroupID](#wmogroupid) | int(11) | signed |  | NO | 0 |  |  |
| [SoundProviderPref](#soundproviderpref) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [SoundProviderPrefUnderwater](#soundproviderprefunderwater) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [AmbienceID](#ambienceid) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [UwAmbience](#uwambience) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [ZoneMusic](#zonemusic) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [UwZoneMusic](#uwzonemusic) | int(10) | unsigned |  | NO | 0 |  |  |
| [IntroSound](#introsound) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [UwIntroSound](#uwintrosound) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [AreaTableID](#areatableid) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [Flags](#flags) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [VerifiedBuild](#verifiedbuild) | int(11) | signed | PRI | NO | 0 |  |  |
&nbsp;
## Description of fields

### AreaName
*- no description -*
&nbsp;

### ID
*- no description -*
&nbsp;

### WmoID
*- no description -*
&nbsp;

### NameSetID
*- no description -*
&nbsp;

### WmoGroupID
*- no description -*
&nbsp;

### SoundProviderPref
*- no description -*
&nbsp;

### SoundProviderPrefUnderwater
*- no description -*
&nbsp;

### AmbienceID
*- no description -*
&nbsp;

### UwAmbience
*- no description -*
&nbsp;

### ZoneMusic
*- no description -*
&nbsp;

### UwZoneMusic
*- no description -*
&nbsp;

### IntroSound
*- no description -*
&nbsp;

### UwIntroSound
*- no description -*
&nbsp;

### AreaTableID
*- no description -*
&nbsp;

### Flags
*- no description -*
&nbsp;

### VerifiedBuild
This field is used by the TrinityDB Team to determine whether a template has been verified from WDB files.

If value is 0 then it has not been parsed yet.

If value is above 0 then it has been parsed with WDB files from that specific client build.

If value is -1 then it is just a place holder until proper data are found on WDBs.

If value is -Client Build then it was parsed with WDB files from that specific client build and manually edited later for some special necessity.

&nbsp;

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/vehicle_seat" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'vehicle_seat'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/wmo_area_table_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'wmo_area_table_locale'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

