---
title: account_data
description: 
published: true
date: 2021-09-07T13:23:06.502Z
tags: database, characters, 3.3.5, 3.3.5a, 335, 335a, wotlk
editor: markdown
dateCreated: 2021-08-30T21:58:27.362Z
---

<a href="https://dev.trinitycore.info/en/database/335/characters/worldstates" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'worldstates'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/335/characters/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to characters</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/335/characters/account_instance_times" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'account_instance_times'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

> Contains data about client account and settings.
{.is-info}


## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [accountId](#accountid) | int(10) | unsigned | PRI | NO | 0 |  | Account Identifier |
| [type](#type) | tinyint(3) | unsigned | PRI | NO | 0 |  |  |
| [time](#time) | int(10) | unsigned |  | NO | 0 |  |  |
| [data](#data) | blob |  |  | NO |  |  |  |
&nbsp;
## Description of fields

### accountId
The unique account ID.
&nbsp;

### type
- 0 = Global-account config cache
- 2 = Global-account bindings cache
- 4 = Global-account macros cache
&nbsp;

### time
Time of last modification in Unixtime
&nbsp;

### data
No description can be written. You just must understand it's data.
&nbsp;

<a href="https://dev.trinitycore.info/en/database/335/characters/worldstates" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'worldstates'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/335/characters/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to characters</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/335/characters/account_instance_times" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'account_instance_times'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

