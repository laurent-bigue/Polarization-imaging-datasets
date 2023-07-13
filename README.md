# Polarization-imaging-datasets
Overview of polarization imaging datasets
This work was presented at SPIE Optics + Photonics 2023, during the conference Polarization Science and Remote Sensing XI

## Tables
You can find here the updated version of the tables describing the polarization databases

| dataset |	availability |	number of scenes |	definition |	bit-depth |	mosaiced sensor |	mono/color |
| :---: |	:---: |	:---: |	:---: |	:---: |	:---: |	:---: |
| Abubakar |	 |	6 |	1280x960 |	8 |	NO |	mono |
| Lapray |	GitHub |	10 |	1024x768 |	12 |	yes |	RGB/IR |
| Qiu |	univ. repository |	40 |	1024x1024 |	8 |	yes |	RGB |
| Zeng |	upon request |	120 |	1280x960 |	8 |	NO |	mono |
| Wen 2019 |	GitHub |	105 |	1456x1088 |	8 |	NO |	RGB |
| Morimatsu |	univ. repository |	40 |	1024x768 |	10 |	NO |	RGB |
| Sargent |	 |	24 |	2448x2048 |	10 or 12 |	NO |	mono |
| Ba |	google drive |	326 |	1024x1024 |	11 |	yes |	RGB |
| Wen 2021a |	GitHub |	40+10 |	720x540 |	8 |	NO |	RGB |
| Wen 2021b |	GitHub |	8 |	1384x1032 |	 |	yes |	RGB |
| Blin |	zenodo.org |	2060 |	 |	 |	yes |	RGB |
| Sun |	univ. repository |	132 |	2048x1848 |	 |	yes |	RGB |
| Sattar |	GitHub |	28 |	1224x1024 |	8 |	yes |	RGB |
| Lei |	GitHub |	522 |	1224x1024 |	11 |	yes |	RGB |
| Ono |	upon request |	82 |	 |	 |	yes |	RGB |
| Kurita |	upon request |	729+82+238 |	 |	-12 |	yes |	RGB |
| Liu |	upon request |	200+100 |	 |	 |	yes |	RGB |

**Table 1: Basic characteristics of imaging polarization datasets.**

| dataset |	Fork-net |	Sargent2020 |	Wen2019 |	Morimatsu2020 |	Wen2021 |
| :----: |	:---: |	:---: |	:---: |	:---: |	:---: |
| number of scenes |	120 |	24 |	105 |	40 |	50 |
| definition |	1280 x 960 |	2448x2048 |	1456 x 1088 |	1024 x 768 |	720 x 540 |
| spectral bands |	mono |	mono |	RGB |	RGB |	RGB |
| bit depth |	8 |	10 or 12 |	8 |	10 |	8 |
| camera |	Point Grey BFLY-U3-23S6M-C |	Blackfly |	JAI AP-1600T-PMCL ? |	JAI CV-M9GE 3-CCD |	FLIR BFS-U3-04S2m-cs  |
| sensor |	 Sony IMX249 |	Sony IMX250  |	3x Sony IMX273 ? |	Sony ICX204AL |	Sony IMX 287 |
| sensor technology |	CMOS |	CMOS |	CMOS |	CCD |	CMOS |
| pixel pitch (µm) |	5.86 |	3.45 |	3.45 ? |	4.65 |	6.9 |
| averaged images |	1 |	50 |	 |	1000 |	 |
| sensor type |	rotating pol. |	rotating pol. |	prism + 3 CMOS |	prism + 3 CCD |	rotating pol. + CMOS |
| polarizing element |	 |	Tiffin 49CP 49mm polarizer  |	 |	SIGMAKOKI SPF-50C-32 |	 |
| objective lens |	 |	Fujinon 12.5mm 2/3"  |	 |	 |	 |
| lens aperture |	fixe |	f/8 |	 |	 |	 |

**Table 2: Characteristics of non-mosaiced datasets.**

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
