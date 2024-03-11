## v0.15.7 
- Introducing Cockpit, Project tab is now Organize tab, UI Improvements
- Inside a playground, new tool now take the active request/response when initialized. 
- Added playground's powersearch options
- Added **New ContextMenu System:** [#8](https://github.com/glitchedgitz/grroxy-issues/issues/8), [#11](https://github.com/glitchedgitz/grroxy-issues/issues/11), [#12](https://github.com/glitchedgitz/grroxy-issues/issues/12)
This system can allow any component to quickly add menu item to other components and with minor tweaks should work with plugins/extensions when we add them.
- Added **Tooltips** [#14](https://github.com/glitchedgitz/grroxy-issues/issues/14)
- Fixed: *[BUG] - Character ":" at the end of the domain - Repeater* [#2](https://github.com/glitchedgitz/grroxy-issues/issues/2)
- Performance and stability improvements

## v0.15.6
- Now we can have multiple instance of grroxy using different host and proxy ports. [#18](https://github.com/glitchedgitz/grroxy-issues/issues/18)
  - New flag `--host`, Specify host address for browser app (Default: `127.0.0.1:8090`)
  - New flag `--proxy`, Specify proxy listening on addr (Default: `127.0.0.1:8888`)
  - Auto select next port for host if supplied port is in use.
- Intercept Drop Fixed [#15](https://github.com/glitchedgitz/grroxy-issues/issues/15)
- New command `resume`, Now you can use `grroxy resume` to just start from where you left. [#19](https://github.com/glitchedgitz/grroxy-issues/issues/19)
- Performance and stability improvements
