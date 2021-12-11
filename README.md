# FloodWater Detection using satilite imagery


Natural disasters such as flooding are the most frequent and the most expensive in the world. The government and humanitarian organizations must be able to precisely determine flood extent in near real-time during a flood event so that early warning systems can be strengthened, risks assessed, and relief efforts geared toward the most vulnerable groups can be directed. However, ground-based measures only measure water depth, limit their application to specific locations, and cost a great deal to maintain. It is very important to monitor and map flood hazards, as they contribute significantly to risk management. This dataset consists of synthetic aperture radar (SAR) images taken over several regions that experienced flooding. These satellite images are acquired using a microwave sensor aboard a satellite, which is used to acquire SAR imagery. The SAR system transmits pulses of electromagnetic waves to the Earth and records the echoes reflected. Unlike optical satellite imagery, which reflects solar light and can only provide a picture of the Earth's surface during the day and in the absence of clouds, this form of imagery uses the reflected light to provide images of the Earth's surface. In this project, we have been using various deep learning models such as U-Net, custom encoder-decoder model and Seg-Net model which is taken from one of the Deep learning research papers. Out of them, the U-Net model is giving better accuracy than others, so we applied some pretrained backbone models from tensorflow applications such as MobileNetV3, ResNet-50 etc.
