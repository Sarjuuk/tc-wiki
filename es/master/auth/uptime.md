---
title: uptime
description: This table holds the server's uptime. Trinity will automatically update the latest entry's value until it crashes and a new record is added.
published: true
date: 2021-08-30T06:11:20.903Z
tags: database, auth, master
editor: markdown
dateCreated: 2021-08-26T03:16:18.297Z
---

<a href="https://dev.trinitycore.info/en/database/master/auth/updates_include" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'updates_include'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/auth/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to auth</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/auth/account" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'account'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>


## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
|---|---|---|:---:|:---:|---|---|---|
[realmid](#realmid) | int(10) | unsigned | PRI | NO |  |  |  |
[starttime](#starttime) | int(10) | unsigned |  | NO | 0 |  |  |
[uptime](#uptime) | int(10) | unsigned |  | NO | 0 |  |  |
[maxplayers](#maxplayers) | smallint(5) | unsigned |  | NO | 0 |  |  |
[revision](#revision) | varchar(255) | signed |  | NO | 'Trinitycore' |  |  |

&nbsp;
## Description of fields

### realmid   
The ID of the realm. See realmlist.id
&nbsp;
    
### starttime  
The time when the server was started, in Unix time.
&nbsp;

### uptime
The uptime of the server, in seconds.
&nbsp;

### maxplayers
The maximum number of players connected.
&nbsp;

### revision
The detailed revision of the worldserver
&nbsp;

<a href="https://dev.trinitycore.info/en/database/master/auth/updates_include" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'updates_include'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/auth/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to auth</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/auth/account" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'account'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>