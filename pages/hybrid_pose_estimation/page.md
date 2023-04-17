# Hybrid Pose Estimation

This page serves as an online space for hosting a visual and animated appendix for the paper titled _Hybrid pose estimation of space debris with neural networks developed using photorealistic synthetic data_ which can be seen at _(link pending publication of proceedings)_.

The videos which can be seen here at the results of different pose estimation simulations, the details of which can be found in the paper.

The data used in this work can be obtained on <a href="https://www.kaggle.com/datasets/eberhardtkorf/synthetic-cubesat" target="_blank">Kaggle</a></td>.

### Perspective-n-Point (PnP) Sequence A

<p align="center">
  <video width="100%" height="auto" src="assets/pnp_seq_a.mp4" controls="controls">
</p>

### Direct-to-Filter (DtF) Sequence A

<p align="center">
  <video width="100%" height="auto" src="assets/dtf_seq_a.mp4" controls="controls">
</p>

### Perspective-n-Point (PnP) Sequence B

<p align="center">
  <video width="100%" height="auto" src="assets/pnp_seq_b.mp4" controls="controls">
</p>

### Direct-to-Filter (DtF) Sequence B

<p align="center">
  <video width="100%" height="auto" src="assets/dtf_seq_b.mp4" controls="controls">
</p>

### Perspective-n-Point (PnP) Sequence C

<p align="center">
  <video width="100%" height="auto" src="assets/pnp_seq_c.mp4" controls="controls">
</p>

### Direct-to-Filter (DtF) Sequence C

<p align="center">
  <video width="100%" height="auto" src="assets/dtf_seq_c.mp4" controls="controls">
</p>

### Tabulated Results of Simulations

| Sequence and Method | Translation Error (m) | Velocity Error (m/s) | Attitude Error (degrees) | Angular Velocity Error (degrees/s) |
|:-------------------:|:---------------------:|:--------------------:|:------------------------:|:----------------------------------:|
|      Seq. A PnP     |      **0.00182**      |        0.00021       |        **0.20129**       |             **0.02962**            |
|      Seq. A DtF     |        0.00189        |      **0.00020**     |          1.17795         |               0.13506              |
|      Seq. B PnP     |        0.02726        |        0.00152       |          10.6747         |               2.29237              |
|      Seq. B DtF     |      **0.00469**      |      **0.00049**     |        **0.92106**       |             **0.11931**            |
|      Seq. C PnP     |        0.01752        |        0.00222       |          31.2067         |               4.42044              |
|      Seq. C DtF     |      **0.00609**      |      **0.00149**     |        **4.10269**       |             **0.87454**            |
|     Mean of PnP     |        0.01553        |        0.00131       |          14.0278         |               2.24747              |
|     Mean of DtF     |      **0.00422**      |      **0.00072**     |        **2.06722**       |             **0.37630**            |