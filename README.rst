fork of ngx-fancy-index (which itself is a module that creates a nicer index page for directories without an index.html and allows one to use their own header/footer html (included via a subrequest).

This is modified in this code so that a module does not create an HTML table, but a simple JS object in a <script> tag and it is the custom header/footer that can use that data via html.

