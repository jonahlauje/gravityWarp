# gravityWarp
A multiplayer first-person shooter where you can warp gravity and walk on walls!

Play the game at: https://jonahlauje.github.io/gravityWarp/Play

# Changelog
p0.1.0 
- First version of the game

p0.1.1 
- Implemented fullscreen checker, forces 1920x1080 resolution at main menu

p0.2.0 
- Revamped gravity warping: added a slerp animation, expanded map

p0.3.0 
- Made other players' movement much smoother using lerping
- Updated UI: added weapon icons
- Post processing implemented (might undo bc performance hit)
- New keybind for fullscreen: ~
- Reduced recoil significantly
- ADSing now only has a 20% firerate penalty as opposed to 40% before
- Added a killzone: falling off the map results in death
- Gravity is now applied in FixedUpdate instead of Update (IDK why it was in update before)

p0.4
- Added personalisation menu (does not work yet)
- Fixed (?) issue related to locked transform.right and transform.forward values
