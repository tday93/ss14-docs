# Cooking and Bartending System

| Designers | Implemented | GitHub Links |
|---|---|---|
| tday93 | :x: No | TBD |

## Overview

This document proposes an updated cooking and bartending system. Specifically it will propose am updated set of base cooking
and bartending mechanics, a system for food and drinks to give beneficial status effects to the consumer, and outline
future opportunites for cooking and bartending to be expanded beyond this proposal.


## Background

Cooking as it currently exists involves an extremely limited number of operations, end outputs which are
distinguished almost entirely by the sprite that they use, and recipes which are extremely static and leave little
room for player creativity.

Improvements to this system will therefore need to accomplish the following:

1. Involve a more interesting set of cooking and mixology mechanics.
2. Allow for the creation of food and drinks which are mechanically and not just cosmetically distinct.
3. Let the Chef or Bartender expand beyond a fixed set of recipes, and mechanically influence the end result by doing
   so.


## Cooking and Mixology Mechanics

The mechanics of cooking food and mixing drinks should be intuitive and diagetic. Food and drink items should be
prepared in-game via processes that are analagous to how those items are prepared in real life.

Additionally, to better match how real-world kitchens operate, these mechanics should allow bulk operations wherever
possible. A chef serving a station of 80 people would not individually prepare 80 single bowls of soup, each from
scratch. They would make 80 bowls worth of soup in a single batch, and split it in to 80 portions.

To that end, this proposal recommends the following set of baseline cooking and bartending mechanics.

### Proposed Base Mechanics

> Note: Several of these exist in-game already, either fully or in-part. They are listed here to allow a complete list
> of base mechanics.

* Chopping / Slicing / Dicing: Using a knife on an ingredient or food that has been placed within the world.
* Rolling: Using a rolling pin on an ingredient that has been placed within the world.
* Topping: Using an ingredient or container filled with a single ingrdient on another that has been placed within the world.
* Mixing / Stirring: Using a mixing implement on a container filled with ingredients that has been placed within the world.
* Sauteeing / Boiling / Grilling: Placing an ingredient or container filled with ingredients on to a stovetop or range within the
    world, until a visual indicator shows that it is "done".
* Baking / Microwaving: Placing a single ingredient or container of ingredients within an oven or microwave for a fixed
    amount of time. Note that this operation would operate on each ingredient or container thereof indivudually. Flat
    dough and four tomatoes will no longer magically voltron into a pizza.

* Shaking: Using a mixer filled with ingredients and ice.
* Pouring: Transfering liquid ingredients from one container to another.
* Garnishing: Using a prepared ingredient or decoration on a drink container that has been placed within the world.


### Example Cooking Processes


#### Cooking a pizza.

1. The chef prepares dough by transferring flour and water in to a bowl or container, and then mixing that bowl with a
   spoon or whisk.
2. The chef flattens that dough with a rolling pin, to create flattened dough.
3. The chef places a number of tomatoes within a pot, then places it on the stove until it turns in to tomato sauce.
4. The chef tops the flattened dough with tomato sauce.
4. The chef slices a cheese wedge from a wheel of cheese.
5. The chef tops the the flattened dough and tomato sauce with the cheese.
6. (The chef adds any additional toppings they would like)
7. The chef places the uncooked pizza into an oven for a fixed amount of time, and retrieves a pizza.
8. The chef slices the pizza and serves up the slices.

#### Making cheese burgers in bulk.

1. The chef prepares a large batch of dough - mixing a large amount of flour and water in a bowl.
2. The chef slices a large number of pieces of dough off of the dough they have prepared, and places them all in the
   oven at once, setting it to cook for a fixed amount of time.
3. The chef prepares a number of burger patties by chopping meat.
4. The chef places all of the prepared patties on to a range/grill to grill.
5. While the patties are cooking, the chef takes the finished buns out of the oven, and slices them in to bottom bun /
   top bun pairs.
6. The chef tops the bottom buns with the now-cooked burger patties.
7. The chef cuts a number of cheese slices from a edge of cheese, and tops the bottom bun and cooked patty with them.
8. The chef tops the bottom bun, cooked patty, and cheese slice with the top buns.
9. The chef serves a number of burgers all at once.


> WIP AND/OR NOTES BELOW HERE

## Food and Drink Effects

In order to distinguish foods and drinks from one-another mechanically, each food or drink item must present a
mechanically distinguishable effect. While the scope of the possible effects is immense, this proposal recommends the
following general guidelines for designing food or drink sourced status effects.

<<<<<<< HEAD
1. They should be desirable by and obvious to players, ideally for reasons beyond powergaming.
   * Mathematical advantages are fine, but where possible look for more interesting effects.
2. They should avoid causing issues of balance.
   * No stun immunity burgers as an example.
3. They should have minimal overlap with effects available from chemistry or medical treatment.
   * No healing, no direct copies of effects obtained from drugs.
4. Where possible, they should benefit the players work on the station.
=======
* Possible effects should:
   * Be generally beneficial
   * Not cause gameplay problems, no burger of stun resistance
   * Be desirable by players

>>>>>>> 0ac25e2748c4c7ae16588f4b27dcebb5c5409aa0


Guideline one is obvious - more desirable effects means more desriable foods and drinks. Additionally, while
mathematical advantages absolutely do have a place, they also have fundamental issues of player visibility, or can be
sources of major conflict with guideline number two. An effect gained from a food or drink should be immediate,
unmistakeable, and not a detriment to the player.

The second guideline is simply pre-emptive headache prevention. If another system expects players to have certain qualities or
statistics as part of that systems balance, food or drink should not allow a player to trivialize that balance.

Food and drinks should not be drugs by other names. Furthermore, since gaining beneficial physical effects from food and drinks
beyond satiation has absolutely no basis in reality, there is an opportunity to get silly with them. Lean in to the
silliness.

Finally, pushing for effects that benefit a player's work on the station both encourages cooperative behavior from the
consumer, and establishes a feedback loop between cooking / bartending and the other station roles. This will also mean
that players have a reason to prefer different foods/drinks depending on the shift and the role they are playing, and
chefs and bartenders will have reasons to cook and mix a wide variety of food.


### Example Effects

The following examples present possible effects that follow the above principles.

1. Heavy Hauler - You are slowed less when pulling inanimate objects.
   * Super Heavy Hauler - You are slowed less when pulling inanimate objects - and can pull an item per hand.

2. Yearning for the mines - You drop more ore when mining.

3. Healer's Spirit - When examining another players health you can see the exact amount of their highest damage type.

4. Barber's Nightmare - Your hair changes randomly every few seconds.

5. Untethered - You are no longer affected by gravity generators.

6. Professional Jerry-Rigger - You can craft cable types in to each other.

7. Homeostatic Hero - Your body remains a reasonable temperature - even in extreme heat or cold.

8. Green Thumb - You have a chance to gain additional products from plants you harvest.



## Dynamic Food and Drink Items

There are two major considerations with regards to dynamic food and drink items.

1. How can food and drink items be created dynamically, without recipe and sprite bloat?
2. How can the fact that they can be dynamically assmbled be made mechanically relevant?


### Dynamic Assembly and Sprites

> THIS WHOLE SECTION NEEDS WORK
Dynamic assembly relies on recipes defining both required and optional components. The required ingredients define the
identity of the food, drink, or ingredient created, and the optional ingredients affect the mechanical outcome,
altering or improving the effect offered by the final food or drink.

The exact process by which dynamic foods are triggered to form from an assemblage of ingredients depends on the specific
process used to create them. A dynamic sandwich would be formed by placing the second piece of bread, a burger by the
top bun, a pizza by baking it.

The decision for a category of food or drink to use dynamic sprite to represent a dyanmic assembly must be taken on a
case by case basis. In many cases, variation in the art of base recipes will be enough - dynamic components can be left
to effect the final dish fully mechanically. In some, dynamic sprites are almost certainly desired - sandwiches and
burgers are the clearest example.



### Dynamic Mechanics


If there is no mechanical reason to produce more complex foods, players will have little motivation to do so other than
novelty. To that end this proposal recommends the following system of dynamically calculated status effects.

1. Each ingredient used to cook a food or mix a drink would have one or more Effect/Priority pairs.
    * The effect determines the effect granted by the completed food/drink on consumption if it is chosen.
    * The priority determines the priority by which that effect is selected on comsuption from all possible effects.
2. Each ingredient or food item has a single complexity/intensity value, which would determin:
   * The number of effects granted by the food on consumption
   * The strength of those effects when granted.

* Cooking operations can increase the complexity/intensity
* Some sort of math to determine complexity => number of effects granted
* Ingredient selection as means of determining end effects.


* Variation on system for drink mixing:
   * Static set of effects for base alcohol type(s)
   * Complexity influenced by mixers + garnishing.
<<<<<<< HEAD
      * Possibly also rare alcohol variations


## Interdepartmental Interactions

### Improvements from other Departments
* Produce from botany
* Better base ingredients from cargo
* Rare ingredients from salvage
* Improved cooking machines from science
* Strange ingredients from chemistry


### Improvements for other Departments


* Tasty snacks and treats with cool buffs

=======
      * Also by rare/special alcohol variations (maybe findable on salvage missiones, or orderable via cargo, captain should definitely have a private stash)
>>>>>>> 0ac25e2748c4c7ae16588f4b27dcebb5c5409aa0


## Required Machines, Containers, and Implements

### Machines

* A reworked microwave oven
* A traditional oven
* A stovetop/grill

### Containers

* A combined Item/Regent container and variants


### Implements




## Future Opportunities


* Blenders
* Freezers/Chillers
* Bento Boxes / Lunch Boxes






