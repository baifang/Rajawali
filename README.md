[![AndroidLibs](https://img.shields.io/badge/AndroidLibs-Rajawali-brightgreen.svg?style=flat)](https://www.android-libs.com/lib/rajawali?utm_source=github-badge&utm_medium=github-badge&utm_campaign=github-badge)

![Rajawali](http://www.rozengain.com/files/rajawali-logo.jpg)

## Build Status
**Master Branch Status**  [![master](https://travis-ci.org/Rajawali/Rajawali.svg?branch=master)](https://travis-ci.org/Rajawali/Rajawali)

**Development Branch Status**  [![development](https://travis-ci.org/Rajawali/Rajawali.svg?branch=development)](https://travis-ci.org/Rajawali/Rajawali)

## About
Rajawali is a 3D engine for Android based on OpenGL ES 2.0/3.0. It can be used for normal apps as well as live wallpapers.

Want to keep the developers going? Buy them a beer! (http://www.pledgie.com/campaigns/21807)

[Join the Rajawali Community](https://plus.google.com/u/0/communities/116529974266844528013) on [![Rajawali Community on Google Plus](http://sinceresocial.com/wp-content/uploads/2012/05/google+-20px.png)](https://plus.google.com/u/0/communities/116529974266844528013) to stay up-to-date on the latest news. 

_NOTE: Rajawali's release process is changing and the master branch should be considered unstable. Use the [`v0.9`](https://github.com/MasDennis/Rajawali/tree/v0.9) tag if you need a stable version. We are working to improve documentation on this subject._

The [RajawaliExamples](https://github.com/MasDennis/RajawaliExamples) project is an ever growing toolkit for developing 3D content. [Check it out!](https://github.com/MasDennis/RajawaliExamples)

## Made With Rajawali

Numerous apps and live wallpapers have been made with Rajawali. [Check them out!](https://plus.google.com/u/0/communities/116529974266844528013/stream/526227da-cf2d-46f9-8ad6-beaca7b8ddd5)

## Using Rajawali

Using Rajawali is as simple as adding a single line to your gradle dependencies:

`compile 'org.rajawali3d:rajawali:x.x.x@aar` where x.x.x is the version number (and the last number is the build number). If you wish to use the `master` branch snapshot, append `-SNAPSHOT`. For example, to use release `1.0.48`, you would use:

`compile 'org.rajawali3d:rajawal:1.0.48@aar`

To use the `master` branch build 48 snapshot `1.0.48-SNAPSHOT`, you would use:

`compile 'org.rajawali3d:rajawali:1.0.48-SNAPSHOT@aar`

All commits to `master` branch or deployed as snapshots. All tags will be deployed as releases. To see the latest build number, see the [build history](https://travis-ci.org/Rajawali/Rajawali/builds) and be sure you choose a `master` branch build.

For the above to work you will need to make sure your repository list includes:

`mavenCentral()` for releases, and `maven { url "https://oss.sonatype.org/content/repositories/snapshots/" }` for snapshots.

Alternatively, if you checkout Rajawali via GIT, you can run `gradle assembleRelease uploadArchives` (or simply add a Gralde launch config to Android Studio for the `assembleRelease` and `uploadArchives` tasks). This will deploy to your local maven ropository. Consuming apps should have `mavenLocal()` in their repository list and add `compile 'org.rajawali3d:rajawali:1.0.0-SNAPSHOT@aar` to their dependencies.

## Rajawali Examples On The Market

[Download the free app](https://market.android.com/details?id=com.monyetmabuk.rajawali.tutorials)

## Rajawali + Augmented Reality

[RajawaliVuforia GitHub](https://github.com/MasDennis/RajawaliVuforia)

[YouTube Video of RajawaliVuforia in action](http://www.youtube.com/watch?v=rjLa4K9Ffuo)

## Rajawali + Virtual Reality

[RajawaliVR GitHub](https://github.com/MasDennis/RajawaliVR)

[YouTube Video of RajawaliVR in action](https://www.youtube.com/watch?v=3L0l_jmkcBE&feature=youtu.be)

## Tutorials

1. [Basic Setup & a Sphere](https://github.com/MasDennis/Rajawali/wiki/Tutorial-01----Basic-Setup-&-a-Sphere)  
2. [Creating a Live Wallpaper and Importing a Model](https://github.com/MasDennis/Rajawali/wiki/Tutorial-02-Creating-a-Live-Wallpaper-and-Importing-a-Model)  
3. [Materials](https://github.com/MasDennis/Rajawali/wiki/Tutorial-03-Materials)  
4. [Optimization](https://github.com/MasDennis/Rajawali/wiki/Tutorial-04-Optimization)  
5. [Skybox] (https://github.com/MasDennis/Rajawali/wiki/Tutorial-05-Skybox)  
6. [Screenshots] (https://github.com/MasDennis/Rajawali/wiki/Tutorial-06-Screenshots)  
7. [Plugins] (https://github.com/MasDennis/Rajawali/wiki/Tutorial-05-Plugins)  
8. [User Interface Elements] (https://github.com/MasDennis/Rajawali/wiki/Tutorial-08-Adding-User-Interface-Elements)  
9. [Creating a Custom Material GLSL Shader](https://github.com/MasDennis/Rajawali/wiki/Tutorial-09-Creating-a-Custom-Material---GLSL-Shader)  
10. [2D Renderer](https://github.com/MasDennis/Rajawali/wiki/Tutorial-10-2D-Renderer)  
11. [Particles](https://github.com/MasDennis/Rajawali/wiki/Tutorial-11-Particles)  
12. [Object Picking](https://github.com/MasDennis/Rajawali/wiki/Tutorial-12-Object-Picking)  
13. [Animation Classes](https://github.com/MasDennis/Rajawali/wiki/Tutorial-13-Animation-Classes)  
14. [Bump Normal Mapping](https://github.com/MasDennis/Rajawali/wiki/Tutorial-14-Bump-Normal-Mapping)  
15. [MD2 Animation](https://github.com/MasDennis/Rajawali/wiki/Tutorial-15-MD2-Animation)  
16. [Collision Detection](https://github.com/MasDennis/Rajawali/wiki/Tutorial-16-Collision-Detection)  
17. [Importing .Obj Files](https://github.com/MasDennis/Rajawali/wiki/Tutorial-17-Importing-.Obj-Files)  
18. [Drawing Lines](https://github.com/MasDennis/Rajawali/wiki/Tutorial-18-Drawing-Lines)  
19. [Catmull Rom Splines](https://github.com/MasDennis/Rajawali/wiki/Tutorial-19-Catmull-Rom-Splines)  
20. [Animated Sprites](https://github.com/MasDennis/Rajawali/wiki/Tutorial-20-Animated-Sprites)  
21. [Fog](https://github.com/MasDennis/Rajawali/wiki/Tutorial-21-Fog)  
22. [More Optimisation](https://github.com/MasDennis/Rajawali/wiki/Tutorial-22-More-Optimisation)  
23. [Custom Vertex Shader](https://github.com/MasDennis/Rajawali/wiki/Tutorial-23-Custom-Vertex-Shader)  
24. [Using Geometry Data To Position And Rotate Objects](https://github.com/MasDennis/Rajawali/wiki/Tutorial-24-Using-Geometry-Data-To-Position-And-Rotate-Objects)  
25. [Video Material](https://github.com/MasDennis/Rajawali/wiki/Tutorial-25-Video-Material)  
26. [Orthographic Camera](https://github.com/MasDennis/Rajawali/wiki/Tutorial-26-Orthographic-Camera)
27. [Texture Compression](https://github.com/MasDennis/Rajawali/wiki/Tutorial-27-Texture-Compression)
28. [Transparent Textures](https://github.com/MasDennis/Rajawali/wiki/Tutorial-28-Transparent-Textures)
29. [Skeletal Animation](https://github.com/MasDennis/Rajawali/wiki/Tutorial-29-Skeletal-Animation)
30. [Creating a Day Dream](https://github.com/MasDennis/Rajawali/wiki/Tutorial-30-Creating-a-Day-Dream)
31. [Using RajawaliScene] (https://github.com/MasDennis/Rajawali/wiki/Tutorial-31-Using-RajawaliScene)

## Tutorials & Articles By Others
* (Kean Walmsley from Autodesk) Creating a 3D viewer for our Apollonian service using Android [Part 1](http://through-the-interface.typepad.com/through_the_interface/2012/04/creating-a-3d-viewer-for-our-apollonian-service-using-android-part-1.html) [Part 2](http://through-the-interface.typepad.com/through_the_interface/2012/05/creating-a-3d-viewer-for-our-apollonian-service-using-android-part-2.html) [Part 3](http://through-the-interface.typepad.com/through_the_interface/2012/05/creating-a-3d-viewer-for-our-apollonian-service-using-android-part-3.html)
* Rajawali と戯れる [Part 1](http://dev.classmethod.jp/smartphone/android/android-rajawali-tutorials-01/) [Part 2](http://dev.classmethod.jp/smartphone/android/android-rajawali-tutorials-02/) (Japanese)
* [Introducing Plugin Architecture for Rajawali](http://www.andrewjo.com/blog/mobile-development/introducing-plugin-architecture-for-rajawali)
* [Object Occlusion Testing in Rajawali](http://www.andrewjo.com/blog/mobile-development/object-occlusion-testing-in-rajawali)
* [Ниже пример как сделать простую 3D модель и запустить сцену на Android](http://konsultantspb.ru/3d-engine-rajawali/)(Russian)
* [Android in razvoj 3D igre](http://www.monitor.si/clanek/android-in-razvoj-3d-igre/142302/)(Slovenian)
* [Rajawali là gì?](http://www.trithucmoi.co/en/component/content/article/101-rajawali-va-ardor3d.html)(Vietnamese)

## Learn Rajawali at a Training Center
* [Android Game Development in India](http://virtualinfocom.com/android_game/android_game_development_institute.html)
* [Android Application Programming in India](http://virtualinfocom.com/android_game_application_development_training.html)

