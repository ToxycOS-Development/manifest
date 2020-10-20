ToxycOS
==========

# Build guide

Prior to building, you will need basic knowledge of [Git](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet).

### Requirements
- Around 100G disk space.
- A computer with at least 16GB RAM running Linux (recommended) or MacOS.
- Build environment [setup](https://github.com/akhilnarang/scripts). 

### Instructions
1. Run the following commands to sync source

```
repo init -u https://github.com/ToxycOS/manifest -b r4.x
```
2. To sync source, enter

```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

3. Once the source is downloaded/synced, prepare your device trees, dependencies and start the build.

### Compilation Help
To get help with build errors, please visit [**Android Building Help**](https://t.me/AndroidBuildingHelp).

