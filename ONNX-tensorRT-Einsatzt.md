# Wie wird ONNX-Models mit tensorRT auf gezielte Plattform deployiert.
ONNX-Models werden auf gezielte Plattformen als API zum Einstaz kommen.
Dafür gibt es viele Frameworken, die genutzt werden können.
1. **_[TensorRT inference Server](https://github.com/NVIDIA/tensorrt-inference-server)_**

Eine Praktische Tutoriel, ONNX-Models mit TensorRT serveing  ist auf diesem [Link](https://medium.com/@fanzongshaoxing/deploy-onnx-models-with-tensorrt-inference-serving-894629d86e9a) nachzufolgen. TensorRT inference sever bittet mehr Vorteil, denn es schließt die mehrere Backend Framework ein. vorallem TensorRT, Tensorflow, ONNX, pyTorch, and Caffe2.

Ein Überblck zum Einsatzt des Models mit tensorRT ist durch dieses unterstehende Bild zu veranschaulichen 

![NVIDIA TensorRT Inference Server Architecture](https://miro.medium.com/max/625/0*bR2OBenLI9vIWYR1.png "NVIDIA TensorRT Inference Server Architecture")
_<center>[NVIDIA TensorRT Inference Server Architecture](https://medium.com/@fanzongshaoxing/deploy-onnx-models-with-tensorrt-inference-serving-894629d86e9a)</center>_

2. **_[Tensorflow Serving](https://github.com/tensorflow/serving)_**

Hier Wird Tensoflow + TRT benutzt, um das Model zum einsetzen.

3. **_[Models Server]()_**

Zu betrachten werden hier frameworks, die zum Serving des Maschinelles Models dienen. bsp. MLFlow, KubeFlow, und RedisAI

4. **_[Pure Python Backend Service]()_**

Es geht um die Ausnutzung von python frameworks zur aufbaue des Web-Anwendung bzw. Flask, Django zu nutzen. 
