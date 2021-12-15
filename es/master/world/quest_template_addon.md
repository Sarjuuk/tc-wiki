---
title: quest_template_addon
description: 
published: true
date: 2021-08-30T20:38:02.304Z
tags: database, master, world
editor: markdown
dateCreated: 2021-08-30T06:00:00.000Z
---

<a href="https://dev.trinitycore.info/en/database/master/world/quest_template" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'quest_template'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to world</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/quest_template_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'quest_template_locale'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

## Structure

| Field | Type | Attributes | Key | Null | Default | Extra | Comment |
| --- | --- | --- | :---: | :---: | --- | --- | --- |
| [ID](#id) | mediumint(8) | unsigned | PRI | NO | 0 |  |  |
| [MaxLevel](#maxlevel) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [AllowableClasses](#allowableclasses) | int(10) | unsigned |  | NO | 0 |  |  |
| [SourceSpellID](#sourcespellid) | mediumint(8) | unsigned |  | NO | 0 |  |  |
| [PrevQuestID](#prevquestid) | mediumint(8) | signed |  | NO | 0 |  |  |
| [NextQuestID](#nextquestid) | mediumint(8) | unsigned |  | NO | 0 |  |  |
| [ExclusiveGroup](#exclusivegroup) | mediumint(8) | signed |  | NO | 0 |  |  |
| [RewardMailTemplateID](#rewardmailtemplateid) | mediumint(8) | unsigned |  | NO | 0 |  |  |
| [RewardMailDelay](#rewardmaildelay) | int(10) | unsigned |  | NO | 0 |  |  |
| [RequiredSkillID](#requiredskillid) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [RequiredSkillPoints](#requiredskillpoints) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [RequiredMinRepFaction](#requiredminrepfaction) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [RequiredMaxRepFaction](#requiredmaxrepfaction) | smallint(5) | unsigned |  | NO | 0 |  |  |
| [RequiredMinRepValue](#requiredminrepvalue) | mediumint(8) | signed |  | NO | 0 |  |  |
| [RequiredMaxRepValue](#requiredmaxrepvalue) | mediumint(8) | signed |  | NO | 0 |  |  |
| [ProvidedItemCount](#provideditemcount) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [SpecialFlags](#specialflags) | tinyint(3) | unsigned |  | NO | 0 |  |  |
| [ScriptName](#scriptname) | varchar(64) | signed |  | NO | '' |  |  |
&nbsp;
## Description of fields

### ID
*- no description -*
&nbsp;

### MaxLevel
*- no description -*
&nbsp;

### AllowableClasses
*- no description -*
&nbsp;

### SourceSpellID
*- no description -*
&nbsp;

### PrevQuestID
*- no description -*
&nbsp;

### NextQuestID
*- no description -*
&nbsp;

### ExclusiveGroup
*- no description -*
&nbsp;

### RewardMailTemplateID
*- no description -*
&nbsp;

### RewardMailDelay
*- no description -*
&nbsp;

### RequiredSkillID
*- no description -*
&nbsp;

### RequiredSkillPoints
*- no description -*
&nbsp;

### RequiredMinRepFaction
*- no description -*
&nbsp;

### RequiredMaxRepFaction
*- no description -*
&nbsp;

### RequiredMinRepValue
*- no description -*
&nbsp;

### RequiredMaxRepValue
*- no description -*
&nbsp;

### ProvidedItemCount
*- no description -*
&nbsp;

### SpecialFlags
*- no description -*
&nbsp;

### ScriptName
*- no description -*
&nbsp;

<a href="https://dev.trinitycore.info/en/database/master/world/quest_template" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-arrow-left theme--light"></i><span>Back to 'quest_template'</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/home" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><i aria-hidden="true" class="v-icon notranslate v-icon--left mdi mdi-home-outline theme--light"></i><span>Return to world</span></span></a>&nbsp;&nbsp;&nbsp;<a href="https://dev.trinitycore.info/en/database/master/world/quest_template_locale" class="mt-5 v-btn v-btn--depressed v-btn--flat v-btn--outlined theme--light v-size--default darkblue--text text--lighten-3"><span class="v-btn__content"><span>Go to 'quest_template_locale'</span><i aria-hidden="true" class="v-icon notranslate v-icon--right mdi mdi-arrow-right theme--light"></i></span></a>

