# IADD_Database

This repository contains the documentations and download links for 
the 2022 Iran Autonomous Driving Database (IADD). IADD aims at improving the
generalization of the deep learning-based object detectors


## 1. Image Samples
Few samples of our database are presented below:
<p align="center"><img src="image_samples/raw_data/Record000_DA_001070.jpg" width="1920" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/raw_data/Record000_DA_001640.jpg" width="1920" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/raw_data/Record000_DA_002434.jpg" width="1920" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/raw_data/Record000_DA_003490.jpg" width="1920" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/raw_data/Record002_D_009467.jpg" width="1920" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/raw_data/Record002_D_009573.jpg" width="1920" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/raw_data/Record009_D_019823.jpg" width="1920" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/raw_data/Record009_D_020489.jpg" width="1920" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/raw_data/Record011_D_025612.jpg" width="1920" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/raw_data/Record135_D_87.jpg" width="3840" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/raw_data/Record138_D_359.jpg" width="3840" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/raw_data/Record430_R_494.jpg" width="1280" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/raw_data/Record433_R_292.jpg" width="1280" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/raw_data/Record435_R_328.jpg" width="1280" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/raw_data/Record437_D_412.jpg" width="1280" title="Image sample 1" alt=""></p>

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
- Training data: [part1](https://drive.google.com/file/d/1wx6c8nhQ9m5wki2uhCoLqANrM8_J5tkw/view?usp=sharing), [part2](https://drive.google.com/file/d/1BgSvWdKMvdJSwHH36SyO_h_bCQ2YegCJ/view?usp=sharing), [part3](https://drive.google.com/file/d/1R-IBeBJNojR8jRjeClnmB4Mmp9Dm3psB/view?usp=sharing)
- [Validation data](https://drive.google.com/file/d/145oqhEp8X9V4i1Bi7xv-GzCfQJGQTa7Z/view?usp=sharing)
- [Test data](https://drive.google.com/file/d/1LMCh1Zzw6MaGiV3iqilry01uZZ6s7ncp/view?usp=sharing)
- [No annot data](https://drive.google.com/file/d/1H4XisCX5Z56GRZ-cbUSiaGh-7B6f0v4W/view?usp=sharing)
- [RealSense synchronized data (vision + imu)](https://drive.google.com/file/d/1BGI6zE_KAqsoi10v78lsLFaxokKbnSWp/view?usp=sharing)
- [Additional vision + imu data (not realsense)](https://drive.google.com/file/d/11N1OYDeE3pI6CFumMPOBYCIFPEPuvSI1/view?usp=sharing)

## 4. Predictions
Couple of prediction samples based on the trained YOLOV4 architecture are visualized below.
<p align="center"><img src="image_samples/outputs/Record000_DA_001640.jpg" width="1920" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/outputs/Record000_DA_002434.jpg" width="1920" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/outputs/Record000_DA_003490.jpg" width="1920" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/outputs/Record000_DA_003608.jpg" width="1920" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/outputs/Record001_D_05145.jpg" width="1920" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/outputs/Record002_D_009467.jpg" width="1920" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/outputs/Record009_D_019823.jpg" width="1920" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/outputs/Record012_D_027343.jpg" width="1920" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/outputs/Record128_D_35.jpg" width="1920" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/outputs/Record135_D_87.jpg" width="3840" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/outputs/Record138_D_359.jpg" width="3840" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/outputs/Record433_R_292.jpg" width="1280" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/outputs/Record435_R_328.jpg" width="1280" title="Image sample 1" alt=""></p>
<p align="center"><img src="image_samples/outputs/Record437_D_412.jpg" width="1280" title="Image sample 1" alt=""></p>

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
