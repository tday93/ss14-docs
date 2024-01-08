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

In order to distinguish foods from one-another mechanically

* Possible effects should:
   * Be generally beneficial
   * Not cause gameplay problems, no burger of stun resistance
   * Be desirable by players






## Dynamic Food and Drink Items

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
      * Also by rare/special alcohol variations (maybe findable on salvage missiones, or orderable via cargo, captain should definitely have a private stash)


## Required Machines, Containers, and Implements


## Future Opportunities


* Blenders
* Freezers/Chillers
* Bento Boxes / Lunch Boxes






