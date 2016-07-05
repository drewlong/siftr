<h2>Siftr - Webscraping made easier</h2>
<hr />
Siftr is a command line tool that incorporates easily into your programming workflow, making it incredibly easy to track down elements during your testing/scouting phase. 
Usage: <br>
<hr />
siftr -r http://example.com &nbsp; &nbsp; (get raw html/response) <br>
siftr -e http://example.com &nbsp; &nbsp; (harvest email addresses) <br>
siftr -s http://example.com -t a &nbsp; &nbsp; (search mode -- type 'a', attribute 'href')<br>

Options<br>
-r &#09; Raw response <br>
-e &#09; Email harvest mode <br>
-s &#09; Search mode<br>
&nbsp; &nbsp; -t Type of element (a, div, script, etc...)<br>
&nbsp; &nbsp; -a Attribute (href, src, etc...)<br>
&nbsp; &nbsp; -i Includes (string to compare)<br>
-j &nbsp; JSON pretty generate response<br>
