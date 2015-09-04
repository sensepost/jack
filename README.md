jack
====

By Chris Le Roy (@brompwnie) chris@sensepost.com

Overview
=====
Jack is a web based ClickJacking PoC development assistance tool.

Jack makes use of static HTML and JavaScript. 

Contents
====
Jack Contains:
* resources/**
* index.html
* sandbox.html
* oldIndex.html

Running
====
Jack is web based and requires a web server to serve its HTML and JS content. Typically something like Apache will suffice but anything that is able to serve HTML content to a browser will do. Place the two folders, resources and static into a "www" type like directory and request the HTML file "index.html" to start using Jack.

Notes
====
Depending on your setup, you may need to configure your browser to allow Jack to load resources that are being served via encrypted channels.
