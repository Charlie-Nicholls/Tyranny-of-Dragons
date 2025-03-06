---
type: locale
locations:
  - "[[Sword Coast]]"
displayLink: "[[Waterdeep]]"
---

![[imgWaterdeep.jpg|banner]]
###### Waterdeep
<span class="sub2">:FasCity: City</span>

___

>[!recite|clean no-t]
>	One line descriptionText

### Description
Waterdeep, also known as the City of Splendors or the Crown of the North, is the most important and influential city in the North and perhaps in all of [[Faerûn#Faerûn]]. It is truly marvelous cosmopolitan city of great culture that attracts the most talented artisans, artists, and scholars from across the Realms, as well as a commercial hub for financial interests along the coast and beyond.

### Map
```leaflet
id: waterdeep-map
image: [[imgWaterdeepMap.jpg]]
height: 800px
lat: 50%
long: 50%
minZoom: 7.5
maxZoom: 10.5
defaultZoom: 7.5
zoomDelta: 0.5
unit: meters
recenter: true
scale: 1
noUI: false
lock: true
```


<br>


---

> [!column|flex 3]
>> [!hint]-  NPCs
>>```dataview
LIST WITHOUT ID displayLink
FROM "Compendium/NPCs" AND [[#]]
SORT file.name ASC
>
>> [!example]- LOCATIONS
>>```dataview
LIST WITHOUT ID displayLink
FROM "Compendium/Atlas/Material Plane/Toril/Faerûn/Western Heartlands/The Sword Coast/Waterdeep"  AND [[#]]
WHERE file.name != this.file.name
SORT file.name ASC
>
>> [!note]- HISTORY
>>```dataview
LIST WITHOUT ID displayLink
FROM "Session Notes" AND [[#]]
SORT file.ctime DESC