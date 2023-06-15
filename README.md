# Flying Beam

Flying beam technology involves using sensors and algorithms to analyze the characteristics of objects passing through a sorting machine. Here's a simplified explanation of how it works:

**Material feeding**: The sorting machine receives a continuous stream of mixed materials or objects, such as plastic recyclables and are transported along a conveyor belt.

**Reflection and detection**: A beam of light, usually infrared, is projected across the width of the conveyor belt. The objects interact with the light as they pass through the flying beam. Different materials or objects reflect light differently based on their unique properties, such as color, transparency, or shape.

**Sensor detection**: Sensors positioned on the other side of the conveyor belt detect the reflections and collect data on the objects' characteristics.

**Analysis and decision-making**: The collected data is analyzed by algorithms, which compare the detected characteristics to pre-defined sorting criteria. The algorithms determine the type or category of each object.

**Sorting mechanism**: Based on the analysis, the sorting machine activates appropriate tools, such as air jets or mechanical arms, to divert or separate the objects into different streams or collection bins which can also be replaced by actuators that we currently have.

![image](https://github.com/abdulla-plaper/Flying_Beam/assets/132251249/b3fd1494-179b-44c0-8d66-ae40646b5149)

Due to the unsuitability of the product offered by TOMRA(INNOSORT FLAKE) for our RVM, which has dimensions of approximately 2 meters in width and weighs 1000kg, we are unable to implement it. Therefore, we will need to undertake a DIY approach to develop and integrate the sensor ourselves.

# What is the difference between our sensor and Flying Beam's sensor?
Both use the same sensor, which is the NIR spectrometer and along with that Flying Beam uses a color camera to enhance the sorting capabilities, so now it's just up to us to construct a version ourselves.

# DIY a flying beam?

We have the opportunity to enhance our existing RVM design by incorporating the Flying Beam technology. With some modifications, we can integrate the technology into our current setup. Here's a proposed approach:

Conveyor Belt Placement: Instead of having the sensor upfront, we can shift the entire system to the middle of the machine. This positioning allows the sensor to be placed above the conveyor belt, while customers will have a clear view of the conveyor belt and not the sensor.

Improved Object Rejection: To handle objects that the sensor cannot detect or that the machine cannot accept, we can implement a system that reverses the direction of the conveyor belt. This mechanism will return the object to the owner. Additionally, an error message can be displayed to notify the user of the issue.

The benefits of this upgraded system include:

Enhanced User Experience: By moving the detection system away from the user's point of view, we improve the overall user experience. Customers will have an unobstructed view of the conveyor belt, making the process more engaging and user-friendly.

Optimal Lighting Conditions: Shifting the detection system further into the machine allows for better control over lighting conditions. This reduces the potential interference caused by external light sources and dust interference, leading to more accurate and reliable detections. It helps minimize erroneous results that might occur with our current system.

we also need to develop Image Processing and Analysis algorithms as we integrate an optical camera for plastic classification along with a NIR spectrometer and LED for illumination,for sorting mechanism we also need to change the system so include actuators to be able to push the plastic into their respective bins



