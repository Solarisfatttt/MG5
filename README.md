# MG5
## Devlog
Put your Devlog here.
1.
  Navmesh works better than physical simulation when the map is created in 3d and there is a height different(caused by mountains or trees). Also a 2d or 2.5d game with lot barriers such as LOL.
  However, it will not work well in 2d game or Platformer games, these games require very precise controls and demand that players reach specific locations by moving at certain angles, such as in the original Super Mario.
2. call to Vector3.Distance is for detecting if player is close enough to the bird, all birds fits the condition of close enough will try to run away from the player
  for : loop all birds
  Bird bird = birds[i] : every bird will check the if statement, and get bird's position for this bird in loop
  if statement: True if the distance between bird and player mathches the requirement
    Runaway: already defined method to make bird run away, (if distance matches)
  
## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)
