---
tag: daily
---
<%tp.system.prompt("Note")%>
<%* 
let title = await tp.date.now("YYYY-MM-DD—HH-mm");
await tp.file.rename(`${title}`);
tp.file.move("Tracking/" + title);
%>
