# Experiments
This repository is used to save **the history log of experiments**.
## File structure 
Each `exp [number]` means one single experiment. It includes the following files:
- config.yaml --> Config of my experiment, it includes almost setting of experiments.

## Description
### Latent_Disentangle
Let latent dimension = 2. Check exp_num/config.yaml for more detial.
- Metrics of vae and mlp

|      | 0   | 1   | 2   |
| ---- | --- | --- | --- |
| *beta weight* | 0.1 | 0.5 | 1.0 |
| vae->IoU  |0.55 |  0.43   |  0.35   |
| mlp->R2  | 0.95 |  0.88   |  0.9  |

- Loss curve
    - exp0

    |![vae](./exp0/vae.png)| ![vae_bce_kld](./exp0/vae_bce_kld.png)| ![mlp](./exp0/mlp.png)|
    |--- | ---| --- |
    - exp1

    |![vae](./exp1/vae.png)| ![vae_bce_kld](./exp2/vae_bce_kld.png)| ![mlp](./exp1/mlp.png)|
    |--- | ---| --- |
    - exp2

    |![vae](./exp2/vae.png)| ![vae_bce_kld](./exp2/vae_bce_kld.png)| ![mlp](./exp2/mlp.png)|
    |--- | ---| --- |
    
    <!-- - exp3 -->
    <!---->
    <!-- |![vae](./exp3/vae.png)| ![vae_bce_kld](./exp3/vae_bce_kld.png)| ![mlp](./exp3/mlp.png)| -->
    <!-- |--- | ---| --- | -->
    
    - exp4

    |![vae](./exp4/vae.png)| ![vae_bce_kld](./exp4/vae_bce_kld.png)| ![mlp](./exp4/mlp.png)|
    |--- | ---| --- |

    <!-- - exp5 -->
    <!---->
    <!-- |![vae](./exp0/vae.png)| ![vae_bce_kld](./exp0/vae_bce_kld.png)| ![mlp](./exp0/mlp.png)| -->
    <!-- |--- | ---| --- | -->




- Latent Space Plots
    - exp0

    |![aspect ratio](./exp0/ar_LS_evolution.gif)| ![incident angle](./exp0/angle_LS_evolution.gif)|
    |--- | ---|
    - exp1

    | ![aspect ratio](./exp1/ar_LS_evolution.gif)|![incident angle](./exp1/angle_LS_evolution.gif) |
    |--- |--- |
    - exp2

    | ![aspect ratio](./exp2/ar_LS_evolution.gif) |   ![incident angle](./exp2/angle_LS_evolution.gif)|
    |--- | ---|
    
    <!-- -exp3 -->

    -exp4

    | ![aspect ratio](./exp4/ar_LS_evolution.gif) |   ![incident angle](./exp4/angle_LS_evolution.gif)|
    |--- | ---|

### Reconstruction 
- exp0

| origin |![particle01](./exp0/inspect/original_pparticle_0000_00_idx0.png)|![particle02](./exp0/inspect/original_pparticle_0000_01_idx1.png) | ![particle03](./exp0/inspect/original_pparticle_0000_02_idx2.png) |
|--- |--- |--- |--- |
| reconstruction |![particle01](./exp0/inspect/reconstructed_pparticle_0000_00_idx0.png)|![particle02](./exp0/inspect/reconstructed_pparticle_0000_01_idx1.png)  |![particle03](./exp0/inspect/reconstructed_pparticle_0000_02_idx2.png) |
- exp1

| origin |![particle01](./exp1/inspect/original_pparticle_0000_00_idx0.png)|![particle02](./exp1/inspect/original_pparticle_0000_01_idx1.png) | ![particle03](./exp1/inspect/original_pparticle_0000_02_idx2.png) |
|--- |--- |--- |--- |
| reconstruction |![particle01](./exp1/inspect/reconstructed_pparticle_0000_00_idx0.png)|![particle02](./exp1/inspect/reconstructed_pparticle_0000_01_idx1.png)  |![particle03](./exp1/inspect/reconstructed_pparticle_0000_02_idx2.png) |

- exp2

| origin |![particle01](./exp2/inspect/original_pparticle_0000_00_idx0.png)|![particle02](./exp2/inspect/original_pparticle_0000_01_idx1.png) | ![particle03](./exp2/inspect/original_pparticle_0000_02_idx2.png) |
|--- |--- |--- |--- |
| reconstruction |![particle01](./exp2/inspect/reconstructed_pparticle_0000_00_idx0.png)|![particle02](./exp2/inspect/reconstructed_pparticle_0000_01_idx1.png)  |![particle03](./exp2/inspect/reconstructed_pparticle_0000_02_idx2.png) |
- exp4

| origin |![particle01](./exp4/inspect/original_pparticle_0000_00_idx0.png)|![particle02](./exp4/inspect/original_pparticle_0000_01_idx1.png) | ![particle03](./exp4/inspect/original_pparticle_0000_02_idx2.png) |
|--- |--- |--- |--- |
| reconstruction |![particle01](./exp4/inspect/reconstructed_pparticle_0000_00_idx0.png)|![particle02](./exp4/inspect/reconstructed_pparticle_0000_01_idx1.png)  |![particle03](./exp4/inspect/reconstructed_pparticle_0000_02_idx2.png) |
