---
title: updates
description: List of all applied updates in this database.
published: true
date: 2021-08-30T06:10:19.651Z
tags: database, auth, master
editor: markdown
dateCreated: 2021-08-26T03:10:42.105Z
---

<a href="https://dev.trinitycore.info/en/database/master/auth/realmlist" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'realmlist'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/auth/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to auth</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/auth/updates_include" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'updates_include'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
|---|---|---|:---:|:---:|---|---|---|
[name](#name) | varchar(200) | signed | PRI | NO |  |  | filename with extension of the update. |
[hash](#hash) | char(40) | signed |  | YES |  |  | sha1 hash of the sql file. |
[state](#state) | enum('RELEASED','ARCHIVED') |  |  | NO | RELEASED |  | defines if an update is released or archived. |
[timestamp](#timestamp) | timestamp | signed |  | NO | CURRENT_TIMESTAMP |  | timestamp when the query was applied. |
[speed](#speed) | int(10) | unsigned |  | NO | 0 |  |  |

&nbsp;
## Description of fields

### name   
*- no description -*
&nbsp;
    
### hash  
*- no description -*
&nbsp;

### state
*- no description -*
&nbsp;

### timestamp
*- no description -*
&nbsp;

### speed
*- no description -*
&nbsp;

<a href="https://dev.trinitycore.info/en/database/master/auth/realmlist" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'realmlist'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/auth/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to auth</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/auth/updates_include" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'updates_include'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>