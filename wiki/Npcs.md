---
title: NPCs
---

<p>
  
<center><img src="wiki/images/npcs.png"></center>

<p>
<%
foreach (glob("wiki/*.md") as $path) {
  $file = basename($path);
  echo "<li><a href="$path">$file</a></li>\n";
}
%>

<h3>NPCs in Rust</h3>
