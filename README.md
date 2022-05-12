# Lantana
> 💐 An experiment for a better Lua-shell interactive experience in Hilbish.

Lantana is a runner mode plugin for Hilbish which will provide a true hybrid
shell to it. Currently, Hilbish runs input as Lua then attempts as Shell;
Lantana will instead have it in one, providing a concise syntax for interactive
usage.

This is work in progress!

# Setup
Clone to any location Hilbish searches for libraries. Example:  
`git clone https://github.com/TorchedSammy/Lantana ~/.local/share/hilbish/libs/lantana`

Then in your config just add:  
```lua
local lantana = require 'lantana'
lantana.setup()

```
# License
MIT
