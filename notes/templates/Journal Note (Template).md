<% tp.file.include('[[Frontmatter (Template)]]') %>
<% await tp.file.move("/Journal/" + tp.file.title) %>
🏷️ tags: #private
[[<% tp.file.creation_date("MMMM YYYY") %>]]

# <% tp.file.creation_date("DD.MM.YYYY")%>

<% tp.file.cursor(1) %>


<% tp.file.include('[[Footer (Template)]]')%> 