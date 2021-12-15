---
title: serverside_spell
description: 
published: true
date: 2021-08-30T20:38:02.309Z
tags: database, master, world
editor: markdown
dateCreated: 2021-08-30T06:00:00.000Z
---

<a href="https://dev.trinitycore.info/en/database/master/world/script_waypoint" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'script_waypoint'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to world</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/serverside_spell_effect" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'serverside_spell_effect'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [Id](#id) | int(10) | unsigned | PRI | NO |  |  |  |
| [DifficultyID](#difficultyid) | int(11) | signed | PRI | NO | 0 |  |  |
| [CategoryId](#categoryid) | int(10) | unsigned |  | NO | 0 |  |  |
| [Dispel](#dispel) | int(10) | unsigned |  | NO | 0 |  |  |
| [Mechanic](#mechanic) | int(10) | unsigned |  | NO | 0 |  |  |
| [Attributes](#attributes) | int(10) | unsigned |  | NO | 0 |  |  |
| [AttributesEx](#attributesex) | int(10) | unsigned |  | NO | 0 |  |  |
| [AttributesEx2](#attributesex2) | int(10) | unsigned |  | NO | 0 |  |  |
| [AttributesEx3](#attributesex3) | int(10) | unsigned |  | NO | 0 |  |  |
| [AttributesEx4](#attributesex4) | int(10) | unsigned |  | NO | 0 |  |  |
| [AttributesEx5](#attributesex5) | int(10) | unsigned |  | NO | 0 |  |  |
| [AttributesEx6](#attributesex6) | int(10) | unsigned |  | NO | 0 |  |  |
| [AttributesEx7](#attributesex7) | int(10) | unsigned |  | NO | 0 |  |  |
| [AttributesEx8](#attributesex8) | int(10) | unsigned |  | NO | 0 |  |  |
| [AttributesEx9](#attributesex9) | int(10) | unsigned |  | NO | 0 |  |  |
| [AttributesEx10](#attributesex10) | int(10) | unsigned |  | NO | 0 |  |  |
| [AttributesEx11](#attributesex11) | int(10) | unsigned |  | NO | 0 |  |  |
| [AttributesEx12](#attributesex12) | int(10) | unsigned |  | NO | 0 |  |  |
| [AttributesEx13](#attributesex13) | int(10) | unsigned |  | NO | 0 |  |  |
| [AttributesEx14](#attributesex14) | int(10) | unsigned |  | NO | 0 |  |  |
| [Stances](#stances) | bigint(20) | unsigned |  | NO | 0 |  |  |
| [StancesNot](#stancesnot) | bigint(20) | unsigned |  | NO | 0 |  |  |
| [Targets](#targets) | int(10) | unsigned |  | NO | 0 |  |  |
| [TargetCreatureType](#targetcreaturetype) | int(10) | unsigned |  | NO | 0 |  |  |
| [RequiresSpellFocus](#requiresspellfocus) | int(10) | unsigned |  | NO | 0 |  |  |
| [FacingCasterFlags](#facingcasterflags) | int(10) | unsigned |  | NO | 0 |  |  |
| [CasterAuraState](#casteraurastate) | int(10) | unsigned |  | NO | 0 |  |  |
| [TargetAuraState](#targetaurastate) | int(10) | unsigned |  | NO | 0 |  |  |
| [ExcludeCasterAuraState](#excludecasteraurastate) | int(10) | unsigned |  | NO | 0 |  |  |
| [ExcludeTargetAuraState](#excludetargetaurastate) | int(10) | unsigned |  | NO | 0 |  |  |
| [CasterAuraSpell](#casterauraspell) | int(10) | unsigned |  | NO | 0 |  |  |
| [TargetAuraSpell](#targetauraspell) | int(10) | unsigned |  | NO | 0 |  |  |
| [ExcludeCasterAuraSpell](#excludecasterauraspell) | int(10) | unsigned |  | NO | 0 |  |  |
| [ExcludeTargetAuraSpell](#excludetargetauraspell) | int(10) | unsigned |  | NO | 0 |  |  |
| [CastingTimeIndex](#castingtimeindex) | int(10) | unsigned |  | NO | 1 |  |  |
| [RecoveryTime](#recoverytime) | int(10) | unsigned |  | NO | 0 |  |  |
| [CategoryRecoveryTime](#categoryrecoverytime) | int(10) | unsigned |  | NO | 0 |  |  |
| [StartRecoveryCategory](#startrecoverycategory) | int(10) | unsigned |  | NO | 0 |  |  |
| [StartRecoveryTime](#startrecoverytime) | int(10) | unsigned |  | NO | 0 |  |  |
| [InterruptFlags](#interruptflags) | int(10) | unsigned |  | NO | 0 |  |  |
| [AuraInterruptFlags1](#aurainterruptflags1) | int(10) | unsigned |  | NO | 0 |  |  |
| [AuraInterruptFlags2](#aurainterruptflags2) | int(10) | unsigned |  | NO | 0 |  |  |
| [ChannelInterruptFlags1](#channelinterruptflags1) | int(10) | unsigned |  | NO | 0 |  |  |
| [ChannelInterruptFlags2](#channelinterruptflags2) | int(10) | unsigned |  | NO | 0 |  |  |
| [ProcFlags](#procflags) | int(10) | unsigned |  | NO | 0 |  |  |
| [ProcChance](#procchance) | int(10) | unsigned |  | NO | 0 |  |  |
| [ProcCharges](#proccharges) | int(10) | unsigned |  | NO | 0 |  |  |
| [ProcCooldown](#proccooldown) | int(10) | unsigned |  | NO | 0 |  |  |
| [ProcBasePPM](#procbaseppm) | float |  |  | NO | 0 |  |  |
| [MaxLevel](#maxlevel) | int(10) | unsigned |  | NO | 0 |  |  |
| [BaseLevel](#baselevel) | int(10) | unsigned |  | NO | 0 |  |  |
| [SpellLevel](#spelllevel) | int(10) | unsigned |  | NO | 0 |  |  |
| [DurationIndex](#durationindex) | int(10) | unsigned |  | NO | 0 |  |  |
| [RangeIndex](#rangeindex) | int(10) | unsigned |  | NO | 1 |  |  |
| [Speed](#speed) | float |  |  | NO | 0 |  |  |
| [LaunchDelay](#launchdelay) | float |  |  | NO | 0 |  |  |
| [StackAmount](#stackamount) | int(10) | unsigned |  | NO | 0 |  |  |
| [EquippedItemClass](#equippeditemclass) | int(11) | signed |  | NO | -1 |  |  |
| [EquippedItemSubClassMask](#equippeditemsubclassmask) | int(11) | signed |  | NO | 0 |  |  |
| [EquippedItemInventoryTypeMask](#equippediteminventorytypemask) | int(11) | signed |  | NO | 0 |  |  |
| [ContentTuningId](#contenttuningid) | int(10) | unsigned |  | NO | 0 |  |  |
| [SpellName](#spellname) | varchar(100) | signed |  | YES | NULL |  |  |
| [ConeAngle](#coneangle) | float |  |  | NO | 0 |  |  |
| [ConeWidth](#conewidth) | float |  |  | NO | 0 |  |  |
| [MaxTargetLevel](#maxtargetlevel) | int(10) | unsigned |  | NO | 0 |  |  |
| [MaxAffectedTargets](#maxaffectedtargets) | int(10) | unsigned |  | NO | 0 |  |  |
| [SpellFamilyName](#spellfamilyname) | int(10) | unsigned |  | NO | 0 |  |  |
| [SpellFamilyFlags1](#spellfamilyflags1) | int(10) | unsigned |  | NO | 0 |  |  |
| [SpellFamilyFlags2](#spellfamilyflags2) | int(10) | unsigned |  | NO | 0 |  |  |
| [SpellFamilyFlags3](#spellfamilyflags3) | int(10) | unsigned |  | NO | 0 |  |  |
| [SpellFamilyFlags4](#spellfamilyflags4) | int(10) | unsigned |  | NO | 0 |  |  |
| [DmgClass](#dmgclass) | int(10) | unsigned |  | NO | 0 |  |  |
| [PreventionType](#preventiontype) | int(10) | unsigned |  | NO | 0 |  |  |
| [AreaGroupId](#areagroupid) | int(11) | signed |  | NO | 0 |  |  |
| [SchoolMask](#schoolmask) | int(10) | unsigned |  | NO | 0 |  |  |
| [ChargeCategoryId](#chargecategoryid) | int(10) | unsigned |  | NO | 0 |  |  |
&nbsp;
## Description of fields

### Id
*- no description -*
&nbsp;

### DifficultyID
*- no description -*
&nbsp;

### CategoryId
*- no description -*
&nbsp;

### Dispel
*- no description -*
&nbsp;

### Mechanic
*- no description -*
&nbsp;

### Attributes
*- no description -*
&nbsp;

### AttributesEx
*- no description -*
&nbsp;

### AttributesEx2
*- no description -*
&nbsp;

### AttributesEx3
*- no description -*
&nbsp;

### AttributesEx4
*- no description -*
&nbsp;

### AttributesEx5
*- no description -*
&nbsp;

### AttributesEx6
*- no description -*
&nbsp;

### AttributesEx7
*- no description -*
&nbsp;

### AttributesEx8
*- no description -*
&nbsp;

### AttributesEx9
*- no description -*
&nbsp;

### AttributesEx10
*- no description -*
&nbsp;

### AttributesEx11
*- no description -*
&nbsp;

### AttributesEx12
*- no description -*
&nbsp;

### AttributesEx13
*- no description -*
&nbsp;

### AttributesEx14
*- no description -*
&nbsp;

### Stances
*- no description -*
&nbsp;

### StancesNot
*- no description -*
&nbsp;

### Targets
*- no description -*
&nbsp;

### TargetCreatureType
*- no description -*
&nbsp;

### RequiresSpellFocus
*- no description -*
&nbsp;

### FacingCasterFlags
*- no description -*
&nbsp;

### CasterAuraState
*- no description -*
&nbsp;

### TargetAuraState
*- no description -*
&nbsp;

### ExcludeCasterAuraState
*- no description -*
&nbsp;

### ExcludeTargetAuraState
*- no description -*
&nbsp;

### CasterAuraSpell
*- no description -*
&nbsp;

### TargetAuraSpell
*- no description -*
&nbsp;

### ExcludeCasterAuraSpell
*- no description -*
&nbsp;

### ExcludeTargetAuraSpell
*- no description -*
&nbsp;

### CastingTimeIndex
*- no description -*
&nbsp;

### RecoveryTime
*- no description -*
&nbsp;

### CategoryRecoveryTime
*- no description -*
&nbsp;

### StartRecoveryCategory
*- no description -*
&nbsp;

### StartRecoveryTime
*- no description -*
&nbsp;

### InterruptFlags
*- no description -*
&nbsp;

### AuraInterruptFlags1
*- no description -*
&nbsp;

### AuraInterruptFlags2
*- no description -*
&nbsp;

### ChannelInterruptFlags1
*- no description -*
&nbsp;

### ChannelInterruptFlags2
*- no description -*
&nbsp;

### ProcFlags
*- no description -*
&nbsp;

### ProcChance
*- no description -*
&nbsp;

### ProcCharges
*- no description -*
&nbsp;

### ProcCooldown
*- no description -*
&nbsp;

### ProcBasePPM
*- no description -*
&nbsp;

### MaxLevel
*- no description -*
&nbsp;

### BaseLevel
*- no description -*
&nbsp;

### SpellLevel
*- no description -*
&nbsp;

### DurationIndex
*- no description -*
&nbsp;

### RangeIndex
*- no description -*
&nbsp;

### Speed
*- no description -*
&nbsp;

### LaunchDelay
*- no description -*
&nbsp;

### StackAmount
*- no description -*
&nbsp;

### EquippedItemClass
*- no description -*
&nbsp;

### EquippedItemSubClassMask
*- no description -*
&nbsp;

### EquippedItemInventoryTypeMask
*- no description -*
&nbsp;

### ContentTuningId
*- no description -*
&nbsp;

### SpellName
*- no description -*
&nbsp;

### ConeAngle
*- no description -*
&nbsp;

### ConeWidth
*- no description -*
&nbsp;

### MaxTargetLevel
*- no description -*
&nbsp;

### MaxAffectedTargets
*- no description -*
&nbsp;

### SpellFamilyName
*- no description -*
&nbsp;

### SpellFamilyFlags1
*- no description -*
&nbsp;

### SpellFamilyFlags2
*- no description -*
&nbsp;

### SpellFamilyFlags3
*- no description -*
&nbsp;

### SpellFamilyFlags4
*- no description -*
&nbsp;

### DmgClass
*- no description -*
&nbsp;

### PreventionType
*- no description -*
&nbsp;

### AreaGroupId
*- no description -*
&nbsp;

### SchoolMask
*- no description -*
&nbsp;

### ChargeCategoryId
*- no description -*
&nbsp;

<a href="https://dev.trinitycore.info/en/database/master/world/script_waypoint" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'script_waypoint'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to world</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/serverside_spell_effect" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'serverside_spell_effect'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

