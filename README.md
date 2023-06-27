# ketamine-nightmares

The source for Ketamine Nightmares, a resource for the [ANZCA](http://www.anzca.edu.au/) Examinations.

Content by Stuart N Watson. Technical guidance from Alexander L Clarke.

HTML content files created with Microsoft Word. Filtered and converted to US-ASCII with tidy-html5. Using grep, GNU parallel and tidy, execute:

<code>grep -l -r "<meta http-equiv=Content-Type content=\"text/html; charset=windows-1252\">" | parallel tidy -q -m --bare -win1252</code>
