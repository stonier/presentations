Presentations
=============

Reveal JS style presentations.

On Github Pages
---------------

These presentations automagically show up on github io.

* [Dec '16 - The Obligatory Introduction (Walkabout)](http://stonier.github.io/presentations/1612-the_obligatory_introduction/index.html)
* [Mar '15 - Intro to Robotics (Seoul Tech Society)](http://stonier.github.io/presentations/1505-seoul_tech_robotics/index.html)
* [Apr '15 - ROS Communications 1.0 & 2.0 (Korean Service Robot Modularity Workshop)](http://stonier.github.io/presentations/1505-ros_communications/index.html#/)

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

Export PDF
----------

* Add the suffix to the URL: http://.../.../index.html?print-pdf
