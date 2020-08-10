# bamboo_detection
This is a dataset that I collected to train my own Bamboo detector with **TensorFlow's Object Detection API**. Images are from Google Images and Google Maps. In total, there are 160 images (144 are used for training and 16 for validation).
## Getting Started
###### Folder Structure:
+ annotations: contains the xml files in PASCAL VOC format
+ data: contains the input file for the TF object detection API and the label files (csv)
+ images: contains the image data in jpg format
+ training: contains the pipeline configuration file, frozen model and labelmap
    - generate_tfrecord.py is used to generate the input files
      for the TF API and xml_to_csv.py is used to convert the xml files into one csv
