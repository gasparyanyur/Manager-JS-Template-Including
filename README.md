Include HTML Template By URL hash

Usable:
Manager.Route('hash-in-url','template-url','template-name');

<tag content-view='template-name'></tag>

Example:
When:
----------------
location.hash : '#abc',
templateUrl : 'templates/abc.html',
templateName: 'content'

Then:
----------------

In your Script you must have
Manager.Route('abc','templates/abc.html','content') 

In your Html you must have
< tagname content-view="content" > </ tagname >
