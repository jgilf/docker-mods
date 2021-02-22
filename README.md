# Youtube - Docker mod for plex

This mod adds [YouTube-Agent](https://github.com/ZeroQI/YouTube-Agent.bundle) to Plex, to be downloaded/updated during container start.

In plex docker arguments, set an environment variable `DOCKER_MODS=https://github.com/jgilf/docker-mods:youtube`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/mods:plex-absolute-hama|linuxserver/mods:plex-mod2`
