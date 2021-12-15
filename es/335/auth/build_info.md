---
title: build_info
description: 
published: true
date: 2021-08-30T22:01:08.220Z
tags: database, 3.3.5, 3.3.5a, 335, 335a, wotlk, auth
editor: markdown
dateCreated: 2021-08-30T06:00:00.000Z
---

<a href="https://dev.trinitycore.info/en/database/335/auth/autobroadcast" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'autobroadcast'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/335/auth/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to auth</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/335/auth/ip_banned" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'ip_banned'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [build](#build) | int(11) | signed | PRI | NO |  |  |  |
| [majorVersion](#majorversion) | int(11) | signed |  | YES | NULL |  |  |
| [minorVersion](#minorversion) | int(11) | signed |  | YES | NULL |  |  |
| [bugfixVersion](#bugfixversion) | int(11) | signed |  | YES | NULL |  |  |
| [hotfixVersion](#hotfixversion) | char(3) | signed |  | YES | NULL |  |  |
| [winAuthSeed](#winauthseed) | varchar(32) | signed |  | YES | NULL |  |  |
| [win64AuthSeed](#win64authseed) | varchar(32) | signed |  | YES | NULL |  |  |
| [mac64AuthSeed](#mac64authseed) | varchar(32) | signed |  | YES | NULL |  |  |
| [winChecksumSeed](#winchecksumseed) | varchar(40) | signed |  | YES | NULL |  |  |
| [macChecksumSeed](#macchecksumseed) | varchar(40) | signed |  | YES | NULL |  |  |
&nbsp;
## Description of fields

### build
*- no description -*
&nbsp;

### majorVersion
*- no description -*
&nbsp;

### minorVersion
*- no description -*
&nbsp;

### bugfixVersion
*- no description -*
&nbsp;

### hotfixVersion
*- no description -*
&nbsp;

### winAuthSeed
*- no description -*
&nbsp;

### win64AuthSeed
*- no description -*
&nbsp;

### mac64AuthSeed
*- no description -*
&nbsp;

### winChecksumSeed
*- no description -*
&nbsp;

### macChecksumSeed
*- no description -*
&nbsp;

<a href="https://dev.trinitycore.info/en/database/335/auth/autobroadcast" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'autobroadcast'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/335/auth/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to auth</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/335/auth/ip_banned" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'ip_banned'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

