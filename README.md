---

## Overview

AVFuseFormer is a computationally efficient audio-visual speech separation framework designed to effectively exploit complementary audio and visual information. It incorporates:

* **LGAF**, which establishes dynamic cross-modal interactions and adaptively aggregates complementary audio-visual information.
* **DFBN**, which models local and global contexts together with temporal and channel-wise dependencies.
* A **hierarchical encoder–decoder architecture**, which integrates multimodal fusion and sequence modeling for efficient speech separation.

---

## Network Architecture

### AVFuseFormer

### Core Modules

---

## Real-World Demonstration

To evaluate the effectiveness of AVFuseFormer on real-world audio-visual speech data, we test the model using several video recordings collected from YouTube. Each recording contains overlapping speech from two speakers under different facial-pose and head-motion conditions.

### Demo Video

https://github.com/user-attachments/assets/96e16abe-bd4e-4187-a4cc-caf40e977b46

### Full Demo Collection

The complete set of real-world separation demonstrations can also be accessed and downloaded via Google Drive.

### Demo Conditions

| Videos | Facial pose and motion                                                     |
| :----: | :------------------------------------------------------------------------- |
|   1–2  | The speakers mainly maintain frontal facial poses.                         |
|   3–5  | The speakers exhibit varying degrees of side-facing poses and head motion. |

These examples demonstrate the effectiveness of AVFuseFormer under both relatively controlled frontal-view conditions and more challenging scenarios involving substantial pose variations and head movements.

---

## Source Code

> [!NOTE]
> The source code and pretrained models will be made publicly available upon acceptance of the paper. Please stay tuned for future updates.

---

## Contact

For questions regarding this work, please open an issue in this repository.
