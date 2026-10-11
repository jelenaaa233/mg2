# minigame 2
## Devlog
1. One issue I encountered was that I could not get the spell to work correctly at first. I was able to move my character, but I could not damage the chests. I checked my code and made sure the spell's timer was decreasing using Time.deltaTime. After fixing the code and testing it again in Unity, the spell worked correctly. The chests started changing color, their health decreased, and they disappeared when their health reached zero.
2. I think this line of code changes the color of the chest using RGB values. The variable r controls the amount of red, while the other two values control green and blue. The period (.) is used to access a property of an object. For example, _spriteRenderer.color accesses the color property of the sprite renderer. I think the word "new" is used to create a new Color value with the numbers inside the parentheses. This new color is then assigned to the chest.

## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
