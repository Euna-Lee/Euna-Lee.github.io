---
layout: page
title: Super Food Chain
description: An action snake-like game where you assemble a chain of flavorful allies in a battle against enemies for culinary domination.
img: assets/img/SuperFoodChain.png
importance: 1
category: work
---

A link to downloading and finding more about the game is here: [Super Food Chain](https://ed-deeee.itch.io/super-food-chain).

{% include figure.liquid loading="eager" path="assets/img/SuperFoodChain.png" title="SuperFoodChain" class="img-fluid rounded z-depth-1" %}

| | |
|---|---|
| **Role** | Programmer (physics collisions and companion logic) |
| **Team** | 8 programmers and artists |
| **Timeline** | Jan. 2025 – May 2025 |
| **Tech** | Java, LibGDX, Box2D |

## Overview

You play as an assortment of fruits fighting through a kitchen full of hungry enemies. Defeat pests, collect the coins they drop, and spend them to recruit more ingredients into a growing snake-like chain to defeat the boss(es)! A bigger chain has more stacked effects, but it's also harder to steer and even easier to lose. Manage your resources and claim victory over the kitchen!

## Gameplay

- **15 levels** with escalating difficulty
- **3 bosses**, each with a unique telegraphed attack pattern: the Rat, the Chopsticks, and Chef
- **5 companions** with distinct abilities: Strawberry, Pineapple, Garlic, Avocado, and Blue Raspberry
- A **journal** that fills in as you discover companions and enemies, and a **level select** that unlocks as you progress

## Contributions

- Built the collision and physics systems with LibGDX's Box2D library
- Debugged complex physics interactions across tightly coupled feature code
- Designed and implemented each companion and their unique ability
- Playtested and rebalanced difficulty based on feedback, tuning the game for its target audience of 10-15 year olds

## Challenges

**Working across programmers and artists.** This was my first large-scale game with a mixed team, and I hadn't anticipated how easily programmers and artists could end up with different visions of what was needed. Because features were so intertwined, we also had to explain our code to each other constantly, even while splitting up the work.

**Learning Box2D.** I owned collisions, which meant learning Box2D from scratch. It was confusing at first and caused disruptive bugs that took hours to track down, but getting it right taught me how to debug systematically.

**Balancing with a small playtest pool.** Our testers were either too good or too bad, so feedback was hard to read. We ultimately made the game harder than we first intended, which had to be simplified further to fit our showcase audience of 10-15 year olds.

## Gallery

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/SuperFoodChain_1.png" title="SuperFoodChain" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/SuperFoodChain_3.png" title="SuperFoodChain" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/SuperFoodChain_2.png" title="SuperFoodChain" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Gameplay against each of the three bosses: The Rat, Chopsticks, and Chef.
</div>

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/SuperFoodChain_4.png" title="SuperFoodChain" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/SuperFoodChain_5.png" title="SuperFoodChain" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Left: the journal, which updates as you meet new companions and enemies. Right: level select, which unlocks the next level after you beat the previous one.
</div>
