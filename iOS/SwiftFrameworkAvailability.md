# Swift Frameworks by iOS Version

Below is a grid of which swift frameworks are available on each iOS version.
Prior to Swift 5 (iOS 12.2), the frameworks were included with each app and dynamically linked but since that, they have been part of the OS.
If you see errors related to specific swift frameworks missing when building your app on certain OS versions, check the grid below for compatibility.

**NOTE:** The grid shows which frameworks are deployed with each OS version. It _doesn't_ mean that the missing framework won't work on earlier OS versions (it may or may not) but that it may need to be deployed with your app to work correctly.

**NOTE:** iOS 13 is incomplete as I don’t have a disk image for that yet to check. Once I find one, I'll update this list.

| Library Name                         | iOS 12 | iOS 13 | iOS 14 | iOS 15 | iOS 16 | iOS 17 | iOS 18 |
| ------------------------------------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| libswift_Builtin_float.dylib         |        |        |        |        |        |        | x      |
| ~libswiftPencilKit.dylib             |        |        |        | x      | x      | x      | x (<18.4)  |
| libswift_Concurrency.dylib           |        |        |        | x      | x      | x      | x      |
| libswift_errno.dylib                 |        |        |        |        |        |        | x      |
| libswift_math.dylib                  |        |        |        |        |        |        | x      |
| libswift_Differentiation.dylib       |        |        |        | x      | x      | x      | x      |
| libswift_RegexParser.dylib           |        |        |        |        | x      | x      | x      |
| libswift_signal.dylib                |        |        |        |        |        |        | x      |
| libswift_stdio.dylib                 |        |        |        |        |        |        | x      |
| libswift_StringProcessing.dylib      |        |        |        |        | x      | x      | x      |
| libswift_time.dylib                  |        |        |        |        |        |        | x      |
| libswift_Volatile.dylib              |        |        |        |        |        |        | x (18.4+)  |
| libswiftos.dylib                     | x      | x      | x      | x      | x      | x      | x      |
| libswiftsimd.dylib                   | x      | x      | x      | x      | x      | x      | x      |
| libswiftARKit.dylib                  | x      | x      | x      | x      | x      | x      | x      |
| libswiftAVFoundation.dylib           | x      | x      | x      | x      | x      | x      | x      |
| libswiftAccelerate.dylib             | x      | x      | x      | x      | x      | x      | x      |
| libswiftAppleArchive.dylib           |        |        | x      | x      | x      | x      | x      |
| libswiftAssetsLibrary.dylib          |        |        | x      | x      | x      | x      | x      |
| libswiftCallKit.dylib                | x      | x      | x      | x      | x      | x      | x      |
| libswiftCarPlay.dylib                |        |        |        | x      | x      | x      | x      |
| libswiftCloudKit.dylib               | x      | x      | x      | x      | x      | x      |        |
| libswiftCompression.dylib            |        |        | x      | x      | x      | x      | x      |
| libswiftContacts.dylib               | x      | x      | x      | x      | x      | x      | x      |
| libswiftCore.dylib                   | x      | x      | x      | x      | x      | x      | x      |
| libswiftCoreAudio.dylib              | x      | x      | x      | x      | x      | x      | x      |
| libswiftCoreData.dylib               | x      | x      | x      | x      | x      | x      | x      |
| libswiftCoreFoundation.dylib         | x      | x      | x      | x      | x      | x      | x      |
| libswiftCoreGraphics.dylib           | x      | x      | x      | x      | x      | x      | x      |
| libswiftCoreImage.dylib              | x      | x      | x      | x      | x      | x      | x      |
| libswiftCoreLocation.dylib           | x      | x      | x      | x      | x      | x      | x      |
| libswiftCoreMIDI.dylib               |        |        | x      | x      | x      | x      | x      |
| libswiftCoreML.dylib                 |        |        | x      | x      | x      | x      | x      |
| libswiftCoreMedia.dylib              | x      | x      | x      | x      | x      | x      | x      |
| libswiftCoreNFC.dylib                |        |        | x      | x      | x      | x      | x      |
| libswiftCryptoTokenKit.dylib         |        |        | x      | x      | x      | x      | x      |
| libswiftDarwin.dylib                 | x      | x      | x      | x      | x      | x      | x      |
| libswiftDataDetection.dylib          |        |        |        | x      | x      | x      | x      |
| libswiftDemangle.dylib               |        |        |        | x      | x      | x      | x      |
| libswiftDispatch.dylib               | x      | x      | x      | x      | x      | x      | x      |
| libswiftDistributed.dylib            |        |        |        |        | x      | x      | x      |
| libswiftExtensionFoundation.dylib    |        |        |        | x      | x      | x      | x      |
| libswiftExtensionKit.dylib           |        |        |        | x      | x      | x      | x      |
| libswiftFileProvider.dylib           |        |        |        | x      | x      | x      | x      |
| libswiftFoundation.dylib             | x      | x      | x      | x      | x      | x      | x      |
| libswiftGLKit.dylib                  | x      | x      | x      | x      | x      | x      | x      |
| libswiftGameplayKit.dylib            | x      | x      | x      | x      | x      | x      | x      |
| libswiftHealthKit.dylib              |        |        | x      | x      | x      | x      | x      |
| libswiftHealthKit_Private.dylib      |        |        |        | x      | x      |        |        |
| libswiftHomeKit.dylib                | x      | x      | x      | x      | x      | x      |        |
| libswiftIdentityLookup.dylib         |        |        |        |        | x      | x      | x      |
| libswiftIntents.dylib                | x      | x      | x      | x      | x      | x      | x      |
| libswiftMLCompute.dylib              |        |        | x      | x      | x      | x      | x      |
| libswiftMapKit.dylib                 | x      | x      | x      | x      | x      | x      | x      |
| libswiftMediaPlayer.dylib            | x      | x      | x      | x      | x      | x      | x      |
| libswiftMetal.dylib                  | x      | x      | x      | x      | x      | x      | x      |
| libswiftMetalKit.dylib               | x      | x      | x      | x      | x      | x      | x      |
| libswiftMetricKit.dylib              |        |        | x      | x      | x      | x      | x      |
| libswiftModelIO.dylib                | x      | x      | x      | x      | x      | x      | x      |
| libswiftNaturalLanguage.dylib        | x      | x      | x      | x      | x      | x      | x      |
| libswiftNearbyInteraction.dylib      |        |        | x      | x      | x      | x      | x      |
| libswiftNetwork.dylib                | x      | x      | x      | x      | x      | x      | x      |
| libswiftOSLog.dylib                  |        |        |        | x      | x      | x      | x      |
| libswiftObjectiveC.dylib             | x      | x      | x      | x      | x      | x      | x      |
| libswiftObservation.dylib            |        |        |        |        |        | x      | x      |
| libswiftPassKit.dylib                |        |        |        | x      | x      | x      | x      |
| libswiftPencilKit.dylib              |        |        | x      |        |        |        |        |
| libswiftPhotos.dylib                 | x      | x      | x      | x      | x      | x      | x      |
| libswiftPhotosUI.dylib               |        |        | x      | x      | x      | x      | x      |
| libswiftQuartzCore.dylib             | x      | x      | x      | x      | x      | x      | x      |
| libswiftQuickLook.dylib              |        |        |        | x      | x      |        |        |
| libswiftRegexBuilder.dylib           |        |        |        |        | x      | x      | x      |
| libswiftSceneKit.dylib               | x      | x      | x      | x      | x      | x      | x      |
| libswiftShazamKit.dylib              |        |        |        | x      | x      | x      | x      |
| libswiftSIMDOperators.dylib          | x      | x      |        |        |        |        |        |
| libswiftSoundAnalysis.dylib          |        |        |        | x      | x      |        |        |
| libswiftSoundAnalysis_Private.dylib  |        |        |        |        | x      |        |        |
| libswiftSpatial.dylib                |        |        |        |        | x      | x      | x      |
| libswiftSpeech.dylib                 |        |        | x      | x      | x      | x      | x      |
| libswiftSpriteKit.dylib              | x      | x      | x      | x      | x      | x      | x      |
| libswiftSwiftOnoneSupport.dylib      | x      | x      | x      | x      | x      | x      | x      |
| libswiftSystem.dylib                 |        |        | x      | x      | x      | x      | x      |
| libswiftSystem_Foundation.dylib      |        |        | x      | x      | x      | x      | x      |
| libswiftUIKit.dylib                  | x      | x      | x      | x      | x      | x      | x      |
| libswiftUniformTypeIdentifiers.dylib |        |        | x      | x      | x      | x      | x      |
| libswift_unistd.dylib                |        |        |        |        |        |        | x      |
| libswiftVideoToolbox.dylib           |        |        |        |        |        | x      | x      |
| libswiftVision.dylib                 | x      | x      | x      | x      | x      | x      | x      |
| libswiftWatchKit.dylib               | x      | x      | x      | x      | x      | x      | x      |
| libswiftWebKit.dylib                 |        |        | x      | x      | x      | x      | x      |
| libswiftXPC.dylib                    |        |        |        |        | x      | x      | x      |
 x      |
