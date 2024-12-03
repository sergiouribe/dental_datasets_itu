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
| Orthopantomogram teeth segmentation and numbering dataset | Zenodo           | [Dataset Link](https://zenodo.org/records/10538750?token=eyJhbGciOiJIUzUxMiJ9...) | 2024 | Pakistan     | 10.5281/zenodo.10538750                   | Aga Khan University Hospital    | Developing AI models for dental diagnostics | Orthopantomogram (OPG)             | Orthophos XG 3-D (Dentsply Sirona GmbH) operated at 60–90 kV and 3–16 mA | Creative Commons License    | Specialist dentists | Instance segmentation | JSON format for annotations; PNG for images | 250 images of permanent dentition, 2440 × 1292 pixels | OPG_001.png, OPG_002.png, ... |






## LIST


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






