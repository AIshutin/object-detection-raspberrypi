# object-detection-raspberrypi
My simple project for Raspberry Pi 4. The idea is to:
- observe cats near the feeder
- send photos in Telegram
- make dashboards with their feeding behaviour
- [optional] send reminders about feeding time if there is no food


## Planned performance benchmarks:

- https://github.com/WongKinYiu/yolov7 
- https://docs.openvino.ai/2023.0/omz_models_model_mobilenet_v3_small_1_0_224_tf.html
- mobilenet_v3_small from torchvision, just in case
- https://docs.openvino.ai/2023.0/omz_models_model_mobilenet_yolo_v4_syg.html
- https://docs.openvino.ai/2023.0/omz_models_model_yolo_v4_tiny_tf.html
- ... other classification models, since I am not sure if I really need detection.