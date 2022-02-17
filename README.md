# Reflection

## Technical setup instructions

This project can be run from the Unity editor. When the user enters game mode, they will view the environment from a single fixed location. The user can rotate their view to see other sides by moving the mouse cursor over the screen.

## Visuals

Video demo: https://www.youtube.com/watch?v=C2fEBSaO9Ms
Moments: https://imgur.com/a/tPn5ou4

## The Storyworld

The world is set up in an apocalyptic scenario, where people have escaped biowarfare on land by taking a ship and setting to the sea. The ship, however, broke down on the way with no land in sight. All the passengers drowned except for one child and his mother. When this parent-child duo managed to leave the sunken ship, they proceeded to build a house on top of the wreckage left in the water, which was surprisingly very stable. After a short while, the duo then realized they could use the boats they have to go back to the ship and look for valuable or useful items. They found a few furniture pieces and food items which they managed to make use of. They also found barrels of a very valuable chemical compound -- the same one which was used during the war against them. They decided to bring it back. Fast forward a few weeks, the barrels suddenly started leaking the chemical inside the house. In panic, the mother hurries to take a boat to the ship to look for tools that could help rid them of this disaster. She warned her son very clearly not to go anywhere near the dripping chemical. The son, however, had a burning desire to take a look at the special side compartment his mother built for storage. She had asked him previously not to snoop around there, and now is his best chance to find out what is stored there besides food. What will he do?

## Reflection (on the experience)

WIP: https://imgur.com/a/xzuzrDW
Playtesting: *Please refer to the youtube video above* 
I think the environment conveyed a contrast between the room and some of the items in the room (the bed and the sofa), which is what I was going for. I was worried that after implementing water floting, the motion from the point of viewof the user would be excessive or sickening, but I don't think it's that bad after testing it. 
When I first started building the project, I tried to minimize my use of assets as much as possible. I quickly ran into a problem that changed my mind. Whenever I added objects and started manipulating them for my purposes by subdividing and deleting faces, the objects started having unpleasant meshes with transparent faces on certain sides. I also realized that basic objects like planes and cubes would only display the material from the outer side or from a single side. I tried solving this by duplicating objects and setting their faces to opposite sides, but that led to very inconsistent behavior when I played the game. I gave up on building my own house and items and started using assets, which made the building process much smoother. In the future, I will try not to waste too much time focusing on small details and instead use available resources to construct a cohesive environment more efficiently. Maybe learning object design could be a task for later. 