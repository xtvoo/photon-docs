DOCUMENTATION
ROBLOX
humanoid

Functions to get property information from humanoid.

instance health -> float
instance max_health -> float
instance get_rigtype() -> rig_type
instance move_direction -> vector3
instance jumppower -> float
instance set_jumppower(float) -> void
instance hipheight -> float
instance set_hipheight(float) -> void
instance walkspeed -> float
instance set_walkspeed(float) -> void
instance sit -> bool
instance set_sit(bool) -> void
instance get_state() -> humanoid_state

Example
local players = game:get_service("Players")
local localplayer = players.local_player
local character = localplayer.character
local humanoid = character:find_first_child_class("Humanoid")

humanoid:set_walkspeed(200)
humanoid:set_jumppower(200)

print(humanoid.health)

if humanoid:get_state() == humanoid_state.FREE_FALL then
    print("character is free falling")
end

if humanoid:get_rigtype() == rig_type.R6 then
    print("character is r6")
else
    print("character is r15")
end
