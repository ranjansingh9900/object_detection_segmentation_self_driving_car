## object_detection_segmentation_self_driving_car
 ## About Dataset [read more about dataset](https://docs.google.com/document/d/1wLVyAp8HUIT9b4_SVX5RMHUrkyVYUSmb/edit?usp=drive_link&ouid=117477926192622339096&rtpof=true&sd=true).

1. **src**: This directory contains the source code of the project.

    - **config**: [link](https://drive.google.com/file/d/1qd0hQX3P1epQ6XZF2tIEUrgGydBkqfOI/view?usp=drive_link). Contains configuration files for different tasks.
    - **dataset**: Contains classes and utilities related to dataset handling.
        - **bdd.py**: [link](https://drive.google.com/file/d/1R6zdDsTYglLwevYFNcW1PEm6i_5zOKQw/view?usp=drive_link). Superclass dataset, possibly defining common functionality for different dataset types.
        - **bdd_detection.py** [link](https://drive.google.com/file/d/1vuL83RXVgq58H5_pZaj5o1Eo-SBiFg1O/view?usp=drive_link). , **bdd_drivable_segmentation.py** [link](https://drive.google.com/file/d/15NG9b0bQ0YvQU1fiW-xzSXfloKhcX0RB/view?usp=drive_link). , **bdd_instance_segmentation.py** [link](https://drive.google.com/file/d/1lrolPIEmRnnzY5WAc-fRWirzsaJkkNNk/view?usp=drive_link). : Subclasses for specific tasks.
        - **bdd_utils.py** [link](https://drive.google.com/file/d/1unve0-1gf61UTV1cfKzuR1ljBexJ5J6R/view?usp=drive_link). : Utility functions for dataset handling.
    - **dbs**: Contains pre-created databases for testing and training.
    - **models**: Contains definitions for different models used in the project.
        - **Detection**: Models and related files for object detection tasks.
        - **Segmentation**: Models and related files for segmentation tasks.
    - **utils**: Contains utility functions.
        - **DataLoaders.py**: Functions for data loading.
        - **utils.py**: General utility functions.
        - **Data Augmentation.ipynb**: Jupyter notebook providing tutorials for data augmentation.
    - **Notebooks**: Jupyter notebooks for tutorials and experiments on different tasks.

2. **doc**: Documentation files, possibly including images.

3. **scripts**: Scripts for downloading data and weights.

4. **api**: Contains Flask application files for serving models via API.

5. **yolov5**, **yolov6**, **yolov7**: Directories possibly containing repositories for different versions of YOLO model implementations.

6. **dataset**: Directory containing the dataset used in the project.

7. **train.py**: Script for training models.

8. **test.py**: Script for testing models.

9. **detect.py**: Script for running inference.

10. **prepare.py**: Script for preparing data for YOLO algorithms.

11. **util.py**: Contains various utility functions related to training, testing, and detection.

This structure indicates a well-organized project with clear separation of concerns, making it easier to maintain and extend. It also includes documentation and scripts for data handling and model serving, which are essential for practical deployment.
  
  
 

