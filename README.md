# Nebula-Beta

Nebula is a testing platform for augmented reality. Simply add the `nebula` script to your Unity project, record a test scene with our [application](http://nebula-ar.herokuapp.com) and start testing.

## Install & Run

1. Copy the `nebula.cs` script from this repository and add it as a component of an empty GameObject in your Unity scene.
2. Create a folder named `NebulaTextures` inside the `Resources` folder of your `Assets` directory.

Your Unity project will then include the following structure:

```
    + Assets
        - nebula
        + Resources
            + NebulaTextures
```

To use Nebula in Unity you will need to provide a valid scene, recorded using our iOS app. Scenes recorded with our app can be retrieved from our [cloud platform](http://nebula-ar.herokuapp.com/dashboard). Click on the scene you want to use and it will download a zip file containing a list of images and a `data.json` file.

Once you have recorded a scene and downloaded the zip file, move all the contents of the folder to your `Resources` folder in your unity project. Place all the images inside `NebulaTextures` and the `data.json` file inside `Resources`, like so:


```
    + Assets
        - nebula                          // script
        + Resources
            - data.json                   // retrieved from web
            + NebulaTextures
                - <filename_01>.jpg       // retrieved from web
                - <filename_02>.jpg       // retrieved from web
```

Run your Unity scene. You should see your GameObjects displayed as if they were part of the original recording. You can move and adjust your GameObjects as you normally would while in Play mode.

### Coming soon..

__Swift Library__

We are building a library that will allow you to test augmented reality apps developed for iOS without having to run the app from scratch every time.

__Web Editor__

With our web editor you will be able to create augmented reality experiences without needing an actual device. This makes testing faster and allows you to build experiences for specific locations.



## Contact

Please feel free to get in contact with any questions, comments, or suggestions. We're also looking for collaborators if you want to be involved further.

jordan@jordancampbell.org






















<!-- # end -->
