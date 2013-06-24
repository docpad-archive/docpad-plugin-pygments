# Pygments Plugin for [DocPad](https://docpad.org)

[![Build Status](https://secure.travis-ci.org/docpad/docpad-plugin-pygments.png?branch=master)](http://travis-ci.org/docpad/docpad-plugin-pygments "Check this project's build status on TravisCI")
[![NPM version](https://badge.fury.io/js/docpad-plugin-pygments.png)](https://npmjs.org/package/docpad-plugin-pygments "View this project on NPM")
[![Flattr donate button](https://raw.github.com/balupton/flattr-buttons/master/badge-89x18.gif)](http://flattr.com/thing/344188/balupton-on-Flattr "Donate monthly to this project using Flattr")
[![PayPayl donate button](https://www.paypalobjects.com/en_AU/i/btn/btn_donate_SM.gif)](https://www.paypal.com/au/cgi-bin/webscr?cmd=_flow&SESSION=IHj3DG3oy_N9A9ZDIUnPksOi59v0i-EWDTunfmDrmU38Tuohg_xQTx0xcjq&dispatch=5885d80a13c0db1f8e263663d3faee8d14f86393d55a810282b64afed84968ec "Donate once-off to this project using Paypal")

This plugin enables [Pygments](http://pygments.org/) syntax highlighting for [DocPad](https://docpad.org)

**NOTE: Please try the [HighlightJS](http://docpad.org/plugin/highlightjs) plugin instead, it is faster and more reliable as it is coded in JavaScript, whereas for Pygments we have to start up a new process for each code block which is incredibly slow and sometimes unreliable.**


## Install

1. Install Python

	If you are on Linux or OSX, generally Python is already installed for you.

	1. Installing Python via Homebrew

		1. [Install Homebrew](http://mxcl.github.com/homebrew/)

		2. Install Python

			``` bash
			brew install python
			```

		3. Add the Python share directory to your path: `/usr/local/share/python`

		4. Now follow the generic installation instructions


2. Install Pip

	``` bash
	easy_install pip
	```


3. Install Pygments

	```
	pip install pygments
	```

4. Include your favourite [Pygments Stylesheet](https://github.com/richleland/pygments-css) into your website



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


## History
[You can discover the history inside the `History.md` file](https://github.com/bevry/docpad-plugin-ghpages/blob/master/History.md#files)


## Contributing
[You can discover the contributing instructions inside the `Contributing.md` file](https://github.com/bevry/docpad-plugin-ghpages/blob/master/Contributing.md#files)


## License
Licensed under the incredibly [permissive](http://en.wikipedia.org/wiki/Permissive_free_software_licence) [MIT License](http://creativecommons.org/licenses/MIT/)
<br/>Copyright &copy; 2012+ [Bevry Pty Ltd](http://bevry.me) <us@bevry.me>
