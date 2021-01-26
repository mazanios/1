1. ссылка не репозиторий
2. что нужно чтобы запустить
3. size of the image passed to the inference engine (not the original one loaded!)
4. FPS или ms needed per inference
5. remarks (if any)
# ObjectDetection4TouchDesginer
1) https://github.com/T-Sumida/ObjectDetection4TouchDesginer
2)Environment
   - Windows10 home 64bit
   - TouchDesigner
   - Anaconda
   $conda create -n {env_name} python=3.7.2
   $activate {env_name}
   $pip install -r requirements.txt
3)
4)~7 seconds
# onnx-efficientdet
1) https://github.com/phantrdat/onnx-efficientdet
2) For CPU:
   - pip install onnxruntime
   Install protobuf: 
   - pip install protobuf==3.12.2
   Convert pytorch model from [https://github.com/zylo117/Yet-Another-EfficientDet-Pytorch](https://github.com/zylo117/Yet-Another-EfficientDet-Pytorch)
3)input_sizes = [512, 640, 768, 896, 1024, 1280, 1280, 1536]
4)~0.24 seconds
# onnx-docker(yoloV3_object_detection_onnxruntime_inference.ipynb)
1)https://github.com/onnx/onnx-docker/tree/master/onnx-ecosystem/inference_demos
2)### install requirements
   pip install onnx
   pip install onnxruntime
3)image_size = (416, 416)
4)~0.9 seconds
