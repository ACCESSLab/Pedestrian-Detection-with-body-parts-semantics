# Pedestrian-Detection-with-body-parts-semantics
Pedestrian detection for autonomous cars using inference fusion of deep neural networks. BP-SSD can robustly detect body parts along with full-body pedestrians,
## Features 
This method has following adavantages:
  * **Modularity:** our framework offers a modular structure where many object detection and semantic segmentation networks can be adopted, enabling iterative development and testing. 
  * **Parallelism:** our framework can operate anchor box detection and semantic segmentation networks in parallel, resulting in better runtime efficiency.  
  * **Scalability:** our framework can also obtain higher runtime efficiency by combining relatively less complex networks.     
  * **Robustness:** our framework allow combining relatively less complex networks which can jointly provide more robust  performance at a reasonable runtime efficiency.
  * **Maintainability:** Due to the modular structure of our framework facilitates the process of adding or removing networks for different scenarios (e.g., crowded environments, highway environments, intersections, etc).
