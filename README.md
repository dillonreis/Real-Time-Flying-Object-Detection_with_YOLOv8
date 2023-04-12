# Real-Time-Flying-Object-Detection
Real-Time Flying Object Detection for Airspace Monitoring and Threat Identification


# Some temporary notes on what's included in here
* Flying Object Detection with YOLOv8.ipynb - where the files were produced, such as the model and plots
* All of the image data were removed in order to upload to github, so please add those back in locally to run the notebook - specifically the `test`, `train`, and `valid` folders
* A `labels.cache` file is in the `train` and `valid` folder - it took 6 hours to produce these with a GPU, so please try using these caches in your trials and ensure these files are in those folders before you run locally
* If not running on Google Colab, remember to edit `data.yaml` to specify the route of the train/test/valid folders
* The current model is only based on 10 epochs due to computation limitations, so the plots in the notebook are pretty bad due to that for now. These plots are located in `runs/detect/train13/` and the current best model is `runs/detect/train13/weights/best.pt`.
