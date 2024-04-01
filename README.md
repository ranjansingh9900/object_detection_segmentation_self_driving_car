## object_detection_segmentation_self_driving_car
 ## About Dataset [click here](https://docs.google.com/document/d/1wLVyAp8HUIT9b4_SVX5RMHUrkyVYUSmb/edit?usp=drive_link&ouid=117477926192622339096&rtpof=true&sd=true)

1. **src**: This directory contains the source code of the project.

    - **config**: [link](https://drive.google.com/file/d/1qd0hQX3P1epQ6XZF2tIEUrgGydBkqfOI/view?usp=drive_link) Contains configuration files for different tasks.
    - **dataset**: Contains classes and utilities related to dataset handling.
        - **bdd.py**: [link](https://drive.google.com/file/d/1R6zdDsTYglLwevYFNcW1PEm6i_5zOKQw/view?usp=drive_link) Superclass dataset, possibly defining common functionality for different dataset types.
        - **bdd_detection.py** [link](https://drive.google.com/file/d/1vuL83RXVgq58H5_pZaj5o1Eo-SBiFg1O/view?usp=drive_link) , **bdd_drivable_segmentation.py** [link](https://drive.google.com/file/d/15NG9b0bQ0YvQU1fiW-xzSXfloKhcX0RB/view?usp=drive_link) , **bdd_instance_segmentation.py** [link](https://drive.google.com/file/d/1lrolPIEmRnnzY5WAc-fRWirzsaJkkNNk/view?usp=drive_link) : Subclasses for specific tasks.
        - **bdd_utils.py** [link](https://drive.google.com/file/d/1unve0-1gf61UTV1cfKzuR1ljBexJ5J6R/view?usp=drive_link) : Utility functions for dataset handling.
    - **dbs**: Contains pre-created databases for testing and training.
    - **models**: Contains definitions for different models used in the project.
        - **Detection**: Models and related files for object detection tasks. Include [faster RCNN](https://drive.google.com/file/d/1t22wtl1eXlQbiFsxl3WJJo0JYRWeN6RH/view?usp=drive_link) and [detection_model](https://drive.google.com/file/d/1xEvjKuJVmmRxb46_xGyf7GrivQwP-bzU/view?usp=drive_link)
        - **Segmentation**: Models and related files for segmentation tasks.
        - includes [FCC](https://drive.google.com/file/d/1An6kNwLgdU10iTM3Aavbbb_-8JY1SEHP/view?usp=drive_link) , [DeepLabv3](https://drive.google.com/file/d/19tONS91wQQMA1X9WINfyd34AIhCdHgKH/view?usp=drive_link) , [maskRCNN](https://drive.google.com/file/d/1t240Y-sa-FBy49PZ_Acz_E1HQFqBG36J/view?usp=drive_link) 
    - **utils**: Contains utility functions.
        - **DataLoaders.py** [link](https://drive.google.com/file/d/1gUpjzV_qHpleEVBmV0lV_q1Zyngpk9qS/view?usp=drive_link): Functions for data loading.
        - **utils.py** [link](https://drive.google.com/file/d/1ckhvOvnSfXa_I1R5lK9mpPJLnq5T5vBM/view?usp=drive_link): General utility functions.
        - **Data Augmentation.ipynb** [link](https://drive.google.com/file/d/18giZyPZHIwG4sySU00Hc1ZfF4qjUJ8Ty/view?usp=drive_link): Jupyter notebook providing tutorials for data augmentation.
    - [Models](https://drive.google.com/file/d/1itDvsgFR3kqrUylKAQqVk5sBf5VawEg_/view?usp=drive_link)

2. **doc**: Documentation files, possibly including images.

3. **scripts**: Scripts for downloading data and weights.
   data.py [link](https://drive.google.com/file/d/10M0a34YnNyruFdu7tFwesfYzBpr3cr4g/view?usp=drive_link): This script likely handles the downloading and preparation of data for your project from Google Drive or another source.
   weights.py [link](https://drive.google.com/file/d/10M0a34YnNyruFdu7tFwesfYzBpr3cr4g/view?usp=drive_link): This script probably deals with downloading pre-trained model weights or checkpoints from Google Drive or another online repository.

5. **api** [link](https://drive.google.com/file/d/1iOx88-5lHbSarWHDPbxNH07ooWXg03Nb/view?usp=drive_link): Contains Flask application files for serving models via API.

6. **yolov5** [link](https://drive.google.com/file/d/1JifxHHBpoOqBfJQJp6pz7pUzvbU982Ck/view?usp=drive_link) **yolov6** [link](https://drive.google.com/file/d/1nWM86vPQRjECXsD8Bu0pwNL83hhvS3U3/view?usp=drive_link), **yolov7** [link](https://drive.google.com/file/d/1Q5y3P_5aTY2yj-Sq1I-BEgZmUez2QZK7/view?usp=drive_link): Directories possibly containing repositories for different versions of YOLO model implementations.

7. **dataset** [link](https://docs.google.com/document/d/1wLVyAp8HUIT9b4_SVX5RMHUrkyVYUSmb/edit?usp=drive_link&ouid=117477926192622339096&rtpof=true&sd=true): Directory containing the dataset used in the project.

8. **train.py** [link](https://drive.google.com/file/d/1g4xKy4ZAhCWJq59FXrZQMDlFy_7wIQSE/view?usp=drive_link): Script for training models.

9. **test.py** [link](https://drive.google.com/file/d/1qPPoHh_nSYFJcAhLpHXhReDbP7O5T68K/view?usp=drive_link): Script for testing models.

10. **detect.py** [link](https://drive.google.com/file/d/1BGJAvzrAX1izL4chG_BJNERp9zf-LiBS/view?usp=drive_link): Script for running inference.

11. **prepare.py** [link](https://drive.google.com/file/d/16VEc2f-Anq6892vxZlYs4lqLUgmkbb0Q/view?usp=drive_link): Script for preparing data for YOLO algorithms.

12. **util.py** [link](https://drive.google.com/file/d/16Yn-__I00YRPeUX3fshi_ObDpu-AvZRn/view?usp=drive_link): Contains various utility functions related to training, testing, and detection.

This structure indicates a well-organized project with clear separation of concerns, making it easier to maintain and extend. It also includes documentation and scripts for data handling and model serving, which are essential for practical deployment.
  
  
 

