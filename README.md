## Description

This project contains my [Logseq](https://logseq.com/) configuration including
plugins I use. I use this configuration across all my graphs with the
global-config-file feature in logseq version TBD.

## Setup

To try my configuration:
```
# If you have an existing logseq configuration, save it
$ mv ~/.logseq ~/.logseq.bak

# Clone this configuration
$ git clone https://github.com/cldwalker/logseq-config ~/.logseq
```

Alternatively, you can copy over files for more granular usage.

## Plugins

To see the plugins I use, see [plugins.edn](plugins.edn).

## Previously used plugins

These are plugins I've tried. As someone who has built many editor plugins, this is not meant to make anyone feel bad about their hard wrok. This section mostly is a reminder of what plugins I've tried. Sharing in case it helps others.

* https://github.com/hkgnp/logseq-mermaid-plugin - Switched from this to logseq-fenced-code-plus as I prefer my content to stay local.
* https://github.com/hkgnp/logseq-quicktodo-plugin - This focuses just on quickly adding TODOs. I like to quickly capture content that isn't always a TODO.
* https://github.com/haydenull/logseq-plugin-agenda - One of the most beautiful plugins I've tried. Unfortunately the dashboard view isn't useful to me with so many TODOs, even when I filter out with one tag. The calendar view was sometimes nice but didn't use it enough.
* https://github.com/yoyurec/logseq-solarized-extended-theme - Great looking theme. Liked it initially but then it got one too many features and didn't have ways to toggle them off
* https://github.com/pengx17/logseq-plugin-tabs - Was useful initially but then I found it accrued too many tabs while navigating back and forth, which created too much visual clutter
* https://github.com/benjaffe/logseq-reference-styles - Fun plugin to configure emojis for block refs. Find I didn't use it much
* https://github.com/sawhney17/logseq-property-visualizer - Interesting usage of properties but find I didn't need use it much
* https://github.com/hyrijk/logseq-plugin-block-to-page - Didn't work when I tried with latest master
* https://github.com/hkgnp/logseq-chartrender-plugin - Renders bar charts well but didn't use much

## Dev

Be sure to have [babashka](https://github.com/babashka/babashka) installed.

Run `bb tasks` to see available tasks. Currently there are tasks for listing plugins
and writing a `plugins.edn`.

## License
See LICENSE.md

## Additional Links
* https://cs.github.com/?scopeName=All+repos&scope=&q=logseq+path%3Alogseq%2Fconfig.edn - Github search for additional logseq configurations
