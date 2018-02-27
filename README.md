# Nebula-Beta

Nebula is a testing platform for augmented reality. Simply add the `nebula` script to your Unity project, record a test scene with our [application](http://nebula-ar.herokuapp.com) and start testing.

## Install & Run

1. Copy the `nebula.cs` script from this repository and add it as a component of an empty GameObject in your Unity scene.
2. Create a folder named `NebulaTextures` inside the `Resources` folder of your `Assets` directory.

Your Unity project will then include the following structure:

```
    + Assets
        - nebula.cs
        + Resources
            - data.json
            + NebulaTextures
                - <filename_01>.jpg
                - ...
                - <filename_n>.jpg
```


To use Nebula in Unity you will need to provide a valid scene, recorded using our iOS app. Scenes recorded with our app can be retrieved from our [cloud platform](http://nebula-ar.herokuapp.com/dashboard).

Once you have recorded a scene and downloaded the zip file, simply move all the contents of the folder to your `Resources` folder in your unity project.

Run your Unity scene. You should see your GameObjects displayed as if they were part of the original recording. You can move and adjust your GameObjects as you normally would while in Play mode.



### Coming soon..

1. Swift Library

We are building a library that will allow you to test augmented reality apps developed for iOS without having to run the app from scratch every time.

1. Web Editor

With our web editor you will be able to create augmented reality experiences without needing an actual device. This makes testing faster and allows you to build experiences for specific locations.



























<!-- # end -->
