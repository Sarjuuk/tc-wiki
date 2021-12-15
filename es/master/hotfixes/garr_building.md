---
title: garr_building
description: 
published: true
date: 2021-11-14T19:41:35.104Z
tags: database, master, hotfixes
editor: markdown
dateCreated: 2021-08-30T06:00:00.000Z
---

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/garr_ability_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'garr_ability_locale'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/garr_building_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'garr_building_locale'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [ID](#id) | int(10) | unsigned | PRI | NO | 0 |  |  |
| [HordeName](#hordename) | text |  |  | YES | NULL |  |  |
| [AllianceName](#alliancename) | text |  |  | YES | NULL |  |  |
| [Description](#description) | text |  |  | YES | NULL |  |  |
| [Tooltip](#tooltip) | text |  |  | YES | NULL |  |  |
| [GarrTypeID](#garrtypeid) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [BuildingType](#buildingtype) | tinyint(4) | signed |  | NO | 0 |  |  |
| [HordeGameObjectID](#hordegameobjectid) | int(11) | signed |  | NO | 0 |  |  |
| [AllianceGameObjectID](#alliancegameobjectid) | int(11) | signed |  | NO | 0 |  |  |
| [GarrSiteID](#garrsiteid) | int(11) | signed |  | NO | 0 |  |  |
| [UpgradeLevel](#upgradelevel) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [BuildSeconds](#buildseconds) | int(11) | signed |  | NO | 0 |  |  |
| [CurrencyTypeID](#currencytypeid) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [CurrencyQty](#currencyqty) | int(11) | signed |  | NO | 0 |  |  |
| [HordeUiTextureKitID](#hordeuitexturekitid) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [AllianceUiTextureKitID](#allianceuitexturekitid) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [IconFileDataID](#iconfiledataid) | int(11) | signed |  | NO | 0 |  |  |
| [AllianceSceneScriptPackageID](#alliancescenescriptpackageid) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [HordeSceneScriptPackageID](#hordescenescriptpackageid) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [MaxAssignments](#maxassignments) | int(11) | signed |  | NO | 0 |  |  |
| [ShipmentCapacity](#shipmentcapacity) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [GarrAbilityID](#garrabilityid) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [BonusGarrAbilityID](#bonusgarrabilityid) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [GoldCost](#goldcost) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [Flags](#flags) | int(11) | signed |  | NO | 0 |  |  |
| [VerifiedBuild](#verifiedbuild) | int(11) | signed | PRI | NO | 0 |  |  |
&nbsp;
## Description of fields

### ID
*- no description -*
&nbsp;

### HordeName
*- no description -*
&nbsp;

### AllianceName
*- no description -*
&nbsp;

### Description
*- no description -*
&nbsp;

### Tooltip
*- no description -*
&nbsp;

### GarrTypeID
*- no description -*
&nbsp;

### BuildingType
*- no description -*
&nbsp;

### HordeGameObjectID
*- no description -*
&nbsp;

### AllianceGameObjectID
*- no description -*
&nbsp;

### GarrSiteID
*- no description -*
&nbsp;

### UpgradeLevel
*- no description -*
&nbsp;

### BuildSeconds
*- no description -*
&nbsp;

### CurrencyTypeID
*- no description -*
&nbsp;

### CurrencyQty
*- no description -*
&nbsp;

### HordeUiTextureKitID
*- no description -*
&nbsp;

### AllianceUiTextureKitID
*- no description -*
&nbsp;

### IconFileDataID
*- no description -*
&nbsp;

### AllianceSceneScriptPackageID
*- no description -*
&nbsp;

### HordeSceneScriptPackageID
*- no description -*
&nbsp;

### MaxAssignments
*- no description -*
&nbsp;

### ShipmentCapacity
*- no description -*
&nbsp;

### GarrAbilityID
*- no description -*
&nbsp;

### BonusGarrAbilityID
*- no description -*
&nbsp;

### GoldCost
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

<a href="https://dev.trinitycore.info/en/database/master/hotfixes/garr_ability_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'garr_ability_locale'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to hotfixes</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/hotfixes/garr_building_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'garr_building_locale'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

