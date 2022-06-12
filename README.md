# DynmapBlockScan-Data
The is a child repo of [DynmapBlockScan](https://github.com/webbukkit/DynmapBlockScan). This repo contains the generated files from the Dynmap Blockscan mod **_only_**.

You can download DynmapBlockScan from mikeprimm's build server http://mikeprimm.com/dynmap/builds/DynmapBlockScan/

I will try my best to keep the [wiki](https://github.com/FedUpWith-Tech/DynmapBlockScan-Data/wiki) up-to-date with the currently available models.

## How to use this repo?

### Adding the modded textures to your server
  1. Download the model files for each of your installed mods for the applicable versions
  2. Place the downloaded files directly into the `dynmap/renderdata/` folder (note: don't place them in the modsupport folder) 
  3. Restart your server

### Contributing
This repo is ENTIRELY community driven, I don't have the time to go through and generate all these files for every mod and every mod version. As such, if you have generated model files for a given mod and would like to share you can upload to this repo via a [PR](https://github.com/FedUpWith-Tech/DynmapBlockScan-Data/pulls).

For visual clarity the repo is structured as follows

```
/                # The root folder of the repo, has license, README.md, and the /models/ folder

/models/         # This folder contains the model data for each mod in their respective subfolders

/models/<mod>/<version>/   # This is the mod folder which contains both the texture and block definitions files. If there are multiple versions available, they will be in versioned folders. 
```

### Issues?
Any issues pertaining to generating files should be opened on the [Dynmap Blockscan Issue Tracker](https://github.com/webbukkit/DynmapBlockScan/issues) **NOT HERE.** The only issues opened here should be related to: incorrectly generated model data, outdated/incorrectly dated model data, or for outdated information specifically on this repo. All other issues will be closed without response.
