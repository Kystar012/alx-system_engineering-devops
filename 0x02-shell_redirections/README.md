<!DOCTYPE html>
<html lang="en">
<body>
<header>
<h1>Shell Redirections</h1>
</header>
<hr>
<section>
<h2>This file expalins various scripts used to execute basic shell redirections.</h2>
<p><em>The following table lists various shell redirections commands and thier uses.</em></p>
<table border="1">
<tr>
<th>scripts </th>
<th>what does the script do</th></tr>
<tr><td>#!/bin/bash<br> echo hello world</td><td>The script displays "hello world" to the  std output.</td></tr>
<tr><td> #!/bin/bash<br>cat /ect/passwd </td><td>dispays the content of a file,/etc/passwd</td></tr>
<tr><td> #!/bin/bash<br>cat /etc/passwd /etchosts</td><td> displays content of two files</td></tr>
<tr><td>#!/bin/bash<br>tail -10 /etc/passwd</td><td>The script lists the last 10 lines of the file /etc/passwd.</td></tr>
<tr><td>#!/bin/bash<br>head -n 10 /etc/passwd<td><td>Lists the first 10 lines of the file /etc/passwd</td></tr>
<tr><td>#!/bin/bash<br>echo "Best School" > \*\\'\"Best School"\'\\*$\?\*\*\*\*\*:\)\ <td><td>The script creates a file specified and echos the line into the file</td><tr>
<tr><td>#!/bin/bash<br>echo \"\(\Ôo\)\'\ </td><td> The script echos the confused smily face to the stdoutput</td></tr>
<tr><td>#!/bin/bash<br>head -3 iacta | tail -1 iacta</td>
<td>The script displays the third line of file iacta</td></tr>
<tr><td>#!/bin/bash<br>tail -1 iacta >> iacta</td><td>The script duplicates the last line of file iacta</td></tr>
<tr><td>#!/bin/bash<br>find . -type f -name *.js  -delete </td><td> <td>The script deletes all .js files in tge directory and sundirectory</td></tr>
<tr><td>
