# custom-paper-patches
This repo contains my custom patches for PaperMC

Custom Features
------
* Faster turtle egg hatch time
* Maxed book level for villagers
* Cheapest books for villagers
* Faster water/snow cauldrons, but mainly snow
* Instant-minable deepslate (No sound for the client though :\)
* Better trident spawn rate
* Instant-minable basalt (No sound for the client though :\)
* Faster Goat Attacks
* More slime spawns

How to use
------
1- Clone or pull repo from [PaperMC](https://github.com/PaperMC/Paper) using git and an IDE (ex IntelliJ Idea).
2- Download patches found on the correct branch corresponding to your minecraft version. Move all .patch files to project's root `patches/server/`
3- Clone this repo, run `./gradlew applyPatches`, then `./gradlew createReobfBundlerJar` from your terminal. You can find the compiled jar in the project root's `build/libs` directory.
