# Dataset
The folder contains the scraped parasitic images from [DPDx A-Z](https://www.cdc.gov/dpdx/az.html) webpage of `cdc.gov` and some manually picked images.

For dataset distribution refer to [Data Processing folder](.\Data Processing\readme.md).
## Files
- Folders:
  - `train`: Contains 1140 images and a CSV file for training network
  - `val`: Contains 38 images and a CSV file for validation/fine-tuning
  - `test`: Contains 39 images and a CSV file for evaluation
- 7zips:
  - `Parasitic.7z`: Contains initial 511 images and a CSV file
  - `Dataset.7z`: Contains 563 images(52 manually picked) and a CSV file
  - `Train.7z`: Compressed `Train` folder
  - `Val.7z`: Compressed `Val` folder
  - `Test.7z`: Compressed `Test` folder

### Extract compressed files(7zip):
To unzip `.7z` files, download a [7-zip](https://www.7-zip.org/) application file from [here](https://www.7-zip.org/download.html).
For command line extraction, lets take `Train.7z`, run the following command in your command shell:
```
7z x Train.7z
```
