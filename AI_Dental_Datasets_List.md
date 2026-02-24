# AI Dental Research Dataset Catalogue

## Datasets Overview

This repository serves as a centralized database of datasets for artificial intelligence research in dental health. Below, each dataset is described in detail, including source information, imaging details, and usage licenses.
## TABLE

| Dataset Name                            | Database         | Dataset URL                                     | Year | Country      | DOI                                        | Source of Data Acquisition      | Reason for Image Acquisition            | Imaging Modality                         | Equipment Detail                                 | License Type                   | Annotators    | Annotation Type     | Files Formats                | Images and Resolutions                                  | Example of File Names                                 |
 |-----------------------------------------|------------------|-------------------------------------------------|------|--------------|--------------------------------------------|---------------------------------|------------------------------------------|-------------------------------------------|--------------------------------------------------|--------------------------------|---------------|---------------------|------------------------------|------------------------------------------------------|------------------------------------------------------|
 | DENTEX Panoramic Dataset                | Zenodo           | [DENTEX Panoramic](DENTEX Panoramic)            | 2023 | Switzerland  | 10.48550/arXiv.2305.19112, 10.48550/arXiv.2303.06500 | Dental clinics                  | Dental diagnosis                        | Panoramic radiographs                      | VistaPano S X-ray unit (Durr Dental, Germany) | No License Specified            | Not specified | Label               | PNG                          | Panoramic images, 2048x989 to 2950x1330                | train_30.png, val_12.png                               |
 | CTooth Dataset                          | arXiv            | [CTooth Dataset](CTooth Dataset)                | 2022 | China        | 10.1007/978-3-031-17027-0_7                | Dental clinics                  | Dental diagnosis, research               | Cone Beam Computed Tomography (CBCT)       | Op300, Instrumentarium, Finland                    | CC BY-NC 4.0                    | Yes           | Label               | DICOM (.dcm)                 | DICOM standard, raw images                              | *.dcm                                                |
 | Panoramic Dental X-rays With Segmented Mandibles | Mendeley         | [Panoramic Dental X-rays With Segmented Mandibles](Panoramic Dental X-rays With Segmented Mandibles) | 2020 | Iran         | 10.1117/1.JMI.2.4.044003                   | Dental clinics                  | Dental diagnosis, research               | Panoramic radiographs                      | Soredex CranexD digital panoramic x-ray unit        | CC BY-NC 3.0                    | 2             | Pixel-level         | PNG                          | Panoramic images, 2048x989 to 2950x1330, Cropped       | 1.png, 85.png, etc.                                  |
 | Dental Radiography                      | Kaggle           | [Dental Radiography](Dental Radiography)        | 2023 | Iran         | N/A                                        | Dental clinic                   | Dental diagnosis, research               | Panoramic radiographs                      | N/A                                              | CC BY-SA 4.0                    | Not specified | Label               | JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp) | Panoramic images, 256x512 px, Cropped                 | 0041_jpg.rf.45bc3049f99113cefd018e407df2415f, 0095_jpg.rf.d7773e0afb13f54a3e6244079b483ab2, etc. |
 | Panoramic-Caries-Segmentation           | GitHub           | [Panoramic-Caries-Segmentation](Panoramic-Caries-Segmentation) | 2023 | China        | 10.1016/j.neucom.2023.03.069               | Not described                   | Not described                             | Panoramic radiographs                      | N/A                                              | No License Specified            | 5             | Pixel-level         | PNG                          | Panoramic images, 1435x2943, Cropped                  | 1018.png, 1026.png, etc.                             |
 | TK_Tooth_Number_Code                    | GitHub           | [TK_Tooth_Number_Code](TK_Tooth_Number_Code)    | 2022 | N/A          | Not described                              | Not described                   | Not described                             | Panoramic radiographs                      | N/A                                              | No License Specified            | Not specified | Label               | PNG                          | Cropped Panoramic images, 250x152, Cropped            | 109_upper_0.png, 109_lower_0.png, etc.               |
 | CL Detection                            | Grand-challenge  | [CL Detection](CL Detection)                    | 2023 | Taiwan       | N/A                                        | Dental clinics                  | Benchmarking                              | Cephalometric radiographs                   | N/A                                              | No License Specified            | Not specified | Pixel-level         | JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp) | Cephalometric, 2048x1555 and 1804x2148               | N/A                                                 |
 | Tufts Panoramic Dataset                 | PubMed           | [Tufts Panoramic Dataset](Tufts Panoramic Dataset) | 2021 | USA          | 10.1109/JBHI.2021.3117575                  | University Dental School Clinic | Diagnostic Investigation                  | Panoramic radiographs                      | OP100 Orthopantomograph (Instrumentarium Imaging/Kavo Kerr) and Plammeca Promax 2D | No License Specified            | 2             | Label               | JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp) | Panoramic images, 840x1615                              | 1.JPG, 2.JPG, etc.                                   |
 | 3DTeethSeg22_challenge ToothFairy or Teeth3DS | OSF              | [3DTeethSeg22_challenge ToothFairy or Teeth3DS](3DTeethSeg22_challenge ToothFairy or Teeth3DS) | 2022 | France, Belgium | 10.48550/arXiv.2210.06094                  | Dental clinics                  | Dental diagnosis                          | Intra-oral 3D scans                         | Primescan, Trios3, iTero Element 2 Plus             | CC BY-NC-ND 4.0                  | 50            | Pixel-level         | DICOM (.dcm)                 | DICOM standard, raw images                              | *.dcm                                                |
 | v7labs Panoramic Dental                 | Google Datasets  | [v7labs Panoramic Dental](v7labs Panoramic Dental) | 2023 | USA          | N/A                                        | Dental clinics                  | Dental diagnosis, research               | Panoramic radiographs                      | N/A                                              | No License Specified            | No            | Pixel-level         | PNG                          | Panoramic images, 1250 x 3122 px                        | 93.png, 85.png, etc.                                 |
 | tooth-marked-tongue                     | Kaggle           | [tooth-marked-tongue](tooth-marked-tongue)      | 2022 | China        | 10.3390/diagnostics12102451                | Schools                         | Dental diagnosis                          | Intraoral photograph                        | Canon Eos 700d                                    | No License Specified            | 5             | Label               | PNG                          | Photos, 861x755 (Height 861 px, Width: 755 px)         | 140826072926_st.png, etc.                            |
 | Oral Cancer (Lips and Tongue) images    | Kaggle           | [Oral Cancer (Lips and Tongue) images](Oral Cancer (Lips and Tongue) images) | 2022 | India        | N/A                                        | Hospitals                       | Diagnostic for oral diseases              | Intraoral photograph                        | N/A                                              | Copyright the Authors            | Not specified | Label               | JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp) | Photos, 825 x 1100 px                                 | 324950_1100.jpg, IMG_3506-e1564923599677.jpg, etc.   |
 | Pulp Exposure                           | PubMed           | [Pulp Exposure](Pulp Exposure)                  | 2023 | Saudi Arabia, Spain, Korea | 10.1186/s12903-023-03251-0                 | Dental clinics, University Dental School Clinic | Not described                             | Intraoral radiographs                      | N/A                                              | No License Specified            | 10            | Box                 | JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp) | Periapical, 1402 x 1876                                 | Test Dataset 22.jpg, Test Dataset 17.jpg etc...      |
 | Panoramic-Paraguay                      | Zenodo           | [Panoramic-Paraguay](Panoramic-Paraguay)        | 2021 | Paraguay     | 10.3390/s21093110                         | University Dental School Clinic | Not described                             | Panoramic radiographs                      | N/A                                              | No License Specified            | 60            | N/A                 | JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp) | Panoramic images, 1024 x 2041 px                       | 104.jpg, 133.jpg, etc...                             |
 | Panoramic Dental Xray Dataset           | Mendeley         | [Panoramic Dental Xray Dataset](Panoramic Dental Xray Dataset) | 2023 | Tunisia      | 10.1007/s11042-023-17568-z                 | Dental clinics                  | Dental diagnosis, research               | Panoramic radiographs                      | N/A                                              | CC BY 4.0                      | 2             | Pixel-level         | JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp) | Panoramic images, 1464 x 2964 px                        | 18.jpg, 22.jpg, etc..                                 |
 | PhysioNet Multimodal                    | Google Datasets  | [PhysioNet Multimodal Dental Dataset](PhysioNet Multimodal Dental Dataset) | 2022 | China        | 10.13026/s5z3-2766                         | Dental clinics                  | Dental diagnosis, research               | Cone Beam Computed Tomography (CBCT), Panoramic radiographs | PhysioNet                                          | PhysioNet Restricted Health Data License 1.5.0 | 56            | Box                 | DICOM (.dcm)                 | DICOM standard, raw images                              | Folder name: 0006_0, 0008_0, etc.. Slices: Slice_0000.dcm, Slice_0001.dcm, etc.. |   |
 | A dual-labeled dataset for automatic teeth segmentation, numbering, and state assessment | Kaggle | [A dual-labeled dataset](A dual-labeled dataset) | 2023 | Unknown     | N/A                                         | Dental clinics                  | Dental diagnosis, research                | Panoramic radiographs                      | N/A                                       | Unknown                 | Yes          | Label               | PNG                          | Panoramic images, varying file sizes from 374 KB to 3.44 MB | 2005.png, 2006.png, etc.                           |
 | ORCHID: Oral Cancer Histology Image Database | medRxiv          | [ORCHID](ORCHID)                                | 2024 | India        | 10.1038/s41597-024-03836-6                   | Hospitals, Research Institutes   | Oral cancer and precancer diagnosis       | Histopathology                     | Bright field microscopy (1000X effective magnification) | Unknown                 | Yes          | Patch-level         | PNG                          | 300x300 pixel patches from 100X objective images   | ORCHID_InstituteID_SampleID_ImageID_PatchID.png      |
 | Vident-real: An Intra-Oral Video Dataset for Multi-Task Learning | Gdańsk University of Technology | [Vident-real.zip](http://Vident-real.zip) | 2024 | Poland   | [10.34808/vjnh-9c35](http://10.34808/vjnh-9c35) | Medical University of Gdańsk | Conservative dental treatments | Intra-oral video recordings | Tiny micro-camera attached to dental handpieces | CC BY-NC 4.0 | N/A | Pseudo-labels (enhanced frame, segmented teeth, homography between frames) | JPEG (debayerized from RAW 10-bit images) | 800x800 pixels, 70,000 frames across 100 video sequences | vid001_frame001.jpg, vid002_frame001.jpg, etc. | 
 | Multimodal Dental Dataset               | PhysioNet        | [Dataset Link](https://doi.org/10.13026/h1tt-fc69) | 2024 | China        | [10.13026/h1tt-fc69](https://doi.org/10.13026/h1tt-fc69) | Guilin Medical University      | Collection of imaging data for machine learning and clinical research | CBCT, Panoramic Radiographs, Periapical Radiographs | Smart3D-X CBCT machine, 2D flat panel detector for panoramic imaging, Portable intraoral X-ray generator | Open Access (Creative Commons Attribution-NonCommercial-NoDerivatives 4.0) | Multiple annotators (13 labeled images) | Tooth annotation | DICOM for CBCT and Panoramic, TIF for Periapical | 329 CBCT images, 8 Panoramic, 16,203 Periapical images | e.g., '0006_0' for patient 0006's first visit         |
 | ACTA-DIRECT Dataset | ACTA-DIRECT Dataset | [ACTA-DIRECT Dataset](https://publication.yoda.vu.nl/full/VU01/WK8SQN.html) | 2024 | Netherlands | 10.48338/VU01-UAAHEY | Extracted dental samples | Diagnostic insights for radiographic early-caries with micro-CT | Micro-CT scans and conventional radiographs |  | Open - freely retrievable | Three different experts for conventional annotations | Initial proximal caries lesion annotations |  | 179 extracted molar and premolar teeth | 
| Orthopantomogram teeth segmentation and numbering dataset | Zenodo           | [Dataset Link](https://zenodo.org/records/10538750?token=eyJhbGciOiJIUzUxMiJ9...) | 2024 | Pakistan     | 10.5281/zenodo.10538750                   | Aga Khan University Hospital    | Developing AI models for dental diagnostics | Orthopantomogram (OPG)             | Orthophos XG 3-D (Dentsply Sirona GmbH) operated at 60–90 kV and 3–16 mA | Creative Commons License    | Specialist dentists | Instance segmentation | JSON format for annotations; PNG for images | 250 images of permanent dentition, 2440 × 1292 pixels | OPG_001.png, OPG_002.png, ... |  
| AlphaDent Dataset | GitHub | [AlphaDent GitHub Repository](https://github.com/ZFTurbo/AlphaDent) | 2025 | Russia | N/A | Sechenov University, AlphaChip LLC, HSE University | Detection and segmentation of dental pathologies | Intraoral DSLR photography | Canon 6D Mark II with Canon 100mm f/2.8L macro IS USM lens | Open License (not specified) | 1 (dentist) | Instance segmentation | JPEG (.jpg), PNG (.png), TXT (.txt) | ~1320 images (>5000x3000 px); 295 patients | p001_F_32_001.jpg, 01_class_5.png, p001_F_32_001.txt |
| Gingivitis Image Captioning Dataset | Mendeley | [Gingivitis Image Captioning Dataset](https://data.mendeley.com/datasets/3253gj88rr/1) | 2024 | Vietnam | 10.17632/3253gj88rr.1 | Hanoi Medical University | Gingivitis diagnosis, image captioning research | Intraoral photograph | Nikon D810 with Nikon AF-S 105mm F/1.4EED Nano lens, Godox MF12 Macro Flash | CC BY 4.0 | 3 (periodontists with >10 years experience) | Label (MGI scores) and captions | JPEG (.jpg), CSV, TXT | 1,096 high-resolution intraoral images of 12 anterior teeth | 00945.jpg, 00945.txt |
| Incisor Pulp Chamber Tomographic Images (IPCTI) | Mendeley | [IPCTI Dataset](https://data.mendeley.com/datasets/) | 2025 | Brazil | 10.1016/j.dib.2025.112033 | Universidade Federal de Juiz de Fora | Forensic odontology, dental age estimation | Cone Beam Computed Tomography (CBCT) | Not specified (standardized CBCT protocols) | CC (Creative Commons) | Not specified | Box (bounding box) | Image files | CBCT coronal and sagittal views of upper central incisors, ages 18-60 | Not specified |
| Dental OPG X-ray Dataset (Six Classes) | Mendeley | [Dental OPG X-ray Dataset](https://data.mendeley.com/datasets/c4hhrkxytw/4) | 2024 | Bangladesh | 10.17632/c4hhrkxytw.4 | Three private dental clinics, Dhaka | Dental disease detection and classification | Panoramic radiographs | Samsung A52 (SM-A525F), 64 megapixels | CC BY-NC 4.0 | 2 (dentists with 16 and 32 years experience) | Box (bounding box) | JPEG (.jpg), JSON | 232 original + 604 augmented panoramic images, 1176 x 603 px | Not specified |
| Varying Views of Teeth Dataset | Mendeley | [Varying Views of Teeth Dataset](https://data.mendeley.com/datasets/6zsnhrds9t/1) | 2024 | India | 10.1016/j.dib.2024.110772 | Bharati Vidyapeeth University | Dental diagnosis, pediatric dentistry research | Intraoral photograph | Not specified | CC (Creative Commons) | Not specified | Label | Image files | 9,562 images of healthy teeth from children aged 1-14 | Not specified |
| Dental Periapical X-ray Dataset | Mendeley | [Dental Periapical X-ray Dataset](https://data.mendeley.com/datasets/) | 2024 | Jordan | 10.1016/j.dib.2024.110539 | Jerash Governmental Hospital | Dental periapical disease diagnosis | Intraoral radiographs (periapical) | Not specified | CC BY-NC 4.0 | Not specified | Pixel-level (segmentation) | Image files | 929 high-quality periapical X-ray images | Not specified |
| Apical Periodontitis Panoramic Dataset | Mendeley | [Apical Periodontitis Dataset](https://data.mendeley.com/datasets/kx52tk2ddj/3) | 2024 | Vietnam | 10.1016/j.dib.2024.110486 | Hanoi Medical University | Apical periodontitis detection and classification | Panoramic radiographs | Not specified | CC BY-NC 4.0 | 3 (experienced dentists) | Label (Periapical Lesions Classification) | JPEG (.jpg) | 3,926 original + 17,004 augmented panoramic radiographs | Not specified |
| Histopathological Imaging Database for Oral Cancer | Mendeley | [Histopathological Oral Cancer Dataset](https://data.mendeley.com/datasets/ftmp4cvtmb/2) | 2020 | India | 10.1016/j.dib.2020.105114 | Ayursundra Healthcare, Dr B. Borooah Cancer Institute, Guwahati | Oral squamous cell carcinoma diagnosis | Histopathology (H&E stained slides) | Leica ICC50 HD microscope | CC BY 4.0 | Medical experts | Label | Image files | 1,224 images: 528 at 100x and 696 at 400x magnification, from 230 patients | Not specified |




## LIST

### **AlphaDent Dataset**  
- **Database:** GitHub  
- **Dataset URL:** https://github.com/ZFTurbo/AlphaDent  
- **Year:** 2025  
- **Country:** Russia  
- **DOI:** Not registered (referenced in Sosnin et al., 2025)  
- **Source of Data Acquisition:** Sechenov University, AlphaChip LLC, HSE University  
- **Reason for Image Acquisition:** Detection and segmentation of dental pathologies using AI  
- **Imaging Modality:** Intraoral DSLR photography  
- **Equipment Detail:** Canon 6D Mark II with Canon 100mm f/2.8L macro IS USM lens  
- **License Type:** Open License (not further specified)  
- **Annotators:** One main annotator (dentist); masks created with CVAT  
- **Annotation Type:** Instance segmentation for 9 classes  
- **Files Formats:** JPEG (.jpg), PNG (.png), TXT (.txt)  
- **Images and Resolutions:**  
  - 1320 high-resolution images (>5000x3000 px)  
  - 295 patients (273 train, 22 validation)  
  - 135 test images (withheld labels for leaderboard use)  
- **Example of File Names:**  
  - `p001_F_32_001.jpg` (image)  
  - `00_class_2.png` (mask)  
  - `p001_F_32_001.txt` (annotations)  
- **Additional Notes:**  
  - Class types include abrasion, fillings, crowns, and 6 caries classes  
  - Leaderboard hosted on [Kaggle](https://www.kaggle.com/competitions/alpha-dent)  
  - Includes YOLOv8-ready `yolo_seg_train.yaml` file  
  - Ethical approval from Sechenov University (Protocol No. 02-24, 29 Jan 2024)
    

###  **ACTA-DIRECT Dataset**  
- **Database:**  ACTA-DIRECT Dataset
- **Dataset URL:**  https://publication.yoda.vu.nl/full/VU01/WK8SQN.html
- **Year:** 2024  
- **Country:**  Netherlands
- **DOI:**  10.48338/VU01-UAAHEY
- **Source of Data Acquisition:** Extracted dental samples  
- **Reason for Image Acquisition:** Diagnostic insights for radiographic early-caries with micro-CT  
- **Imaging Modality:** Micro-CT scans and conventional radiographs  
- **Equipment Detail:**  
- **License Type:** Open - freely retrievable  
- **Annotators:** Three different experts for conventional annotations  
- **Annotation Type:** Initial proximal caries lesion annotations  
- **Files Formats:**  
- **Images and Resolutions:** 179 extracted molar and premolar teeth  
- **Example of File Names:**  


### Orthopantomogram Teeth Segmentation and Numbering Dataset

- **Database**: Zenodo
 **Dataset URL**: [Orthopantomogram Teeth Segmentation](https://zenodo.org/records/10538750?token=eyJhbGciOiJIUzUxMiJ9eyJpZCI6ImYxOGQ2N2Q5LWUyOTktNGE1Zi1iNTljLTNkYzkzNzM2NGU5OSIsImRhdGEiOnt9LCJyYW5kb20iOiJhYjBjYTEyZmIwZDdhNThlYTIxODVhMmVlM2I0ZTk5MyJ9.Q2qqd4WSorIY4YXQPU3Re-RSpc3r1D6oGGdJQc72ne8yOigSzsD8oG8W-ojPK1btsMNhiNf5tAVEnV6Rwo469g)
- **Year**: 2024
- **Country**: Pakistan
- **DOI**: 10.5281/zenodo.10538750
- **Source of Data Acquisition**: Dental clinics at Aga Khan University Hospital
- **Reason for Image Acquisition**: Dental diagnosis and AI research
- **Imaging Modality**: Orthopantomograms (OPGs)
- **Equipment Detail**: Orthophos XG 3-D (Dentsply Sirona GmbH, Germany)
- **License Type**: Creative Commons License (Open Access)
- **Annotators**: Specialist dentists trained in annotation
- **Annotation Type**: Instance Segmentation
- **Files Formats**: PNG
- **Images and Resolutions**: 250 OPGs, resolution of 2440 × 1292 pixels
- **Example of File Names**: not specified in the document

### Multimodal Dental Dataset

- **Database**: PhysioNet
- **Dataset URL**: [Multimodal Dental Dataset](https://doi.org/10.13026/h1tt-fc69)
- **Year**: 2024
- **Country**: China
- **DOI**: 10.1038/s41597-024-04130-1
- **Source of Data Acquisition**: Dental hospitals
- **Reason for Image Acquisition**: Oral disease diagnosis and treatment planning
- **Imaging Modality**: Cone Beam Computed Tomography (CBCT), panoramic radiographs, and periapical radiographs
- **Equipment Detail**: Smart3D-X (Beijing Langshi Instrument Co., Ltd., China)
- **License Type**: Open Access under Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License
- **Annotators**: Multiple trained technicians
- **Annotation Type**: Image segmentation and labeling
- **File Formats**: DICOM and PNG
- **Images and Resolutions**: 329 CBCT images, 1 panoramic image (1468x2904 resolution), 16,203 periapical radiographs with various resolutions
- **Example of File Names**: 0006_0.dcm, 0006_1.png, PeX-ray_0001_1.tif

### DENTEX Panoramic Dataset

- **Database**: Zenodo
- **Dataset URL**: [DENTEX Panoramic](https://zenodo.org/records/7812323)
- **Year**: 2023
- **Country**: Switzerland
- **DOI**: 10.48550/arXiv.2305.19112 and 10.48550/arXiv.2303.06500
- **Source of Data Acquisition**: Dental clinics
- **Reason for Image Acquisition**: Dental diagnosis
- **Imaging Modality**: Panoramic radiographs
- **Equipment Detail**: VistaPano S X-ray unit (Durr Dental, Germany)
- **License Type**: No License Specified
- **Annotators**: Not specified
- **Annotation Type**: Label
- **Files Formats**: PNG
- **Images and Resolutions**: Panoramic images, multiple resolutions ranging from 2048x989 to 2950x1330
- **Example of File Names**: train_30.png, val_12.png

### CTooth Dataset

- **Database**: arXiv
- **Dataset URL**: [CTooth Dataset](https://www.kaggle.com/datasets/weiweicui/ctooth-dataset)
- **Year**: 2022
- **Country**: China
- **DOI**: 10.1007/978-3-031-17027-0_7
- **Source of Data Acquisition**: Dental clinics
- **Reason for Image Acquisition**: Dental diagnosis, research
- **Imaging Modality**: Cone Beam Computed Tomography (CBCT)
- **Equipment Detail**: Op300, Instrumentarium, Finland
- **License Type**: CC BY-NC 4.0
- **Annotators**: Yes
- **Annotation Type**: Label
- **Annotation Software**: IITKSNAP
- **Files Formats**: DICOM (.dcm)
- **Images and Resolutions**: DICOM standard, raw images
- **Example of File Names**: *.dcm

### Panoramic Dental X-rays With Segmented Mandibles

- **Database**: Mendeley
- **Dataset URL**: [Panoramic Dental X-rays With Segmented Mandibles](https://data.mendeley.com/datasets/hxt48yk462/2)
- **Year**: 2020
- **Country**: Iran
- **DOI**: 10.1117/1.JMI.2.4.044003
- **Source of Data Acquisition**: Dental clinics
- **Reason for Image Acquisition**: Dental diagnosis, research
- **Imaging Modality**: Panoramic radiographs
- **Equipment Detail**: Soredex CranexD digital panoramic x-ray unit
- **License Type**: CC BY-NC 3.0
- **Annotators**: 2
- **Annotation Type**: Pixel-level
- **Files Formats**: PNG
- **Images and Resolutions**: Panoramic images, multiple resolutions ranging from 2048x989 to 2950x1330
- **Image Manipulation**: Cropped
- **Example of File Names**: 1.png, 85.png, etc.


### Dental Radiography

- **Database**: Kaggle
- **Dataset URL**: [Dental Radiography](https://www.kaggle.com/datasets/imtkaggleteam/dental-radiography)
- **Year**: 2023
- **Country**: Iran
- **DOI**: N/A
- **Source of Data Acquisition**: Dental clinic
- **Reason for Image Acquisition**: Dental diagnosis, research
- **Imaging Modality**: Panoramic radiographs
- **Equipment Detail**: N/A
- **License Type**: CC BY-SA 4.0
- **Annotators**: Not specified
- **Files Formats**: JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp)
- **Images and Resolutions**: Panoramic images, 256x512 px
- **Image Quality**: Cropped
- **Image Manipulation**: Cropped
- **Contains Additional Information**: Yes, an Excel sheet (named: _annotations.csv) with image size and description of each image
- **Example of File Names**: 0041_jpg.rf.45bc3049f99113cefd018e407df2415f, 0095_jpg.rf.d7773e0afb13f54a3e6244079b483ab2, etc.

### Panoramic-Caries-Segmentation

- **Database**: GitHub
- **Dataset URL**: [Panoramic-Caries-Segmentation](https://github.com/Zzz512/MLUA)
- **Year**: 2023
- **Country**: China
- **DOI**: 10.1016/j.neucom.2023.03.069
- **Source of Data Acquisition**: Not described
- **Reason for Image Acquisition**: Not described
- **Imaging Modality**: Panoramic radiographs
- **Equipment Detail**: N/A
- **License Type**: No License Specified
- **Annotators**: 5
- **Annotation Type**: Pixel-level
- **Files Formats**: PNG
- **Images and Resolutions**: Panoramic images, 1435x2943
- **Image Quality**: Raw images
- **Image Manipulation**: Cropped
- **Contains Additional Information**: Yes, Readme file
- **Example of File Names**: 1018.png, 1026.png, etc.

### TK_Tooth_Number_Code
- **Database**: GitHub
- **Dataset URL**: [TK_Tooth_Number_Code](https://github.com/tanjidakabir/TK_Tooth_Number_Code)
- **Year**: 2022
- **Country**: N/A
- **DOI**: Not described
- **Source of Data Acquisition**: Not described
- **Reason for Image Acquisition**: Not described
- **Imaging Modality**: Panoramic radiographs
- **Equipment Detail**: N/A
- **License Type**: No License Specified
- **Annotators**: Not specified
- **Annotation Type**: Label
- **Files Formats**: PNG
- **Images and Resolutions**: Cropped Panoramic images, 250x152
- **Image Quality**: Raw images
- **Image Manipulation**: Cropped
- **Contains Additional Information**: Yes, readme file, model description, mask file and several xlsx files to describe the data
- **Example of File Names**: 109_upper_0.png, 109_lower_0.png, etc.

### CL Detection

- **Database**: Grand-challenge
- **Dataset URL**: [CL Detection](https://cl-detection2023.grand-challenge.org/)
- **Year**: 2023
- **Country**: Taiwan
- **DOI**: N/A
- **Source of Data Acquisition**: Dental clinics
- **Reason for Image Acquisition**: Benchmarking
- **Imaging Modality**: Cephalometric radiographs
- **Equipment Detail**: N/A
- **License Type**: No License Specified
- **Annotators**: Not specified
- **Annotation Type**: Pixel-level
- **Files Formats**: JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp)
- **Images and Resolutions**: Cephalometric, 2048x1555 and 1804x2148
- **Image Quality**: Raw images
- **Example of File Names**: N/A

###  Tufts Panoramic Dataset

- **Database**: PubMed
- **Dataset URL**: [Tufts Panoramic Dataset](https://tdd.ece.tufts.edu/)
- **Year**: 2021
- **Country**: USA
- **DOI**: 10.1109/JBHI.2021.3117575
- **Source of Data Acquisition**: University Dental School Clinic
- **Reason for Image Acquisition**: Diagnostic Investigation
- **Imaging Modality**: Panoramic radiographs
- **Equipment Detail**: OP100 Orthopantomograph (Instrumentarium Imaging/Kavo Kerr) and Plammeca Promax 2D
- **License Type**: No License Specified
- **Annotators**: 2
- **Annotation Type**: Label
- **Files Formats**: JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp)
- **Images and Resolutions**: Panoramic images, 840x1615
- **Example of File Names**: 1.JPG, 2.JPG, etc.


###  3DTeethSeg22_challenge ToothFairy or Teeth3DS

- **Database**: OSF
- **Dataset URL**: [3DTeethSeg22_challenge ToothFairy or Teeth3DS](https://osf.io/xctdy/)
- **Year**: 2022
- **Country**: France, Belgium
- **DOI**: 10.48550/arXiv.2210.06094
- **Source of Data Acquisition**: Dental clinics
- **Reason for Image Acquisition**: Dental diagnosis
- **Imaging Modality**: Intra-oral 3D scans
- **Equipment Detail**: Primescan, Trios3, iTero Element 2 Plus
- **License Type**: CC BY-NC-ND 4.0
- **Annotators**: 50
- **Annotation Type**: Pixel-level
- **Annotation Software**: Custom tool mentioned
- **Files Formats**: DICOM (.dcm)
- **Images and Resolutions**: DICOM standard, raw images
- **Contains Additional Information**: Yes, Annotations included
- **Example of File Names**: *.dcm

### v7labs Panoramic Dental

- **Database**: Google Datasets
- **Dataset URL**: [v7labs Panoramic Dental](https://www.v7labs.com/open-datasets/panoramic-dental)
- **Year**: 2023
- **Country**: USA
- **DOI**: N/A
- **Source of Data Acquisition**: Dental clinics
- **Reason for Image Acquisition**: Dental diagnosis, research
- **Imaging Modality**: Panoramic radiographs
- **Equipment Detail**: N/A
- **License Type**: No License Specified
- **Annotators**: No
- **Annotation Type**: Pixel-level
- **Files Formats**: PNG
- **Images and Resolutions**: Panoramic images, 1250 x 3122 px
- **Image Quality**: Raw images
- **Example of File Names**: 93.png, 85.png, etc.

###  tooth-marked-tongue

- **Database**: Kaggle
- **Dataset URL**: [tooth-marked-tongue](https://www.kaggle.com/datasets/clearhanhui/biyesheji)
- **Year**: 2022
- **Country**: China
- **DOI**: 10.3390/diagnostics12102451
- **Source of Data Acquisition**: Schools
- **Reason for Image Acquisition**: Dental diagnosis
- **Imaging Modality**: Intraoral photograph
- **Equipment Detail**: Canon Eos 700d
- **License Type**: No License Specified
- **Annotators**: 5
- **Annotation Type**: Label
- **Annotation Software**: Labelme, Labelimg
- **Files Formats**: PNG
- **Images and Resolutions**: Photos, 861x755 (Height 861 px, Width: 755 px)
- **Image Quality**: Raw images
- **Example of File Names**: 140826072926_st.png, etc.

### Oral Cancer (Lips and Tongue) images

- **Database**: Kaggle
- **Dataset URL**: [Oral Cancer (Lips and Tongue) images](https://www.kaggle.com/datasets/shivam17299/oral-cancer-lips-and-tongue-images/data)
- **Year**: 2022
- **Country**: India
- **DOI**: N/A
- **Source of Data Acquisition**: Hospitals
- **Reason for Image Acquisition**: Diagnostic for oral diseases
- **Imaging Modality**: Intraoral photograph
- **Equipment Detail**: N/A
- **License Type**: Copyright the Authors
- **Annotators**: Not specified
- **Annotation Type**: Label
- **Files Formats**: JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp)
- **Images and Resolutions**: Photos, 825 x 1100 px
- **Image Quality**: Raw images
- **Example of File Names**: 324950_1100.jpg, IMG_3506-e1564923599677.jpg, etc.

### Pulp Exposure

- **Database**: PubMed
- **Dataset URL**: [Pulp Exposure](https://doi.org/10.6084/m9.figshare.23930368.v1)
- **Year**: 2023
- **Country**: Saudi Arabia, Spain, Korea
- **DOI**: 10.1186/s12903-023-03251-0
- **Source of Data Acquisition**: Dental clinics, University Dental School Clinic
- **Reason for Image Acquisition**: Not described
- **Imaging Modality**: Intraoral radiographs
- **Equipment Detail**: N/A
- **License Type**: No License Specified
- **Annotators**: 10
- **Annotation Type**: Box
- **Files Formats**: JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp)
- **Images and Resolutions**: Periapical, 1402 x 1876
- **Image Quality**: Raw images
- **Example of File Names**: Test Dataset 22.jpg, Test Dataset 17.jpg etc...

###  Panoramic-Paraguay

- **Database**: Zenodo
- **Dataset URL**: [Panoramic-Paraguay](https://zenodo.org/records/4457648)
- **Year**: 2021
- **Country**: Paraguay
- **DOI**: 10.3390/s21093110
- **Source of Data Acquisition**: University Dental School Clinic
- **Reason for Image Acquisition**: Not described
- **Imaging Modality**: Panoramic radiographs
- **Equipment Detail**: N/A
- **License Type**: No License Specified
- **Annotators**: 60
- **Annotation Type**: N/A
- **Files Formats**: JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp)
- **Images and Resolutions**: Panoramic images, 1024 x 2041 px
- **Image Quality**: Raw images
- **Example of File Names**: 104.jpg, 133.jpg, etc...


### Panoramic Dental Xray Dataset

- **Database**: Mendeley
- **Dataset URL**: [Panoramic Dental Xray Dataset](https://data.mendeley.com/datasets/73n3kz2k4k/2)
- **Year**: 2023
- **Country**: Tunisia
- **DOI**: 10.1007/s11042-023-17568-z
- **Source of Data Acquisition**: Dental clinics
- **Reason for Image Acquisition**: Dental diagnosis, research
- **Imaging Modality**: Panoramic radiographs
- **Equipment Detail**: N/A
- **License Type**: CC BY 4.0
- **Annotators**: 2
- **Annotation Type**: Pixel-level
- **Annotation Software**: VGG Image Annotator
- **Files Formats**: JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp)
- **Images and Resolutions**: Panoramic images, 1464 x 2964 px
- **Image Quality**: Raw images
- **Example of File Names**: 18.jpg, 22.jpg, etc..

###  PhysioNet Multimodal

- **Database**: Google Datasets
- **Dataset URL**: [PhysioNet Multimodal Dental Dataset](https://physionet.org/content/multimodal-dental-dataset/1.0.0/)
- **Year**: 2022
- **Country**: China
- **DOI**: 10.13026/s5z3-2766
- **Source of Data Acquisition**: Dental clinics
- **Reason for Image Acquisition**: Dental diagnosis, research
- **Imaging Modality**: Cone Beam Computed Tomography (CBCT), Panoramic radiographs
- **Equipment Detail**: PhysioNet
- **License Type**: PhysioNet Restricted Health Data License 1.5.0
- **Annotators**: 56
- **Annotation Type**: Box
- **Annotation Software**: 13
- **Files Formats**: DICOM (.dcm)
- **Images and Resolutions**: DICOM standard, raw images
- **Contains Additional Information**: Yes, LICENSE.txt and excel files
- **Example of File Names**: Folder name: 0006_0, 0008_0, etc.. Slices: Slice_0000.dcm, Slice_0001.dcm, etc..

 ### Dual-Labeled Dental Dataset

- **Database**: Kaggle
- **Dataset URL**: [Dual-Labeled Dental Dataset](A dual-labeled dataset)
- **Year**: 2023
- **Country**: Unknown
- **DOI**: N/A
- **Source of Data Acquisition**: Dental clinics
- **Reason for Image Acquisition**: Dental diagnosis, research
- **Imaging Modality**: Panoramic radiographs
- **Equipment Detail**: N/A
- **License Type**: Unknown
- **Annotators**: Yes
- **Annotation Type**: Label
- **Files Formats**: PNG
- **Images and Resolutions**: Panoramic images, file sizes vary from 374 KB to 3.44 MB
- **Number of Images**: 500 uploaded (2000 total expected)
- **Image Labeling Information**: Teeth were numbered using the FDI notation (33 labels); seven status labels include 'Tooth without anomalies,' 'Tooth with fillings,' 'Tooth with RCT,' etc.
- **Example of File Names**: 2005.png, 2006.png, etc.
- **Expected Update Frequency**: Remaining files expected by December 31
- **Additional Notes**: The tooth condition labels in the initial version are not final and are not recommended for use. However, tooth segmentation labels can be used.

 ### ORCHID: Oral Cancer Histology Image Database

- **Database**: medRxiv
- **Dataset URL**: [ORCHID](ORCHID)
- **Year**: 2024
- **Country**: India
- **DOI**: [10.1038/s41597-024-03836-6](https://doi.org/10.1038/s41597-024-03836-6)
- **Source of Data Acquisition**: Hospitals, Research Institutes (e.g., Jamia Millia Islamia, Rajendra Institute of Medical Sciences)
- **Reason for Image Acquisition**: Diagnosis of oral submucous fibrosis (OSMF) and oral squamous cell carcinoma (OSCC)
- **Imaging Modality**: Histopathology (H&E stained slides)
- **Equipment Detail**: Bright field microscopy (1000X effective magnification using a 100X objective lens)
- **License Type**: Unknown
- **Annotators**: Yes
- **Annotation Type**: Patch-level
- **Files Formats**: PNG
- **Images and Resolutions**: 300x300 pixel patches generated from 100X objective images
- **Number of Images**: Approximately 300,000 image patches
- **Example of File Names**: `ORCHID_InstitutionID_SampleID_ImageID_PatchID.png`
- **Dataset Highlights**:
  - Includes sub-classifications for OSCC into well-differentiated (WD), moderately-differentiated (MD), and poorly-differentiated (PD) categories.
  - Stain normalization applied using the Reinhard method.

### Vident-real: An Intra-Oral Video Dataset for Multi-Task Learning

- **Database:** Gdańsk University of Technology
- **Dataset URL:** [Vident-real.zip](http://Vident-real.zip)
- **Year:** 2024
- **Country:** Poland
- **DOI:** [10.34808/vjnh-9c35](http://10.34808/vjnh-9c35)
- **Source of Data Acquisition:** Medical University of Gdańsk
- **Reason for Image Acquisition:** Conservative dental treatments
- **Imaging Modality:** Intra-oral video recordings
- **Equipment Detail:** Tiny micro-camera attached to dental handpieces
- **License Type:** [CC BY-NC 4.0](http://creativecommons.org/licenses/by-nc/4.0/)
- **Annotators:** N/A
- **Annotation Type:** Pseudo-labels (enhanced frame, segmented teeth, homography between frames)
- **Files Formats:** JPEG (debayerized from RAW 10-bit images)
- **Images and Resolutions:**
  - Resolution: 800x800 pixels
  - Total frames: 70,000
  - Video sequences: 100
- **Example of File Names:**
  - vid001_frame001.jpg
  - vid002_frame001.jpg
  - ...

### Gingivitis Image Captioning Dataset

- **Database:** Mendeley
- **Dataset URL:** [Gingivitis Image Captioning Dataset](https://data.mendeley.com/datasets/3253gj88rr/1)
- **Year:** 2024
- **Country:** Vietnam
- **DOI:** 10.17632/3253gj88rr.1
- **Associated Publication DOI:** 10.1016/j.dib.2024.110960
- **Source of Data Acquisition:** High-quality Dental Treatment Centre, Hanoi Medical University
- **Reason for Image Acquisition:** Gingivitis diagnosis, image captioning research
- **Imaging Modality:** Intraoral photograph
- **Equipment Detail:** Nikon D810 with Nikon AF-S 105mm F/1.4EED Nano lens; Godox MF12 Macro Flash at 90-degree angle
- **License Type:** CC BY 4.0
- **Annotators:** 3 periodontists with over 10 years of experience
- **Annotation Type:** Label (Modified Gingival Index scores per tooth) and captions (3 descriptive captions per image)
- **Files Formats:** JPEG (.jpg), TXT (.txt), CSV
- **Images and Resolutions:**
  - 1,096 high-resolution intraoral images
  - Each image covers 12 anterior teeth (6 maxillary, 6 mandibular) and surrounding gingival tissue
  - Dataset size: 6.1 GB
  - Structured into training, validation, and testing subsets
- **Example of File Names:**
  - `00945.jpg` (image)
  - `00945.txt` (label file)
  - Captions stored as CSV files
- **Additional Notes:**
  - Labels use MGI codes: 1 = Maxillary ROI, 2 = Mandibular ROI, 3-6 = MGI0 to MGI4
  - High inter-rater reliability achieved through calibration process
  - Teeth cleaned and dried before photography; mouth gag used for visibility
  - No preprocessing or image augmentation applied
  - Ethical approval: IRB of Hanoi Medical University (1149/GCN-HMUIRB, 28 Dec 2023)
  - Data collected between January and May 2024

### Incisor Pulp Chamber Tomographic Images (IPCTI)

- **Database:** Mendeley
- **Dataset URL:** [IPCTI Dataset](https://data.mendeley.com/datasets/)
- **Year:** 2025
- **Country:** Brazil
- **DOI:** 10.1016/j.dib.2025.112033
- **Source of Data Acquisition:** Universidade Federal de Juiz de Fora, Zona da Mata Mineira
- **Reason for Image Acquisition:** Forensic odontology, dental age estimation
- **Imaging Modality:** Cone Beam Computed Tomography (CBCT)
- **Equipment Detail:** Not specified (standardized CBCT scanning protocols)
- **License Type:** CC (Creative Commons)
- **Annotators:** Not specified
- **Annotation Type:** Bounding box annotations for tooth localization
- **Files Formats:** Image files
- **Images and Resolutions:**
  - CBCT images of upper central incisors
  - Coronal and sagittal views per scan
  - Cohort: Brazilian individuals aged 18 to 60
- **Example of File Names:** Not specified
- **Additional Notes:**
  - Crown and pulp chamber dimensions used as age indicators (secondary dentin deposition)
  - Supports tooth detection, segmentation, and age estimation tasks

### Dental OPG X-ray Dataset (Six Classes)

- **Database:** Mendeley
- **Dataset URL:** [Dental OPG X-ray Dataset](https://data.mendeley.com/datasets/c4hhrkxytw/4)
- **Year:** 2024
- **Country:** Bangladesh
- **DOI:** 10.17632/c4hhrkxytw.4
- **Associated Publication DOI:** 10.1016/j.dib.2024.110970
- **Source of Data Acquisition:** Three private dental clinics: Prescription Point Ltd, LabAid Specialized Hospital, Ibn Sina Diagnostic and Imaging Center, Dhaka
- **Reason for Image Acquisition:** Dental disease detection and classification using deep learning
- **Imaging Modality:** Panoramic radiographs
- **Equipment Detail:** Samsung A52 (SM-A525F), 64 megapixels, f/1.8, 26 mm focal length
- **License Type:** CC BY-NC 4.0
- **Annotators:** 2 dentists (16 and 32 years of experience); annotated using CVAT
- **Annotation Type:** Bounding box (object detection)
- **Files Formats:** JPEG (.jpg), JSON
- **Images and Resolutions:**
  - 232 original panoramic radiographs
  - 604 augmented images (train: 558, test: 23, valid: 23)
  - Median image ratio: 1176 x 603 px, aspect ratio 16:9
  - Total instances across all classes: 1,204
  - Dataset size: 197 MB
- **Six Classes:** Healthy teeth, caries, impacted teeth, infections, fractured teeth, broken-down crown/root (BDC/BDR)
- **Example of File Names:** Not specified
- **Additional Notes:**
  - CLAHE applied for image enhancement
  - Augmentation via Roboflow (horizontal flips, rotations, shear, exposure adjustments, mosaic)
  - Excludes individuals under 10 years of age
  - Ethical approval: Bangladesh Dental College & Hospital (Protocol No: MK-198109)
  - Evaluated with YOLOv7: precision 96.03%, recall 86.53%, mAP50 93.54%

### Varying Views of Maxillary and Mandibular Aspects of Teeth Dataset

- **Database:** Mendeley
- **Dataset URL:** [Varying Views of Teeth Dataset](https://data.mendeley.com/datasets/6zsnhrds9t/1)
- **Year:** 2024
- **Country:** India
- **DOI:** 10.1016/j.dib.2024.110772
- **Source of Data Acquisition:** Bharati Vidyapeeth (Deemed to be University) and Vishwakarma University
- **Reason for Image Acquisition:** Dental condition analysis in children, machine learning research
- **Imaging Modality:** Intraoral photograph
- **Equipment Detail:** Not specified
- **License Type:** CC (Creative Commons)
- **Annotators:** Not specified
- **Annotation Type:** Label (categorized by view and arch type)
- **Files Formats:** Image files
- **Images and Resolutions:**
  - 9,562 images of healthy (non-carious) teeth
  - Children aged 1 to 14 years
  - Eight subcategories: maxillary/mandibular arches, front, right, left, and occlusal views
- **Example of File Names:** Not specified
- **Additional Notes:**
  - Covers primary, mixed, and permanent dentition
  - Stored under eight subcategories in the Mendeley repository
  - Intended for remote dental assessment in underserved areas

### Dental Periapical X-ray Dataset

- **Database:** Mendeley
- **Dataset URL:** [Dental Periapical X-ray Dataset](https://data.mendeley.com/datasets/)
- **Year:** 2024
- **Country:** Jordan
- **DOI:** 10.1016/j.dib.2024.110539
- **Source of Data Acquisition:** Oral and dental health department, Jerash Governmental Hospital, North Jordan
- **Reason for Image Acquisition:** Dental periapical disease diagnosis using deep learning
- **Imaging Modality:** Intraoral radiographs (periapical)
- **Equipment Detail:** Not specified
- **License Type:** CC BY-NC 4.0
- **Annotators:** Not specified
- **Annotation Type:** Pixel-level segmentation (healthy vs. diseased)
- **Files Formats:** Image files
- **Images and Resolutions:**
  - 929 high-quality periapical X-ray images
  - Subjects of varying ages with dental and pulpal diseases, bone loss, periapical pathologies
- **Example of File Names:** Not specified
- **Additional Notes:**
  - Images obtained during routine examinations and treatment procedures
  - Segmented into healthy and diseased categories
  - Supports automated diagnosis of caries, pulpal diseases, and periapical pathologies

### Apical Periodontitis Panoramic Radiographs Dataset

- **Database:** Mendeley
- **Dataset URL:** [Apical Periodontitis Dataset](https://data.mendeley.com/datasets/kx52tk2ddj/3)
- **Year:** 2024
- **Country:** Vietnam
- **DOI:** 10.1016/j.dib.2024.110486
- **Source of Data Acquisition:** High-quality Dental Treatment Centre, School of Dentistry, Hanoi Medical University
- **Reason for Image Acquisition:** Apical periodontitis detection and classification
- **Imaging Modality:** Panoramic radiographs
- **Equipment Detail:** Not specified
- **License Type:** CC BY-NC 4.0
- **Annotators:** 3 experienced dentists
- **Annotation Type:** Label (based on Periapical Lesions Classification)
- **Files Formats:** JPEG (.jpg)
- **Images and Resolutions:**
  - 3,926 original panoramic radiographs (from 16,519 screened)
  - 17,004 augmented images (scaling, mirroring, flipping)
  - 6,029 apical lesions expanded to 25,827 post-augmentation
- **Example of File Names:** Not specified
- **Additional Notes:**
  - Data collected between January 2016 and March 2021
  - Lesions classified by Periapical Lesions Classification system
  - Augmentation performed in Python (PyCharm): random scaling (0.8-1.2x), mirroring, rotation (-90 to 180 degrees), noise addition
  - Ethical approval: HMUIRB463 (03 Aug 2021)

### Histopathological Imaging Database for Oral Cancer

- **Database:** Mendeley
- **Dataset URL:** [Histopathological Oral Cancer Dataset](https://data.mendeley.com/datasets/ftmp4cvtmb/2)
- **Year:** 2020
- **Country:** India
- **DOI:** 10.1016/j.dib.2020.105114
- **Source of Data Acquisition:** Ayursundra Healthcare Pvt. Ltd. and Dr B. Borooah Cancer Institute (BBCI), Guwahati, Assam
- **Reason for Image Acquisition:** Oral squamous cell carcinoma (OSCC) diagnosis
- **Imaging Modality:** Histopathology (H&E stained biopsy slides)
- **Equipment Detail:** Leica ICC50 HD microscope
- **License Type:** CC BY 4.0
- **Annotators:** Medical experts
- **Annotation Type:** Label (normal epithelium vs. OSCC)
- **Files Formats:** Image files
- **Images and Resolutions:**
  - 1,224 total images from 230 patients
  - Set 1: 528 images at 100x magnification (89 normal, 439 OSCC)
  - Set 2: 696 images at 400x magnification (201 normal, 495 OSCC)
  - Tissue sections from buccal mucosa
- **Example of File Names:** Not specified
- **Additional Notes:**
  - Data collected from October 2016 to November 2017
  - Punch biopsy specimens fixed in 4% buffered formalin, dehydrated in alcohol series, cleared in xylene
  - 100x images suitable for architectural/tissue-level analysis
  - 400x images suitable for cellular-level textural feature analysis
  - First publicly available dataset of normal oral epithelium and OSCC histopathological images
