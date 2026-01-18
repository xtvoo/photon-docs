DOCUMENTATION
ROBLOX
part

Functions to get property information from parts.

instance position -> vector3
instance set_position(vector3) -> void
instance cframe_position -> vector3
instance set_cframe_position(vector3) -> void
instance cframe_angle -> vector3
instance set_cframe_angle(vector3) -> void
instance cframe_lookvector -> vector3
instance set_cframe_lookvector(vector3) -> void
instance cframe_rightvector -> vector3
instance cframe_upvector -> vector3
instance velocity -> vector3
instance set_velocity(vector3) -> void
instance linear_velocity -> vector3
instance set_linear_velocity(vector3) -> void
instance size -> vector3
instance set_size(vector3) -> void
instance collision -> bool
instance set_collision(bool) -> void
instance transparency -> float
instance set_transparency(float) -> void
instance reflectance-> float
instance spectate() -> void
instance color -> color
instance set_color(color) -> color
instance material -> material_type enum
instance set_material(material_type) -> void
instance anchored -> bool
instance set_anchored(bool) -> void
instance get_primitive() -> instance

Example
local workspace = game:get_service("Workspace")
local players = game:get_service("Players")
local localplayer = players.local_player

local stored_parts = {}
for _, v in pairs(workspace:get_children()) do
    if v.class_name == "Part" then
       local part_position = v.position
       local part_size = v.size
       print(v.name)
       table.insert(stored_parts, v)
    end
end

local local_character = localplayer.character
if local_character:isvalid() then
   for _, v in pairs(local_character:get_children()) do
      if v.class_name == "MeshPart" or v.class_name == "Part" then
         v:set_collision(false)
      end
   end
end

if local_character:isvalid() then
   local rootpart = local_character:find_first_child("HumanoidRootPart")
   if rootpart:isvalid() then
      rootpart:set_velocity(vector3(0, 50, 0))
   end
end
