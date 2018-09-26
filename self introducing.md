# 오승영

* Nvidia GPU:
  * Prebuilt binaries are now (as of TensorFlow 1.11) built against cuDNN 7.2 and TensorRT 4. See updated install guides: [Installing TensorFlow on Ubuntu](https://www.tensorflow.org/install/install_linux#tensorflow_gpu_support)
* Google Cloud TPU:
  * Experimental tf.data integration for Keras on Google Cloud TPUs.
  * Experimental / preview support for eager execution on Google Cloud TPUs.
* DistributionStrategy:
  * Add multi-GPU DistributionStrategy support in tf.keras. Users can now use `fit`, `evaluate` and `predict` to distribute their model on multiple GPUs.
  * Add multi-worker DistributionStrategy and standalone client support in Estimator. See [README] (https://github.com/tensorflow/tensorflow/tree/master/tensorflow/contrib/distribute) for more details.
* Add C, C++, and Python functions for querying kernels
