# Overview of polarization imaging datasets

The communication "Production of high-resolution reference polarization images from real world scenes" was presented at SPIE Optics + Photonics 2023, during the conference **Polarization Science and Remote Sensing XI**.

## Tables
You can find here the updated version of the tables describing the polarization databases

| dataset |	availability |	number of scenes |	definition |	bit-depth |	mosaiced sensor |	mono/color |
| :---: |	:---: |	:---: |	:---: |	:---: |	:---: |	:---: |
| Abubakar [1] |	 |	6 |	1280 x 960 |	8 |	NO |	mono |
| Lapray [2] |	GitHub |	10 |	1024 x 768 |	12 |	yes |	RGB/IR |
| Zhang 2018 [3] |	 |	215 |	640x480 |	 |	NO |	mono |
| Zeng [4] |	upon request |	120 |	1280 x 960 |	8 |	NO |	mono |
| Qiu [5] |	univ. repository |	40 |	1024 x 1024 |	8 |	yes |	RGB |
| Wen 2019 [6] |	GitHub |	105 |	1456 x 1088 |	8 |	NO |	RGB |
| Sargent [7] |	upon request |	24 |	2448 x 2048 |	10 or 12 |	NO |	mono |
| Morimatsu [8, 9] |	univ. repository |	40 |	1024 x 768 |	10 |	NO |	RGB |
| Li [10] |		150 |		 |	yes |	mono |
| Ba [11] |	google drive |	326 |	1024 x 1024 |	11 |	yes |	RGB |
| Wen 2021a [12] |	GitHub |	40+10 |	720 x 540 |	8 |	NO |	RGB |
| Wen 2021b [13] |	GitHub |	8 |	1384 x 1032 |	8 |	yes |	RGB |
| Blin [14] |	zenodo.org |	2060 |	500 x 500 |	8 |	yes |	RGB |
| Sun [15] |	google drive |	132 |	2048 x 1848 |	8 |	yes |	RGB |
| Zhang 2021 [16] |	 |	200 |	640 x 480 |	 |	NO |	mono |
| Sattar [17] |	GitHub |	28 |	1224 x 1024 |	8 |	yes |	RGB |
| Lei [18] |	GitHub |	522 |	1224 x 1024 |	11 |	yes |	RGB |
| Ono [19] |	upon request |	82 |	2448 x 2040 |	11 |	yes |	RGB |
| Kurita [20] |	upon request |	729+82+238 |	2448 x 2048 |	12 |	yes |	RGB |
| Liu [21] |	upon request |	200+100 |	2448 x 2048 |	 |	yes |	RGB |
| Yu [22] |	google drive |	120 |	1224 x 1024 |	 |	yes |	RGB |![image]


**Table 1: Basic characteristics of imaging polarization datasets (updated Sept. 06, 2023).**

The following table describes non mosaiced datasets, likely to be used for testing demosaicing algorithms.

| dataset |	Zeng ('Forknet')&nbsp;[3] |	Zeng ('Forknet')&nbsp;[4] |	Sargent&nbsp;[7] |	Wen 2019&nbsp;[6] |	Morimatsu&nbsp;[8, 9] |	Wen 2021a&nbsp;[12] |
| :---: |	:---: |	:---: |	:---: |	:---: |	:---: |	:---: |
| number of scenes |	215 |	120 |	24 |	105 |	40 |	50 |
| definition |	640x480 |	1280 x 960 |	2448 x 2048 |	1456 x 1088 |	1024 x 768 |	720 x 540 |
| spectral bands |	mono |	mono |	mono |	RGB |	RGB |	RGB |
| bit depth |	 |	8 |	10 or 12 |	8 |	10 |	8 |
| camera |	 |	Point Grey BFLY-U3-23S6M-C |	Blackfly |	JAI AP-1600T-USB |	JAI CV-M9GE 3-CCD |	FLIR BFS-U3-04S2m-cs  |
| sensor |	 |	 Sony IMX249 |	Sony IMX250  |	3x Sony IMX273 |	Sony ICX204AL |	Sony IMX 287 |
| sensor technology |	 |	CMOS |	CMOS |	CMOS |	CCD |	CMOS |
| pixel pitch (µm) |	 |	5.86 |	3.45 |	3.45 |	4.65 |	6.9 |
| averaged images |	 |	1 |	50 |	1 |	1000 |	1 |
| sensor type |	rotating pol. |	rotating pol. + CMOS |	rotating pol. + CMOS |	rotating pol. + prism + 3 CMOS |	prism + 3 CCD |	rotating pol. + rotating color wheel + CMOS |
| polarizing element |	Newport 10LP-VISB  |	 |	Tiffin 49CP 49mm polarizer  |	 |	Sigmakoki SPF-50C-32 |	 |
| objective lens |	 |	 |	Fujinon 12.5mm 2/3"  |	 |	 |	 |
| lens aperture |	 |	fixed |	f/8 |	f/1.4 |	 |	f/1.4 |


**Table 2: Characteristics of non-mosaiced datasets (updated Sept. 06, 2023).**

## References

[1] Abubakar, A., Zhao, X., Li, S., Takruri, M., Bastaki, E., and Bermak, A., “A block-matching and 3-d filtering algorithm for gaussian noise in dofp polarization images,” IEEE Sens. J. 18, 7429–7435 (2018).

[2] Lapray, P.-J., Gendre, L., Bigu ́e, L., and Foulonneau, A., “Database of polarimetric and multispectral images in the visible and nir regions,” in [Unconventional Optical Imaging], Proc. SPIE 10677, 1067738 (2018).

[3] Zeng, X., Luo, Y., Zhao, X., and Ye, W., “An end-to-end fully-convolutional neural network for division of focal plane sensors to reconstruct s0, dolp, and aop,” Opt. Express 27, 8566–8577 (2019).

[4] Qiu, S., Fu, Q., Wang, C., and Heidrich, W., “Polarization demosaicking for monochrome and color po- larization focal plane arrays,” in [Conference on Vision, Modeling, and Visualization], The Eurographics Association (2019).

[5] Wen, S., Zheng, Y., Lu, F., and Zhao, Q., “Convolutional demosaicing network for joint chromatic and polarimetric imagery,” Opt. Lett. 44, 5646–5649 (2019).

[6] Sargent, G. C., Ratliff, B. M., and Asari, V. K., “Conditional generative adversarial network demosaicing strategy for division of focal plane polarimeters,” Opt. Express 28, 38419–38443 (2020).

[7] Morimatsu, M., Monno, Y., Tanaka, M., and Okutomi, M., “Monochrome and color polarization demo- saicking using edge-aware residual interpolation,” in [2020 IEEE International Conf. on Image Processing (ICIP)], 2571–2575, IEEE (2020).

[8] Morimatsu, M., Monno, Y., Tanaka, M., and Okutomi, M., “Monochrome and color polarization demo- saicking based on intensity-guided residual 
interpolation,” IEEE Sens. J. 21, 26985–26996 (2021).

[9] Ba, Y., Gilbert, A., Wang, F., Yang, J., Chen, R., Wang, Y., Yan, L., Shi, B., and Kadambi, A., “Deep shape from polarization,” in [ECCV 2020], LNCS 12369, 554–571, Springer International Publishing, Cham (2020).

[10] Wen, S., Zheng, Y., and Lu, F., “A sparse representation based joint demosaicing method for single-chip polarized color sensor,” IEEE Trans. Image Proc. 30, 4171–4182 (2021).

[11] Wen, S., Zheng, Y., and Lu, F., “Polarization guided specular reflection separation,” IEEE Trans. Image Proc. 30, 7280–7291 (2021).

[12] Blin, R., Ainouz, S., Canu, S., and Meriaudeau, F., “Multimodal polarimetric and color fusion for road scene analysis in adverse weather conditions,” in [2021 IEEE International Conf. on Image Processing (ICIP)], 3338–3342, IEEE (2021).

[13] Sun, Y., Zhang, J., and Liang, R., “Color polarization demosaicking by a convolutional neural network,” Opt. Lett. 46, 4338–4341 (2021).

[14] Zhang, J., Shao, J., Chen, J., Yang, D., and Liang, B., “Polarization image fusion with self-learned fusion strategy,” Pattern Recognition 118, 108045 (2021).

[15] Sattar, S., Lapray, P.-J., Aksas, L., Foulonneau, A., and Bigu ́e, L., “Snapshot spectropolarimetric imaging using a pair of filter array cameras,” Opt. Eng. 61, 043104 (2022).

[16] Lei, C., Qi, C., Xie, J., Fan, N., Koltun, V., and Chen, Q., “Shape from polarization for complex scenes in the wild,” in [2022 IEEE/CVF Conf. on Computer Vision and Pattern Recognition (CVPR)], 12622–12631, IEEE (2022).

[17] Ono, T., Kondo, Y., Sun, L., Kurita, T., and Moriuchi, Y., “Degree-of-linear-polarization-based color constancy,” in [2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)], 19708– 19717, IEEE (2022).

[18] Kurita, T., Kondo, Y., Sun, L., and Moriuchi, Y., “Simultaneous acquisition of high quality rgb image and polarization information using a sparse polarization sensor,” in [2023 IEEE/CVF Winter Conf. on Applications of Computer Vision (WACV)], 178–188, IEEE (2023).

[19] Liu, J., Duan, J., Hao, Y., Chen, G., Zhang, H., and Zheng, Y., “Polarization image demosaicing and rgb image enhancement for a color polarization sparse focal plane array,” Opt. Express 31, 23475–23490 (2023).

[20] Yu, D., Li, Q., Zhang, Z., Huo, G., Xu, C., and Zhou, Y., “Color polarization image super-resolution reconstruction via a cross-branch supervised learning strategy,” Optics and Lasers in Engineering 165,
107469 (2023).

## Citation
If you find this work helpful in your research, please cite:

```
@inproceedings{biguedb2023,
   author = {Bigué, L. and Foulonneau, A. and Lapray, P. J.},
   title = {Production of high-resolution reference polarization images from real world scenes},
   booktitle = {Polarization Science and Remote Sensing XI},
   publisher = {SPIE},
   volume = {12690},
   pages = {12690-15},
   year={2023},
   type = {Conference Proceedings}
}
```
