# XDU-Liyukou Dataset
The **XDU-Liyukou dataset** is designed for **multimodal change detection**. It covers an area of Liyukou, Huyi, Xi'an, Shannxi Province. The dataset consists of a hyperspectral image (HSI) acquired on April 6, 2023, and an RGB image captured on November 18, 2022.

- **RGB Image** : collected by the FILR DUO Pro R sensor, spatial size 700 × 350.

- **HSI** : collected by the Micro-Hyperspec sensor, spatial size 200 × 150, with 194 spectral bands spanning 0.4–1.0 um. After removing noisy bands, 194 effective bands are retained for change detection.
  
- **Ground-Truth Map** :The ground-truth map contains three colors, where green pixels and the yellow pixels represent the changed and unchanged areas, respectively, and the blue pixels represent objects whose changed status is uncertain

The dataset encompasses diverse scenes,including trees, roads, soil, and buildings, showcasing the dynamic changes of various ground objects such as farmlands and land covers. 

## Citation

If you use the **XDU-Liyukou dataset** in your research, please cite:

```bibtex
@article{XDU_Liyukou_2025,
  author  = {Wenqian Dong and Junying Ren and Song Xiao and Leyuan Fang and Jiahui Qu and Yunsong Li},
  title   = {Cycle Translation-Based Collaborative Training for Hyperspectral-RGB Multimodal Change Detection},
  journal = {IEEE Transactions on Image Processing},
  year    = {2025},
  note    = {submitted}
}
