# APF-YOLOv8

Hy, Peace be upon you,

This repository contains the source code for the paper, **"APF-YOLOV8: Enhancing Multiscale Detection and Intra-Class Variance Handling for UAV-Based Insulator Power Line Inspections"**, submitted to **F1000Research** on January 02, 2025. 

### Paper Abstract

UAV-based power line inspections offer a safer, more efficient alternative to traditional methods, but insulator detection presents key challenges: multiscale object detection and intra-class variance. Insulators vary in size due to UAV altitude and perspective changes, while their visual similarities across types (e.g., glass, porcelain, composite) complicate classification. To address these issues, we introduce APF-YOLO, an enhanced YOLOv8-based model integrating the Adaptive Path Fusion (APF) neck and the Adaptive Feature Alignment Module (AFAM). AFAM balances fine-grained detail extraction for small objects with semantic context for larger ones through local and global pathways by integrating advanced attention mechanisms. This work also introduces the Merged Public Insulator Dataset (MPID), a comprehensive dataset designed for insulator detection, representing diverse real-world conditions such as occlusions, varying scales, and environmental challenges. Evaluations on MPID demonstrate that APF-YOLO surpasses state-of-the-art models with different neck configurations, achieving at least a +2.71% improvement in mAP@0.5:0.9 and a +1.24% increase in recall, while maintaining real-time performance in server-grade environments. Although APF-YOLO adds computational requirements, these remain within acceptable limits for real-world applications. Future work will optimize APF-YOLO for edge devices through techniques such as model pruning and lightweight feature extractors, enhancing its adaptability and efficiency. Combined with MPID, APF-YOLO establishes a strong foundation for advancing UAV-based insulator detection, contributing to safer and more effective power line monitoring.

### Data
The dataset used in this study can be accessed at the following link: 

https://github.com/phd-benel/MPID


### Model Architecture

The architecture of the enhanced YOLOv8 model will be upload soon. This is to protect the integrity of the contributions made in this research.

### Experimental settings
The experimental settings can be found at the following links from the ClearML MLOPS platform : 
https://app.clear.ml/projects/0625a3d38e554e7a84e20e37b3240f4b/experiments/837c6f87f72f4dc9b69dead7d65d9238/output/execution
https://app.clear.ml/projects/0625a3d38e554e7a84e20e37b3240f4b/experiments/cf9ee7bbc0554f94966f9ab9bb6216a2/output/execution
https://app.clear.ml/projects/0625a3d38e554e7a84e20e37b3240f4b/experiments/0f4d1d59ef7249aa865651d1fc3fad0c/output/execution
https://app.clear.ml/projects/0625a3d38e554e7a84e20e37b3240f4b/experiments/5ca45b30180b4266a56307cf91a95d70/output/execution
https://app.clear.ml/projects/0625a3d38e554e7a84e20e37b3240f4b/experiments/5035deb1de8b465aa90b1c0ff136a715/output/execution
https://app.clear.ml/projects/0625a3d38e554e7a84e20e37b3240f4b/experiments/3bd82eda556d4266a28785f5f74b7aca/output/execution
https://app.clear.ml/projects/0625a3d38e554e7a84e20e37b3240f4b/experiments/cbc5c11fdf73488081bec6bc62fbe5e2/output/execution
https://app.clear.ml/projects/0625a3d38e554e7a84e20e37b3240f4b/experiments/5d2369e1d3a4489792c83fb063d36489/output/execution
https://app.clear.ml/projects/0625a3d38e554e7a84e20e37b3240f4b/experiments/f3540e5bbdd1449d88ac791636428783/output/execution
https://app.clear.ml/projects/0625a3d38e554e7a84e20e37b3240f4b/experiments/16d8341d69514ac2bdff42ec59171dd7/output/execution
https://app.clear.ml/projects/0625a3d38e554e7a84e20e37b3240f4b/experiments/f042e206ced248e19ce7880d01f1609b/output/execution
https://app.clear.ml/projects/0625a3d38e554e7a84e20e37b3240f4b/experiments/c2be5b5efc7b4702800d803a7f213ecf/output/execution
https://app.clear.ml/projects/0625a3d38e554e7a84e20e37b3240f4b/experiments/c4b910cbbd3942d2ab661fdd3cecb0ab/output/execution


### Code
The source code for the enhanced YOLOv8 model will be made publicly available upon acceptance of the paper . This is to protect the integrity of the contributions made in this research.

### Citation
The paper is currently under review for publication in **F1000Research**. Once accepted, please cite the paper using the following format (to be updated).

### License
This project is licensed under the **CC BY 4.0 **. Please refer to the `LICENSE.md` file for detailed information.

### Acknowledgments
We would like to extend our gratitude to the **Ultralytics YOLOv8** community for their invaluable contributions and resources, which significantly aided in the development of this research.

### Contact
For further information or inquiries, please feel free to report an issue on this repository. I am happy to provide assistance and clarification as needed.

