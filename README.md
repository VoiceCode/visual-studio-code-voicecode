# Visual Studio Code / VoiceCode Integration Package

This is a [Visual Studio Code](https://code.visualstudio.com/) package/plugin that lets [VoiceCode](http://voicecode.io) control Visual Studio Code

This integration is needed because many VoiceCode voice commands are more sophisticated than simply pressing keys or clicking the mouse. For example, a command that *selects the next curly brace*, or a command that *extends the current selection(s) forward until the next comma*, etc.

## Setup

### Connecting

#### Automatically On Startup

#### Manually

### Triggering existing VSC commands

In VoiceCode simply do:

```coffeescript
@runVscCommand "trigger", "tree-view:add-file"
```
