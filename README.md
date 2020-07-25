## ONNX to TFLite Conversion

This notebook demonstrates the conversion process from an **.ONNX** model _(exported from MATLAB)_ to a **.tflite** model _(to be used within TensorFlow Lite, on an Android or iOS device.)_ In addition to conversion, this notebook contains cells for running inference using a set of test images to validate that predictions remain consistent across converted models.

> **Note:** TensorFlow's API is constantly evolving. This notebook was written in November of 2019, during the transition period from TF 1.X to TF 2.X, so it is likely that relevant APIs will have updated since.
