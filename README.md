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
- Latent Space Plots
    - exp0
    ![aspect ratio](./exp0/ar_L-S_evolution.gif)

    ![incident angle](./exp0/angle_LS_evolution.gif)
    
    - exp1
    ![aspect ratio](./exp1/ar_L-S_evolution.gif)
    
    ![incident angle](./exp1/angle_LS_evolution.gif)
    
    - exp2
    ![aspect ratio](./exp2/ar_L-S_evolution.gif)
    
    ![incident angle](./exp2/angle_LS_evolution.gif)
