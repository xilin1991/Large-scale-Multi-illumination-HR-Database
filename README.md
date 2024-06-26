# Large-scale-Multi-illumination-HR-Database (rPPG dataset)
## 1.Overview

BUAA-MIHR dataset is a remote photoplethysmography (rPPG) dataset. BUAA-MIHR dataset for evaluation of remote photoplethysmography pipeline under multi-illumination situations. We recruited 15 healthy subjects (12 male, 3 female, 18 to 30 years old) in this experiment and a total number of 165 video sequences were recorded under various illuminations. The experiments were conducted in a darkroom in order to isolate from ambient light.

## 2.Apparatus and Experimental Environment

Logitech HD pro webcam C930E color camera was used to record videos of 640 × 480 pixels, 8 bit depth, 30 fps, 60s, uncompressed bitmap format. PPG signal was measured using CONTEC CMS50E.

The video is captured in a darkroom, which is covered witha blackout cloth. A split type illuminometer is used as the instrument for measuring light intensity and brightness in the darkroom. We varied illuminance in the range:
<!-- $$ \{10^{0}, 10^{0.2}, 10^{0.4}, 10^{0.6}, 10^{0.8}, 10^{1.0}, 10^{1.2}, 10^{1.4}, 10^{1.6}, 10^{1.8}, 10^{2.0}\}\ \mathbf{lux},$$ -->
<p style="text-align: center"><a href="https://www.codecogs.com/eqnedit.php?latex=\{10^0,&space;10^{0.2},&space;10^{0.4},&space;10^{0.6},&space;10^{0.8},&space;10^{1.0},&space;10^{1.2},&space;10^{1.4},&space;10^{1.6},&space;10^{1.8},&space;10^{2.0}\}\&space;\mathbf{lux}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\{10^0,&space;10^{0.2},&space;10^{0.4},&space;10^{0.6},&space;10^{0.8},&space;10^{1.0},&space;10^{1.2},&space;10^{1.4},&space;10^{1.6},&space;10^{1.8},&space;10^{2.0}\}\&space;\mathbf{lux}" title="\{10^0, 10^{0.2}, 10^{0.4}, 10^{0.6}, 10^{0.8}, 10^{1.0}, 10^{1.2}, 10^{1.4}, 10^{1.6}, 10^{1.8}, 10^{2.0}\}\ \textbf{lux}" /></a>,</p>

equivalent to
<!-- $$ \{1.0, 1.6, 2.5, 4.0, 6.3, 10.0, 15.8, 25.1, 39.8, 63.1, 100.0\}\ \mathbf{lux}.$$ -->
<p style="text-align: center"><a href="https://www.codecogs.com/eqnedit.php?latex=\{1.0,&space;1.6,&space;2.5,&space;4.0,&space;6.3,&space;10.0,&space;15.8,&space;25.1,&space;39.8,&space;63.1,&space;100.0\}\&space;\textbf{lux}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\{1.0,&space;1.6,&space;2.5,&space;4.0,&space;6.3,&space;10.0,&space;15.8,&space;25.1,&space;39.8,&space;63.1,&space;100.0\}\&space;\textbf{lux}" title="\{1.0, 1.6, 2.5, 4.0, 6.3, 10.0, 15.8, 25.1, 39.8, 63.1, 100.0\}\ \textbf{lux}" /></a>.</p>

### Device and settings
|      **Device**       |     **Model**      |                       **Settings**                       |
| :-------------------: | :----------------: | :------------------------------------------------------: |
|       Computer        |    Lenovo Y430p    |                     Ubuntu 16.04 LTS                     |
|      RGB camera       |   Logitech C930e   |                    HD 640×480, FPS 30                    |
|      LED ligths       | Panasonic HHLT0623 | Temperature: 4000K, Rated Voltage: 220V, Frequency: 50Hz |
|     Illuminometer     |  BENETECH GM1030   |                   Real-time interface                    |
| Biosignal Acquisition |   CONTEC CMS50E    |                           N/A                            |


## 3.Contact

Weihai Chen (whchen@buaa.edu.cn), School of Automation Science and Electrical Engineering, Beihang University

Changchen Zhao (cczhao@zjut.edu.cn), College of Information Engineering, Zhejiang University of Technology

Lin Xi (xilin1991@buaa.edu.cn), School of Automation Science and Electrical Engineering, Beihang University


## 4.Download

* BUAA-MIHR database is released to universities and research institutes for research purpose only.

* Note that please contact xilin1991@buaa.edu.cn for requests using an official email address (that is, university or institute email address, and non-official email addresses such as Gmail and 163 are not acceptable). When we receive your reply, we would provide the download link to you.

* Download BUAA-MIHR database in [Baidu Pan](https://pan.baidu.com/s/1SDhPdx3_Cav65LyBMpN-sA) or [OneDrive](https://1drv.ms/f/c/05b6df5b859ecdde/Qt7NnoVb37YggAWEGgAAAAAAjPUJciP1vODR-A).

* By using the BUAA-MIHR database, you are recommended to cite the paper.

## 5.License

The dataset is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/). See [LICENSE](./LICENSE) for details.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>

## Citation
* Xi, L., Chen, W., Zhao, C., Wu, X., & Wang, J. (2020, November). Image enhancement for remote photoplethysmography in a low-light environment. In 2020 15th IEEE International Conference on Automatic Face and Gesture Recognition (FG 2020) (pp. 1-7). IEEE. [[paper](https://ieeexplore.ieee.org/document/9320298)]
```text
@INPROCEEDINGS{9320298,
    author={Xi, Lin and Chen, Weihai and Zhao, Changchen and Wu, Xingming and Wang, Jianhua},
    booktitle={2020 15th IEEE International Conference on Automatic Face and Gesture Recognition (FG 2020)},
    title={Image Enhancement for Remote Photoplethysmography in a Low-Light Environment},
    year={2020},
    pages={1-7},
}
```
