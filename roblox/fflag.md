DOCUMENTATION
ROBLOX
fflag

Functions to change/get fflags.

void get_fflag_bool(name) -> bool

Get the boolean value of the named fflag.

Will return nil if named fflag couldn't be found.

void get_fflag_value(name) -> int

Get the integer value of the named fflag.

void get_fflag_string(name) -> string

Get the string value of the named fflag.

void get_fflag_log(name) -> byte

Get the byte value of the named fflag.

void set_fflag_bool(name) -> void

void set_fflag_value(name) -> void

Example
local maxbandwidthbps = get_fflag_value("PhysicsSenderMaxBandwidthBps") -- integer type
if maxbandwidthbps ~= nil then
    print(maxbandwidthbps)
    set_fflag_value("PhysicsSenderMaxBandwidthBps", 0) -- prevents physics packets from reaching the server
end

local debughumanoidrendering = get_fflag_bool("DebugHumanoidRendering") -- bool type
if debughumanoidrendering ~= nil then
    print(debughumanoidrendering)
    set_fflag_bool("DebugHumanoidRendering", true)
end
