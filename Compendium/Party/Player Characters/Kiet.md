---
type: pc
level: 6
ac: 10
hp: 10
modifier: 0
race: "Human"
class: "Warlock"
subClass: "Fiend"
cover: "/Assets/Images/Portrait.jpg"
displayLink: "[[Kiet]]"
---

###### Kiet
:FasPerson: Player Character | :FasQuoteLeft: It's Keith without the 'h' :FasQuoteRight:
___
> [!infobox|no-t right]
> ![[portrait.jpg|350]]
>
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: Level   | `=this.level` |
> | :RiSwordFill: Class |  `=this.class`|
> | :FasBurst: Patron |  `=this.subClass`|
> |  :FasUserGroup: Race |  `=this.race`|
> 
>> [!tip]- STATS
>> | Stat | Score |
>> | ---- | :----: |
>> | :LiEye: Passive Perception | 11 |
>> | :FasMagnifyingGlass: Passive Investigation | ? |
>> | :RiSpeakFill: Passive Insight | ? |
>> | :FasShield: Armour Class | `=this.ac` |
>> | :FasHeart: Max Hit Points | `=this.hp` |
>
>> [!info]- STORYLINES
>>```dataview
>>LIST WITHOUT ID displayLink
>>FROM "Compendium/Party/Quests" AND ([[#]]  OR [[The Party]])
>>SORT file.ctime DESC
>
>>[!note]- HISTORY
>>```dataview
>>LIST WITHOUT ID displayLink
>>FROM "Session Notes" AND [[#]]
>>SORT file.ctime DESC
>
>^InfoBox

> [!infobox|no-t clean right]
>```meta-bind-button
label: Character Sheet
icon: link
tooltip: external character sheet
style: default
action: {type: open, link: undefined, newTab: true}

# Profile

> [!recite|clean no-t]
>	Introduction for players
>^IntroText
	
### Description
Description

### Motivations
- List of Motivations

### Magic Items / Abilities
- None

### Allies
- [[Characters]] or [[Organisations]]

### Enemies
- [[Characters]] or [[Organisations]]
