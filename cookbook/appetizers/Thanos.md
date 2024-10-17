---
title: 5. Thanos (Filters)
outline: [2, 3]
order: 5
---

# How to Snap ~25% of the World away

::: info :neofox_floof_mug: MMMH, REAL CODE
This **RUNS**! *Playful premises aside*, this is a functioning showcase of **fenn**ecs principles.

Get comfy, grab a cup of ~~Java~~ ~~CoffeeScript~~ ~~Visual J#~~ whatever, and get your paws dirty playing around in the code! It's good fun!

All `.csproj` and `.cs` files are [over here on Github!](https://github.com/outfox/fennecs/blob/main/cookbook) 

:::

### Premise
Hey there, mighty Titan (who flunked probabilitics)! Ready to bring perfect balance to your `fennecs.World`?

In this example, we'll show you how to use fennecs' `Query.Subset` and `Query.Exclude` methods to ~~snap away~~ `Despawn` half the entities in your world. 

::: details SPOILER
Well... randomly half of randomly half!
:::
 
### How it works
First we create a bunch of entities, give some of them a "Lucky" and some of them a "Unlucky" component, then we filter our Query to target the Unlucky and move the Lucky ones out of harm's way.

Finally, we unleash the power of the ~~Infinity Gauntlet~~ `Stream<>.Despawn()` to bring an awkward balance to the Universe. 

I'm sure you already see that nothing can go wrong! Let's get snapping!


::: code-group
<<< ../../../cookbook/Thanos.cs {cs:line-numbers} [Implementation]
<<< ../../../cookbook/Thanos.output.txt{txt} [Output]
:::
