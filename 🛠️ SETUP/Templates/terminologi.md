---
date: <%tp.file.creation_date(“YYYY-MM-DD”)/%>
date: {{date}}{{time}}
modification date: <% tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
---
# [[<% TP.FILE.TITLE%>]]
<% await tp.file.move("/📕 Terminologi/" +tp.file.title) %>
### Pengertian:

---
### kerugian:

