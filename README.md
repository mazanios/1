1. Еhe link is not a repository.
2. What you need to run.
3. The size of the image passed to the output engine (not the original loaded one!).
4. FPS or MS required for output.
5. Notes (if any).

# ObjectDetection4TouchDesginer
1. https://github.com/T-Sumida/ObjectDetection4TouchDesginer.
2. Environment.
   - Windows10 home 64bit.
   - TouchDesigner.
   - Anaconda.
   $conda create -n {env_name} python=3.7.2.
   $activate {env_name}.
   $pip install -r requirements.txt.
4. ~7 seconds.
# Onnx-efficientdet
1. https://github.com/phantrdat/onnx-efficientdet.
2. For CPU:
   - pip install onnxruntime.
   Install protobuf: 
   - pip install protobuf==3.12.2
   Convert pytorch model from [https://github.com/zylo117/Yet-Another-EfficientDet-Pytorch](https://github.com/zylo117/Yet-Another-EfficientDet-Pytorch)
3. input_sizes = [512, 640, 768, 896, 1024, 1280, 1280, 1536].
4. ~0.24 seconds.
# Onnx-docker(yoloV3_object_detection_onnxruntime_inference.ipynb)
1. https://github.com/onnx/onnx-docker/tree/master/onnx-ecosystem/inference_demos.
2. install requirements:
   pip install onnx
   pip install onnxruntime
3. image_size = (416, 416).
4. ~0.9 seconds.
