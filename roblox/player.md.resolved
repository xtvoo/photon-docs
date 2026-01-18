DOCUMENTATION
ROBLOX
player

Functions to get property information from players.

instance is_friend() -> bool
instance get_team() -> instance
instance display_name -> string
instance local_player -> instance
instance userid -> string
instance character -> instance
instance get_camera_max_dist() -> float
instance set_camera_max_dist(float) -> void
instance get_camera_min_dist() -> float
instance set_camera_min_dist(float) -> void

Example
local players = game:get_service("Players")
local localplayer = players.local_player
local character = localplayer.character

print(localplayer.name)
print(localplayer.display_name)
local local_team = localplayer:get_team()

for i, v in pairs(players:get_children()) do
    if v.class_name == "Player" and v.identity ~= localplayer.identity then
        print(v.name)
        print(tostring(v:is_friend()))
    end
end
