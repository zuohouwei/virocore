ViroCore
=====================

ViroCore is SceneKit for Android, a 3D framework for developers to build immersive applications using Java. ViroCore combines a high-performance rendering engine with a descriptive API for creating 3D/AR/VR apps. While lower-level APIs like OpenGL require you to learn and precisely implement rendering algorithms, ViroCore requires only high-level scene descriptions and the events and interactions you desire.

Platforms supported:
Android, ARCore, Google Daydream, Samsung GearVR, Google Cardboard VR

[Sign up](https://viromedia.com/signup) for an API key. The platform is free to use with no limits on distribution.

To report bugs/issues with Viro platform, please file new issues on this repository.

## Instructions for running sample code:

1. Follow the prerequisite directions on our [Quick start guide](https://virocore.viromedia.com/docs/getting-started) to setup dependencies for trying these sample projects with the Viro Media App.
2. Clone the repo into your workspace with git: `git clone https://github.com/viromedia/virocore.git`.
3. Choose the code sample you wish to deploy, and open the root directory in Android studio. 
4. Edit AndroidManifest.xml, and replace "API_KEY_HERE" with the key emailed to you with signup.
5. Click on Build Variants, and select arcoreDebug as the build variant.
6. (Optional) Clean and gradle sync
7. Built and deploy.
8. You should now be in the application! Enjoy!

## More Information

Viro Media Website: https://viromedia.com/

ViroCore Documentation: https://virocore.viromedia.com/

API Reference(Java Docs): https://developer.viromedia.com/

Join our Slack group [here](https://join.slack.com/t/virodevelopers/shared_invite/enQtMzExNTgyNjkwMjU2LWM2OGNmYTI4NjI5OWI5NDc4ZGMwNTJjNGUzNDZjYjU0YjVmNjcxNjZkZjU3ZGM1YmY5ZGEwY2I1MzNlZDIyNGY).

Check out our [blog](https://blog.viromedia.com/) for tutorials, news, and updates.

## Sample Code List

### [AR Hellow World Android](https://github.com/viromedia/virocore/blob/master/ARHelloWorldAndroid/app/src/main/java/com/example/virosample/ViroARHelloWorldActivity.java)

<a href="https://github.com/viromedia/virocore/blob/master/ARHelloWorldAndroid/app/src/main/java/com/example/virosample/ViroARHelloWorldActivity.java">
<img src="https://raw.githubusercontent.com/viromedia/virocore/master/ARHelloWorldAndroid/ViroARPlanesDemoActivity.gif">
</a>

### [AR Placing Objects](https://github.com/viromedia/virocore/blob/master/ARPlacingObjects/app/src/main/java/com/example/virosample/ViroARObjectPlacementActivity.java)

<a href="https://github.com/viromedia/virocore/blob/master/ARPlacingObjects/app/src/main/java/com/example/virosample/ViroARObjectPlacementActivity.java">
<img src="https://raw.githubusercontent.com/viromedia/virocore/master/ARPlacingObjects/ViroARHitTestDemoActivity.gif">
</a>

### [AR Retail](https://github.com/viromedia/virocore/tree/master/ARRetail)

<a href="https://github.com/viromedia/virocore/tree/master/ARRetail">
<img src="https://raw.githubusercontent.com/viromedia/virocore/master/ARRetail/ARRetailActivity.gif">
</a>

[Link to AR Retail tutorial](https://blog.viromedia.com/tutorial-how-to-build-amazons-ar-view-for-arcore-android-using-virocore-and-java-ba1cc3ff2d87)
