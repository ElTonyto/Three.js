# Three.js

Final task of WebGL classes - Tony Pedrero

## Starting the project

The first thing to do in order to get a working project is to download the
Three.js's master to this link : https://github.com/mrdoob/three.js/archive/master.zip.
Then you will have to unzip it into a vendor directory you will create.

Finally, you will have to run a server on your computer ( for instance: php -S localhost:8080 in a shell).

## Content

I decided to continue from the project started in classes, adding some elements to it in order to change the lightning of the scene. 

I have added a red button to the scene. This button is made of a BoxGeomerty and an FBX element witch as been imported.

Both of these elements are MeshMaterials and react to the lights (reflexion and shadows).

I added an animation when the user passes on the button, it starts pressing down. At the same time, the lights intensity goes down until going to complete dark. At the end, the scene is lighted in red and a huge and scary mask appears.

When the user leaves the mouse from the button, the animation goes back to the normal lights and colors but also keeps the mask and the new lights.
