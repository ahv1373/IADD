# IADD_Database

This repository contains the documentations and download links for 
the 2022 Iran Autonomous Driving Database (IADD). IADD aims at improving the
generalization of the deep learning-based object detectors


## 1. Image Samples
Few samples of our database are presented below:
<p align="center"><img src="image_samples/raw_data/Record020_N_Record020_N_041129.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/raw_data/Record303_D_2.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/raw_data/Record310_D_2.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/raw_data/Record400_D_2.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/raw_data/Record407_D_1.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/raw_data/Record414_D_1.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/raw_data/Record417_R_1.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/raw_data/Record427_D_2.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/raw_data/Record438_R_1.jpg" width="1080" title="Image sample 1"></p>

## 2. Annotation
IADD supports six different classes which are listed below.
- person
- car
- motorcycle
- bus
- truck
- traffic light

All annotations are provided in the YOLO format. To facilitate the annotation procedure, a [YOLOR](https://github.com/WongKinYiu/yolor)
architecture has been trained on a small-scale portion of our dataset.
Afterwards, the rest of the data are automatically annotated by the mentioned model. The errors in the predictions are then handled by expert
annotators and the potential mis-alignments are modified.

## 3. Download
Download Links for the database are presented here:
- Training data: [part1](https://drive.google.com/file/d/1wx6c8nhQ9m5wki2uhCoLqANrM8_J5tkw/view?usp=sharing), [part2](https://drive.google.com/file/d/1BgSvWdKMvdJSwHH36SyO_h_bCQ2YegCJ/view?usp=sharing)
- [Validation data](https://drive.google.com/file/d/145oqhEp8X9V4i1Bi7xv-GzCfQJGQTa7Z/view?usp=sharing)
- [Test data](https://drive.google.com/file/d/1LMCh1Zzw6MaGiV3iqilry01uZZ6s7ncp/view?usp=sharing)
- [No annot data](https://drive.google.com/file/d/1H4XisCX5Z56GRZ-cbUSiaGh-7B6f0v4W/view?usp=sharing)
- [RealSense synchronized data (vision + imu)](https://drive.google.com/file/d/1BGI6zE_KAqsoi10v78lsLFaxokKbnSWp/view?usp=sharing)
- [Additional vision + imu data (not realsense)](https://drive.google.com/file/d/11N1OYDeE3pI6CFumMPOBYCIFPEPuvSI1/view?usp=sharing)

## 4. Predictions
Couple of prediction samples based on the trained YOLOV4 architecture are visualized below.
<p align="center"><img src="image_samples/outputs/1.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/outputs/2.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/outputs/3.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/outputs/4.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/outputs/5.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/outputs/6.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/outputs/7.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/outputs/8.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/outputs/9.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/outputs/10.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/outputs/11.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/outputs/12.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/outputs/13.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/outputs/14.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/outputs/15.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/outputs/16.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/outputs/17.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/outputs/18.jpg" width="1080" title="Image sample 1"></p>
<p align="center"><img src="image_samples/outputs/19.jpg" width="1080" title="Image sample 1"></p>

## 5. Citations
If you find this repository helpful and decided to utilize IADD database in your research project, consider citing us as below:
```bibtex
@INPROCEEDINGS{iadd_database,
  author={},
  booktitle={}, 
  title={}, 
  year={2022},
  volume={},
  number={},
  pages={},
  doi={}}
```
