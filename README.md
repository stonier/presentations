# Presentations

## Reveal.js

The latest I've made with [reveal.js v3.3.0](https://github.com/hakimel/reveal.js/releases/tag/3.3.0), see the 3.3.0 [README](https://github.com/hakimel/reveal.js/blob/3.3.0/README.md) for specific instructions about this version.

## On Github Pages

These presentations automagically show up on github io.

* [Dec '16 - The Obligatory Introduction (Walkabout)](http://stonier.github.io/presentations/1612-the_obligatory_introduction/index.html)
* [Mar '15 - Intro to Robotics (Seoul Tech Society)](http://stonier.github.io/presentations/1505-seoul_tech_robotics/index.html)
* [Apr '15 - ROS Communications 1.0 & 2.0 (Korean Service Robot Modularity Workshop)](http://stonier.github.io/presentations/1505-ros_communications/index.html#/)

## Running

### Speaker Notes

Hit 's' in the middle of the presentation. A secondary remote controlling window will appear.

## Creating

### Download

* Download the latest release from https://github.com/hakimel/reveal.js/releases
  * OR just copy it from the latest one here
* Point your browser at index.html
* Start hacking.

### Export PDF

Suffix the string `?print-pdf` to the end of the url. e.g. 

```
file:///home/snorri/jobs/007_presentations/interviews/1612-introduction/index.html?print-pdf
```

Then go to print and make sure:

* Layout  : landscape
* Margins : none
* Options : background graphics is true

### Setting up a Server

* https://github.com/hakimel/reveal.js#markdown

Note - when setting up the devel server, i also needed (got "sh: 1: node: not found" when runnign 'npm install')

```
> sudo apt-get install nodejs nodejs-legacy npm
> sudo npm install -g grunt-cli
```

* In the root of your presentation, run `grunt serve` or `grunt serve --port 8001`
* Point your browser at http://localhost:8000

