# in-class-activities
## Devlogs
### W1
Write your W1 activity Devlog here.
For this class I learn about how to connect Visual Studio and Unity. Hello World
### W2
Create future Devlog sub-headers with the three # symbols, then write your Devlogs below them.
###
 Because float displays values in fraction, which meet the need of RGB color to represent in range of 0.0 to 1.0. This makes it easier to perform operations like blending, shading, and interpolation.
###
 Becuase bouncing number should be a integer, and int is the way to present integer in C#
###
 The error says there is a grammar error, here it need a semicolon to end the statement.
my Devlogs. Hello World

### W3 Table 19
Because the ratio between sanity and brightness of light is positive, which means sanity,directly modifies the light component in the scene, so it doesn’t need to return anything. Just change body function of the input is enough.

Metaphor: Class can be a blueprint of a machine, component is the actual machines built, and with methods, each machines represent their function.

There is a code letting the ball get brighter, but none of the code reduce or limit the lightness.

### W4 Table 19
Line 17 define the member variable _isGrounded using type bool, aim to stores a true or false value to make later decision when player is pressing on specific bottom. Line 28 is a if statement that detect if the player is pressing space and when _isGround is true, execute later codes. In line 32 it set _isGround as false when the cat already on air (the prior codes are running) to prevent the cat from going too high if players click the space continuously. 

### answer question
1.I add cat and soccerball as rigid body, because both of the objects have to active and hit with each other and objects in the game. I make the goal to check Is Trigger on because it need to detect whether the ball gets into it and record points.

2.The first time I run the game the cat rolls around and falling from the sky because the object is not still in the scene. So the first thing I did is freeze the rotation x and z for the cat and it goes well. Another problem I meet is that soccerball and cat falls a little bit and sink into the ground. I fixed them by larger the collider. Through the larger collider both of the objects stand on the ground.

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 