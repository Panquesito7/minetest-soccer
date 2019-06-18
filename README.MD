# Soccer

Play soccer on Minetest!

This currently only provides the ball; the actual logic for implementing a match
will be implemented in the future. For now, you can use Mesecons Wooden Pressure
Plates along with some logic to at least handle scoring. Goals are also provided
but have no functionality.

The ball is not craftable ATM. Use /giveme soccer:ball_item, and place it with
right-click. You can take it again by punching it.

You can push the ball by standing near it, and kick it by holding the "sneak"
key (by default "Shift"). The ball will get pushed/kicked in the direction the
player is facing (you can center-on the ball by looking up).

## Dependencies
- default (included in minetest_game)
- wool (included in minetest_game)

## Requirements
- soccer 0.1.0 for MT/MTG 0.4.10+ (may work on older versions of MT/MTG).
- soccer 0.1.1 for MT/MTG 5.0.0+.

## Special thanks
- 12Me21: Ideas about the crafting recipe.
- ecube: Original (black) texture.
- Xiug: Ideas and textures.


## License
See license [here](https://github.com/kaeza/minetest-soccer/blob/master/LICENSE.txt) for further information.

## Installation
- Unzip the archive, rename the folder to "soccer" (**without the quotes**) and
place it in ..minetest/mods/

- GNU/Linux: If you use a system-wide installation place
    it in ~/.minetest/mods/.

- If you only want this to be used in a single world, place
    the folder in ..worldmods/ in your world directory.

For further information or help, see:
https://wiki.minetest.com/wiki/Installing_Mods
