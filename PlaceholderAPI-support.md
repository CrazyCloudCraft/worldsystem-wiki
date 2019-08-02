There are some placeholders, which WorldSystem provides, version 2.4.4.2 or higher is required.

* `%worldsystem_has_world%`: Returns if a player has created a world yet
* `%worldsystem_is_creator%`: Returns if a player is the owner of the world he is on
* `%worldsystem_world_name_of_player%`: Returns the full name of the world the player belongs. Returns `none` if he does not have a world
* `%worldsystem_world_of_player_loaded%`: Returns if the world of a player is loaded. Returns `none` if he does not have a world
* `%worldsystem_pretty_world_name%`: Returns world name player is on if it is not a WorldSystem world. If so, then the owner's name gets returned.