# -Ubuntu-app-installDebug-FAILED-
I've installed react-native and android studio, the emulator launched but I have a problem when I run the last step. 1. cd AwesomeProject 2. react-native run-android 

Please I need help. Thanks for comment 

The problem is the next:

Incremental java compilation is an incubating feature.
:app:preBuild UP-TO-DATE
:app:preDebugBuild UP-TO-DATE
:app:checkDebugManifest
:app:preReleaseBuild UP-TO-DATE
:app:prepareComAndroidSupportAppcompatV72301Library UP-TO-DATE
:app:prepareComAndroidSupportSupportV42301Library UP-TO-DATE
:app:prepareComFacebookFbuiTextlayoutbuilderTextlayoutbuilder100Library UP-TO-DATE
:app:prepareComFacebookFrescoDrawee130Library UP-TO-DATE
:app:prepareComFacebookFrescoFbcore130Library UP-TO-DATE
:app:prepareComFacebookFrescoFresco130Library UP-TO-DATE
:app:prepareComFacebookFrescoImagepipeline130Library UP-TO-DATE
:app:prepareComFacebookFrescoImagepipelineBase130Library UP-TO-DATE
:app:prepareComFacebookFrescoImagepipelineOkhttp3130Library UP-TO-DATE
:app:prepareComFacebookReactReactNative0493Library UP-TO-DATE
:app:prepareComFacebookSoloaderSoloader010Library UP-TO-DATE
:app:prepareOrgWebkitAndroidJscR174650Library UP-TO-DATE
:app:prepareDebugDependencies
:app:compileDebugAidl UP-TO-DATE
:app:compileDebugRenderscript UP-TO-DATE
:app:generateDebugBuildConfig UP-TO-DATE
:app:mergeDebugShaders UP-TO-DATE
:app:compileDebugShaders UP-TO-DATE
:app:generateDebugAssets UP-TO-DATE
:app:mergeDebugAssets UP-TO-DATE
:app:generateDebugResValues UP-TO-DATE
:app:generateDebugResources UP-TO-DATE
:app:mergeDebugResources UP-TO-DATE
:app:bundleDebugJsAndAssets SKIPPED
:app:processDebugManifest UP-TO-DATE
:app:processDebugResources UP-TO-DATE
:app:generateDebugSources UP-TO-DATE
:app:incrementalDebugJavaCompilationSafeguard UP-TO-DATE
:app:compileDebugJavaWithJavac UP-TO-DATE
:app:compileDebugNdk UP-TO-DATE
:app:compileDebugSources UP-TO-DATE
:app:transformClassesWithDexForDebug UP-TO-DATE
:app:mergeDebugJniLibFolders UP-TO-DATE
:app:transformNative_libsWithMergeJniLibsForDebug UP-TO-DATE
:app:processDebugJavaRes UP-TO-DATE
:app:transformResourcesWithMergeJavaResForDebug UP-TO-DATE
:app:validateSigningDebug
:app:packageDebug UP-TO-DATE
:app:assembleDebug UP-TO-DATE
:app:installDebug FAILED  

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':app:installDebug'.
> com.android.builder.testing.api.DeviceException: No connected devices!

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output.

BUILD FAILED

Total time: 19.108 secs
Could not install the app on the device, read the error above for details.
Make sure you have an Android emulator running or a device connected and have
set up your Android development environment:
https://facebook.github.io/react-native/docs/android-setup.html
