DOCUMENTATION
ROBLOX
game

Functions to get property information from game.

void get_gravity() -> float

Returns the workspace gravity

void set_gravity(value) -> void

Sets the workspace gravity

void get_tickrate() -> float

Returns the workspace tickrate

void set_tickrate(value) -> void

Sets the workspace tickrate

Normal gravity: 196.2 studs/second

Example
local current_tickrate = get_tickrate()
local current_gravity = get_gravity()

print(current_tickrate, current_gravity)

set_tickrate(120) -- 2 times faster, origin 60 fps
set_gravity(0)
