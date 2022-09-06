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

* https://github.com/hkgnp/logseq-mermaid-plugin - Switched from this to logseq-fenced-code-plus as I prefer my content to ping an external server.
* https://github.com/hkgnp/logseq-quicktodo-plugin - This focuses just on quickly adding TODOs. I like to quickly capture content that isn't always a TODO.
* TODO - Add other plugins I've tried

## Dev

Be sure to have [babashka](https://github.com/babashka/babashka) installed.

Run `bb tasks` to see available tasks. Currently there are tasks for listing plugins
and writing a `plugins.edn`.

## License
See LICENSE.md

## Additional Links
* https://cs.github.com/?scopeName=All+repos&scope=&q=logseq+path%3Alogseq%2Fconfig.edn - Github search for additional logseq configurations
