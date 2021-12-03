# Dog-Breed-Detection

### Image Classification in TFLite
_***TensorFlow Lite is a set of tools that enables on-device machine learning by helping developers run their models on mobile, embedded, and IoT devices.***_

One of the key features of TLite is, it is optimized for on-device machine learning by addressing 5 key constraints.
1. _Latency_- There's no round-trip to a server
1. _Privacy_- No personal data leaves the device
1. _Connectivity_- Internet connectivity is not required
1. _Size_- Reduced model and binary size
1. _Power Consumption_- Efficient inference and a lack of network connections 
---
### About the Model
**I have developed a model to detect dog breeds**. The data for training was collected from the Stanford Dog Data Set available freely on Kaggle and Tensorflow Lite framework was used for Data Augmentation and Model building. The dataset in total has 120 classes of different dog breeds with around 150 images in each class.

**The model achieved an accuracy of:**
1. ***74.25% (Using ResNet 50)***- Average Training time per Epoch Cycle= 143 Seconds
1. ***87.12% (Using ResNet V2 152)***- Average Training time per Epoch Cycle= 507 Seconds
1. ***88.73% (Using Efficientnet V2 Imagenet1k_b3)***- Average Training time per Epoch Cycle= 192 Seconds 

```
Note : These accuracy values are for test data set
```
---

