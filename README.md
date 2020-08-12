# p5js-snippets

<a href="https://praxis.nyc"><img src="https://praxis.nyc/assets/favicons/apple-touch-icon.png" width="60px" height="60px" /></a>

Snippets for your p5js creations. For Sublime and Atom.

> This is a companion for [Praxis Processing](https://praxis.nyc/processing) workshop. Check also [p5js-template](https://github.com/praxisnyc/p5js-template).

> Questions? Comments? Debugging? [Join our Processing group on keybase](https://keybase.io/team/praxis_nyc.processing).

|Group|Functions|Description|
|---|---|---|
|Structure|preload, setup, draw||
|2D shape|point, line, circle, ellipse, square, rect, arc, quad, triangle, beginShape, vertex||
|color|noFill||


## Sublime Text Install

1. Move to snippets folder (change to `2` if previous version)
	- **mac:** `cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages`
	- **linux:** `cd ~/.config/sublime-text-3/Packages`
	- **windows:** `cd "%AppData%\Sublime Text 3\Packages\User"`
2. clone repository `git clone https://github.com/praxisnyc/p5js-snippets.git p5js-snippets`


## Sublime Text Update

1. Move to p5js-snippets folder (change to `2` if previous version)
	- **mac:** `cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/p5js-snippets`
	- **linux:** `cd ~/.config/sublime-text-3/Packages/p5js-snippets`
	- **windows:** `cd "%AppData%\Sublime Text 3\Packages\User\p5js-snippets"`
2. `git pull`

## Atom Install

For atom you need to consolidate snippets after each edit.

1. Move to snippets folder
	- **mac:** `cd /.atom/`
	- **linux:** `pending`
	- **windows:** `pending`
2. create snippets folder: `mkd snippets`
3. clone repository `git clone https://github.com/praxisnyc/p5js-snippets.git p5js-snippets`
4. consolidate (below)

## Atom consolidate


1. Install [modular-snippets](https://atom.io/packages/modular-snippets)
2. hit `command-shift-P` and choose `Modular Snippets: Reload`

> Warning: consolidation *replaces* your existing snippets. If you have snippets already, save a copy of `snippets.cson` on `cd /.atom/snippets/` directory.

## Atom Update

1. Move to p5js-snippets folder
	- **mac:** `cd /.atom/snippets/p5js-snippets`
	- **linux:** `pending`
	- **windows:** `pending`
3. `git pull`
4. consolidate (above)


### Thanks to:

1. [sergiomajluf/p5.js-sublime](https://github.com/sergiomajluf/p5.js-sublime)
2. [node-atomizr](https://www.npmjs.com/package/node-atomizr) for conversion