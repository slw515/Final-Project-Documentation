# Final-Project-Documentation

The motivation for this project is to utilize web technologies today that allow users to be placed into more immersive experience. As a child, I really loved playing the Kinect and Wii because I was able to see my physical movements being mirrored on my television. I find it incredible now that there are so many libraries out there that might allow developers to create these amazing experiences that can be experienced from a laptop or a phone. This is my attempt to use one of these libraries to build a dynamic, interesting game that can be played with just a person's laptop anywhere. 

This is a web game that tracks the position of a person in front of the camera to determine the movements of the ball the that is being controlled. The game features Posenet, taking advantage of the library's impressive ability to consistently track parts of a person's body. Leaning to one side or another makes the ball move to the same side that the person is leaning towards. Jumping, which is detected once the shoulder positions are tracked to be above a certain position, causes the ball to jump. The game takes the data from Posenet's processing of the live video and uses p5.js to display this information for the user to see in their live video at the top of the game.

The research that I have done so far has taught me how the ThreeJS library can be used to create simple games, and I now have a solid understanding of the z-dimension so that I might make this game. I have also been experimenting with NodeJS to see how I can create a backend, which I intend to use to hold players' high scores. 

The game was inspired by Temple Run and seeks to be styled like a futuristic sci-fi game. Attached is a working screenshot of the application. 

I have done previous projects in p5.js, specifically in making simple games with user controlled objects. Using Three.js will be more challenging to incorporate a third dimension to the gameplay. 
