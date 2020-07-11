# tflite-runtime
Compiled TensorFlow lite runtime. This interpreter-only package is a fraction the size of the full TensorFlow package and includes the bare minimum code required to run inferences with TensorFlow Lite—it includes only the `tf.lite.Interpreter` Python class. This small package is ideal when all you want to do is execute `.tflite` models and avoid wasting disk space with the large TensorFlow library.

The original build instructions can be found here: https://github.com/tensorflow/tensorflow/tree/master/tensorflow/lite/tools/pip_package

## Installation

To install, run `pip3 install` and pass it the appropriate Python wheel URL from the following table.

For example, if you have Raspberry Pi that's running Raspbian Buster (which has Python 3.7), install the Python wheel as follows:
