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
Jack is web based and requires either a web server to serve its HTML and JS content or can be run locally. Typically something like Apache will suffice but anything that is able to serve HTML content to a browser will do. Simply download Jack's contents and open "index.html" with your browser locally and Jack is ready to go. Alternatively if you prefer the older UI for Jack, open "oldIndex.html" with your browser for the old UI.

Notes
====
Depending on your setup, you may need to configure your browser to allow Jack to load resources that are being served via encrypted channels.
