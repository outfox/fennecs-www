---
title: 3. Tsubasa (Runners)
outline: [2, 3]
order: 3
---

# Nankatsu High School Team's first Practice

::: info :neofox_floof_mug: MMMH, REAL CODE
This **RUNS**! *Playful premises aside*, this is a functioning showcase of **fenn**ecs principles.

Get comfy, grab a cup of ~~Java~~ ~~CoffeeScript~~ ~~Visual J#~~ whatever, and get your paws dirty playing around in the code! It's good fun!

All `.csproj` and `.cs` files are [over here on Github!](https://github.com/outfox/fennecs/blob/main/cookbook) 

:::

### Premise
Japan's least coordinated soccer team tries to score a goal. They're just kids, all running after the ball at once. Only one of them is kind of a good shot, some kid named "Tsubasa"...

We create a team of 11 Entities with `Player`, `Name`, `Talent`, and `Position` [Components](/docs/Components/), and a ball entity with `Ball` and `Position` Components.

In our "game" loop, we get the current position of our ball Entity, and let each player Entity run after it. If they get close enough, they kick the ball to a new position. As soon as the only player with a truthy `Talent` Component scores, the match ends with a golden goal.

### Recipe
::: code-group
<<< ../../../cookbook/Tsubasa.cs{cs:line-numbers} [Implementation]
<<< ../../../cookbook/Tsubasa.output.txt{txt} [Output]
:::
