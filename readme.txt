The file structure is the same as current structure

├── images
│├── train
│├── test
├── output
│├── label_map.pkl
│├── model_epoch_30.pth
│├── model_epoch_50.pth
│└── predictions.json
├── preproccesing_scripts
│├── 71_segments.csv
│├── bbox_71_annotations.csv
│├── download_images.ipynb
│├── eda.ipynb
│├── reformat_csv_files.ipynb
│├── top30_annotations.csv
│└── train_test.ipynb
├── modelling.ipynb
├── readme.txt
├── test_with_size_fixed.json
└── train_with_size_fixed.json

1. the images are stored in /images/train, /images/test
2. the model weights, predictions.json, are stored in /output
3. modeling contains code to run the faster-rcnn and view predictions on test images
4. /preprocessing/eda.ipynb contains the code to view original annotations on test images (use the img_num code from modelling)