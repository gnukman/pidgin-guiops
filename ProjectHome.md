# Pidgin GUIOps plugin #

The Pidgin GUIOps plugin provides more GUI customization options:

  * display buddy status next to buddy name instead of under it in the buddy list
  * hide buddy list and conversation menu's with shortcut key
  * hide buddy list statusbox with shortcut key
  * make conversation window borders thinner
  * hide conversation window status box

The buddy icon is also resized to a smaller size, or can even be hidden.

## Special thanks go to: ##

**craigwharding:** http://code.google.com/p/pidgin-personalbar

I used parts of his code to display my plugin in the Pidgin plugin list.

**piWener:** http://www.anhtt.net

I used parts the code of his enhanced blistops plugin to display status messages next to the buddy names


## Changelog: ##

### 0.5.1 (05/12/2011) ###

  * added cross\_compile.sh and local.mak to the package to compile the plugin for Windows on Debian/Ubuntu

### 0.5 (24/11/2011) ###

  * changed the key combinations from F11 and F12 to CTRL+ALT+M (Menu) and CTRL+ALT+S (Statusbox) to avoid conflicts with other applications
  * added ability to quickly show/hide offline contacts with CTRL+H (inspired by Empathy)
  * added option to hide the buddylist when it is created (inspired by blistops)
  * regrouped the options in an attempt to make them less confusing

### 0.4 (05/11/2009) ###

As the customization options aren't limited to the buddy list anymore, I decided to give the plugin a new name. So renamed "compactbuddylist" to "Pidgin GUIOps"

### 0.3 (08/09/2009) ###

Adds the ability to hide the menubar with F11 and the statusbox with F12.


### 0.2.1 (29/08/2009) ###

Fixes a bug where compactbuddylist crashes Pidgin randomly in Windows.


### 0.2 (25/08/2009) ###

Uses a much simpler way to display the status next to the buddy names (this prevents breaking the original markup that pidgin applies to the names and statuses).


### 0.1 (18/08/2009) ###

First try. Still has some issues.