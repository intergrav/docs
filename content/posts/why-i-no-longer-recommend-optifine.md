+++
title = "Why I no longer recommend OptiFine"
date = "2023-03-16T23:54:37-04:00"
author = "intergrav"
cover = "/img/why-i-no-longer-recommend-optifine.png"
tags = ["minecraft", "optimization"]
keywords = ["OptiFine", "minecraft", "optimization", "intergrav", "Adrenaline", "Additive"]
description = "There are many reasons not to use OptiFine today. This in-depth post shows you why and how you can move away."
showFullContent = false
readingTime = false
hideComments = false
color = "green"
+++

> In this post, some knowledge was collected from myself, [triphora](https://empireminecraft.com/threads/psa-guide-why-you-shouldnt-use-optifine-1-16.84590/), and [LambdAurora](https://lambdaurora.dev/optifine_alternatives/). I recommend looking at what they said as well!

In the past, [OptiFine](https://www.optifine.net/) was *the* way to get much improved performance and many extra features in Minecraft. Nowadays, in more recent Minecraft versions, this is no longer the case.

## Why not?

OptiFine acts as a "modpack inside a mod," which makes it impossible to disable certain features that are unwanted or incompatible with other mods. You get essentially forced to remove the incompatible mod or OptiFine.

It's closed-source. This makes it almost impossible for both users and developers to understand what the mod is doing. This may make it much more challenging for developers to keep their mods compatible with OptiFine.

OptiFine isn't natively supported on [Quilt](https://quiltmc.org) or [Fabric](https://fabricmc.net). It requires a compatibility layer such as [OptiFabric](https://www.curseforge.com/minecraft/mc-mods/optifabric) to run on those loaders, which even then, [doesn't always work](https://github.com/modmuss50/OptiFabric/issues/242).

OptiFine usually takes a *loooooong* time to update to newer MC versions, whereas current alternatives typically update much faster. At the time of writing this, it seems like OptiFine for 1.19.3 is *still* in a pre-release state even though 1.19.3 came out back in December!

OptiFine is not available on sites such as [Modrinth](https://modrinth.com/) or [CurseForge](https://beta.curseforge.com/), which prevents it from being in any modpacks.

While you may think switching to Sodium and Co would be an overwhelming task, it's actually quite easy to get used to. I know this as I did, in fact, use OptiFine for many years before I switched, and it was generally an easy thing to do.

## So, what should I use instead?

Many alternatives have risen in popularity ever since the [Sodium](https://modrinth.com/mod/sodium) mod had started development, a complete rewrite to Minecraft's rendering engine. It's much more optimized than OptiFine, supports modern loaders such as Fabric and Quilt, and is best of all - open-source!

For convenience, I recommend using a different launcher than Mojang's default, such as Prism Launcher. The main reason is so that you can easily manage your mods and modpacks, such as installing or updating them within the launcher. See my [other blog post](../stop-using-mojangs-minecraft-launcher) for more information.

> If you don't want to read this whole post, perhaps try out one of my modpacks! I have two that I actively maintain that you might want to try - these being [Adrenaline](https://modrinth.com/modpack/adrenaline), a bare-bones and lightweight performance layer, and [Additive](https://modrinth.com/modpack/additive), which is built on top of Adrenaline with extra mods for OptiFine parity. *For other alternatives, see [Fabulously](https://modrinth.com/modpack/fabulously-optimized) and [Simply](https://modrinth.com/modpack/sop) Optimized.* You can install these modpacks using a third-party launcher according to [Modrinth's documentation](https://docs.modrinth.com/docs/modpacks/playing_modpacks/).

For performance benefits, I recommend these mods along with Sodium. If you don't want to install all of them, the main optimizations are contained in the first four mods. *Not every performance mod is mentioned here, if you want all of the ones I recommend, see my [modpack](https://modrinth.com/modpack/adrenaline).*

- [Lithium](https://modrinth.com/mod/lithium) for mostly server-side optimizations
- [Starlight](https://modrinth.com/mod/starlight) is a rewrite to Minecraft's lighting engine
- [FerriteCore](https://modrinth.com/mod/ferrite-core) optimizes memory usage in many different ways
- [EntityCulling](https://modrinth.com/mod/entityculling) skips rendering entities that shouldn't be seen
- [LazyDFU](https://modrinth.com/mod/lazydfu) makes unnecessary initialization work only performed when required (no longer needed on ≥1.19.4)
- [More Culling](https://modrinth.com/mod/moreculling) extra culling optimizations
- [ImmediatelyFast](https://modrinth.com/mod/immediatelyfast) improves immediate mode rendering performance

## What about shaders or other features?

For shaders, you can install the [Iris](https://modrinth.com/mod/iris) mod. It supports most OptiFine shaders, with growing support for even more each update.

For zoom, you can install a mod like [Zoomify](https://modrinth.com/mod/zoomify), [Logical Zoom](https://modrinth.com/mod/logical-zoom), or [Ok Zoomer](https://modrinth.com/mod/ok-zoomer) if you're using Quilt.

For better grass, you can use LambdAurora's [LambdaBetterGrass](https://modrinth.com/mod/lambdabettergrass), which is Quilt only as of 1.19.3, or robotkoer's [Fast Better Grass](https://modrinth.com/resourcepack/fast-better-grass) if you don't want to use a mod and you only want the fast option.

For the other features that OptiFine provides, see LambdAurora's list of alternatives [here](https://lambdaurora.dev/optifine_alternatives/).

## Conclusion

Thanks for reading! I hope this helps you better understand why you shouldn't use OptiFine in modern versions of Minecraft.

![Image](/img/iris1.png)