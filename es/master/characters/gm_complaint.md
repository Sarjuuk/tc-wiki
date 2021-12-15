---
title: gm_complaint
description: 
published: true
date: 2021-08-30T21:22:03.993Z
tags: database, master, characters
editor: markdown
dateCreated: 2021-08-30T06:00:00.000Z
---

<a href="https://dev.trinitycore.info/en/database/master/characters/gm_bug" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'gm_bug'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/characters/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to characters</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/characters/gm_complaint_chatlog" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'gm_complaint_chatlog'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [id](#id) | int(10) | unsigned | PRI | NO |  |  |  |
| [playerGuid](#playerguid) | bigint(20) | unsigned |  | NO |  |  |  |
| [note](#note) | text |  |  | NO |  |  |  |
| [createTime](#createtime) | bigint(20) | signed |  | NO | 0 |  |  |
| [mapId](#mapid) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [posX](#posx) | float |  |  | NO | 0 |  |  |
| [posY](#posy) | float |  |  | NO | 0 |  |  |
| [posZ](#posz) | float |  |  | NO | 0 |  |  |
| [facing](#facing) | float |  |  | NO | 0 |  |  |
| [targetCharacterGuid](#targetcharacterguid) | bigint(20) | unsigned |  | NO |  |  |  |
| [complaintType](#complainttype) | smallint(5) | unsigned |  | NO |  |  |  |
| [reportLineIndex](#reportlineindex) | int(10) | signed |  | NO |  |  |  |
| [closedBy](#closedby) | bigint(20) | signed |  | NO | 0 |  |  |
| [assignedTo](#assignedto) | bigint(20) | unsigned |  | NO | 0 |  | GUID of admin to whom ticket is assigned |
| [comment](#comment) | text |  |  | NO |  |  |  |
&nbsp;
## Description of fields

### id
*- no description -*
&nbsp;

### playerGuid
*- no description -*
&nbsp;

### note
*- no description -*
&nbsp;

### createTime
*- no description -*
&nbsp;

### mapId
*- no description -*
&nbsp;

### posX
*- no description -*
&nbsp;

### posY
*- no description -*
&nbsp;

### posZ
*- no description -*
&nbsp;

### facing
*- no description -*
&nbsp;

### targetCharacterGuid
*- no description -*
&nbsp;

### complaintType
*- no description -*
&nbsp;

### reportLineIndex
*- no description -*
&nbsp;

### closedBy
*- no description -*
&nbsp;

### assignedTo
*- no description -*
&nbsp;

### comment
*- no description -*
&nbsp;

<a href="https://dev.trinitycore.info/en/database/master/characters/gm_bug" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'gm_bug'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/characters/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to characters</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/characters/gm_complaint_chatlog" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'gm_complaint_chatlog'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

