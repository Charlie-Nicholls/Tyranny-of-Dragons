---
type: pc
level: 1
ac: 10
hp: 10
modifier: 0
race: "Human"
class: "Ranger"
subClass: "Hunter"
cover: "/Assets/Images/Portrait.jpg"
displayLink: "[[Hank]]"
---

###### Hank
:FasPerson: Player Character | :FasQuoteLeft: Wanna go for a run? :FasQuoteRight:
___
> [!infobox|no-t right]
> ![[portrait.jpg|350]]
>
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: Level   | `=this.level` |
> | :RiSwordFill: Class |  `=this.class`|
> | :FasBullseye: Conclave |  `=this.subClass`|
> |  :FasUserGroup: Race |  `=this.race`|
> 
>> [!tip]- STATS
>> | Stat | Score |
>> | ---- | :----: |
>> | :LiEye: Passive Perception | 11 |
>> | :FasMagnifyingGlass: Passive Investigation | 10 |
>> | :RiSpeakFill: Passive Insight | 11 |
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
action: {type: open, link: https://www.dndbeyond.com/characters/145630299, newTab: true}

# Profile

> [!recite|clean no-t]
>	One line description
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
