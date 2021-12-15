# Materials for Teaching Scrum using Minetest

This repository contains material useful for teaching Scrum using Minetest. This includes maps, guides, and other things.

## Worlds

At this point, the repository contains two worlds (`Flatworld 13` and `Flatworld A5`) that have been used to teach Scrum using Minetest. Both have different characteristics as described below.

| *Map* | *Description* | *Resources* | *Backlog* |
| ----- | ------------- | ----------- | --------- |
| Flatworld 13 | A flat valley surrounded by relatively high mountains. The mountains contain a number of dungeons. | Mostly grassland. Very little wood (only in the form of shrubs). Some sand, but no metal. | The backlog contains user stories to build a city scape. The user stories contain only few acceptance criteria and are very poorly written to encourage students to engage the product owners and refine the stories. [Trello Template](https://trello.com/b/arE4u92Q) |
| Flatworld A5 | A large lake surrounded by beach and very dense forest. | A lot of wood in the forest -- in fact, so much wood that it is necessary to clear away a large portion of it to be able to start building. | The backlog contains user stories to build a castle. The user stories contain detailed acceptance criteria. Importantly, the backlog requires a much higher integration of the different user stories since they describe elements that need to be contained within the castle walls and have dependencies to each other (such as: the pantry needs to be placed besides the kitchen). [Trello Template](https://trello.com/b/8mDa0xJn) |

The worlds come in two flavors: with and without *pyramids*. The pyramids are scattered over the world to provide a convenient starting point for the different teams. Along with a map (see below) this allows teams of participant to gather in a defined spot at the beginning of the workshop.


## Maps

The maps for the worlds in this repository (files ending in `.xcf`) can be opened using [GIMP](https://www.gimp.org/downloads/). They give an overview of the playing area and the position of the *pyramids*. The team names can be placed next to the pyramids on the map and given to participants so that they know where to gather.

The maps have been created using [Minetest Mapper](https://github.com/minetest/minetestmapper).

## Config

This repository also contains a `minetest.conf` file that was used to run a workshop with 95 participants on an i7-4790 with 24GB of RAM and a 100/100MBit internet connection. The `max_lag` value oscillated between 1 and 5 using this configuration. CPU cores were utilised to about 50% max. Players experienced slight lag at times, but overall, the game was playable.

Please make sure to replace the values for the player, the server name, and the default password with your own values when using this configuration.
