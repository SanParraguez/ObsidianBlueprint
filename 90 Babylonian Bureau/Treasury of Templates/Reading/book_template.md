<%"---"%>
tag: Reading/Book
title: "{{title}}"
subtitle: "{{subtitle}}"
author: [{{authors}}]
category: [{{categories}}]
publisher: {{publisher}}
publish: {{publishDate}}
pages: {{totalPage}}
isbn: {{isbn10}} {{isbn13}}
cover: {{coverUrl}}
localCover: {{localCoverImage}}
status: Unread
created: {{DATE:YYYY-MM-DD HH:mm:ss}}
updated: {{DATE:YYYY-MM-DD HH:mm:ss}}
finished: ["YYYY-MM-DD"]
version: 0
<%"---"%>
# {{title}}

<%"[["%>{{author}}<%"]]"%>

<%* if (tp.frontmatter.cover && tp.frontmatter.cover.trim() !== "") { tR += `![cover|150](${tp.frontmatter.cover})` } %>

## Comments

