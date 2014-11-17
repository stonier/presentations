presentations
=============

Reveal JS style presentations.

Installation Requirements
-------------------------

* https://github.com/hakimel/reveal.js#markdown

Note - when setting up the devel server, i also needed (got "sh: 1: node: not found" when runnign 'npm install')

```
> sudo apt-get install nodejs nodejs-legacy npm
> sudo npm install -g grunt-cli
```

Template Presentation
---------------------

* Download the latest release from https://github.com/hakimel/reveal.js/releases.
* Point your browser at index.html
* Start hacking.

Speaker Notes
-------------

* In the root of your presentation, run `grunt serve` or `grunt serve --port 8001`
* Point your browser at http://localhost:8000
