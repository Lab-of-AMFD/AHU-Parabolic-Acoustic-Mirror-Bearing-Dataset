# AHU Parabolic Acoustic Mirror Bearing Dataset

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=YOUR_USERNAME.PAM-Bearing-Dataset)

We have released an open-source, dual-acquisition acoustic dataset for rolling bearing fault diagnosis. 

We hope this dataset can benefit your research in condition monitoring and signal processing.

**Data on Google Drive:** [Insert Link Here]
**Data on Quark Netdisk:** [Insert Link Here]

**The following is a brief introduction to the dataset. For more detailed information, please refer to the dataset specification file.**

---

## Dataset Overview

[cite_start]This dataset includes acoustic signals from nine rolling bearings with three fault locations and three fault types, collected under various operating conditions[cite: 306, 710]. [cite_start]All data are clearly labeled with corresponding fault types and working conditions[cite: 711]. 

A unique feature of this dataset is that the acoustic signals were acquired simultaneously using two distinct methods:
* [cite_start]**PM:** With a parabolic acoustic mirror[cite: 712].
* [cite_start]**DM:** With direct microphone acquisition[cite: 712].

[cite_start]These datasets are publicly available, and anyone can use them to validate acoustic fault diagnosis algorithms[cite: 13, 599]. Publications making use of the PAM-Bearing dataset are requested to cite the following paper:

**L. [cite_start]Peng, F. Liu, M. Xia, C. Shen, Q. He, and Y. Liu, Parabolic Acoustic Mirror: Utilize the shape of its own housing to improve the online monitoring accuracy of rotating electromechanical equipment[cite: 2, 3]. [cite_start]IEEE Transactions on Industrial Electronics, 202x[cite: 1].**

---

## Brief Introduction to Experiments

### Experimental Platform

[cite_start]To verify the feasibility of using a parabolic acoustic mirror for focused acoustic signal acquisition, the mirror was mounted at the shaft end in place of the traditional bearing end cap[cite: 726]. [cite_start]This setup enabled the collection of acoustic signals from faulty bearings during operation[cite: 727].

[cite_start]The experimental platform consisted of a base frame, a three-phase asynchronous motor, a Siemens frequency converter, and a custom bearing end-cap testing assembly[cite: 728]. [cite_start]The testing assembly integrated the supporting bearing, test bearing, hydraulic loading device, parabolic acoustic mirror, acceleration sensors, and other relevant sensors[cite: 729]. 

### Operating Conditions

[cite_start]The radial load is applied through a hydraulic loading system[cite: 732]. [cite_start]To avoid directly stressing the test bearing, the applied pressure is transmitted to the housing of the centrally positioned supporting bearing[cite: 733]. [cite_start]Rotational speed is controlled via the Siemens frequency converter[cite: 734]. 

The experimental operating conditions include:
* [cite_start]**Radial Load:** 5 KN (labeled as L05)[cite: 307, 723].
* [cite_start]**Rotational Speeds:** 600 rpm, 900 rpm, and 1200 rpm[cite: 723].

### Sampling Setting

[cite_start]Each folder contains multiple samples in .mat format, recorded at a sampling rate of 20,000 Hz, with each sample lasting 25 seconds[cite: 720].

---

## Dataset Details

### Folder Structure

[cite_start]The dataset is organized into two main folders: PM (parabolic mirror) and DM (direct microphone)[cite: 714]. [cite_start]Each folder contains subfolders for three fault locations and healthy bearings[cite: 715]. [cite_start]Within each fault location folder, data are further divided into three fault types, and each fault type folder contains recordings at three different rotational speeds[cite: 716]. [cite_start]All data are stored in .mat format[cite: 717].

### File Naming Convention

[cite_start]The .mat file names are defined according to specific labels[cite: 721]. [cite_start]For example, the filename `DM_L05_r600_B02` indicates a Direct Microphone acquisition, 5 KN load, 600 rpm, with a Ball crack fault[cite: 723].

The labels are represented by the following codes:
* [cite_start]**Acquisition Method:** `PM` (Parabolic Mirror) or `DM` (Direct Microphone)[cite: 723].
* [cite_start]**Fault Location:** `B` (Ball), `IR` (Inner ring), `OR` (Outer ring)[cite: 723].
* [cite_start]**Fault Type:** `01` (Pitting), `02` (Crack), `03` (Wear)[cite: 723].

---

## Equipment Specifications

[cite_start]The parameters of the faulty bearings and the parabolic acoustic mirror are shown in Tables 1 and 2, respectively[cite: 741].

**Table 1. Bearing Parameters of LYC N/NU407ECM**
| Parameter | Value |
| :--- | :--- |
| Inner raceway diameter | [cite_start]54 mm [cite: 738] |
| Outer raceway diameter | [cite_start]83 mm [cite: 738] |
| Pitch diameter | [cite_start]68.5 mm [cite: 738] |
| Number of balls | [cite_start]11 [cite: 738] |
| Ball diameter | [cite_start]15 mm [cite: 738] |
| Contact angle | [cite_start]0° [cite: 738] |

**Table 2. Specification parameters of parabolic acoustic mirror**
| Parameter | Value |
| :--- | :--- |
| [cite_start]Parabolic equation | y^2=90x [cite: 740] |
| Material | [cite_start]Aluminum alloy [cite: 740] |
| Focal length | [cite_start]22.5 mm [cite: 740] |
| Depth | [cite_start]22.5 mm [cite: 740] |
| Thickness | [cite_start]7 mm [cite: 740] |
| Aperture diameter | [cite_start]90 mm [cite: 740] |

---

## Contact

If you have any questions or suggestions, do not hesitate to contact:

**[Your Name]**, [Your Email Address]
