# Pygments Plugin for [DocPad](https://docpad.org)

<!-- BADGES/ -->

[![Build Status](http://img.shields.io/travis-ci/docpad/docpad-plugin-pygments.png?branch=master)](http://travis-ci.org/docpad/docpad-plugin-pygments "Check this project's build status on TravisCI")
[![NPM version](http://badge.fury.io/js/docpad-plugin-pygments.png)](https://npmjs.org/package/docpad-plugin-pygments "View this project on NPM")
[![Dependency Status](https://david-dm.org/docpad/docpad-plugin-pygments.png?theme=shields.io)](https://david-dm.org/docpad/docpad-plugin-pygments)
[![Development Dependency Status](https://david-dm.org/docpad/docpad-plugin-pygments/dev-status.png?theme=shields.io)](https://david-dm.org/docpad/docpad-plugin-pygments#info=devDependencies)<br/>
[![Gittip donate button](http://img.shields.io/gittip/docpad.png)](https://www.gittip.com/docpad/ "Donate weekly to this project using Gittip")
[![Flattr donate button](http://img.shields.io/flattr/donate.png?color=yellow)](http://flattr.com/thing/344188/balupton-on-Flattr "Donate monthly to this project using Flattr")
[![PayPayl donate button](http://img.shields.io/paypal/donate.png?color=yellow)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=QB8GQPZAH84N6 "Donate once-off to this project using Paypal")
[![BitCoin donate button](http://img.shields.io/bitcoin/donate.png?color=yellow)](https://coinbase.com/checkouts/9ef59f5479eec1d97d63382c9ebcb93a "Donate once-off to this project using BitCoin")
[![Wishlist browse button](http://img.shields.io/wishlist/browse.png?color=yellow)](http://amzn.com/w/2F8TXKSNAFG4V "Buy an item on our wishlist for us")

<!-- /BADGES -->


This plugin enables [Pygments](http://pygments.org/) syntax highlighting for [DocPad](https://docpad.org)

**NOTE: Please try the [HighlightJS](http://docpad.org/plugin/highlightjs) plugin instead, it is faster and more reliable as it is coded in JavaScript, whereas for Pygments we have to start up a new process for each code block which is incredibly slow and sometimes unreliable.**


## Install

1. Install Python Dependency

	If you are on Linux or OSX, generally Python is already installed for you.

	1. Installing Python via Homebrew

		1. [Install Homebrew](http://mxcl.github.com/homebrew/)

		2. Install Python Dependency

			``` bash
			brew install python
			```

		3. Add the Python share directory to your path: `/usr/local/share/python`

		4. Now follow the generic installation instructions


2. Install Pip Dependency

	``` bash
	easy_install pip
	```


3. Install Pygments Dependency

	```
	pip install pygments
	```

4. Include your favourite [Pygments Stylesheet](https://github.com/richleland/pygments-css) into your website

5. Install this Plugin

	```
	docpad install pygments
	```



## Usage

- With Github Flavored Markdown

		## Coffeescript with markdown backticks:

		``` coffeescript
		alert 'hello'
		```

		## Guessing with markdown backticks:

		```
		alert 'hello'
		```

		## Guessing with markdown standard:

			alert 'hello'


- With HTML

	``` html
	<h2>Coffeescript with html:</h2>

	<code class="highlight" lang="coffeescript">
		alert 'hello'
	</code>


	<h2>Guessing with html:</h2>

	<code class="highlight">
		alert 'hello'
	</code>
	```


## Deployment
If you are wanting to generate your DocPad website on your hosting provider, rather than deploying a static site. You will have to install pygments on the host as well. You're probably better off using the [HighlightJS](http://docpad.org/plugin/highlightjs) plugin instead.


<!-- HISTORY/ -->

## History
[Discover the change history by heading on over to the `HISTORY.md` file.](https://github.com/docpad/docpad-plugin-pygments/blob/master/HISTORY.md#files)

<!-- /HISTORY -->


<!-- CONTRIBUTE/ -->

## Contribute

[Discover how you can contribute by heading on over to the `CONTRIBUTING.md` file.](https://github.com/docpad/docpad-plugin-pygments/blob/master/CONTRIBUTING.md#files)

<!-- /CONTRIBUTE -->


<!-- BACKERS/ -->

## Backers

### Maintainers

These amazing people are maintaining this project:

- Benjamin Lupton <b@lupton.cc> (https://github.com/balupton)

### Sponsors

No sponsors yet! Will you be the first?

[![Gittip donate button](http://img.shields.io/gittip/docpad.png)](https://www.gittip.com/docpad/ "Donate weekly to this project using Gittip")
[![Flattr donate button](http://img.shields.io/flattr/donate.png?color=yellow)](http://flattr.com/thing/344188/balupton-on-Flattr "Donate monthly to this project using Flattr")
[![PayPayl donate button](http://img.shields.io/paypal/donate.png?color=yellow)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=QB8GQPZAH84N6 "Donate once-off to this project using Paypal")
[![BitCoin donate button](http://img.shields.io/bitcoin/donate.png?color=yellow)](https://coinbase.com/checkouts/9ef59f5479eec1d97d63382c9ebcb93a "Donate once-off to this project using BitCoin")
[![Wishlist browse button](http://img.shields.io/wishlist/browse.png?color=yellow)](http://amzn.com/w/2F8TXKSNAFG4V "Buy an item on our wishlist for us")

### Contributors

These amazing people have contributed code to this project:

- [Benjamin Lupton](https://github.com/balupton) <b@lupton.cc> — [view contributions](https://github.com/docpad/docpad-plugin-pygments/commits?author=balupton)

[Become a contributor!](https://github.com/docpad/docpad-plugin-pygments/blob/master/CONTRIBUTING.md#files)

<!-- /BACKERS -->


<!-- LICENSE/ -->

## License

Licensed under the incredibly [permissive](http://en.wikipedia.org/wiki/Permissive_free_software_licence) [MIT license](http://creativecommons.org/licenses/MIT/)

Copyright &copy; 2012+ Bevry Pty Ltd <us@bevry.me> (http://bevry.me)

<!-- /LICENSE -->


