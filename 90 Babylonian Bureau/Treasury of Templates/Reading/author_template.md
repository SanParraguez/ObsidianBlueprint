---
tags:
  - Reading/Author
version: 0
---
# <% tp.file.title %>

```dataview
table without id
	link(file.link, default(title, file.name)) as Title,
	dateformat(publish, "yyyy") as Publish,
	category[0] as Category,
	"![Cover|80](" + cover + ")" as Cover
from "01 Library of Alexandria/Hall of Scrolls"
where contains( author, this.file.name )
sort publish desc, file.name asc
```
