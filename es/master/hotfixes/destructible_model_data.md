---
title: destructible_model_data
description: 
published: true
date: 2021-11-14T19:41:35.096Z
tags: database, master, hotfixes
editor: markdown
dateCreated: 2021-08-30T06:00:00.000Z
---

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/curve_point" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'curve_point'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/difficulty" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'difficulty'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [ID](#id) | int(10) | unsigned | PRI | NO | 0 |  |  |
| [State0ImpactEffectDoodadSet](#state0impacteffectdoodadset) | tinyint(4) | signed |  | NO | 0 |  |  |
| [State0AmbientDoodadSet](#state0ambientdoodadset) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [State1Wmo](#state1wmo) | int(11) | signed |  | NO | 0 |  |  |
| [State1DestructionDoodadSet](#state1destructiondoodadset) | tinyint(4) | signed |  | NO | 0 |  |  |
| [State1ImpactEffectDoodadSet](#state1impacteffectdoodadset) | tinyint(4) | signed |  | NO | 0 |  |  |
| [State1AmbientDoodadSet](#state1ambientdoodadset) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [State2Wmo](#state2wmo) | int(11) | signed |  | NO | 0 |  |  |
| [State2DestructionDoodadSet](#state2destructiondoodadset) | tinyint(4) | signed |  | NO | 0 |  |  |
| [State2ImpactEffectDoodadSet](#state2impacteffectdoodadset) | tinyint(4) | signed |  | NO | 0 |  |  |
| [State2AmbientDoodadSet](#state2ambientdoodadset) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [State3Wmo](#state3wmo) | int(11) | signed |  | NO | 0 |  |  |
| [State3InitDoodadSet](#state3initdoodadset) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [State3AmbientDoodadSet](#state3ambientdoodadset) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [EjectDirection](#ejectdirection) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [DoNotHighlight](#donothighlight) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [State0Wmo](#state0wmo) | int(11) | signed |  | NO | 0 |  |  |
| [HealEffect](#healeffect) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [HealEffectSpeed](#healeffectspeed) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [State0NameSet](#state0nameset) | tinyint(4) | signed |  | NO | 0 |  |  |
| [State1NameSet](#state1nameset) | tinyint(4) | signed |  | NO | 0 |  |  |
| [State2NameSet](#state2nameset) | tinyint(4) | signed |  | NO | 0 |  |  |
| [State3NameSet](#state3nameset) | tinyint(4) | signed |  | NO | 0 |  |  |
| [VerifiedBuild](#verifiedbuild) | int(11) | signed | PRI | NO | 0 |  |  |
&nbsp;
## Description of fields

### ID
*- no description -*
&nbsp;

### State0ImpactEffectDoodadSet
*- no description -*
&nbsp;

### State0AmbientDoodadSet
*- no description -*
&nbsp;

### State1Wmo
*- no description -*
&nbsp;

### State1DestructionDoodadSet
*- no description -*
&nbsp;

### State1ImpactEffectDoodadSet
*- no description -*
&nbsp;

### State1AmbientDoodadSet
*- no description -*
&nbsp;

### State2Wmo
*- no description -*
&nbsp;

### State2DestructionDoodadSet
*- no description -*
&nbsp;

### State2ImpactEffectDoodadSet
*- no description -*
&nbsp;

### State2AmbientDoodadSet
*- no description -*
&nbsp;

### State3Wmo
*- no description -*
&nbsp;

### State3InitDoodadSet
*- no description -*
&nbsp;

### State3AmbientDoodadSet
*- no description -*
&nbsp;

### EjectDirection
*- no description -*
&nbsp;

### DoNotHighlight
*- no description -*
&nbsp;

### State0Wmo
*- no description -*
&nbsp;

### HealEffect
*- no description -*
&nbsp;

### HealEffectSpeed
*- no description -*
&nbsp;

### State0NameSet
*- no description -*
&nbsp;

### State1NameSet
*- no description -*
&nbsp;

### State2NameSet
*- no description -*
&nbsp;

### State3NameSet
*- no description -*
&nbsp;

### VerifiedBuild
This field is used by the TrinityDB Team to determine whether a template has been verified from WDB files.

If value is 0 then it has not been parsed yet.

If value is above 0 then it has been parsed with WDB files from that specific client build.

If value is -1 then it is just a place holder until proper data are found on WDBs.

If value is -Client Build then it was parsed with WDB files from that specific client build and manually edited later for some special necessity.

&nbsp;

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/curve_point" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'curve_point'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/difficulty" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'difficulty'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

