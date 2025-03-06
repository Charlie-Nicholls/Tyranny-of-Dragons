---
type: locale
locations:
 - "[[Waterdeep]]"
displayLink: "[[Trades Ward]]"
---

![[banner.jpg|banner]]
###### Trades Ward
<span class="sub2">:FasCircleQuestion: Ward</span>

---

> [!recite|clean no-t]
>	One line description
>^IntroText

### Description
Description of location

---

> [!column|flex 3]
>> [!hint]-  NPCs
>>```dataview
LIST WITHOUT ID displayLink
FROM "Compendium/NPCs" AND [[#]] OR "Compendium/Party" AND [[#]] 
> 
>> [!example]- LOCATIONS
>>```dataview
LIST WITHOUT ID displayLink
FROM "Compendium/Atlas/Material Plane/Toril/Faerûn/Western Heartlands/Sword Coast/Waterdeep/Trades Ward" AND [[#]]
WHERE file.name != this.file.name
SORT file.name ASC
>
>> [!note]- HISTORY
>>```dataview
LIST WITHOUT ID displayLink
FROM "Session Notes" AND [[#]]
SORT file.ctime DESC