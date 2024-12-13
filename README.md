# Classifying Animal Images Using CNN's

## Data:
Our data was taking from the COCO dataset website : https://cocodataset.org/#download
We used the 2017 and 2014 datasets, which can be downloaded from the website

## Steps:
  # Part 1:
  1. Downloaded data from COCO website
  2. Filter dataset by pictures that contain an animal
  3. Create set of unique labels corresponding to each animal class in the dataset (10 total)
  4. Extract corresponding image annotations from annotation subdirectory
  5. Convert data to YOLO compataible format/file structure
  6. Normalize data
  7. Download YOLO model
  8. Train YOLO model for desired number of epochs, batch size, etc. on the training dataset
  9. Examine training metrics and further train / fine-tune the model if needed
  10. Test model on test-dataset. Examine the model's predictions using fiftyone library - https://docs.voxel51.com/integrations/coco.html
  # Part 2:
  1. Download BLIP model.
  2. Test BLIP model on several images, examine captions.
  3. Input output from YOLO model as text string to BLIP, test again.
  4. Experiment with various text string formats, testing on a wide variety of images.


*Reference project.jpnyb for Part 1 steps 1-6, YOLOTraining.jpnyb for Part 1 steps 7-10, and Part 2.
