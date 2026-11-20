# AI Dental Research Dataset Catalogue

## Datasets Overview

This repository serves as a centralized database of datasets for artificial intelligence research in dental health. Below, each dataset is described in detail, including source information, imaging details, and usage licenses.
## TABLE

| Dataset Name | Database | Dataset URL | Year | Country | DOI | Source of Data Acquisition | Reason for Image Acquisition | Imaging Modality | Equipment Detail | License Type | Annotators | Annotation Type | Files Formats | Images and Resolutions | Example of File Names |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| DENTEX Panoramic Dataset | Zenodo | [DENTEX Panoramic](DENTEX Panoramic) | 2023 | Switzerland | 10.48550/arXiv.2305.19112, 10.48550/arXiv.2303.06500 | Dental clinics | Dental diagnosis | Panoramic radiographs | VistaPano S X-ray unit (Durr Dental, Germany) | No License Specified | Not specified | Label | PNG | Panoramic images, 2048x989 to 2950x1330 | train_30.png, val_12.png |
| CTooth Dataset | arXiv | [CTooth Dataset](CTooth Dataset) | 2022 | China | 10.1007/978-3-031-17027-0_7 | Dental clinics | Dental diagnosis, research | Cone Beam Computed Tomography (CBCT) | Op300, Instrumentarium, Finland | CC BY-NC 4.0 | Yes | Label | DICOM (.dcm) | DICOM standard, raw images | *.dcm |
| Panoramic Dental X-rays With Segmented Mandibles | Mendeley | [Panoramic Dental X-rays With Segmented Mandibles](Panoramic Dental X-rays With Segmented Mandibles) | 2020 | Iran | 10.1117/1.JMI.2.4.044003 | Dental clinics | Dental diagnosis, research | Panoramic radiographs | Soredex CranexD digital panoramic x-ray unit | CC BY-NC 3.0 | 2 | Pixel-level | PNG | Panoramic images, 2048x989 to 2950x1330, Cropped | 1.png, 85.png, etc. |
| Dental Radiography | Kaggle | [Dental Radiography](Dental Radiography) | 2023 | Iran | N/A | Dental clinic | Dental diagnosis, research | Panoramic radiographs | N/A | CC BY-SA 4.0 | Not specified | Label | JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp) | Panoramic images, 256x512 px, Cropped | 0041_jpg.rf.45bc3049f99113cefd018e407df2415f, 0095_jpg.rf.d7773e0afb13f54a3e6244079b483ab2, etc. |
| Panoramic-Caries-Segmentation | GitHub | [Panoramic-Caries-Segmentation](Panoramic-Caries-Segmentation) | 2023 | China | 10.1016/j.neucom.2023.03.069 | Not described | Not described | Panoramic radiographs | N/A | No License Specified | 5 | Pixel-level | PNG | Panoramic images, 1435x2943, Cropped | 1018.png, 1026.png, etc. |
| TK_Tooth_Number_Code | GitHub | [TK_Tooth_Number_Code](TK_Tooth_Number_Code) | 2022 | N/A | Not described | Not described | Not described | Panoramic radiographs | N/A | No License Specified | Not specified | Label | PNG | Cropped Panoramic images, 250x152, Cropped | 109_upper_0.png, 109_lower_0.png, etc. |
| CL Detection | Grand-challenge | [CL Detection](CL Detection) | 2023 | Taiwan | N/A | Dental clinics | Benchmarking | Cephalometric radiographs | N/A | No License Specified | Not specified | Pixel-level | JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp) | Cephalometric, 2048x1555 and 1804x2148 | N/A |
| Tufts Panoramic Dataset | PubMed | [Tufts Panoramic Dataset](Tufts Panoramic Dataset) | 2021 | USA | 10.1109/JBHI.2021.3117575 | University Dental School Clinic | Diagnostic Investigation | Panoramic radiographs | OP100 Orthopantomograph (Instrumentarium Imaging/Kavo Kerr) and Plammeca Promax 2D | No License Specified | 2 | Label | JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp) | Panoramic images, 840x1615 | 1.JPG, 2.JPG, etc. |
| 3DTeethSeg22_challenge ToothFairy or Teeth3DS | OSF | [3DTeethSeg22_challenge ToothFairy or Teeth3DS](3DTeethSeg22_challenge ToothFairy or Teeth3DS) | 2022 | France, Belgium | 10.48550/arXiv.2210.06094 | Dental clinics | Dental diagnosis | Intra-oral 3D scans | Primescan, Trios3, iTero Element 2 Plus | CC BY-NC-ND 4.0 | 50 | Pixel-level | DICOM (.dcm) | DICOM standard, raw images | *.dcm |
| v7labs Panoramic Dental | Google Datasets | [v7labs Panoramic Dental](v7labs Panoramic Dental) | 2023 | USA | N/A | Dental clinics | Dental diagnosis, research | Panoramic radiographs | N/A | No License Specified | No | Pixel-level | PNG | Panoramic images, 1250 x 3122 px | 93.png, 85.png, etc. |
| tooth-marked-tongue | Kaggle | [tooth-marked-tongue](tooth-marked-tongue) | 2022 | China | 10.3390/diagnostics12102451 | Schools | Dental diagnosis | Intraoral photograph | Canon Eos 700d | No License Specified | 5 | Label | PNG | Photos, 861x755 (Height 861 px, Width: 755 px) | 140826072926_st.png, etc. |
| Oral Cancer (Lips and Tongue) images | Kaggle | [Oral Cancer (Lips and Tongue) images](Oral Cancer (Lips and Tongue) images) | 2022 | India | N/A | Hospitals | Diagnostic for oral diseases | Intraoral photograph | N/A | Copyright the Authors | Not specified | Label | JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp) | Photos, 825 x 1100 px | 324950_1100.jpg, IMG_3506-e1564923599677.jpg, etc. |
| Pulp Exposure | PubMed | [Pulp Exposure](Pulp Exposure) | 2023 | Saudi Arabia, Spain, Korea | 10.1186/s12903-023-03251-0 | Dental clinics, University Dental School Clinic | Not described | Intraoral radiographs | N/A | No License Specified | 10 | Box | JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp) | Periapical, 1402 x 1876 | Test Dataset 22.jpg, Test Dataset 17.jpg etc. |
| Panoramic-Paraguay | Zenodo | [Panoramic-Paraguay](Panoramic-Paraguay) | 2021 | Paraguay | 10.3390/s21093110 | University Dental School Clinic | Not described | Panoramic radiographs | N/A | No License Specified | 60 | N/A | JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp) | Panoramic images, 1024 x 2041 px | 104.jpg, 133.jpg, etc. |
| Panoramic Dental Xray Dataset | Mendeley | [Panoramic Dental Xray Dataset](Panoramic Dental Xray Dataset) | 2023 | Tunisia | 10.1007/s11042-023-17568-z | Dental clinics | Dental diagnosis, research | Panoramic radiographs | N/A | CC BY 4.0 | 2 | Pixel-level | JPEG (.jpg, .jpeg, .jfif, .pjpeg, .pjp) | Panoramic images, 1464 x 2964 px | 18.jpg, 22.jpg, etc. |
| PhysioNet Multimodal | Google Datasets | [PhysioNet Multimodal Dental Dataset](PhysioNet Multimodal Dental Dataset) | 2022 | China | 10.13026/s5z3-2766 | Dental clinics | Dental diagnosis, research | Cone Beam Computed Tomography (CBCT), Panoramic radiographs | PhysioNet | PhysioNet Restricted Health Data License 1.5.0 | 56 | Box | DICOM (.dcm) | DICOM standard, raw images | Folder name: 0006_0, 0008_0, etc. Slices: Slice_0000.dcm, Slice_0001.dcm, etc. |
| A dual-labeled dataset for automatic teeth segmentation, numbering, and state assessment | Kaggle | [A dual-labeled dataset](A dual-labeled dataset) | 2023 | Unknown | N/A | Dental clinics | Dental diagnosis, research | Panoramic radiographs | N/A | Unknown | Yes | Label | PNG | Panoramic images, varying file sizes from 374 KB to 3.44 MB | 2005.png, 2006.png, etc. |
| ORCHID: Oral Cancer Histology Image Database | medRxiv | [ORCHID](ORCHID) | 2024 | India | 10.1038/s41597-024-03836-6 | Hospitals, Research Institutes | Oral cancer and precancer diagnosis | Histopathology | Bright field microscopy (1000X effective magnification) | Unknown | Yes | Patch-level | PNG | 300x300 pixel patches from 100X objective images | ORCHID_InstituteID_SampleID_ImageID_PatchID.png |
| Vident-real: An Intra-Oral Video Dataset for Multi-Task Learning | Gdańsk University of Technology | [Vident-real.zip](http://Vident-real.zip) | 2024 | Poland | [10.34808/vjnh-9c35](http://10.34808/vjnh-9c35) | Medical University of Gdańsk | Conservative dental treatments | Intra-oral video recordings | Tiny micro-camera attached to dental handpieces | CC BY-NC 4.0 | N/A | Pseudo-labels (enhanced frame, segmented teeth, homography between frames) | JPEG (debayerized from RAW 10-bit images) | 800x800 pixels, 70,000 frames across 100 video sequences | vid001_frame001.jpg, vid002_frame001.jpg, etc. |
| Multimodal Dental Dataset | PhysioNet | [Dataset Link](https://doi.org/10.13026/h1tt-fc69) | 2024 | China | 10.13026/h1tt-fc69 | Guilin Medical University | Collection of imaging data for machine learning and clinical research | CBCT, Panoramic Radiographs, Periapical Radiographs | Smart3D-X CBCT machine, 2D flat panel detector for panoramic imaging, Portable intraoral X-ray generator | Open Access (Creative Commons Attribution-NonCommercial-NoDerivatives 4.0) | Multiple annotators (13 labeled images) | Tooth annotation | DICOM for CBCT and Panoramic, TIF for Periapical | 329 CBCT images, 8 Panoramic, 16,203 Periapical images | e.g., `0006_0` for patient 0006's first visit |
| ACTA-DIRECT Dataset | ACTA-DIRECT Dataset | [ACTA-DIRECT Dataset](https://publication.yoda.vu.nl/full/VU01/WK8SQN.html) | 2024 | Netherlands | 10.48338/VU01-UAAHEY | Extracted dental samples | Diagnostic insights for radiographic early-caries with micro-CT | Micro-CT scans and conventional radiographs |  | Open - freely retrievable | Three different experts for conventional annotations | Initial proximal caries lesion annotations |  | 179 extracted molar and premolar teeth |  |
| Orthopantomogram teeth segmentation and numbering dataset | Zenodo | [Dataset Link](https://zenodo.org/records/10538750?token=eyJhbGciOiJIUzUxMiJ9...) | 2024 | Pakistan | 10.5281/zenodo.10538750 | Aga Khan University Hospital | Developing AI models for dental diagnostics | Orthopantomogram (OPG) | Orthophos XG 3-D (Dentsply Sirona GmbH) operated at 60–90 kV and 3–16 mA | Creative Commons License | Specialist dentists | Instance segmentation | JSON format for annotations; PNG for images | 250 images of permanent dentition, 2440 × 1292 pixels | OPG_001.png, OPG_002.png, ... |
| AlphaDent Dataset | GitHub | [AlphaDent GitHub Repository](https://github.com/ZFTurbo/AlphaDent) | 2025 | Russia | N/A | Sechenov University, AlphaChip LLC, HSE University | Detection and segmentation of dental pathologies | Intraoral DSLR photography | Canon 6D Mark II with Canon 100mm f/2.8L macro IS USM lens | Open License (not specified) | 1 (dentist) | Instance segmentation | JPEG (.jpg), PNG (.png), TXT (.txt) | ~1320 images (>5000x3000 px); 295 patients | p001_F_32_001.jpg, 01_class_5.png, p001_F_32_001.txt |
| Gingivitis Image Captioning Dataset | Mendeley | [Gingivitis Image Captioning Dataset](https://data.mendeley.com/datasets/3253gj88rr/1) | 2024 | Vietnam | 10.17632/3253gj88rr.1 | Hanoi Medical University | Gingivitis diagnosis, image captioning research | Intraoral photograph | Nikon D810 with Nikon AF-S 105mm F/1.4EED Nano lens, Godox MF12 Macro Flash | CC BY 4.0 | 3 (periodontists with >10 years experience) | Label (MGI scores) and captions | JPEG (.jpg), CSV, TXT | 1,096 high-resolution intraoral images of 12 anterior teeth | 00945.jpg, 00945.txt |
| Incisor Pulp Chamber Tomographic Images (IPCTI) | Mendeley | [IPCTI Dataset](https://data.mendeley.com/datasets/) | 2025 | Brazil | 10.1016/j.dib.2025.112033 | Universidade Federal de Juiz de Fora | Forensic odontology, dental age estimation | Cone Beam Computed Tomography (CBCT) | Not specified (standardized CBCT protocols) | CC (Creative Commons) | Not specified | Box (bounding box) | Image files | CBCT coronal and sagittal views of upper central incisors, ages 18-60 | Not specified |
| Dental OPG X-ray Dataset (Six Classes) | Mendeley | [Dental OPG X-ray Dataset](https://data.mendeley.com/datasets/c4hhrkxytw/4) | 2024 | Bangladesh | 10.17632/c4hhrkxytw.4 | Three private dental clinics, Dhaka | Dental disease detection and classification | Panoramic radiographs | Samsung A52 (SM-A525F), 64 megapixels | CC BY-NC 4.0 | 2 (dentists with 16 and 32 years experience) | Box (bounding box) | JPEG (.jpg), JSON | 232 original + 604 augmented panoramic images, 1176 x 603 px | Not specified |
| Varying Views of Teeth Dataset | Mendeley | [Varying Views of Teeth Dataset](https://data.mendeley.com/datasets/6zsnhrds9t/1) | 2024 | India | 10.1016/j.dib.2024.110772 | Bharati Vidyapeeth University | Dental diagnosis, pediatric dentistry research | Intraoral photograph | Not specified | CC (Creative Commons) | Not specified | Label | Image files | 9,562 images of healthy teeth from children aged 1-14 | Not specified |
| Dental Periapical X-ray Dataset | Mendeley | [Dental Periapical X-ray Dataset](https://data.mendeley.com/datasets/) | 2024 | Jordan | 10.1016/j.dib.2024.110539 | Jerash Governmental Hospital | Dental periapical disease diagnosis | Intraoral radiographs (periapical) | Not specified | CC BY-NC 4.0 | Not specified | Pixel-level (segmentation) | Image files | 929 high-quality periapical X-ray images | Not specified |
| Apical Periodontitis Panoramic Dataset | Mendeley | [Apical Periodontitis Dataset](https://data.mendeley.com/datasets/kx52tk2ddj/3) | 2024 | Vietnam | 10.1016/j.dib.2024.110486 | Hanoi Medical University | Apical periodontitis detection and classification | Panoramic radiographs | Not specified | CC BY-NC 4.0 | 3 (experienced dentists) | Label (Periapical Lesions Classification) | JPEG (.jpg) | 3,926 original + 17,004 augmented panoramic radiographs | Not specified |
| Histopathological Imaging Database for Oral Cancer | Mendeley | [Histopathological Oral Cancer Dataset](https://data.mendeley.com/datasets/ftmp4cvtmb/2) | 2020 | India | 10.1016/j.dib.2020.105114 | Ayursundra Healthcare, Dr B. Borooah Cancer Institute, Guwahati | Oral squamous cell carcinoma diagnosis | Histopathology (H&E stained slides) | Leica ICC50 HD microscope | CC BY 4.0 | Medical experts | Label | Image files | 1,224 images: 528 at 100x and 696 at 400x magnification, from 230 patients | Not specified |
| Dental caries in bitewing radiographs | Mendeley | [Dental caries in bitewing radiographs](https://data.mendeley.com/datasets/4fbdxs7s7w/1) | 2023 | Czech Republic | 10.17632/4fbdxs7s7w.1 | Hospital | Caries detection research | Bitewing radiographs | N/A | CC (standard Mendeley) | 8 (5 experienced, 3 less) | Box (bounding boxes) | PNG, COCO JSON | 100 images, 1068x847 px | N/A |
| COLLECT: Counterfactual Oral Lesion Library for Explainable Concept Testing | Borealis | [COLLECT Dataset](https://doi.org/10.5683/SP3/KXYCNY) | 2026 | Canada | 10.5683/SP3/KXYCNY | Routine dental examinations; clinical intra-oral images collected by certified oral pathologists | AI model robustness, interpretability, explainable concept testing, and diagnostic reliability in oral lesion classification | Intraoral clinical photography | Digital cameras under standard clinic lighting | CC BY-NC-ND 4.0 | Certified oral pathologists and oral health experts | Expert-validated lesion labels and structured counterfactual transformations | Image files | 600 images total: 40 baseline images × 5 versions each; resolution not specified | Not specified |
| AKUDENTAL Teeth Instance Segmentation Dataset | GitHub | AKUDENTAL | 2026 | Türkiye | 10.1186/s12903-025-07645-0 | Akdeniz University Dental Hospital | Teeth segmentation, detection, numbering, and cross-dataset AI benchmarking | Panoramic radiographs | Two panoramic X-ray devices; specific models not reported | Publicly available for non-commercial academic research | Expert annotator | Instance-level polygon segmentation | Image files, JSON annotations | 333 panoramic radiographs; 2494×1435 to 2871×1536 px; average approximately 2908×1445 px | Not specified |
| BRAR-anchored Multimodal Dataset | Figshare | BRAR-anchored multimodal dataset | 2025 | China | 10.1038/s41597-025-06400-y | Department of Periodontology, Shanghai Stomatological Hospital | Periodontal bone resorption assessment, grading, and AI research | Panoramic radiographs with demographic and clinical metadata | Not specified | Openly available via Figshare | Two trained dentists; validated by a senior oral radiology expert | Patient- and tooth-level clinical annotations; BRAR severity grading | JPG, CSV, PDF | 1,104 full-mouth panoramic radiographs; resolution not specified | Anonymized identifiers |
| Annotated Clinical Image Dataset for Malignant and Potentially Malignant Oral Lesions | Zenodo | Annotated Clinical Image Dataset | 2025 | Egypt | 10.1038/s41415-025-9007-6 | Oral Medicine Clinic, Faculty of Dentistry, Cairo University | AI training and classification of normal, low-risk, and high-risk oral lesions | Intraoral clinical photography | Standardized clinical photography with proper lighting; camera model not specified | CC BY-NC-ND 4.0; restricted access upon request | Two oral medicine specialists with PhDs and >10 years clinical experience | Bounding-box annotations of lesions and anatomical regions; JSON | JPG, JSON | 9,201 original intraoral images; dimensions vary from 40,992 to 24,216,480 total pixels | Not specified |
| Dataset of Annotated Oral Cavity Images for Oral Cancer Detection | Zenodo | Dataset of Annotated Oral Cavity Images for Oral Cancer Detection | 2024 | Sri Lanka | 10.1016/j.oraloncology.2024.106946 | Dental Teaching Hospital, University of Peradeniya | Diagnosis of oral cancer and oral potentially malignant disorders | Intraoral oral-cavity photography | Mobile phone cameras | Open access | Clinicians using custom-made annotation software | Polygon annotations of oral cavity and lesion boundaries; COCO format | Image files, COCO annotations, patient metadata | 3,000 anonymized high-quality images from 714 patients | Not specified |
| Annotated intraoral image dataset for dental caries detection | Zenodo / Scientific Data | [Zenodo](https://zenodo.org/records/14827784) | 2025 | Pakistan | 10.5281/zenodo.14827784 (dataset); 10.1038/s41597-025-05647-9 (paper) | Government schools, Mithi, Sindh (Aga Khan University) | AI-driven dental caries detection research | Intraoral photographs | Samsung Galaxy A23 (Android 14.0) | CC BY-NC-ND 4.0 | 2 dentists (>2 years experience), calibrated by specialist; third resolved disagreements | Bounding boxes (object detection; primary ‘d’, permanent ‘D’) | JPG; LabelMe (.json), YOLO (.txt), PASCAL VOC (.xml), COCO (.json) | 6,313 images (ages 10–24); with/without cheek retractors; 5 views per patient (maxillary/mandibular occlusal, left/right lateral, frontal) | Not specified |
| Mixed Dentition Orthopantomogram Dataset for AI Research in Pediatric Dental Cariology (MD-OPG) | Zenodo; GitHub | [Zenodo record](https://zenodo.org/records/17786082); [GitHub repository](https://github.com/IASBS-AI-LAB/MD-OPG/tree/main) | 2025 dataset release; 2026 publication | Iran (Zanjan) | [10.5281/zenodo.17786082](https://doi.org/10.5281/zenodo.17786082) | Retrospective, de-identified digital panoramic radiographs selected from archival records of a private dental clinic in Zanjan, Iran; dataset developed with the Institute for Advanced Studies in Basic Sciences (IASBS) and Zanjan University of Medical Sciences (ZUMS) | Pediatric dental assessment, diagnosis, treatment planning, and development/benchmarking of AI systems for pediatric dental-caries detection | Digital orthopantomogram (OPG); panoramic dental radiograph | Not specified in the publication, Zenodo record, or accessible repository metadata | No dataset-specific reuse license specified in accessible metadata; associated publication is CC BY, but this should not automatically be considered the dataset license | Two trained mid-level dental-radiograph annotators performed initial annotations; two experienced dental specialists reviewed and resolved disagreements to establish consensus labels | Polygonal region-of-interest annotations in JSON: `P` for proximal caries, `O` for occlusal caries, and rectangular `Z` for the smile-zone/crown-bearing region; derived smile-zone masks available for segmentation | PNG images; JSON annotations; distributed as `MD_OPG.rar` | 170 panoramic radiographs; each original full image is 1920 × 1535 px. Smile-zone images have variable original dimensions and are padded to 440 × 1000 px for segmentation. Dataset includes 716 proximal-caries labels and 179 occlusal-caries labels | Individual file names not specified in accessible documentation; archive: `MD_OPG.rar`; image files: `.png`; annotation files: `.json` |
| PRAD-10K | GitHub | [PRAD-10K](https://github.com/nkicsl/PRAD) | 2025 | China | 10.1007/978-3-032-05169-1_46 (MICCAI 2025 chapter); 10.48550/arXiv.2504.07760 (preprint) | Clinical periapical radiographs collected for endodontic and periodontic diagnosis; annotated by professional endodontists | Auxiliary diagnosis and benchmark model development for periapical radiograph analysis | Periapical radiographs (PR) | Not specified | Not specified; described as partially available to the public through an application process due to copyright and commercial considerations; 5,000 of the 10,000 images available on request | Two endodontists with over 8 years of experience, plus one computer science researcher | Pixel-level annotations for 9 anatomical structures, lesions, restorations, and medical devices; classification labels for periodontitis, apical periodontitis, and inadequate root canal filling | Not specified | 10,000 clinical periapical radiographs | Not specified |
| Dataset for Automating Dental Condition Detection on Panoramic Radiographs | Zenodo | [Zenodo record](https://zenodo.org/records/15487430) | 2025 | Romania | 10.5281/zenodo.15487430 (dataset); 10.3390/diagnostics14202336 (Mureșanu et al. 2024); 10.1016/j.mex.2025.103696 (Eftimie et al. 2025) | Department of Maxillofacial Surgery and Radiology, Iuliu Hațieganu University of Medicine and Pharmacy, Cluj-Napoca, Romania; retrospectively collected April 2021-December 2023, plus an external validation set from other Cluj-Napoca medical centers | Automated detection of dental conditions to support diagnosis, treatment planning, and risk stratification | Panoramic radiographs | Vatech PCH-2500 (Vatech, Hwaseong, Republic of Korea) | CC BY 4.0, subject to an additional database usage agreement restricting use to non-commercial research and education and prohibiting redistribution | Three calibrated researchers using Makesense.ai v1.11.0; inter-observer agreement ICC = 0.91 | Bounding boxes (YOLO format) across 14 classes: implant, prosthetic restoration, obturation, endodontic treatment, carious lesion, bone resorption, impacted tooth, apical periodontitis, root fragment, furcation lesion, apical surgery, root resorption, orthodontic device, surgical device | JPEG (.jpg) | 1,628 panoramic images (training set), plus a separate external validation set of 180 radiographs | Not specified |
| Expert Annotated Mandibular Third Molar (ExAn-MTM) Dataset | Mendeley | [ExAn-MTM Dataset](https://data.mendeley.com/datasets/t8k59p35p6/1) | 2025 | Türkiye | 10.1007/s11227-025-07775-w | Derived and re-annotated from the UESB panoramic radiograph dataset (Silva et al., 2018) | Detection and explainable AI classification of mandibular third molar eruption status to support surgical decision-making | Panoramic radiographs | Not specified | Not specified | One experienced oral and maxillofacial radiologist using the MakeSense annotation tool | Bounding boxes (YOLO format), 2 classes: e-MTM (erupted) and i-MTM (impacted) | Image files with YOLO-format label files; organized into train/valid folders | 973 panoramic radiographs; training set 875 images (624 e-MTM, 980 i-MTM annotations) | Not specified |
| A Multi-Center Dental Panoramic Radiography Image Dataset for Impacted Teeth, Periodontitis, and Dental Caries | GitHub | [qinxin99/qinxini](https://github.com/qinxin99/qinxini) | 2024 | China | 10.1007/s10278-024-00972-8 | Three hospitals: Stomatological Hospital of the General Hospital of Ningxia Medical University (Yinchuan), People's Hospital of Yinchuan City (Ningxia), and a hospital in Shenzhen, Guangdong Province; ethical approval KYLL-2021066 | Multi-center benchmarking of segmentation and classification models for impacted teeth, periodontitis, and dental caries to improve cross-center generalization | Panoramic radiographs | Instrumentarium Dental OP200D (Center 1); Veraviewepocs and ORTHOPHOS XG (Center 2); Sirona X-ray machine (Center 3) | Available on request through GitHub; no standard license specified, stated for research use | Two dentists (25 and 18 years of clinical experience) performed initial annotation; two additional associate professors (15 years' experience each) reviewed and resolved disagreements | Manual contour outlining in ITK-SNAP, converted from DICOM to NIFTI; labels for impacted teeth, caries lesions, and periodontal bone-loss areas | DICOM converted to NIFTI | 6,580 total images across 3 centers (4,940 + 716 + 880 core sets after exclusions: 5,557 + 734 + 126 + 163 = 6,580 in final grouping); 2,567 impacted-teeth images, 2,736 periodontitis images, 1,277 caries images; resolutions 2976×1536, 2893×1480, 2440×1280, and 2440×1292 px depending on center | Not specified |
| COLLECT: Counterfactual Oral Lesion Library for Explainable Concept Testing | Borealis | [COLLECT](https://doi.org/10.5683/SP3/KXYCNY) | 2026 | Canada | 10.5683/SP3/KXYCNY, 10.1177/00220345261466240 | Routine dental examinations; clinical intra-oral images collected by certified oral pathologists | AI model robustness, interpretability, explainable concept testing, and diagnostic reliability in oral lesion classification | Intraoral clinical photography | Digital cameras under standard clinic lighting | CC BY-NC-ND 4.0 | Certified oral pathologists and oral health experts | Expert-validated lesion labels and structured counterfactual transformations | Image files | 600 images total: 40 baseline images × 5 versions each; resolution not specified | Not specified |
| GingivitisSeg | Zenodo / GitHub | [GingivitisSeg](https://github.com/zeynepozdemir/GingivitisSeg) | 2026 | Türkiye | 10.48550/arXiv.2611.15184 (paper); 10.5281/zenodo.21098897 (dataset) | Ankara University Faculty of Dentistry (432 clinical images) + public source (Duy et al., 529 images) | Gingivitis segmentation, computer-assisted periodontal assessment, AI benchmarking | Intraoral photograph | Smartphone cameras (clinical subset); secondary use of existing public photographs | Public (paper CC BY-NC-SA 4.0); dataset publicly released | 2 dental experts (one >10 years experience, one postgraduate resident); joint consensus review | Pixel-level (binary gingival inflammation masks) | Intraoral images + segmentation masks | 961 images; native width 416–7286 px, height 218–4863 px; mean ≈4346 × 2894; mean gingivitis area 3.51% | Not specified |
| ToothPix: A multi-focus oral panoramic X-ray image dataset based on pixel-level annotations | Zenodo | [ToothPix](https://zenodo.org/records/18439233) | 2026 | China | 10.5281/zenodo.18439233 (dataset); 10.1038/s41597-026-07021-9 (article) | Changsha Stomatological Hospital; clinical images acquired July 2024–February 2025 | Routine dental imaging; subsequent AI segmentation and detection research | Panoramic radiographs | Manufacturer and model not reported | Restricted; application and signed Data Use Agreement required | 20 dental imaging specialists, each with ≥3 years of experience | LabelMe polygon annotations of individual teeth; RGB segmentation masks | BMP/PNG images; JSON annotations; RGB PNG masks | 8,655 radiographs from 8,655 patients; 1890 × 841 px; >30,186 individual-tooth annotations | 0001/0001.bmp; 0001/0001.png; 0001/0001.json |
| Dental Odontogenic Lesion CBCT and Histopathology Integrated Dataset (DOLCHID) | Figshare | [DOLCHID](https://doi.org/10.6084/m9.figshare.30156622) | 2025 dataset citation in authors’ repository; 2026 article | China | 10.6084/m9.figshare.30156622 (dataset); 10.1038/s41597-026-07112-7 (article) | School & Hospital of Stomatology, Wuhan University; surgically treated patients | Preoperative imaging and postoperative histopathological diagnosis; subsequent segmentation and classification research | CBCT; H&E histopathology | NewTom VG; Olympus light microscope | CC BY according to Figshare metadata; exact licence version not verified | 3 radiologists and 2 pathologists, each with >10 years of experience; cross-review and consensus | 3D CBCT lesion masks; histopathology ROI masks; four diagnostic classes | NIfTI (.nii.gz) volumes and masks; PNG histopathology images and masks | 262 paired cases: 44 dentigerous cysts, 54 radicular cysts, 92 odontogenic keratocysts, 72 ameloblastomas; reported CBCT voxel size 0.3 mm; histopathology pixel dimensions not reported | AME_1_CBCT_Image.nii.gz; AME_1_CBCT_Label.nii.gz; AME_1_HIST_Image.png; AME_1_HIST_Label.png |
| COde: Casangels Oro-dental Dataset | Hugging Face | [COde](https://huggingface.co/datasets/zirak-ai/COde) | 2025 dataset citation; 2026 article | China | 10.57967/hf/6421 (dataset); 10.1038/s41597-026-07342-9 (article) | Suzhou Dental Doctor Outpatient Clinic; routine visits during 2018–2025 | Routine care; subsequent multimodal anomaly classification and report-generation research | Intraoral photographs; panoramic/periapical radiographs; CBCT-derived 2D images; clinical text | Canon D60 with 100 mm macro lens, as reported; Sirona Galileos CBCT; other X-ray models not specified | CC BY 4.0 | Licensed dental practitioners verified report-derived labels; number and experience not reported | Clinical-report-derived anomaly labels; Chinese/English narratives; diagnoses, treatment plans and follow-up notes | JPEG; CSV; JSON; ShareGPT-format JSON; ZIP distribution | 50,000 photographs and 8,056 radiographic images; 8,775 checkups from 4,800 patients; longest image dimension resized to 448 px | checkup_id followed by sequential image index; literal example not reported |
| A multi-physician dental clinical dataset with structured EMR narratives and paired panoramic radiographs | Figshare | [Dental clinical dataset](https://doi.org/10.6084/m9.figshare.32219928) | 2026 article; initial repository release date not verified | China | 10.6084/m9.figshare.32219928 (dataset); 10.1038/s41597-026-08544-x (article) | Department of Stomatology, First Affiliated Hospital of Shihezi University; adult outpatient records, 2022–2025 | Routine outpatient care; subsequent research linking narratives, diagnoses, treatment decisions and imaging | Panoramic radiographs; structured EMR narratives | Not specified in accessible article webpage | CC BY 4.0 verified for Figshare v2; article-associated v3 licence not independently inspected | 5 physician authors; 20 double-transcription staff; 3 dental quality raters; 2 bilingual dental reviewers | 17 structured fields; category-level ICD-10 codes; synchronized Chinese/English narratives | Main dataset file extensions not verified; archive not inspected | 463 adult cases; 443 paired panoramic radiographs; pixel dimensions not verified | Not verified; individual filenames unavailable in retrieved sources |
| CODE: Comprehensive Oral Mucosa Database with Explanations | Figshare | https://doi.org/10.6084/m9.figshare.30550889 | 2026 | India | 10.1016/j.dib.2026.113270 (article); 10.6084/m9.figshare.30550889 (dataset) | ICMR-funded SMITA project; outpatient and community screening in Tamil Nadu | Normative oral mucosal feature learning, anomaly detection, segmentation, and AI-assisted oral screening research | Smartphone intraoral photographs | OnePlus Nord CE4 Lite 5G; vivo Y33s; Xiaomi 11 | CC BY 4.0, explicitly reported for dataset version 5.0 | Two calibrated oral pathologists, approximately three years of experience each; disagreements resolved by consensus | VIA polygon annotations of anatomical structures, mucosal sub-sites, lesion boundaries, and regions of interest; linked participant metadata | JPG; JSON; XLSX | 5,566 images from 704 participants: 5,386 normal and 180 abnormal; variable pixel dimensions after cropping; annotated and unannotated versions are not independent images | SMITA03453_KSR_DT.jpg |
| DentFilm v1.0: An expert-annotated clinical image dataset of complete denture biofilm | Zenodo | https://doi.org/10.5281/zenodo.22813487 | 2026 | Brazil | 10.1016/j.dib.2026.113318 (article); 10.5281/zenodo.22813487 (dataset) | School of Dentistry, Federal University of Alfenas; 30 maxillary complete-denture wearers | Biofilm segmentation and quantification from unstained complete-denture photographs | Clinical photographs of complete dentures | Canon EOS Rebel T7; Canon EF 100 mm f/2.8 Macro lens; flash-assisted acquisition | Dataset licence requires repository verification; article is CC BY 4.0 | One trained examiner using ibisPaintX | Binary pixel-level biofilm masks drawn on unstained photographs using corresponding disclosed photographs as visual references | JPG photographs; PNG masks; tabular metadata; XLSX demographic data; PDF/TXT documentation | Paper reports 630 photographs and 90 masks from 30 participants; native resolution 6000 × 4000; analysis preprocessing 240 × 160; conflicting statements about release of disclosed images require repository verification | Exact filenames not specified in the supplied paper |
| A dataset of preclinical tooth preparation images | Mendeley Data | https://doi.org/10.17632/27kp5jg4c3.3 | 2026 | Jordan | 10.1016/j.dib.2026.112900 (article); 10.17632/27kp5jg4c3.3 (dataset) | Jordan University of Science and Technology; artificial-tooth crown preparations by 533 fourth-year dental students | Automated preclinical preparation assessment, educational feedback, classification, and quality-score prediction | Multi-view photographs of prepared artificial teeth | Canon EOS 250D/Rebel SL3; Sigma 105 mm f/2.8 DG Macro HSM OS lens; Canon Macro Ring Lite MR-14EX | Dataset licence requires repository verification; article is CC BY-NC 4.0 | One specialist prosthodontist; no inter-rater reliability testing | Tooth-type labels; five binary rubric criteria; aggregate score 0–5; derived pass/fail and ordinal feedback categories | JPG; XLSX; ZIP archives; Python stitching script | 1,283 preparations represented by 3,849 separate-view images at 400 × 400 and 1,283 composites at 1200 × 400; these are alternate representations, not independent samples | 6_C_L.jpg; Annotation.xlsx; Stitched Images.zip; Separate View Images.zip; stitching.py |
| AIRC-LABDEN: A multi-modal dataset for dental plaque diagnosis of patients with fixed labial orthodontic appliances | Mendeley Data, two parts | https://doi.org/10.17632/g8yhdvgjy2.3 ; https://doi.org/10.17632/xjs4bfgzj5.3 | 2026 | Vietnam | 10.1016/j.dib.2026.112833 (article); 10.17632/g8yhdvgjy2.3 and 10.17632/xjs4bfgzj5.3 (dataset parts) | VNU University of Medicine and Pharmacy and 108 Military Central Hospital, Hanoi; 148 orthodontic patients | Plaque localization and multimodal plaque assessment in patients with fixed labial appliances | Intraoral photographs with anonymized clinical records | Canon RP; Canon RF 100 mm f/2.8 L Macro lens; Godox MF12 flash; Dantech KD1 diffuser | Dataset licence requires repository verification; article is CC BY-NC 4.0 | Two dentists with at least five years of experience; YOLOv8-assisted proposals followed by expert verification | Bounding boxes for gingival, incisal, mesial, and distal regions around brackets; plaque presence/absence and tooth identifiers; linked clinical metadata | TXT labels; DOCX clinical records; JSON mapping; CSV split file; image extension requires verification | 10,450 images reported from 148 patients; processed resolution 5536 × 4160; augmentation described, so original-image count requires verification | patientxxxx.docx; teeth_position_mapping.json; Data_splits.csv |


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
 
### Dental caries in bitewing radiographs
- **Database:** Mendeley
- **Dataset URL:** https://data.mendeley.com/datasets/4fbdxs7s7w/1
- **Year:** 2023
- **Country:** Czech Republic
- **DOI:** 10.17632/4fbdxs7s7w.1
- **Source:** Hospital information system (Univerzita Karlova, ČVUT)
- **Reason:** Caries lesion detection, inter-annotator variability, ML evaluation
- **Imaging Modality:** Bitewing radiographs
- **Equipment:** N/A
- **License:** Open (Mendeley)
- **Annotators:** 8 dentists (5 experienced, 3 less)
- **Annotation Type:** Rectangular bounding boxes (COCO JSON)
- **Files Formats:** PNG images, COCO JSON annotations
- **Images and Resolutions:** 100 images, 1068x847 px (rescaled/padded)
- **Example:** dental_rtg_test.zip (75.4 MB)
- **Notes:** Used in Tichý et al. (Clinical Oral Investigations)
  - Punch biopsy specimens fixed in 4% buffered formalin, dehydrated in alcohol series, cleared in xylene
  - 100x images suitable for architectural/tissue-level analysis
  - 400x images suitable for cellular-level textural feature analysis
  - First publicly available dataset of normal oral epithelium and OSCC histopathological images

### COLLECT: Counterfactual Oral Lesion Library for Explainable Concept Testing

- **Database:** Borealis
- **Dataset URL:** [COLLECT: Counterfactual Oral Lesion Library for Explainable Concept Testing](https://doi.org/10.5683/SP3/KXYCNY)
- **Version:** 1.1
- **Year:** 2026
- **Country:** Canada
- **DOI:** 10.5683/SP3/KXYCNY
- **Authors:** Tavakoli Tafti, Kioumars; D'Souza, Zaneta; Ajam, Amena; Chauvin, Peter; Magalhaes, Marcos; Fuoco, Jessie; Sperandio, Felipe Fornias; Al-Shehri, Mohammed; Tichy, Antonin; Tamimi, Faleh; Ducret, Maxime; Schwendicke, Falk; Madathil, Sreenath
- **Source of Data Acquisition:** Clinical intra-oral images collected during routine dental examinations by certified oral pathologists
- **Reason for Image Acquisition:** AI model robustness, interpretability, explainable concept testing, and diagnostic reliability in oral lesion classification
- **Imaging Modality:** Intraoral clinical photography
- **Equipment Detail:** Digital cameras under standard clinic lighting
- **License Type:** Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0)
- **Annotators:** Certified oral pathologists and oral health experts
- **Annotation Type:** Expert-validated lesion categories with structured counterfactual modifications of lesion size, color, and opacity
- **Files Formats:** Image files
- **Images and Resolutions:**
  - 40 high-quality baseline clinical images
  - 10 baseline images for each lesion category
  - Five versions generated per baseline image: one original image and four counterfactual versions
  - 600 images total
  - Image resolution not specified
- **Lesion Categories:**
  - Aphthous Ulcer
  - Geographic Tongue (GT)
  - Hairy Tongue (HT)
  - Oral Squamous Cell Carcinoma (OSCC)
- **Ethical Approval:** McGill University IRB #[A07-M40-21B, 24-11-096]
- **Additional Notes:**
  - Each baseline image was verified by histopathology or expert assessment.
  - **Size modifications:** Aphthous ulcer lesion area was progressively increased in four steps, with each stage adding 25% of the original lesion size. Geographic Tongue, Hairy Tongue, and OSCC lesions were progressively reduced across four steps, with each step decreasing lesion size by 10%.
  - **Color modifications:** Aphthous ulcers and Hairy Tongue lesions had red saturation increased in 25% increments to approximate the appearance of OSCC and Geographic Tongue, respectively. OSCC lesions had whiteness progressively increased to mimic Aphthous Ulcer coloration. Geographic Tongue lesions received a dark brown tint to resemble Hairy Tongue.
  - **Opacity modifications:** Lesions were progressively faded by decreasing opacity by 25% per stage until the lesion completely disappeared and was replaced with healthy-appearing mucosa.

### AKUDENTAL Teeth Instance Segmentation Dataset

- **Database:** GitHub
- **Dataset URL:** [AKUDENTAL](https://github.com/melihoz/AKUDENTAL)
- **Year:** 2026
- **Country:** Türkiye
- **DOI:** 10.1186/s12903-025-07645-0
- **Source of Data Acquisition:** Akdeniz University Dental Hospital
- **Reason for Image Acquisition:** Development and evaluation of AI methods for tooth segmentation, object detection, tooth identification, and cross-dataset benchmarking
- **Imaging Modality:** Panoramic radiographs
- **Equipment Detail:** Two panoramic X-ray devices; specific device models not reported
- **License Type:** Publicly available for non-commercial academic research
- **Annotators:** Expert annotator
- **Annotation Type:** Instance-level polygon-based segmentation
- **Annotation Software:** Labelme
- **Files Formats:** Image files and annotation files
- **Images and Resolutions:**
  - 333 panoramic radiographs
  - Image dimensions range from 2494 × 1435 to 2871 × 1536 pixels
  - Average resolution approximately 2908 × 1445 pixels
  - 190 female and 143 male adult subjects
- **Annotated Classes:**
  - 32 permanent tooth classes based on FDI numbering
  - Bridge
  - Filling/Crown
  - Implant
- **Additional Notes:**
  - Initially, 700 anonymized images were collected and filtered to create the final dataset.
  - Primary and supernumerary teeth were excluded.
  - Polygon annotations were created for individual teeth and dental structures.
  - Supports multiclass segmentation, instance segmentation, and object detection.
  - Associated publication: Oz M, Sengul A, Hatipoglu M, Danisman T. *AKUDENTAL teeth instance segmentation dataset: a cross-dataset analysis*. BMC Oral Health. 2026;26:247.

### BRAR-anchored Multimodal Dataset of Panoramic Radiographs for Periodontal Bone Resorption Grading

- **Database:** Figshare
- **Dataset URL:** [BRAR-anchored multimodal dataset](https://doi.org/10.6084/m9.figshare.30155974.v3)
- **Year:** 2025
- **Country:** China
- **DOI:** 10.1038/s41597-025-06400-y
- **Dataset DOI:** 10.6084/m9.figshare.30155974.v3
- **Source of Data Acquisition:** Department of Periodontology, Shanghai Stomatological Hospital, Fudan University
- **Reason for Image Acquisition:** Periodontal bone resorption assessment, standardized severity grading, AI development, and clinical research
- **Imaging Modality:** Full-mouth panoramic radiographs with demographic and clinical metadata
- **Equipment Detail:** Not specified
- **License Type:** Publicly available via Figshare
- **Annotators:** Two trained dentists; annotations subsequently validated by a senior oral radiology expert
- **Annotation Type:** Patient-level and tooth-level clinical annotations, including bone resorption measurements and Bone Resorption Age Ratio (BRAR)
- **Files Formats:** JPG, CSV, PDF
- **Images and Resolutions:**
  - 1,104 panoramic radiographs from 1,104 patients
  - Image resolution not specified
- **Additional Information:**
  - Demographic data include age and gender.
  - Tooth-level indicators include missing teeth, implants, residual roots, and opposing pairs of functional teeth.
  - BRAR is used to classify periodontal bone resorption severity into three grades:
    - Grade 1: BRAR < 0.25
    - Grade 2: BRAR 0.25–1.0
    - Grade 3: BRAR > 1.0
  - Includes a machine-readable codebook and an annotation/assessment protocol.
- **Example of File Names:** Anonymized identifiers; specific examples not reported.

### Annotated Clinical Image Dataset for AI Classification of Malignant and Potentially Malignant Oral Lesions

- **Database:** Zenodo
- **Dataset URL:** [Annotated Clinical Image Dataset](https://zenodo.org/records/14571990)
- **Year:** 2025
- **Country:** Egypt
- **DOI:** 10.1038/s41415-025-9007-6
- **Source of Data Acquisition:** Oral Medicine Clinic, Faculty of Dentistry, Cairo University
- **Reason for Image Acquisition:** AI training, validation, and testing for classification of normal oral findings, low-risk lesions, oral potentially malignant disorders, and oral cancer
- **Imaging Modality:** Intraoral clinical photography
- **Equipment Detail:** Full-mouth clinical photographs captured with proper lighting; camera model not specified
- **License Type:** CC BY-NC-ND 4.0; restricted access upon request
- **Annotators:** Two oral medicine specialists, each with a PhD and more than 10 years of clinical experience
- **Annotation Type:** Bounding-box annotations outlining lesions and designated oral regions
- **Annotation Software:** LabelMe
- **Files Formats:** JPG, JSON
- **Images and Resolutions:**
  - 9,201 original, non-augmented intraoral images
  - 4,405 images classified as normal
  - 2,314 images classified as low risk
  - 2,482 images classified as high risk
  - Image sizes range from 40,992 to 24,216,480 total pixels
- **Additional Notes:**
  - Images include multiple anatomical sites within the oral cavity.
  - The high-risk category includes oral cancer and oral potentially malignant disorders.
  - The low-risk category includes oral lesions that do not fall within the normal or high-risk groups.
  - Blurred, poorly illuminated, and augmented images were excluded.
  - All images were anonymized.
- **Example of File Names:** Not specified.

### Dataset of Annotated Oral Cavity Images for Oral Cancer Detection

- **Database:** Zenodo
- **Dataset URL:** [Dataset of Annotated Oral Cavity Images for Oral Cancer Detection](https://zenodo.org/records/10664056)
- **Year:** 2024
- **Country:** Sri Lanka
- **DOI:** 10.1016/j.oraloncology.2024.106946
- **Source of Data Acquisition:** Dental Teaching Hospital, University of Peradeniya
- **Reason for Image Acquisition:** Development of machine learning and AI systems for diagnosis and prognosis of oral cancer and oral potentially malignant disorders
- **Imaging Modality:** Oral cavity clinical photography
- **Equipment Detail:** Mobile phone cameras
- **License Type:** Open access
- **Annotators:** Clinicians
- **Annotation Type:** Polygon-shaped annotations of oral cavity boundaries and lesion boundaries
- **Annotation Software:** Custom-made software developed by the research team
- **Files Formats:** Image files, COCO-format annotations, and patient metadata
- **Images and Resolutions:**
  - 3,000 high-quality anonymized oral cavity images
  - Images obtained from 714 patients
  - Resolution not specified
- **Categories:**
  - Healthy
  - Benign
  - Oral potentially malignant disorders (OPMD)
  - Oral cancer (OCA)
- **Additional Notes:**
  - Patient metadata include age, sex, diagnosis, and risk-factor profiles.
  - Risk-factor metadata include smoking, alcohol consumption, and betel chewing habits.
  - The dataset is provided in COCO format to facilitate machine learning and AI development.
 
### Annotated intraoral image dataset for dental caries detection
- **Database:** Zenodo / Scientific Data
- **Dataset URL:** https://zenodo.org/records/14827784
- **Year:** 2025
- **Country:** Pakistan
- **DOI:** 10.5281/zenodo.14827784 (dataset); 10.1038/s41597-025-05647-9 (paper)
- **Source of Data Acquisition:** Government schools of Mithi, Sindh; curated at Aga Khan University
- **Reason for Image Acquisition:** Publicly available annotated dataset for AI dental caries detection
- **Imaging Modality:** Intraoral photographs
- **Equipment Detail:** Samsung Galaxy A23 (Android version 14.0)
- **License Type:** Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)
- **Annotators:** Two dentists (A.K., A.N.) with >2 years experience; calibrated by specialist (N.A.); disagreements resolved by third dentist
- **Annotation Type:** Bounding boxes for visible carious teeth (labels ‘d’ primary, ‘D’ permanent)
- **Files Formats:** JPG images; annotations in LabelMe (.json), YOLO (.txt), PASCAL VOC (.xml), COCO (.json)
- **Images and Resolutions:** 6,313 images from individuals aged 10–24 years; mixed and permanent dentitions; captured with and without cheek retractors; five standardized views per patient (maxillary occlusal, mandibular occlusal, left lateral, right lateral, frontal); benchmark split 5050/631/631 (train/valid/test)
- **Example of File Names:** Not specified
- **Additional Notes:**
  - Inter-rater reliability (Cohen’s Kappa) = 0.89 on 10% of images
  - Benchmark models: YOLOv8s best (mAP = 0.841 @ 0.5 IoU)
  - Limitations stated: single mobile device; no primary dentition (<10 years); no fluorosis annotations
  - Ethical approval: ERC#2024-9433-29648 (Aga Khan University)
  - Images were collected following ethical approval and informed consent.
- **Example of File Names:** Not specified.
  - The controlled counterfactual variations simulate clinically meaningful changes and support research on explainable AI, model robustness, interpretability, and diagnostic reliability.
  - **Dataset publication date:** 2026-02-21

### MD-OPG Dataset

- **Database:** Zenodo; GitHub  
- **Dataset URL:** [Zenodo record](https://zenodo.org/records/17786082); [GitHub repository](https://github.com/IASBS-AI-LAB/MD-OPG/tree/main)  
- **Year:** 2025 dataset release; 2026 benchmark publication  
- **Country:** Iran, Zanjan  
- **DOI:** [10.5281/zenodo.17786082](https://doi.org/10.5281/zenodo.17786082)  
- **Source of Data Acquisition:** Retrospective, de-identified digital panoramic dental radiographs obtained from archival records of a private dental clinic in Zanjan, Iran. The dataset was developed through collaboration involving the Institute for Advanced Studies in Basic Sciences (IASBS) and Zanjan University of Medical Sciences (ZUMS).  
- **Reason for Image Acquisition:** Routine pediatric dental assessment, diagnosis, and treatment planning. The collection was curated for AI research on detection and segmentation of dental caries in children with mixed dentition.  
- **Imaging Modality:** Digital orthopantomogram (OPG), also called a panoramic dental radiograph.  
- **Equipment Detail:** Not specified in the article, Zenodo record, or accessible GitHub metadata.  
- **License Type:** No dataset-specific license was specified in the accessible metadata. The accompanying *Sensors* paper is distributed under a Creative Commons Attribution license; however, this publication license should not be assumed to apply to the image dataset.  
- **Annotators:** Two trained mid-level dental-radiograph annotators conducted the initial annotation. Two experienced dental specialists subsequently reviewed annotations and resolved disagreements to create consensus labels.  
- **Annotation Type:**  
  - Polygon annotations for proximal caries, represented by `P`  
  - Polygon annotations for occlusal caries, represented by `O`  
  - Rectangular annotations for the smile-zone/crown-bearing region, represented by `Z`  
  - Derived smile-zone masks for segmentation tasks  
- **Files Formats:** PNG (`.png`) radiographs and JSON (`.json`) annotation files. The data are distributed in the archive `MD_OPG.rar`.  
- **Images and Resolutions:**  
  - 170 pediatric panoramic radiographs  
  - Full radiograph resolution: 1920 × 1535 pixels  
  - Smile-zone images have variable original dimensions  
  - Smile-zone images are padded to 440 × 1000 pixels for segmentation benchmarking  
  - 716 proximal-caries annotations  
  - 179 occlusal-caries annotations  
  - Patients were 3–12 years old, with a reported mean age of 7.2 years  
  - Images were acquired between 2022 and 2024  
- **Example of File Names:**  
  - Archive: `MD_OPG.rar`  
  - Image files: individual `.png` filenames not specified in the accessible documentation  
  - Annotation files: individual `.json` filenames not specified in the accessible documentation  
- **Additional Notes:**  
  - The dataset focuses on children in the mixed-dentition stage.  
  - Inclusion required digital OPGs showing mixed dentition with adequate image quality for caries annotation.  
  - Images with poor quality, no target caries, or incomplete dentition were excluded.  
  - The canonical dataset archive is hosted on Zenodo under DOI `10.5281/zenodo.17786082`.  
  - Associated article DOI: [10.3390/s26082481](https://doi.org/10.3390/s26082481).
 
### PRAD-10K

- **Database:** GitHub
- **Dataset URL:** [PRAD-10K](https://github.com/nkicsl/PRAD)
- **Year:** 2025
- **Country:** China
- **DOI:** 10.1007/978-3-032-05169-1_46 (MICCAI 2025 published chapter); preprint at 10.48550/arXiv.2504.07760
- **Source of Data Acquisition:** Clinical periapical radiographs (PR), the imaging modality most used in endodontics and periodontics
- **Reason for Image Acquisition:** Address the scarcity of large-scale, publicly available annotated PR datasets to support deep learning research in dental auxiliary diagnosis
- **Imaging Modality:** Periapical radiographs (PR)
- **Equipment Detail:** Not specified
- **License Type:** Not specified as a standard open license. Due to copyright and commercial considerations, the dataset is only partially available to the public through an application process (5,000 of the 10,000 images available on request)
- **Annotators:** Two endodontists with over 8 years of experience, plus one computer science researcher
- **Annotation Type:**
  - Pixel-level annotations for nine distinct categories, covering anatomical structures, lesions, and artificial restorations or medical devices
  - Classification labels for periodontitis, apical periodontitis, and inadequate root canal filling
- **Files Formats:** Not specified
- **Images and Resolutions:** 10,000 clinical periapical radiograph images
- **Example of File Names:** Not specified
- **Additional Notes:**
  - Accompanied by PRNet, a benchmark deep learning segmentation network introduced in the same paper
  - An upgraded version, PRAD++, has since been accepted by IEEE Transactions on Medical Imaging
  - Contact for access: aics@nankai.edu.cn or zzh_nkcs@mail.nankai.edu.cn

### Dataset for Automating Dental Condition Detection on Panoramic Radiographs

- **Database:** Zenodo
- **Dataset URL:** [Zenodo record](https://zenodo.org/records/15487430)
- **Year:** 2025
- **Country:** Romania
- **DOI:** 10.5281/zenodo.15487430 (dataset); 10.3390/diagnostics14202336 (Mureșanu et al., 2024, primary derivation paper); 10.1016/j.mex.2025.103696 (Eftimie et al., 2025, methods paper)
- **Source of Data Acquisition:** Department of Maxillofacial Surgery and Radiology, Iuliu Hațieganu University of Medicine and Pharmacy, Cluj-Napoca, Romania. Images retrospectively collected from patients seen between April 2021 and December 2023. A second, external validation set of 180 radiographs was acquired from other medical centers in Cluj-Napoca. Patient consent was waived for the retrospective collection by the university Ethics Committee (reference 117/04.06.2024); all images were de-identified
- **Reason for Image Acquisition:** Automate detection of dental conditions on panoramic radiographs to support diagnosis and risk stratification (low/medium/high risk categories)
- **Imaging Modality:** Panoramic radiographs
- **Equipment Detail:** Vatech PCH-2500 (Vatech, Hwaseong, Republic of Korea)
- **License Type:** CC BY 4.0, together with an additional database usage agreement restricting use to non-commercial research and educational purposes and prohibiting redistribution to third parties
- **Annotators:** Three calibrated researchers, using the open-source labeling platform Makesense.ai (v1.11.0); inter-observer agreement (ICC) of 0.91
- **Annotation Type:** Bounding boxes exported in YOLO format across 14 classes: implant, prosthetic restoration, obturation, endodontic treatment, carious lesion, bone resorption, impacted tooth, apical periodontitis, root fragment, furcation lesion, apical surgery, root resorption, orthodontic device, and surgical device
- **Files Formats:** JPEG
- **Images and Resolutions:**
  - Training dataset: 1,628 panoramic images
  - External validation set: 180 panoramic radiographs from different medical centers
- **Example of File Names:** Not specified
- **Additional Notes:**
  - Inclusion limited to adult patients with permanent dentition
  - Images with large cysts, tumors, metallic artifacts, blurring, or severe technique errors were excluded
  - Class labels are grouped into low, medium, and high clinical risk tiers
  - Study conducted in accordance with the Declaration of Helsinki

### Expert Annotated Mandibular Third Molar (ExAn-MTM) Dataset

- **Database:** Mendeley
- **Dataset URL:** [ExAn-MTM Dataset](https://data.mendeley.com/datasets/t8k59p35p6/1)
- **Year:** 2025
- **Country:** Türkiye
- **DOI:** 10.1007/s11227-025-07775-w
- **Source of Data Acquisition:** Derived and re-annotated from the UESB panoramic radiograph dataset (Silva et al., 2018), itself the source of the earlier m-TM dataset (Kayadibi et al.)
- **Reason for Image Acquisition:** Support explainable AI detection of mandibular third molar (MTM) eruption status (erupted vs. impacted) to inform surgical decision-making
- **Imaging Modality:** Panoramic radiographs (PR)
- **Equipment Detail:** Not specified
- **License Type:** Not specified
- **Annotators:** One experienced oral and maxillofacial radiologist, using the MakeSense annotation tool
- **Annotation Type:** Bounding boxes in YOLO format, two classes: e-MTM (erupted mandibular third molar) and i-MTM (impacted mandibular third molar)
- **Files Formats:** Image files with YOLO-format label files, organized in train/images, train/labels, valid/images, valid/labels folders
- **Images and Resolutions:**
  - 973 expertly annotated panoramic radiographs
  - Training set: 875 images (624 e-MTM, 980 i-MTM annotations)
  - Remaining images allocated to the validation set
- **Example of File Names:** Not specified
- **Additional Notes:**
  - Developed for the E-MTMYOLO architecture, which combines YOLOv5 with EigenCAM (an explainable AI technique)
  - Must be cited alongside Kayadibi et al. (2025), J Supercomput, and the earlier mTMCNN study (Kayadibi et al., 2025, Int J Med Inform)

### A Multi-Center Dental Panoramic Radiography Image Dataset for Impacted Teeth, Periodontitis, and Dental Caries

- **Database:** GitHub
- **Dataset URL:** [qinxin99/qinxini](https://github.com/qinxin99/qinxini)
- **Year:** 2024
- **Country:** China
- **DOI:** 10.1007/s10278-024-00972-8
- **Source of Data Acquisition:** Three hospital centers: (1) Stomatological Hospital of the General Hospital of Ningxia Medical University, Yinchuan; (2) People's Hospital of Yinchuan City, Ningxia; (3) a hospital in Shenzhen, Guangdong Province. Ethical approval granted by the Medical Ethics Review Committee of the General Hospital of Ningxia Medical University (KYLL-2021066)
- **Reason for Image Acquisition:** Provide a multi-center, multi-task labeled benchmark to improve generalization of segmentation and classification models across imaging centers, addressing the single-center limitation of prior dental radiograph datasets
- **Imaging Modality:** Panoramic radiographs
- **Equipment Detail:** Instrumentarium Dental OP200D, resolution 2976×1536 px (Center 1); Veraviewepocs and ORTHOPHOS XG, resolutions 2893×1480 and 2440×1280 px (Center 2); Sirona X-ray machine, resolution 2440×1292 px (Center 3)
- **License Type:** Not specified; dataset available on request via the GitHub repository, stated for research purposes
- **Annotators:** Two dentists (one university professor with 25 years of clinical experience, one associate professor with 18 years) performed initial manual annotation using ITK-SNAP; two further associate professors (15 years of experience each) reviewed and resolved disagreements
- **Annotation Type:** Manual closed-curve contour outlining of impacted-tooth boundaries, caries-affected areas, and bone-resorption regions in periodontitis cases; images converted from DICOM to NIFTI for annotation
- **Files Formats:** DICOM converted to NIFTI
- **Images and Resolutions:**
  - Total: 6,580 panoramic radiographs across three centers
  - Center 1: 4,940 images (5,557 in the disease-labeled breakdown before final grouping)
  - Center 2: 716 images
  - Center 3: 880 images
  - Disease distribution: 2,567 impacted-teeth images, 2,736 periodontitis images, 1,277 dental-caries images
- **Example of File Names:** Not specified
- **Additional Notes:**
  - Patients under 18 years of age were excluded, along with images with excessive noise, blurring, or severe distortion
  - Periodontitis defined as at least three consecutive permanent teeth in one arch showing periodontal lesions, or loss of adjacent attachment in at least two permanent teeth beyond incisors and first molars
  - Benchmarked with UNet, TransUNet, TA-Net, CE-Net, and DS-TransUNet for segmentation; AlexNet, VGG, GoogLeNet, and ResNet (with and without CBAM) for classification
  - Data available on request via the GitHub repository; see the paper's Table 2 for a detailed per-center breakdown
 

### **COLLECT: Counterfactual Oral Lesion Library for Explainable Concept Testing**

- **Database:** Borealis (McGill University Dataverse)  
- **Dataset URL:** https://doi.org/10.5683/SP3/KXYCNY  
- **Year:** 2026  
- **Country:** Canada  
- **DOI:** 10.5683/SP3/KXYCNY (dataset); 10.1177/00220345261466240 (paper)  
- **Source of Data Acquisition:** Clinical intra-oral images collected by certified oral pathologists during routine dental examinations  
- **Reason for Image Acquisition:** AI model robustness, interpretability, explainable concept testing, and diagnostic reliability in oral lesion classification  
- **Imaging Modality:** Intraoral clinical photography  
- **Equipment Detail:** Digital cameras under standard clinic lighting  
- **License Type:** CC BY-NC-ND 4.0  
- **Annotators:** Certified oral pathologists and oral health experts  
- **Annotation Type:** Expert-validated lesion labels with structured counterfactual transformations (size, color, opacity)  
- **Files Formats:** Image files (ZIP archive); PDF metadata  
- **Images and Resolutions:**  
  - 600 images total (40 baseline images × 5 versions each: original + 4 counterfactuals)  
  - 10 baseline images per lesion category  
  - Resolution not specified  
- **Example of File Names:** Not specified (archive: `COLLECT_Counterfactuals-Images.zip`)  
- **Additional Notes:**  
  - Lesion categories: Aphthous Ulcer, Geographic Tongue (GT), Hairy Tongue (HT), Oral Squamous Cell Carcinoma (OSCC)  
  - Size modifications: Aphthous ulcers increased in 25% steps; GT/HT/OSCC reduced in 10% steps  
  - Color modifications: Progressive red saturation, whiteness, or dark brown tint to mimic clinically similar lesions  
  - Opacity modifications: Decreased by 25% per stage until lesion fully faded and replaced with healthy-appearing mucosa  
  - Ethical approval: McGill University IRB #[A07-M40-21B, 24-11-096]  
  - GitHub: https://github.com/MadathilSA/COLLECT (predictions and figure reproduction notebook)  
  - Associated publication: Tavakoli Tafti et al., *J Dent Res*, 2026
 
### **GingivitisSeg**
- **Database:** Zenodo / GitHub
- **Dataset URL:** https://github.com/zeynepozdemir/GingivitisSeg
- **Year:** 2026
- **Country:** Türkiye
- **DOI:** 10.48550/arXiv.2611.15184 (paper); dataset DOI 10.5281/zenodo.21098897
- **Source of Data Acquisition:** 432 intraoral photographs collected at Ankara University Faculty of Dentistry (Department of Periodontology, Feb 2022–Feb 2023) from patients with clinically evident gingival inflammation; supplemented with 529 images from the public Duy et al. (2024) gingivitis image captioning dataset, newly annotated for pixel-level masks
- **Reason for Image Acquisition:** Development and reproducible benchmarking of semantic segmentation models for gingival inflammation
- **Imaging Modality:** Intraoral photographs
- **Equipment Detail:** Smartphone cameras under clinical conditions (original clinical subset); details of the secondary public-source images reported in Duy et al.
- **License Type:** Publicly available; associated preprint under CC BY-NC-SA 4.0
- **Annotators:** Two dental experts (Department of Periodontology; one with >10 years experience, one postgraduate resident). Joint calibration on representative images, separate initial annotation of subsets, then joint review with consensus resolution of boundary disagreements. Intraobserver ICC = 0.80 on a 30-image re-annotation subset. Quantitative interobserver agreement not calculated (no independent dual annotation before consensus).
- **Annotation Type:** Pixel-level binary segmentation masks of gingival inflammation (redness, edema, contour change); no severity grading; clinical indices (GI, MGI, BOP) not used to define masks
- **Files Formats:** Intraoral images and corresponding segmentation masks (exported via Roboflow JSON then converted); predefined train/val/test splits
- **Images and Resolutions:**
  - 961 images total (432 clinical + 529 public-source)
  - Native resolutions: width 416–7286 px, height 218–4863 px; mean approximately 4346 × 2894
  - Mean image-wise gingivitis foreground proportion 3.51% (range ~0.12–19.83%)
  - Source-stratified splits: 672 train (69.9%), 144 validation (15.0%), 145 test (15.1%)
  - All images contain annotated gingivitis regions (positive-case segmentation benchmark only)
- **Example of File Names:** Not specified in the paper
- **Additional Notes:**
  - Designed as a focused binary pixel-level gingivitis segmentation benchmark with predefined splits for reproducible comparison
  - Severe foreground/background imbalance, low-contrast boundaries, illumination variation, and multi-source resolution heterogeneity are documented challenges
  - Ethics: clinical subset approved by Ankara University Faculty of Dentistry Clinical Research Ethics Committee (Decision No. 05/02, 27 Feb 2023); written informed consent obtained
  - Source code and documentation: https://github.com/zeynepozdemir/GingivitisSeg
  - Preprint under review (Journal of Imaging Informatics in Medicine)

 ### ToothPix: A multi-focus oral panoramic X-ray image dataset based on pixel-level annotations

- **Database:** Zenodo
- **Dataset URL:** https://zenodo.org/records/18439233
- **Year:** Dataset published on 31 January 2026, version V1; associated article published on 17 March 2026.
- **Country:** China
- **Dataset DOI:** 10.5281/zenodo.18439233
- **Publication DOI:** 10.1038/s41597-026-07021-9
- **Source of Data Acquisition:** Changsha Stomatological Hospital; clinical panoramic radiographs acquired from July 2024 to February 2025.
- **Reason for Image Acquisition:** Routine clinical dental imaging; subsequently curated for AI segmentation, detection, and computer-aided diagnosis.
- **Imaging Modality:** Panoramic radiographs.
- **Equipment Detail:** Manufacturer and model not reported in the accessible article or Zenodo description.
- **License Type:** Restricted access. Application and signed Data Use Agreement required. Reuse is governed by the agreement; a standard Creative Commons dataset licence was not identified in the accessible Zenodo description.
- **Annotators:** 20 dental imaging specialists, each with at least three years of oral radiology experience; trained and assigned non-overlapping subsets.
- **Annotation Type:** Manual LabelMe polygon annotations of individual tooth contours; corresponding RGB segmentation masks. The Zenodo record describes more than 30,186 annotations of individual teeth.
- **Files Formats:** BMP/PNG images; JSON annotations; RGB PNG masks. Original acquisition format: DICOM.
- **Images and Resolutions:**
  - 8,655 de-identified panoramic radiographs from 8,655 patients.
  - Patient ages: 4–80 years.
  - Resolution: 1890 × 841 pixels.
  - More than 30,186 individual-tooth annotations.
- **Example of File Names:**
  - `0001/0001.bmp`
  - `0001/0001.png`
  - `0001/0001.json`
- **Code:** https://github.com/JCCui/CGC
- **Additional Notes:**
  - `Data1` contains BMP images and annotations; `Data2` contains equivalent PNG images and annotations; `Mask` contains RGB PNG masks.
  - BMP and PNG versions represent the same images and must not be counted as separate patients.
  - Single-centre dataset with unequal class frequencies.
  - Independent duplicate annotation of every image was not established.
  - Ethical approval: Changsha Stomatological Hospital, reference `(069) of 2025`.
- **Associated Publication:** Cui et al. *A multi-focus oral panoramic x-ray image dataset based on pixel-level annotations*. Scientific Data. 2026. https://doi.org/10.1038/s41597-026-07021-9
- **Sources:**
  - https://zenodo.org/records/18439233
  - https://pmc.ncbi.nlm.nih.gov/articles/PMC13139533/


### Dental Odontogenic Lesion CBCT and Histopathology Integrated Dataset (DOLCHID)

- **Database:** Figshare; GitHub documentation and code.
- **Dataset URL:** https://doi.org/10.6084/m9.figshare.30156622
- **Year:** Article published on 27 March 2026. The authors’ repository cites the dataset as 2025; the initial repository release date was not independently verified.
- **Country:** China
- **Dataset DOI:** 10.6084/m9.figshare.30156622
- **Publication DOI:** 10.1038/s41597-026-07112-7
- **Source of Data Acquisition:** School & Hospital of Stomatology, Wuhan University; 262 surgically treated patients.
- **Reason for Image Acquisition:** Clinical preoperative assessment and postoperative histopathological diagnosis; subsequently curated for lesion segmentation, classification, and multimodal learning.
- **Imaging Modality:** Cone-beam computed tomography (CBCT) and haematoxylin and eosin (H&E) histopathology.
- **Equipment Detail:**
  - NewTom VG, QR Srl, Verona, Italy.
  - Reported field of view: 23 × 17 cm.
  - Reported voxel size: 0.3 mm.
  - Olympus light microscope.
- **License Type:** CC BY, as displayed in indexed Figshare dataset metadata. The exact licence version was not verified. The article’s separate CC BY-NC-ND 4.0 licence should not be substituted for the dataset licence.
- **Annotators:** Three radiologists and two pathologists, each with more than ten years of experience; assigned subsets were cross-reviewed to consensus. Histological diagnoses were reviewed by two pathologists, with a third adjudicator when necessary.
- **Annotation Type:**
  - Three-dimensional CBCT lesion segmentation masks.
  - Histopathology region-of-interest masks.
  - Case-level labels for four odontogenic lesion categories.
  - Segmentation performed using 3D Slicer.
- **Files Formats:**
  - Released CBCT volumes and segmentation masks: compressed NIfTI (`.nii.gz`).
  - Released histopathology images and masks: PNG (`.png`).
  - DICOM acquisition and intermediate NRRD exports are described in the Methods.
- **Images and Resolutions:**
  - 262 paired CBCT and histopathology cases.
  - Dentigerous cysts: 44.
  - Radicular cysts: 54.
  - Odontogenic keratocysts: 92.
  - Ameloblastomas: 72.
  - Reported CBCT voxel size: 0.3 mm.
  - Histopathology pixel dimensions are not specified in the accessible article text and were not independently measured from released files.
- **Example of File Names:**
  - `AME_1_CBCT_Image.nii.gz`
  - `AME_1_CBCT_Label.nii.gz`
  - `AME_1_HIST_Image.png`
  - `AME_1_HIST_Label.png`
- **Code and Documentation:** https://github.com/ZimoHZM/DOLCHID
- **Additional Notes:**
  - Four released folders: `CBCT_Image`, `CBCT_Label`, `HIST_Image`, and `HIST_Label`, each containing 262 files.
  - The article contains inconsistent references to intermediate formats. Released formats above follow the Data Records section and explicit filename examples.
  - Single-centre dataset with unequal class sizes.
  - Ethical approval: `2020-B22`.
- **Associated Publication:** Huang et al. *Dental Odontogenic Lesion CBCT and Histopathology Integrated Dataset for Benchmarking Deep Learning Algorithms*. Scientific Data. 2026. https://doi.org/10.1038/s41597-026-07112-7
- **Sources:**
  - https://pmc.ncbi.nlm.nih.gov/articles/PMC13187427/
  - https://springernature.figshare.com/articles/dataset/Dental_Odontogenic_Lesion_CBCT_and_Histopathology_Integrated_Dataset_for_Benchmarking_Deep_Learning_Algorithms/30156622
  - https://github.com/ZimoHZM/DOLCHID

### CODE: Comprehensive Oral Mucosa Database with Explanations

- **Database:** Figshare.
- **Dataset URL:** https://doi.org/10.6084/m9.figshare.30550889
- **Year:** 2026 publication; dataset version 5.0 reported in the paper.
- **Country:** India.
- **Publication DOI:** 10.1016/j.dib.2026.113270
- **Dataset DOI:** 10.6084/m9.figshare.30550889
- **Source of Data Acquisition:** Outpatient and community-based oral health screening conducted at KSR Institute of Dental Science and Research, Tiruchengode, coordinated by Ragas Dental College and Hospital, Chennai, under the ICMR-funded SMITA project.
- **Reason for Image Acquisition:** Oral screening and development of a normative intraoral image resource for representation learning, anomaly detection, segmentation, image quality assessment, and AI-assisted oral healthcare research.
- **Imaging Modality:** Smartphone-acquired intraoral photographs.
- **Equipment Detail:**
  - OnePlus Nord CE4 Lite 5G.
  - vivo Y33s.
  - Xiaomi 11.
  - Native camera applications with autofocus and default settings.
  - Images cropped to remove extraoral regions while preserving intraoral content.
- **License Type:** CC BY 4.0, explicitly identified for dataset version 5.0 in the paper. The article itself is published under CC BY-NC 4.0.
- **Annotators:**
  - Two calibrated oral pathologists, each with approximately three years of professional experience.
  - A subset of 100 images was independently reviewed.
  - Disagreements were resolved by consensus.
- **Annotation Type:**
  - Polygon annotations generated using VGG Image Annotator, version 3.0.13.
  - Delineation of anatomical structures, mucosal sub-sites, lesion boundaries, and clinically relevant regions of interest.
  - One participant-level JSON file containing annotations for that participant's images.
  - Linked demographic, behavioural, and clinical metadata.
- **Files Formats:**
  - JPG photographs, including annotated and unannotated versions.
  - JSON polygon annotations.
  - XLSX participant metadata.
- **Images and Resolutions:**
  - 5,632 images initially acquired from 704 participants.
  - 5,566 images retained after quality assessment.
  - 5,386 normal images.
  - 180 abnormal images: 163 variations from normal oral mucosa, 10 oral potentially malignant disorders, and seven oral squamous cell carcinomas.
  - Pixel dimensions vary with smartphone and cropping.
  - The 128 × 128 resolution used for autoencoder validation is a preprocessing size, not the native dataset resolution.
  - Annotated and unannotated copies should not be counted as independent images.
- **Example of File Names:**
  - `SMITA03453_KSR_DT.jpg` — dorsal tongue.
  - `SMITA03453_KSR_RB.jpg` — right buccal mucosa.
  - `SMITA03453_KSR_UA.jpg` — upper dental arch.
- **Additional Notes:**
  - Distinct from the Casangels Oro-dental dataset, COde.
  - Primarily a normative dataset, not a balanced disease-classification benchmark.
  - The 180 abnormal images should not all be described as pathological lesions.
  - The paper reports Cohen's kappa of 0.83; the categorical outcome used for this calculation should be clarified before interpreting it as annotation-boundary agreement.
  - Technical validation demonstrates exploratory representation learning rather than established diagnostic accuracy.
- **Associated Publication:** Parangimalai Diwakar et al. *CODE (comprehensive oral mucosa database with explanations): a smartphone-based normative intraoral image dataset for oral mucosal feature learning and ai applications*. Data in Brief. 2026;69:113270.
- **Publication URL:** https://doi.org/10.1016/j.dib.2026.113270
- **Verification Status:** Extracted from the supplied full text. Repository contents and current access conditions have not been independently checked.


### DentFilm v1.0: An Expert-Annotated Clinical Image Dataset of Complete Denture Biofilm

- **Database:** Zenodo.
- **Dataset URL:** https://doi.org/10.5281/zenodo.22813487
- **Year:** 2026 publication.
- **Country:** Brazil.
- **Publication DOI:** 10.1016/j.dib.2026.113318
- **Dataset DOI:** 10.5281/zenodo.22813487
- **Source of Data Acquisition:** School of Dentistry, Federal University of Alfenas (UNIFAL-MG), Brazil; photographs of maxillary conventional acrylic resin complete dentures from 30 participants.
- **Reason for Image Acquisition:** Development and evaluation of automated denture biofilm segmentation, quantification, and hygiene-assessment methods.
- **Imaging Modality:** Clinical photographs of complete dentures.
- **Equipment Detail:**
  - Canon EOS Rebel T7.
  - Canon EF 100 mm f/2.8 Macro lens.
  - Flash-assisted acquisition.
  - Shutter speed 1/160 s, aperture f/11, ISO 100, and autofocus.
- **License Type:** Dataset licence requires verification on Zenodo. The article is published under CC BY 4.0.
- **Annotators:** One trained examiner using ibisPaintX.
- **Annotation Type:**
  - Manual binary pixel-level segmentation of biofilm.
  - Masks drawn directly on unstained photographs while corresponding biofilm-disclosed photographs were displayed as visual references.
  - White pixels represent biofilm; black pixels represent background.
  - Images before and after disclosure were not precisely registered because of positioning differences.
- **Files Formats:**
  - JPG clinical photographs.
  - PNG segmentation masks.
  - Tabular image metadata.
  - XLSX demographic information.
  - PDF/TXT documentation.
- **Images and Resolutions:**
  - Paper reports 630 clinical photographs and 90 segmentation masks from 30 participants.
  - Reported photographic design: 30 participants × three clinical stages × seven views.
  - Ninety annotated images correspond to three selected views per participant.
  - Native photographs: 6000 × 4000 pixels, 24-bit RGB.
  - Images resized to 240 × 160 pixels for computational analysis.
  - The 90 masks are annotation files, not additional clinical photographs.
- **Acquisition Stages:**
  - Before biofilm disclosure.
  - After disclosure with 0.5% basic fuchsin.
  - After biofilm removal.
- **Photographic Views:** Frontal, right and left oblique, right and left lateral, maxillary occlusal, and intaglio surface.
- **Example of File Names:** Exact image and mask filenames are not specified in the supplied paper.
- **Additional Notes:**
  - The paper contains conflicting statements about repository composition: its dataset count includes all three acquisition stages, but the annotation section and figure caption state that disclosed photographs were not released.
  - Repository inspection is needed to establish which stages are downloadable and whether 630 is the released photograph count.
  - Do not describe all 630 photographs as having segmentation masks; only 90 masks are reported.
  - Manual annotation was performed by one examiner and represents an approximate visual reference standard.
  - Dataset diversity is limited to one centre, one imaging system, 30 participants, and maxillary complete dentures.
- **Associated Publication:** Rodrigues et al. *DentFilm v1.0: an expert-annotated clinical image dataset of complete denture biofilm*. Data in Brief. 2026;69:113318.
- **Publication URL:** https://doi.org/10.1016/j.dib.2026.113318
- **Verification Status:** Extracted from the supplied full text. Repository composition, dataset licence, and downloadable resolutions require verification.


### A Dataset of Preclinical Tooth Preparation Images

- **Database:** Mendeley Data.
- **Dataset URL:** https://doi.org/10.17632/27kp5jg4c3.3
- **Year:** 2026 publication.
- **Country:** Jordan.
- **Publication DOI:** 10.1016/j.dib.2026.112900
- **Dataset DOI:** 10.17632/27kp5jg4c3.3
- **Source of Data Acquisition:** Preclinical simulation laboratories at Jordan University of Science and Technology, Irbid. Fourth-year dental students performed full-coverage crown preparations on NISSIN artificial teeth mounted in typodont jaws.
- **Reason for Image Acquisition:** Documentation and automated assessment of preclinical tooth preparations, including educational feedback and quality-score prediction.
- **Imaging Modality:** Multi-view photographs of prepared artificial teeth.
- **Equipment Detail:**
  - Canon EOS 250D/Rebel SL3.
  - Sigma 105 mm f/2.8 DG Macro HSM OS lens.
  - Canon Macro Ring Lite MR-14EX.
  - Shutter speed 1/125 s, aperture f/5.6, ISO 100, and autofocus.
- **License Type:** Dataset licence requires repository verification. The article is published under CC BY-NC 4.0.
- **Annotators:**
  - One specialist prosthodontist provided the reference evaluations.
  - No inter-rater reliability testing was performed.
- **Annotation Type:**
  - Tooth-type labels: incisor, canine, premolar, and molar.
  - Five binary assessment criteria: axial wall reduction, occlusal reduction, retention and resistance form, margin clarity and continuity, and undercut evaluation.
  - Aggregate score from 0 to 5, calculated as the number of criteria met.
  - Derived pass/fail outcome: pass at ≥3; fail at ≤2.
  - Derived ordinal feedback: excellent, good, needs improvement, or redo required.
- **Files Formats:**
  - JPG separate-view and composite images.
  - XLSX annotation workbook.
  - ZIP image archives.
  - Python image-stitching script.
- **Images and Resolutions:**
  - 1,283 tooth preparations contributed by 533 students.
  - 37 incisors, 201 canines, 512 premolars, and 533 molars.
  - 3,849 separate-view photographs at 400 × 400 pixels.
  - 1,283 composite images at 1200 × 400 pixels.
  - Three source views per preparation: facial, lingual, and occlusal.
  - Separate views and composites are alternate representations of the same preparations, not independent samples.
- **Example of File Names:**
  - `6_C_L.jpg` — lingual view of canine sample 6.
  - `Annotation.xlsx`.
  - `Stitched Images.zip`.
  - `Separate View Images.zip`.
  - `stitching.py`.
- **Additional Notes:**
  - Educational/simulated dataset; no patient-derived clinical images or patient variables.
  - Suitable for a broad dental AI catalogue, but outside a strictly clinical patient-imaging scope.
  - Evaluations reflect qualitative photographic judgment, not instrument-based measurements of preparation geometry.
  - Tooth types and evaluation outcomes are imbalanced.
  - All views and composites from a preparation should remain in the same evaluation partition.
- **Associated Publication:** Fraiwan M, Al Fodeh R, Shamiyah D. *A dataset of preclinical tooth preparation images*. Data in Brief. 2026;66:112900.
- **Publication URL:** https://doi.org/10.1016/j.dib.2026.112900
- **Verification Status:** Extracted from the supplied full text. Repository contents and dataset licence have not been independently checked.


### AIRC-LABDEN: A Multi-Modal Dataset for Dental Plaque Diagnosis of Patients with Fixed Labial Orthodontic Appliances

- **Database:** Mendeley Data, distributed in two parts.
- **Dataset URLs:**
  - Part 1: https://doi.org/10.17632/g8yhdvgjy2.3
  - Part 2: https://doi.org/10.17632/xjs4bfgzj5.3
- **Year:** 2026 publication.
- **Country:** Vietnam.
- **Publication DOI:** 10.1016/j.dib.2026.112833
- **Dataset DOIs:** 10.17632/g8yhdvgjy2.3; 10.17632/xjs4bfgzj5.3
- **Source of Data Acquisition:** Faculty of Dentistry, VNU University of Medicine and Pharmacy, and 108 Military Central Hospital, Hanoi; 148 patients undergoing fixed labial orthodontic treatment.
- **Reason for Image Acquisition:** Development of image-based and multimodal methods for plaque localization and assessment around orthodontic brackets.
- **Imaging Modality:** Intraoral photographs linked to anonymized clinical records.
- **Equipment Detail:**
  - Canon RP mirrorless camera.
  - Canon RF 100 mm f/2.8 L Macro lens.
  - Godox MF12 macro flash.
  - Dantech KD1 diffuser kit.
- **License Type:** Dataset licence requires repository verification. The article is published under CC BY-NC 4.0.
- **Annotators:**
  - Two dentists with at least five years of clinical experience.
  - Semi-automated YOLOv8 proposals followed by manual review and expert verification.
- **Annotation Type:**
  - Bounding boxes for four regions around orthodontic brackets: gingival, incisal, mesial, and distal.
  - Plaque presence/absence labels.
  - Tooth identifiers linked to an FDI tooth-position mapping.
  - Clinical metadata covering demographics, treatment duration, Sulcus Bleeding Index, and oral hygiene habits.
- **Files Formats:**
  - TXT annotation files.
  - DOCX anonymized clinical records.
  - JSON tooth-position mapping.
  - CSV patient/image mapping and recommended splits.
  - Image file extension requires repository verification.
- **Images and Resolutions:**
  - 10,450 images reported from 148 patients.
  - Nine standard intraoral views before and after plaque disclosure.
  - Additional image-quality variations include blur, low light, and glare.
  - The paper describes brightness changes, horizontal flipping, and ±15° rotation as augmentation.
  - Processed images are reported at 5536 × 4160 pixels.
  - The number of original photographs, distinct from augmented derivatives, requires verification.
- **Example of File Names:**
  - `patientxxxx.docx`.
  - `teeth_position_mapping.json`.
  - `Data_splits.csv`.
  - Corresponding images and TXT labels share the same filename stem.
- **Additional Notes:**
  - Multimodal dataset combining photographs with patient-level clinical information.
  - Labels support region-based plaque localization; they should not be described as pixel-level segmentation masks.
  - The paper calls the annotation format “five-column” but lists plaque status, four bounding-box values, and a tooth identifier. Inspect actual TXT files before specifying the schema.
  - A CSV split file links images to patients and provides recommended train/validation/test assignments.
  - Patient-level separation and grouping of augmented derivatives should be verified before benchmarking.
- **Associated Publication:** Anh et al. *AIRC-LABDEN: A multi-modal dataset for dental plaque diagnosis of patients with fixed labial orthodontic appliances*. Data in Brief. 2026;66:112833.
- **Publication URL:** https://doi.org/10.1016/j.dib.2026.112833
- **Verification Status:** Extracted from the supplied full text. Repository contents, dataset licence, original-image count, and annotation schema require verification.

- **Verification Status:** Preliminary extraction from the supplied bibliographic record and abstract; publisher page and repository not independently
