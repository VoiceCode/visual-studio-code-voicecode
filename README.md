# Visual Studio Code / VoiceCode Integration Package

This package integrates VoiceCode http://voicecode.io with Visual Studio Code code.visualstudio.com

This integration is needed because many VoiceCode voice commands are more sophisticated than simply pressing keys. For example, a command like "select next curly brace".

The integration is handled via unix sockets for communicating between Visual Studio Code (VSC) and VoiceCode.

## Setup

### Connecting

#### Automatically On Startup

#### Manually

### Triggering existing VSC commands

In VoiceCode simply do:

```coffeescript
@runVscCommand "trigger", "tree-view:add-file"
```
