## Description

This project contains my [Logseq](https://logseq.com/) configuration including
plugins. I use this configuration across all my graphs with the [global
configuration feature](https://docs.logseq.com/#/page/Global%20configuration).

## Setup

To try my configuration:
```
# If you have an existing logseq config directory, back it up
$ mv ~/.logseq/config ~/.logseq/config.bak

# Clone this configuration
$ git clone https://github.com/cldwalker/logseq-config .

# Copy over my config
$ cp -R config ~/.logseq/config
```

Alternatively, you can copy over specific files for more granular usage.

## Plugins

The list of plugins I currently use are in [this file](config/plugins.edn). To
try my plugins, see instructions under the `Functionality` section in
https://docs.logseq.com/#/page/plugins.edn.

## Convert your local graph config to a global one

If you would like to convert your existing Logseq config to a global config and
possibly share with others via git:

1. In a shell: `cd ~/.logseq && git init`.
2. Copy this repository's .gitignore into `~/.logseq`.
3. Copy the `logseq/config.edn` from your most active graph to
   `~/.logseq/config/config.edn`. Be sure to only keep config options you want
   applied across all graphs. Remove the global config options from your local
   config files.
4. Save your config: `git add . && git commit -m "Initial commit"`

## Previously used plugins

These are plugins I've tried. As someone who has built many editor plugins, this
is not meant to make anyone feel bad about their hard work. This section is to
share experiences in case it helps others.

* https://github.com/hkgnp/logseq-mermaid-plugin - Switched from this to logseq-fenced-code-plus as I prefer my content to stay local.
* https://github.com/hkgnp/logseq-quicktodo-plugin - This focuses just on quickly adding TODOs. I like to quickly capture content that isn't always a TODO.
* https://github.com/haydenull/logseq-plugin-agenda - One of the most beautiful plugins I've tried. Unfortunately the dashboard view isn't useful to me with so many TODOs, even when I filter out with one tag. The calendar view was sometimes nice but didn't use it enough.
* https://github.com/yoyurec/logseq-awesome-styler - Great looking theme. Liked it initially but then it got one too many features and didn't have ways to toggle them off
* https://github.com/pengx17/logseq-plugin-tabs - Was useful initially but then I found it accrued too many tabs while navigating back and forth, which created too much visual clutter
* https://github.com/benjaffe/logseq-reference-styles - Fun plugin to configure emojis for block refs. Found I didn't use it much
* https://github.com/sawhney17/logseq-property-visualizer - Interesting usage of properties but found I didn't use it much
* https://github.com/hyrijk/logseq-plugin-block-to-page - Didn't work when I tried with latest master
* https://github.com/hkgnp/logseq-chartrender-plugin - Renders bar charts well but didn't use much
* https://github.com/hkgnp/logseq-datenlp-plugin - Interesting plugin for writing dates as natural language. Didn't use it much though

## Dev

Be sure to have [babashka](https://github.com/babashka/babashka) installed.

Run `bb tasks` to see available tasks. Currently there are tasks for listing plugins.

## License
See LICENSE.md

## Additional Links
* https://github.com/search?q=logseq+path%3Aconfig%2Fconfig.edn&ref=opensearch&type=code - Github search for additional global configurations
* https://github.com/search?q=logseq+path%3Alogseq%2Fconfig.edn&ref=opensearch&type=code - Github search for additional repo/graph configurations
