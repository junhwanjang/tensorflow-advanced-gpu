## Using the iOS Demo App

Please read the [TensorFlow Lite iOS Demo App](https://www.tensorflow.org/lite/demo_ios) page.

## Using the iOS Demo App with support for select TensorFlow ops

TODO(ycling): Link to the select TensorFlow ops documentation when it's
done.

Follow the guide to TensorFlow Lite iOS Library with support for select
TensorFlow ops, then open `tflite_camera_example_with_flex.xcodeproj`.
Note that this project setting is not using CocoaPod.

## Using the iOS Demo app with advanced gpu

Write codes following with [Tensorflow Lite iOS gpu delegate](https://www.tensorflow.org/lite/performance/gpu_advanced)

Applied gpu delegate and binding metal buffer to Input / Output tensor

Device inference Time:  average 20ms ~ 25ms (iphone 8)

[How to build]
``` cd tensorflow-advanced-gpu/tensorflow/lite/examples/ios```
``` /download_models.sh ```
``` cd camera ```
``` pod install ```
- Open tflite_camera_example.xcworkspace 
