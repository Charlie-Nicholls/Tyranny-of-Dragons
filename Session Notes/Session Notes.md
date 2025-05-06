---
cssClasses: index
displayLink: "[[Session Notes]]"
alias:
---
###### <span class="head">Sessions</span> 
![[compendium.jpg|banner]]


 ### :FasBook: Arc 1 - 
 
 ```dataviewjs
let pages = dv.pages('"Session Notes"').sort(p => p.number, "asc"); 
let chapters = [];
for (let i=0; i < pages.length; i++) {
	if (pages[i].number > 0) {
		chapters.push(`[[${pages[i].file.name}|Session ${pages[i].number} - ${pages[i].alias}]]`);
		}
	}
dv.list(chapters)
dv.list(pages[1])
```