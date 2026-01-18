DOCUMENTATION
ROBLOX
camera

Functions to get property information from camera.

instance set_camera_position(vector3, smootness) -> void

Sets the camera lookat position

instance camera_position -> vector3

Gets the camera position.

instance camera_subject -> instance

Gets the camera subject instance.

instance camera_lookvector -> vector3

Gets the camera lookvector.

instance fov -> int

Gets the fov on the camera.

instance set_fov() -> void

Sets the fov on the camera. (0 - 180)

instance get_camera_type()-> camera_type

Gets the camera type, (scriptable, orbital, ...)

Example
local workspace = game:get_service("Workspace")
local camera = workspace:find_first_child_class("Camera")
local camera_subject = camera.camera_subject

print(camera_subject.name .. " - " .. camera_subject.class_name)

local camera_position = camera.camera_position
print(camera_position.x, camera_position.y, camera_position.z)
print(camera.fov)

camera:set_camera_position(vector3(0,0,0), 0.5) -- Goes half way
camera:set_fov(120)
