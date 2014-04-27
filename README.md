(This is a fork of SublimeCompletionFramerjs that supports Shortcuts for Framer)

SublimeCompletionFramerjs
=========================

This plugin adds Framer.js autocompletion for:

1. The Framer docs
2. Your exported views

![View of autocomplete dropdown](http://cl.ly/image/2o043809262v/framercomplete.png "Completion dropdown")

##Installation
1. Place in `~/Library/Application Support/Sublime Text 2/Packages/SublimeCompletionFramerjs`

##User specific settings
To make user specific settings, copy the contents of FramerCompletion.sublime-settings and open Sublime Text 2. Go to: `Sublime Text 2 > Preferences > Package Settings > Framer Completion > Settings - User` and paste the contents there.

###dotNotation
Change to `true` if you want to use dot notation for the PSD autocomplete

Set to `false` if you prefer bracket notation.

##Stuff to do
* Settings for Coffescript
* Testing/optimization (threading?)