# COCO-Object-Detection-dataset-in-TFRecord
You can use the notebook to create TFRecord version of COCO Object Detection dataset.

COCO (Common Objects in COntext) is a popular dataset in Computer Vision. It contains annotations for Computer Vision tasks - object detection, segmentation, keypoint detection, stuff segmentation, panoptic segmentation, densepose, and image captioning. For more details visit https://cocodataset.org/#format-data

The Tensor Processing Unit (TPU) hardware accelerators are very fast. The challenge is often to feed them data fast enough to keep them busy. Google Cloud Storage (GCS) is capable of sustaining very high throughput but as with all cloud storage systems, initiating a connection costs some network back and forth. Therefore, having our data stored as thousands of individual files is not ideal. We are going to batch the COCO dataset with object detection annotations in a smaller number of files and use the power of tf.data.Dataset to read from multiple files in parallel.

View the notebook for further details. 

Kaggle notebook: https://www.kaggle.com/karthikeyanvijayan/coco-object-detection-dataset-in-tfrecord

You can view the generated TFRecord files in the Kaggle dataset: https://www.kaggle.com/karthikeyanvijayan/coco-2017-tfrecords


