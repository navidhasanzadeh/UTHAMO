# UTHAMO
UTHAMO: A Multi-Modal Wi-Fi CSI Dataset for Hand Motion Recognition

The link to download the UTHAMO dataset:

https://ieee-dataport.org/documents/uthamo-multi-modal-wi-fi-csi-based-hand-motion-dataset-0

**Abstract**

UTHAMO is a multi-modal dataset developed for Wi-Fi-based human activity recognition (HAR), focusing on hand motion classification and generalization. The dataset contains Channel State Information (CSI) recordings of four right-hand gestures—Circle, Left-right, Up-Down, and Push-Pull—performed by six adult participants in a controlled indoor environment. Gestures were recorded across four body orientations (0°, 45°, 90°, and 180°) using five ASUS RT-AC86U access points, each with three antennas operating in passive monitor mode at 100 Hz in the 2.4GHz band. A Raspberry Pi served as the transmitter. Each gesture sample consists of five seconds of CSI data, collected over 20 trials per gesture–orientation pair, resulting in a total of 1,920 labeled samples. CSI was extracted using the Nexmon toolkit, yielding complex-valued matrices of size 3x64x500 per AP. To enable multi-modal verification and cross-modal learning, the dataset also includes synchronized video recordings* from six perspectives—five cameras positioned behind each access point and one user-facing camera—as well as motion data from an inertial measurement unit (IMU) worn on the user’s wrist. The IMU captures accelerometer, gyroscope, and magnetometer signals during gesture execution. The gesture set was designed to exhibit similar two-dimensional projections in different planes, making them difficult to distinguish when the observer’s viewpoint is unknown. This configuration creates a challenging benchmark for evaluating the robustness and generalization performance of HAR models under varying perspectives and sensing modalities. 

**Relevant Works**

1- MORIC: https://arxiv.org/abs/2506.12997
```bibtex
@article{hasanzadeh2025dorf,
  title={DoRF: Doppler Radiance Fields for Robust Human Activity Recognition Using Wi-Fi},
  author={Hasanzadeh, Navid and Valaee, Shahrokh},
  journal={arXiv preprint arXiv:2507.12132},
  year={2025}
}
```

2- DoRF: https://arxiv.org/abs/2507.12132
```bibtex
@article{hasanzadeh2025moric,
  title={MORIC: CSI Delay-Doppler Decomposition for Robust Wi-Fi-based Human Activity Recognition},
  author={Hasanzadeh, Navid and Valaee, Shahrokh},
  journal={arXiv preprint arXiv:2506.12997},
  year={2025}
}
```

**Citing UTHAMO dataset**

Please cite as:

```bibtex
@data{qjfg-s580-25,
doi = {10.21227/qjfg-s580},
url = {https://dx.doi.org/10.21227/qjfg-s580},
author = {Navid Hasanzadeh and Radomir Djogo and Hojjat Salehinejad and Shahrokh Valaee},
publisher = {IEEE Dataport},
title = {UTHAMO: A Multi-Modal Wi-Fi CSI-Based Hand Motion Dataset},
year = {2025}}
```


