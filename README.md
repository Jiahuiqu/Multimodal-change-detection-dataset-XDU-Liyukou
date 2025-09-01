# XDU-Liyukou Dataset
he **XDU-Liyukou dataset** is designed for **multimodal change detection**. It covers an area of Liyukou, Huyi, Xi'an, Shannxi Province. The dataset consists of a hyperspectral image (HSI) acquired on April 6, 2023, and an RGB image captured on November 18, 2022.

- **RGB image** : collected by the FILR DUO Pro R sensor, spatial size 700 × 350.

- **HSI** : collected by the Micro-Hyperspec sensor, spatial size 200 × 150, with 194 spectral bands spanning 0.4–1.0 um. After removing noisy bands, 194 effective bands are retained for change detection.

The dataset encompasses diverse scenes,including trees, roads, soil, and buildings, showcasing the dynamic changes of various ground objects such as farmlands and land covers. 
The ground-truth map is with three colors:
- **Green** → changed areas  
- **Yellow** → unchanged areas  
- **Blue** → regions with uncertain change status
