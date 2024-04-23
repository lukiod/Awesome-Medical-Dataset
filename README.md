# Awesome-Medical-Dataset [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

🔥🔥🔥 Medical Dataset is very important for Medical Image Analysis. In this repository, we provide an up-to-date list of medical datasets.

## Table of Content

---

:book: **Contents**

- [Imaging](#Imaging)
  - [Whole Body (5)](#whole-body)
  - [Head and Neck (30)](#head-and-neck)
  - [Chest (24)](#chest)
  - [Abdomen (27)](#abdomen)
  - [Heart (6)](#heart)
  - [Bones (4)](#bones)
  - [Endoscopy (19)](#endoscopy)
  - [Retina (22)](#retina)
  - [Skin (6)](#skin)
  - [Microscopic imaging (22)](#microscopic-imaging)
- [Imaging and Text (22)](#Image-text-dataset)
- [Text (13)](#Text-dataset)

---

## Medical Image Datasets

### Whole Body

| Dataset                                                   | Description                                                         | Official Website                                                                                                    | Release Date | Challenge          |
|:----------------------------------------------------------|:--------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------|:-------------|:-------------------|
| [CT-ORG](./resources/CT-ORG.md)                           | 3D CT, 140 Cases, 6 Categories of Organ Segmentation.               | [Github](https://github.com/bbrister/ctOrganSegmentation)                                                           | 2020         | -                  |
| [AutoPET](./resources/Auto-PET.md)                        | 3D PET-CT, 1214 Cases, 1 Category of Whole Body Tumor Segmentation. | [Grand Challenge](https://autopet.grand-challenge.org/), [Grand Challenge](https://autopet-ii.grand-challenge.org/) | 2022-04      | MICCAI'2022 & 2023 | 
| [TotalSegmentator](./resources/TotalSegmentator.md)       | 3D CT, 1204 Cases, 104 Categories of Whole Body Organ Segmentation. | [Github](https://github.com/wasserth/TotalSegmentator)                                                              | 2022-07      | -                  |
| [TotalSegmentator V2](./resources/TotalSegmentator_v2.md) | 3D CT, 1228 Cases, 117 Categories of Whole Body Organ Segmentation. | [Github](https://github.com/wasserth/TotalSegmentator)                                                              | 2023         | -                  |
| [ULS](./resources/ULS.md)                                 | 3D CT, 38842 Cases, 1 Category of Whole Body Tumor Segmentation.    | [Grand Challenge](https://uls23.grand-challenge.org/)                                                               | 2023-10      | -                  |

### Head and Neck

| Dataset                                               | Description                                                                                                       | Official Website                                                                                                                               | Release Date | Challenge                      |
|:------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------|:-------------|:-------------------------------|
| [L2R-OASIS](./resources/L2R-OASIS.md)                 | 3D MRI, 416 Cases, 35 Categories of Brain Segmentation and Registration                                           | [Grand Challenge](https://learn2reg.grand-challenge.org/Datasets/)                                                                             | 2007         | -                              |
| [DDTI](./resources/DDTI.md)                           | 2D Ultrasound, 637 Cases, 1 Category of Thyroid Nodule Segmentation                                               | [Project Homepage](http://cimalab.intec.co/applications/thyroid/)                                                                              | 2015-01      | -                              |
| [Ultrasound Nerve Segmentation](./resources/UNS.md)   | 2D Ultrasound, 11143 Cases, 1 Category of Cervical Nerve Segmentation                                             | [Kaggle](https://kaggle.com/competitions/ultrasound-nerve-segmentation)                                                                        | 2016-05      | Kaggle                         |
| [BraTS-TCGA-LGG](./resources/BraTS-TCGA-LGG.md)       | 3D MRI, 65 Cases, 3 Categories of Low Grade Glioma (LGG) Segmentation                                             | [TCIA](https://www.cancerimagingarchive.net/analysis-result/brats-tcga-lgg/)                                                                   | 2017         | BRATS2015                      |
| [BraTS-TCGA-GBM](./resources/BraTS-TCGA-GBM.md)       | 3D MRI, 102 Cases, 3 Categories of Glioblastoma Multiforme (GBM) Segmentation                                     | [TCIA](https://www.cancerimagingarchive.net/analysis-result/brats-tcga-gbm/)                                                                   | 2017         | BRATS2015                      |
| [PDDCA](./resources/PDDCA.md)                         | 3D CT, 48 Cases, 9 Categories of Head and Neck Organs Segmentation                                                | [ImagEngLab](https://www.imagenglab.com/newsite/pddca/)                                                                                        | 2017-03      | -                              |
| [iSeg](./resources/iSeg.md)                           | 3D MRI, 13 Cases, 3 Categories of Brain Tissue Segmentation                                                       | [Project Homepage](https://iseg2019.web.unc.edu/)                                                                                              | 2019         | MICCAI'2017 & 2019             |
| [MSD Hippocampus](./resources/MSD_Hippocampus.md)     | 3D MRI, 394 Cases, 2 Categories of Hippocampus Segmentation                                                       | [MSD](http://medicaldecathlon.com/)                                                                                                            | 2019-02      | Medical Segmentation Decathlon |
| [WMH](./resources/WMH.md)                             | 3D MRI, 170 Cases, 1 Category of White Matter Hyperintensity Segmentation                                         | [Project Homepage](https://dataverse.nl/dataset.xhtml?persistentId=doi:10.34894/AECRSD)                                                        | 2019-11      | -                              |
| [TN-SCUI2020](./resources/TN-SCUI2020.md)             | 2D Ultrasound, 4554 Cases, 1 Category of Thyroid Nodule Segmentation                                              | [Grand Challenge](https://tn-scui2020.grand-challenge.org/Home/)                                                                               | 2020-05      | MICCAI'2020                    |
| [BraTS21](./resources/BraTS2021.md)                   | 3D MRI, 2040 Cases, 3 Categories of Glioma Segmentation                                                           | [Synapse](https://www.synapse.org/#!Synapse:syn25829067/wiki/610863)                                                                           | 2021-07      | RSNA-ASNR-MICCAI'2021          |
| [FeTA 2022](./resources/FeTA.md)                      | 3D MRI, 280 Cases, 7 Categories of Infant Brain Tissue Segmentation                                               | [Grand Challenge](https://feta.grand-challenge.org/)                                                                                           | 2021         | MICCAI'2021 & 2022             |
| [ATLAS v2.0 (ISLES 2022)](./resources/ATLASv2.0.md)   | 3D MRI, 1271 Cases, 1 Category of Lesions After Stroke Segmentation                                               | [Grand Challenge](https://atlas.grand-challenge.org/)                                                                                          | 2021-12      | MICCAI'2022                    |
| [cSeg 2022](./resources/cSeg2022.md)                  | 3D MRI, 13 Cases, 3 Categories of Brain Tissue Segmentation                                                       | [Project Homepage](https://tarheels.live/cseg2022/)                                                                                            | 2022-04      | MICCAI'2022                    |
| [HECKTOR](./resources/HECKTOR_2022.md)                | 3D PET-CT, 882 Cases, 2 Categories of Tumor and Lymph Node                                                        | [Grand Challenge](https://hecktor.grand-challenge.org/)                                                                                        | 2022-06      | MICCAI'2022                    |
| [INSTANCE 2022](./resources/INSTANCE_2022.md)         | 3D CT, 200 Cases, 1 Category of Intracranial Hemorrhage Segmentation                                              | [Grand Challenge](https://instance.grand-challenge.org/)                                                                                       | 2022-04      | MICCAI'2022                    |
| [ISLES22](./resources/ISLES22.md)                     | 3D MRI, 400 Cases, 1 Category of Ischemic Stroke Lesion Segmentation                                              | [Grand Challenge](https://isles22.grand-challenge.org/)                                                                                        | 2022-05      | MICCAI'2022                    |
| [Teeth3DS](./resources/Teeth3DS.md)                   | 3D IOS, 1800 Cases, 32 Categories of Teeth Segmentation                                                           | [Github](https://github.com/DCBIA-OrthoLab/3DTeethSeg22_challenge)                                                                             | 2022-10      | MICCAI'2022                    |
| [TN3K](./resources/TN3K.md)                           | 2D Ultrasound, 3494 Cases, 1 Category of Thyroid Nodule Segmentation                                              | [Github](https://github.com/haifangong/TRFE-Net-for-thyroid-nodule-segmentation)                                                               | 2021-05      | ISBI'2021                      |
| [TG3K](./resources/TG3K.md)                           | 2D Ultrasound, 3585 Cases, 1 Category of Thyroid Nodule Segmentation                                              | [Github](https://github.com/haifangong/TRFE-Net-for-thyroid-nodule-segmentation)                                                               | 2022-12      | ISBI'2021                      |
| [HaN-Seg](./resources/HaN-Seg.md)                     | 3D CT & MRI, 42 Cases, 30 Categories of Head and Neck Organs-at-Risk Segmentation                                 | [Grand Challenge](https://han-seg2023.grand-challenge.org/)                                                                                    | 2023-01      | -                              |
| [SMILE-UHURA 2023](./resources/SMILE-UHURA%202023.md) | 3D 7T High Resoulution MRI, 14 Cases, 1 Category of Cerebral Artery Segmentation                                  | [Synapse](https://www.synapse.org/#!Synapse:syn47164761/wiki/620033)                                                                           | 2023-03      | ISBI'2023                      |
| [ToothFairy](./resources/ToothFairy.md)               | 3D CBCT, 443 Cases, 1 Category of Inferior Alveolar Nerve Segmentation                                            | [Grand Challenge](https://toothfairy.grand-challenge.org/toothfairy/)                                                                          | 2023-03      | MICCAI'2023                    |
| [SegRap 2023](./resources/SegRap2023.md)              | 3D CT, 200 Cases, 47 Categories of Head and Neck Organs-at-Risk Segmentation                                      | [Grand Challenge](https://segrap2023.grand-challenge.org/)                                                                                     | 2023-04      | MICCAI'2023                    |
| [CAS2023](./resources/CAS2023.md)                     | 3D MRI, 100 Cases, 1 Category of Cerebral Artery Segmentation                                                     | [CodaLab](https://codalab.lisn.upsaclay.fr/competitions/9804)                                                                                  | 2023-04      | MICCAI'2023                    |
| [CrossMoDA 2023](./resources/CrossMoDA2023.md)        | 3D MRI, 983 Cases, 3 Categories of Vestibular Schwannoma (VS) and Cochlea Segmentation                            | [Project Homepage](https://crossmoda-challenge.ml/)                                                                                            | 2023-04      | MICCAI'2023                    |
| [BraTS2023-SSA](./resources/BraTS2023-SSA.md)         | 3D MRI, 105 Cases, 3 Categories of Glioma Segmentation in Africa                                                  | [Synapse](https://www.synapse.org/#!Synapse:syn51156910/wiki/622556)                                                                           | 2023-05      | ASNR-MICCAI'BRATS2023          |
| [BraTS2023-MEN](./resources/BraTS2023-MEN.md)         | 3D MRI, 1650 Cases, 3 Categories of Meningioma Segmentation                                                       | [Synapse](https://www.synapse.org/#!Synapse:syn51156910/wiki/622353)                                                                           | 2023-05      | ASNR-MICCAI'BRATS2023          |
| [BraTS2023-PED](./resources/BraTS2023-PED.md)         | 3D MRI, 228 Cases, 3 Categories of Pediatrics Glioma Segmentation                                                 | [Synapse](https://www.synapse.org/#!Synapse:syn51156910/wiki/622461)                                                                           | 2023-05      | ASNR-MICCAI'BRATS2023          |
| [BraTS2023-MET](./resources/BraTS2023-MET.md)         | 3D MRI, 328 Cases, 3 Categories of Brain Metastasis Segmentation                                                  | [Synapse](https://www.synapse.org/#!Synapse:syn51156910/wiki/622553)                                                                           | 2023-06      | ASNR-MICCAI'BRATS2023          |

### Chest


| Dataset                                                                       | Description                                                                                     | Official Website                                                                                                       | Release Date | Challenge                      |
|:------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------|:-------------|:-------------------------------|
| [LUNA16](./resources/LUNA16.md)                                               | 3D CT, 888 Cases, 1 Category of Lung Nodule Detection                                           | [Grand Challenge](https://luna16.grand-challenge.org/Home/)                                                            | 2016-03      | LUNA16                         |
| [Breast Ultrasound Dataset B](./resources/Breast_Ultrasound_DatasetB.md)      | 2D Ultrasound, 163 Cases, 1 Category of Breast Lesions Detection                                | [Project Homepage](http://www2.docm.mmu.ac.uk/STAFF/M.Yap/dataset.php)                                                 | 2018-06      | -                              |
| [FUMPE](./resources/FUMPE.md)                                                 | 3D CT, 35 Cases, 1 Category of Pulmonary Embolism (PE) Segmentation                             | [Figshare](https://figshare.com/collections/FUMPE/4107803/1)                                                           | 2018-09      | -                              |
| [SegTHOR](./resources/SegTHOR.md)                                             | 3D CT, 60 Cases, 4 Categories of Thoracic Organs at Risk Segmentation                           | [CodaLab](https://competitions.codalab.org/competitions/21145)                                                         | 2019-01      | ISBI'2019                      |
| [MSD Lung Tumours](./resources/MSD_Lung_Tumours.md)                           | 3D CT, 96 Cases, 1 Category of Lung Tumor Segmentation                                          | [MSD](http://medicaldecathlon.com/)                                                                                    | 2019-02      | Medical Segmentation Decathlon |
| [LNDb](./resources/LNDb.md)                                                   | 3D CT, 294 Cases, 1 Category of Lung Nodule Segmentation                                        | [Grand Challenge](https://lndb.grand-challenge.org/)                                                                   | 2019-11      | ICIAR'2020                     |
| [BUSI](./resources/BUSI.md)                                                   | 3D Ultrasound, 780 Cases, 3 Categories of Breast Tumor Segmentation                             | [Project Homepage](https://scholar.cu.edu.eg/?q=afahmy/pages/dataset)                                                  | 2019-11      | -                              |
| [PleThora](./resources/PleThora.md)                                           | 3D CT, 402 Cases, 2 Categories of Pleural Effusion and Thoracic Segmentation                    | [TCIA](https://www.cancerimagingarchive.net/analysis-result/plethora/)                                                 | 2020-04      | -                              |
| [COVID_CT_COVID-CT](./resources/COVID_CT_COVID-CT.md)                         | 2D CT, 746 Cases, 2 Categories of Pneumonia Classification                                      | [Tianchi](https://tianchi.aliyun.com/dataset/106604)                                                                   | 2020-06      | -                              |
| [COVIDGR](./resources/COVIDGR.md)                                             | 2D X-Ray, 852 Cases, 2 Categories Pneumonia Classification                                      | [Github](https://github.com/ari-dasci/covidgr)                                                                         | 2020-12      | -                              |
| [COVID-19 CHEST X-RAY DATABASE](./resources/COVID-19_CHEST_X-RAY_DATABASE.md) | 2D X-ray, 3886 Cases, 3 Categories of Pneumonia Classification                                  | [Project Homepage](https://www.heywhale.com/mw/dataset/6027caee891f960015c863d7/content)                               | 2021-01      | -                              |
| [Chest CT-Scan images](./resources/ChestCT-Scan_images.md)                    | 2D CT, 1000 Cases, 4 Categories of Lung Tumor Classification                                    | [Tianchi](https://tianchi.aliyun.com/dataset/93929)                                                                    | 2021-03      | -                              |
| [COVID-19-CT SCAN IMAGES](./resources/COVID-19-CT_SCAN_IMAGES.md)             | 2D CT, 1400 Cases, 2 Categories of Pneumonia Classification                                     | [Tianchi](https://tianchi.aliyun.com/dataset/93666)                                                                    | 2021-03      | -                              |
| [Chest X-ray PD Dataset](./resources/ChestX-rayPDDataset.md)                  | 2D X-Ray, 4575 Cases, 3 Categories of Pneumonia Classification                                  | [Project Homepage](https://data.mendeley.com/datasets/jctsfj2sfn/1)                                                    | 2021-04      | -                              |
| [Shenzhen chest X-ray set](./resources/Shenzhen_chest_X-ray.md)               | 2D X-Ray, 662 cases, 2 Categories of Tuberculosis Classification                                | [NIH](https://lhncbc.nlm.nih.gov/LHC-downloads/downloads.html#tuberculosis-image-data-sets)                            | 2021-06      | -                              |
| [Chest X-Ray Imaging_(Pneumonia)](./resources/ChestX-RayImaging_Pneumonia.md) | 2D X-ray, 5856 Cases, 2 Categories of Pneumonia Classification                                  | [Project Homepage](https://www.heywhale.com/mw/dataset/62c2ac49913a54a66037f872/content)                               | 2022-07      | -                              |
| [Parse 2022](./resources/Parse.md)                                            | 3D CT, 200 Cases, 1 Category of Pulmonary Artery Segmentation                                   | [Grand Challenge](https://parse2022.grand-challenge.org/)                                                              | 2022-04      | MICCAI'2022                    |
| [ATM22](./resources/ATM22.md)                                                 | 3D CT, 500 Cases, 1 Category of Lung Airway Segmentation                                        | [Grand Challenge](https://atm22.grand-challenge.org/)                                                                  | 2022-05      | MICCAI'2022                    |
| [MVSeg-3DTEE 2023](./resources/MVSeg-3DTEE.md)                                | 3D Ultrasound, 175 Cases, 2 Categories of Mitral Valve Segmentation                             | [Synapse](https://www.synapse.org/#!Synapse:syn51186045/wiki/621356)                                                   | 2023         | MICCAI'2023                    |
| [TDSC-ABUS2023](./resources/TDSC-ABUS2023.md)                                 | 3D Ultrasound, 200 Cases, 1 Category of Breast Tumor Detection, Segmentation and Classification | [Grand Challenge](https://tdsc-abus2023.grand-challenge.org/TDSC-ABUS2023/)                                            | 2023-03      | MICCAI'2023                    |
| [AIIB23](./resources/AIIB23.md)                                               | 3D CT, 312 Cases, 1 Category of Lung Airway Segmentation                                        | [CodaLab](https://codalab.lisn.upsaclay.fr/competitions/13238)                                                         | 2023-05      | MICCAI'2023                    |
| [SEG.A.](./resources/SEG.A.md)                                                | 3D CTA, 56 Cases, 1 Category of Aorta Segmentation                                              | [Grand Challenge](https://multicenteraorta.grand-challenge.org/)                                                       | 2023-05      | MICCAI'2023                    |
| [LNQ 2023](./resources/LNQ2023.md)                                            | 3D CT, 513 Cases, 1 Category of Lymph Node Quantification                                       | [Grand Challenge](https://lnq2023.grand-challenge.org/lnq2023/)                                                        | 2023-05      | MICCAI'2023                    |
| [SARS-COV-2 Ct-Scan](./resources/SARS-COV-2.md)                               | 2D CT, 2482 Cases, 2 Categories of Pneumonia Classification                                     | [Kaggle](https://www.kaggle.com/datasets/plameneduardo/sarscov2-ctscan-dataset)                                        | 2020-05      | -                              |


### Abdomen

| Dataset                                                                                         | Description                                                                | Official Website                                                                                                              | Release Date | Challenge                      |
|:------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------|:-------------|:-------------------------------|
| [3D-IRCADB](./resources/3D-IRCADB.md)                                                           | 3D CT, 22 Cases, 40 Categories of Abdominal Organ and Tumor Segmentation   | [Project Homepage](https://www.ircad.fr/research/data-sets/liver-segmentation-3d-ircadb-01/)                                  | 2010         | -                              |
| [BTCV](./resources/BTCV.md)                                                                     | 3D CT, 50 Cases, 13 Categories of Abdominal Organ Segmentation             | [Synapse](https://www.synapse.org/#!Synapse:syn3193805/wiki/)                                                                 | 2015-04      | MICCAI'2015                    |
| [BTCV Cervix](./resources/BTCV_Cervix.md)                                                       | 3D CT, 50 Cases, 4 Categories of Abdominal Organ Segmentation              | [Synapse](https://www.synapse.org/#!Synapse:syn3193805/wiki/217790)                                                           | 2015-04      | MICCAI'2015                    |
| [LiTS](./resources/LiTS.md)                                                                     | 3D CT, 201 Cases, 2 Categories of Liver and Tumor Segmentation             | [CodaLab](https://competitions.codalab.org/competitions/17094)                                                                | 2017-06      | ISBI'2017, MICCAI'2017 & 2018  |
| [MSD Pancreas Tumour](./resources/MSD_Pancreas_Tumour.md)                                       | 3D CT, 420 Cases, 2 Categories of Pancreas and Tumour Segmentation         | [MSD](http://medicaldecathlon.com/)                                                                                           | 2019-02      | Medical Segmentation Decathlon |
| [MSD Hepatic Vessel](./resources/MSD_Hepatic_Vessel.md)                                         | 3D CT, 443 Cases, 2 Categories Liver Blood vessels and Tumor Segmentation  | [MSD](http://medicaldecathlon.com/)                                                                                           | 2019-02      | Medical Segmentation Decathlon |
| [MSD Spleen](./resources/MSD_Spleen.md)                                                         | 3D CT, 61 Cases, 1 Category of Spleen Segmentation                         | [MSD](http://medicaldecathlon.com/)                                                                                           | 2019-02      | Medical Segmentation Decathlon |
| [MSD Colon Cancer](./resources/MSD_Colon_Cancer.md)                                             | 3D CT, 190 Cases, 1 Category of Colon Tumor Segmentation                   | [MSD](http://medicaldecathlon.com/)                                                                                           | 2019-02      | Medical Segmentation Decathlon |
| [MSD Prostate](./resources/MSD_Prostate.md)                                                     | 3D MR, 48 Cases, 2 Categories of Prostate Segmentation                     | [MSD](http://medicaldecathlon.com/)                                                                                           | 2019-02      | Medical Segmentation Decathlon |
| [KiTS19](./resources/KiTS19.md)                                                                 | 3D CT, 300 Cases, 2 Categories of Kidney and Tumor Segmentation            | [Grand Challenge](https://kits19.grand-challenge.org/)                                                                        | 2019-03      | MICCAI'2019                    |
| [CHAOS](./resources/CHAOS.md)                                                                   | 3D CT&MRI, 40 Cases, 4 Categories of Abdominal Organ Segmentation          | [Grand Challenge](https://chaos.grand-challenge.org/Combined_Healthy_Abdominal_Organ_Segmentation/)                           | 2019-04      | ISBI'2019                      |
| [KiTS21](./resources/KiTS21.md)                                                                 | 3D CT, 400 Cases, 3 Categories of Kidney and Tumor Segmentation            | [Project Homepage](https://kits-challenge.org/kits21/)                                                                        | 2021-03      | MICCAI'2021                    |
| [FLARE 2021](./resources/FLARE2021.md)                                                          | 3D CT, 511 Cases, 4 Categories of Abdominal Organ Segmentation             | [Grand Challenge](https://flare.grand-challenge.org/)                                                                         | 2021-05      | MICCAI'2021                    |
| [AbdomenCT-1K](./resources/AbdomenCT-1K.md)                                                     | 3D CT, 1112 Cases, 4 Categories of Abdominal Organ Segmentation            | [Github](https://github.com/JunMa11/AbdomenCT-1K)                                                                             | 2021-07      | -                              |
| [QUBIQ2021](./resources/QUBIQ2021.md)                                                           | 3D CT, 90 Cases, 2 Categories of Pancreas and Lesions Segmentation         | [Grand Challenge](https://qubiq21.grand-challenge.org/QUBIQ2021/)                                                             | 2021-08      | MICCAI'2021                    |
| [WORD](./resources/WORD.md)                                                                     | 3D CT, 150 Cases, 16 Categories of Abdominal Organ Segmentation            | [Github](https://github.com/HiLab-git/WORD)                                                                                   | 2021-11      | -                              |
| [FLARE 2023](./resources/FLARE2023.md)                                                          | 3D CT, 2300 Cases, 13 Categories of Abdominal Organ Segmentation           | [Grand Challenge](https://flare22.grand-challenge.org/)                                                                       | 2022-03      | MICCAI'2022                    |
| [KiPA22](./resources/KiPA22.md)                                                                 | 3D CTA, 130 Cases, 4 Categories of Vessel and Tumor Segmentation           | [Grand Challenge](https://kipa22.grand-challenge.org/)                                                                        | 2022-04      | MICCAI'2022                    |
| [AMOS 2022](./resources/AMOS.md)                                                                | 3D CT&MRI, 600 Cases, 15 Categories of Abdominal Organ Segmentation        | [Grand Challenge](https://amos22.grand-challenge.org/)                                                                        | 2022-05      | MICCAI'2022                    |
| [PI-CAI](./resources/PI-CAI.md)                                                                 | 3D MR, 1500 Cases, 1 Category of Prostate Tumor Segmentation               | [Grand Challenge](https://pi-cai.grand-challenge.org/)                                                                        | 2022-05      | -                              |
| [LLD-MMRI2023](./resources/LLD-MMRI2023.md)                                                     | 3D MRI, 394 Cases, Liver Lesion Detection                                  | [Github](https://github.com/LMMMEng/LLD-MMRI2023/tree/main?tab=readme-ov-file)                                                | 2023-02      | MICCAI'2023                    |
| [SPPIN](./resources/SPPIN.md)                                                                   | 3D MRI, 111 Cases, 1 Category of Pediatric Neuroblastoma Segmentation      | [Grand Challenge](https://sppin.grand-challenge.org/sppin/)                                                                   | 2023-04      | MICCAI'2023                    |
| [FLARE 2023](./resources/FLARE2023.md)                                                          | 3D CT, 4500 Cases, 14 Categories of Abdominal Organ and Tumor Segmentation | [CodaLab](https://codalab.lisn.upsaclay.fr/competitions/12239)                                                                | 2023-04      | MICCAI'2023                    |
| [KiTS23](./resources/KiTS23.md)                                                                 | 3D CT, 599 Cases, 3 Categories of Kidney and Tumor Segmentation            | [Project Homepage](https://kits-challenge.org/kits23/)                                                                        | 2023-04      | MICCAI'2023                    |
| [ATLAS (MICCAI2023)](./resources/ATLAS.md)                                                      | 3D CE-MRI, 90 Cases, 2 Categories of Liver and Tumor Segmentation          | [Grand Challenge](https://atlas-challenge.u-bourgogne.fr/)                                                                    | 2023-04      | MICCAI'2023                    |
| [MOOD2023](./resources/MOOD2023.md)                                                             | 3D CT&MR, 1300 Cases, Out-of-Distribution Detection                        | [Project Homepage](http://medicalood.dkfz.de/web/)                                                                            | 2023-04      | MICCAI'2023                    |
| [UW-Madison GI Tract Image Segmentation](./resources/UW-Madison_GI_Tract_Image_Segmentation.md) | 2D MRI, 38496 Cases, 3 Categories of Gastrointestinal Tract Segmentation   | [Kaggle](https://www.kaggle.com/competitions/uw-madison-gi-tract-image-segmentation/overview)                                 | 2022-04      | -                              |

### Heart

| Dataset                                       | Description                                                                               | Official Website                                                        | Release Date | Challenge                      |
|:----------------------------------------------|:------------------------------------------------------------------------------------------|:------------------------------------------------------------------------|:-------------|:-------------------------------|
| [ACDC](./resources/ACDC.md)                   | 3D MRI, 150 Cases, 3 Categories of Left and Right Ventricles and Myocardial Segmentation  | [Project Homepage](https://www.creatis.insa-lyon.fr/Challenge/acdc/)    | 2017         | MICCAI'2017                    |
| [MM-WHS](./resources/MM-WHS.md)               | 3D CT/MRI, 120 Cases, 7 Categories of Heart Substructure Segmentation                     | [Github](https://zmiclab.github.io/zxh/0/mmwhs/)                        | 2017         | MICCAI'2017                    |
| [MyoPS 2020](./resources/MyoPS_2020.md)       | 3D MRI, 45 Cases, 5 Categories of Myocardial Pathology Segmentation                       | [Github](https://zmiclab.github.io/zxh/0/myops20/)                      | 2020-04      | MICCAI'2020                    |
| [LAScarQS 2022](./resources/LAScarQS_2022.md) | 3D MRI, 194 Cases, 2 Categories of Left Atrium and Scar Segmentation                      | [Github](https://zmiclab.github.io/projects/lascarqs22/)                | 2022-04      | MICCAI'2022                    |
| [CMRxMotion](./resources/CMRxMotion.md)       | 3D MRI, 360 Cases, 3 Categories of Heart Structure Segmentation                           | [Synapse](https://www.synapse.org/#!Synapse:syn28503327/wiki/617823)    | 2022-05      | MICCAI'2022                    |
| [MSD Cardiac](./resources/MSD_Cardiac.md)     | 3D MRI, 30 Cases, 1 Category of Left Atrium Segmentation                                  | [MSD](http://medicaldecathlon.com/)                                     | 2019-02      | Medical Segmentation Decathlon |


### Bones

| Dataset                                 | Description                                                                              | Official Website                                               | Release Date | Challenge          |
|:----------------------------------------|:-----------------------------------------------------------------------------------------|:---------------------------------------------------------------|:-------------|:-------------------|
| [VerSe](./resources/VerSe.md)           | 3D CT, 374 Cases, 26 Categories of Spine Segmentation                                    | [Github](https://github.com/anjany/verse)                      | 2020-05      | MICCAI'2019 & 2020 |
| [CTPelvic1K](./resources/CTPelvic1K.md) | 3D CT, 1184 Cases, 4 Categories of Lumbar Spine, Sacrum, Left and Right Hip Segmentation | [Github](https://github.com/MIRACLE-Center/CTPelvic1K)         | 2020-12      | -                  |
| [CTSpine1K](./resources/CTSpine1K.md)   | 3D CT, 1005 Cases, 25 Categories of Spine Segmentation                                   | [Github](https://github.com/MIRACLE-Center/CTSpine1K)          | 2021-05      | -                  |
| [SPIDER](./resources/SPIDER.md)         | 3D MR, 544 Cases, 19 Categories of Spine, Intervertebral Disc, Spinal Canal Segmentation | [Grand Challenge](https://spider.grand-challenge.org/)         | 2023-06      | -                  |

### Endoscopy

| Dataset                                                                                                     | Description                                                                                       | Official Website                                                                               | Release Date | Challenge   |
|:------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------|:-------------|:------------|
| [CVC-ClinicDB](./resources/CVC-ClinicDB.md)                                                                 | 2D, Endoscopy, 612 Cases, 1 Category of Colon Polyp Segmentation                                  | [Grand Challenge](https://polyp.grand-challenge.org/CVCClinicDB/)                              | 2015-02      | MICCAI'2015 |
| [Colonoscopic](./resources/Colonoscopic.md)                                                                 | 2D Endoscopy, 152 Cases, 3 Categories of Gastrointestinal Lesions Classification                  | [Project Homepage](https://www.depeca.uah.es/colonoscopy_dataset/)                             | 2016-09      | -           |
| [The Nerthus Dataset](./resources/Nerthus.md)                                                               | 2D Endoscopy, 5525 Cases, 4 Categories of Intestinal Cleansing Levels Classification              | [Project Homepage](https://datasets.simula.no/nerthus/)                                        | 2017-06      | -           |
| [EAD 2019](./resources/EAD2019.md)                                                                          | 2D Endoscopy, 2991 Cases, 7 Categories of Esophageal, Colon, Stomach, Bladder, Liver Segmentation | [Grand Challenge](https://ead2019.grand-challenge.org/EAD2019/)                                | 2019-08      | -           |
| [Kvasir-SEG](./resources/Kvasir-SEG.md)                                                                     | 2D Endoscopy, 1160 Cases, 1 Category of Colon Polyp Segmentation                                  | [Github](https://github.com/DebeshJha/2020-MediaEval-Medico-polyp-segmentation/tree/master)    | 2019-11      | -           |
| [SARAS-ESAD](./resources/SARAS-ESAD.md)                                                                     | 2D Endoscopy, 33398 Cases, 21 Categories of Surgical Action Recognition                           | [Grand Challenge](https://saras-esad.grand-challenge.org)                                      | 2020-01      | -           |
| [SUN Colonoscopy Video](./resources/SUN_Colonoscopy_Video.md)                                               | 2D Endoscopy, 158,690 Cases, 1 Category of Polyp Segmentation                                     | [Project Homepage](http://amed8k.sundatabase.org/)                                             | 2020-07      | -           |
| [Sinus Surgery Endoscopic Image Datasets](./resources/Sinus_Surgery.md)                                     | 2D Rhinoscopy, 9003 Cases, 1 Category of Surgical Instrument Segmentation                         | [Github](https://github.com/SURA23/Sinus-Surgery-Endoscopic-Image-Datasets?tab=readme-ov-file) | 2020-08      | -           |
| [EndoSLAM](./resources/EndoSLAM.md)                                                                         | 2D Endoscopy, 64577 Cases, 3D Reconstruction                                                      | [Github](https://github.com/CapsuleEndoscope/EndoSLAM)                                         | 2020-10      | -           | 
| [m2caiseg](./resources/m2caiseg.md)                                                                         | 2D Endoscopy, 307 Cases, 19 Categories of Abdominal Organs and Surgical Equipment Segmentation    | [Kaggle](https://www.kaggle.com/datasets/salmanmaq/m2caiseg)                                   | 2020-12      | MICCAI'2016 |
| [CholecSeg8k](./resources/CholecSeg8k.md)                                                                   | 2D Endoscopy, 8080 Cases, 13 Categories of Cholecystectomy Surgery Semantic Segmentation          | [Kaggle](https://www.kaggle.com/datasets/newslab/cholecseg8k)                                  | 2020-12      | -           |
| [Kvasir-Capsule](./resources/Kvasir-Capsule.md)                                                             | 2D Endoscopy, 4741504 Cases, 14 Categories of Digestive Tract Lesion Segmentation                 | [Project Homepage](https://datasets.simula.no/kvasir-capsule/)                                 | 2021-05      | -           |
| [FetReg 2021 Task1](./resources/FetReg.md)                                                                  | 2D Fetoscope, 2718 Cases, 3 Categories of Blood vessels, Fetus, Surgical Tools Segmentation       | [Synapse](https://www.synapse.org/#!Synapse:syn25313156)                                       | 2021-07      | MICCAI'2021 |
| [LDPolypVideo](./resources/LDPolypVideo.md)                                                                 | 2D Endoscopy, 861400 Slices, 1 Category of Polyp Detection                                        | [Github](https://github.com/dashishi/LDPolypVideo-Benchmark)                                   | 2021-09      | -           |
| [EndoMapper](./resources/EndoMapper.md)                                                                     | 2D Endoscopy Video, 59 Cases, 3D Reconstruction and VSLAM                                         | [Synapse]( https://www.synapse.org/#!Synapse:syn26707219/wiki/615178)                          | 2022-04      | -           |
| [CholecT45 Dataset](./resources/CholecT45.md)                                                               | 2D Endoscopy, 90489 Cases, 128 Categories of Cholecystectomy Surgery Action Recognition           | [Github](https://github.com/CAMMA-public/cholect45)                                            | 2022-04      | -           |
| [Surgical scene segmentation](./resources/Surgical_Scene_Segmentation.md)                                   | 2D Endoscopy, 9156 Cases, 32 Categories of Surgery Scene Segmentation                             | [Project Homepage](https://sisvse.github.io/)                                                  | 2022-09      | -           |
| [LIMUC](./resources/LIMUC.md)                                                                               | 2D Endoscopy, 11276 Cases, 4 Categories of Mayo Score Classification                              | [Github](https://github.com/GorkemP/labeled-images-for-ulcerative-colitis)                     | 2022-11      | -           |
| [Endoscopic Bladder Tissue Classification Dataset](./resources/Endoscopic_Bladder_Tissue_Classification.md) | 2D Endoscopy, 1754 Cases, 4 Categories of Cystoscopy Tissue Classification                        | [Project Homepage](https://commons.datacite.org/doi.org/10.5281/zenodo.7741475)                | 2023-03      | -           |

### Retina

| Dataset                                                                   | Description                                                                              | Official Website                                                                                 | Release Date | Challenge   |
|:--------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------|:-------------|:------------|
| [STARE](./resources/STARE.md)                                             | 2D Retinal Images, 20 Cases, 1 Category of Fundus Blood Vessels Segmentation             | [Project Homepage](https://cecas.clemson.edu/~ahoover/stare/)                                    | 2000-03      | -           |
| [DRIVE](./resources/DRIVE.md)                                             | 2D Retinal Images, 40 Cases, 1 Category of Fundus Blood Vessels Segmentation             | [Grand Challenge](https://drive.grand-challenge.org/)                                            | 2004-04      | -           |
| [CHASE](./resources/CHASE.md)                                             | 2D Retinal Images, 28 Cases, 1 Category of Fundus Blood Vessels Segmentation             | [Project Homepage](https://blogs.kingston.ac.uk/retinal/chasedb1/)                               | 2011-06      | -           |
| [RITE](./resources/RITE.md)                                               | 2D Retinal Images, 40 Cases, 1 Category of Fundus Blood Vessels Segmentation             | [Project Homepage](https://medicine.uiowa.edu/eye/rite-dataset)                                  | 2013         | -           |
| [HRF](./resources/HRF.md)                                                 | 2D Retinal Images, 45 Cases, 1 Category of Fundus Blood Vessels Segmentation             | [Project Homepage](https://www5.cs.fau.de/research/data/fundus-images/)                          | 2013-12      | -           |
| [Messidor-2](./resources/Messidor-2.md)                                   | 2D Retinal Images, 1748 Cases, 2 Categories of Diabetic Retinopathy Classification       | [Project Homepage](https://www.adcis.net/en/third-party/messidor2/)                              | 2013         | -           |
| [DRISHTI-GS](./resources/DRISHTI-GS.md)                                   | 2D Retinal Images, 101 Cases, 2 Categories of Optic Cup and Optic Disc Segmentation      | [Project Homepage](https://ieeexplore.ieee.org/document/6867807)                                 | 2014         | -           |
| [Retinal image quality assessment dataset](./resources/Retinal_QA.md)     | 2D Retinal Images, 216 Cases, 3 Categories of Image Quality Evaluation                   | [Project Homepage](http://academictorrents.com/details/99811ba62918f8e73791d21be29dcc372d660305) | 2014-04      | -           |
| [Retina](./resources/Retina.md)                                           | 2D Retinal Images, 601 Cases, 4 Categories of Cataracts, Glaucoma Retinopathy            | -                                                                                                | 2016         | -           |
| [Eyepacs](./resources/Eyepacs.md)                                         | 2D Retinal Images, 35126 Cases, 5 Categories of Diabetic Retinopathy Grading             | [Project Homepage](https://www.eyepacs.com/)                                                     | 2016         | -           |
| [RETOUCH](./resources/RETOUCH.md)                                         | 3D OCT, 112 Cases, 3 Categories of Retinal Fluid Segmentation                            | [Grand Challenge](https://retouch.grand-challenge.org/Home/)                                     | 2017-04      | MICCAI'2017 |
| [LES-AV](./resources/LES-AV.md)                                           | 2D Retinal Images, 22 Cases, 1 Category of Fundus Blood Vessels Segmentation             | [Project Homepage](https://ignaciorlando.github.io/)                                             | 2018         | -           |
| [OCT 2017](./resources/OCT2017.md)                                        | 2D OCT, 35126 Cases, 4 Categories of Eye Disease Classification                          | [Github](https://github.com/aishangcengloua/OCT_Classification?tab=readme-ov-file)               | 2018         | -           |
| [IDRID](./resources/IDRID.md)                                             | 2D Retinal Images, 81 Cases, 5 Categories of Diabetic Retinopathy Segmentation           | [Grand Challenge](https://idrid.grand-challenge.org/Home/)                                       | 2018-07      | ISBI'2018   |
| [PALM19](./resources/PALM19.md)                                           | 2D Retinal Images, 1200 Cases, 1 Category of Fundus Blood Vessels Segmentation           | [Project Homepage](https://palm.grand-challenge.org/Home/)                                       | 2019         | ISBI'2019   |
| [ROSE](./resources/ROSE.md)                                               | 2D OCT, 229 Cases, 1 Category Fundus Blood Vessels Segmentation                          | [Project Homepage](https://imed.nimte.ac.cn/dataofrose.html)                                     | 2020         | -           |
| [OCTA-500](./resources/OCTA-500.md)                                       | 2D OCT , 500 Cases, 1 Category of Fundus Blood Vessel Segmentation                       | [Project Homepage](https://ieee-dataport.org/open-access/octa-500)                               | 2020-06      | -           |
| [ORVS](./resources/ORVS.md)                                               | 2D Retinal Images, 49 Cases, 1 Category of Fundus Blood Vessels Segmentation             | [Github](https://github.com/AbdullahSarhan/ICPRVessels)                                          | 2020-12      | -           |
| [Retinal OCT-C8](./resources/Retinal_OCT-C8.md)                           | 2D OCT, 24000 Cases, 8 Categories of Retinal Disease Classification                      | [Kaggle](https://www.kaggle.com/datasets/obulisainaren/retinal-oct-c8)                           | 2022-01      | -           |
| [Multi-Label Retinal Diseases](./resources/Multi-LabelRetinalDiseases.md) | 2D Retinal Images, 2451 Cases, 20 Categories of Eye Diseases Classification              | [Mendeley](https://data.mendeley.com/datasets/pc4mb3h8hz/1)                                      | 2022-07      | -           |
| [ODIR-5K](./resources/ODIR-5K.md)                                         | 2D Retinal Images, 5000 Cases, 8 Categories of Common Ophthalmic Diseases Classification | [Grand Challenge](https://odir2019.grand-challenge.org/introduction/)                            | 2023         | -           |
| [RFMiD 2.0](./resources/RFMiD.md)                                         | 2D Retinal Images, 3200 Cases, 45 Categories of Eye Disease Classification               | [Grand Challenge](https://riadd.grand-challenge.org/Home/)                                       | 2023-01      | ISBI'2021   |

### Skin

| Dataset                                                          | Description                                                                                      | Official Website                                                                         | Release Date | Challenge |
|:-----------------------------------------------------------------|:-------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------|:-------------|:----------|
| [PH²](./resources/PH2.md)                                        | 2D Dermoscopic Images, 200 Cases, 2 Categories of Melanoma Segmentation                          | [Project Homepage](https://www.fc.up.pt/addi/ph2%20database.html)                        | 2015         | -         |
| [MED-NODE](./resources/MED-NODE.md)                              | 2D Dermoscopic Images, 170 Cases, 2 Categories of Benign and Malignant Melanoma Classification   | [Project Homepage](https://www.cs.rug.nl/~imaging/databases/melanoma_naevi/)             | 2015-07      | -         |
| [ISIC 2017](./resources/ISIC2017.md)                             | 2D Dermoscopic Images, 2750 Cases, 1 Category of Melanoma Segmentation                           | [Project Homepage](https://challenge.isic-archive.com/data/#2017)                        | 2017         | -         |
| [ISIC 2020](./resources/ISIC2020.md)                             | 2D Dermoscopic Images, 33126 Cases, 2 Categories of Benign and Malignant Melanoma Classification | [Project Homepage](https://challenge2020.isic-archive.com/)                              | 2020         | -         |
| [PED-UFES-20](./resources/PED-UFES-20.md)                        | 2D Dermoscopic Images, 2298 Cases, 6 Categories of Dermatology classification                    | [Mendeley](https://data.mendeley.com/datasets/zr7vgbcyr2/1)                              | 2020-07      | -         |
| [Web-scraped Skin Image](./resources/Web-scraped_Skin_Image.md)  | 2D Dermoscopic Images, 804 Cases, 6 Categories of Dermatology Classification                     | [Kaggle](https://www.kaggle.com/datasets/arafathussain/monkeypox-skin-image-dataset-2022)| 2022-08      | -         |

### Microscopic imaging

[NeurIPS 2022 Cell Seg](./resources/NeurIPS2022CellSeg.md) (2D Microscopic imaging, 3022 Cases, 1 Category)

[Malignant Lymphoma Classification](./resources/MalignantLymphomaClassification.md) (2D Pathological sections, 374 Cases, 3 Categories)

[BioMediTech](./resources/BioMediTech.md) (2D Cell imaging, 1862 Cases, 4 Categories)

[GlaS](./resources/GlaS.md) (2D Pathological Images, 165 Cases, 1 Category)

[LC25000](./resources/LC25000.md) (2D Pathological Images, 25000 Cases, 5 Categories)

[CoNIC2022](./resources/CoNIC2022.md) (2D Pathological Images, 4981 Cases, 7 Categories of Segmentation of Nuclei within Tissues)

[MoNuSeg](./resources/MoNuSeg.md) (2D Microscopic imaging, 53 Cases, 1 Category of Nucleus Segmentation)

[Corneal Nerve Tortuosity](./resources/Corneal_Nerve_Tortuosity.md) (2D Microscopic imaging, 30 Cases, 3 Categories of Degree of Corneal Nerve Distortion)

[Corneal Nerve](./resources/Corneal_Nerve.md) (2D Microscopic imaging, 90 Cases, 2 Categories of Corneal Abnormality Classification)

[CORN](./resources/CORN.md) (2D Microscopic imaging，1698 Cases, 1 Category of Corneal Nerve Segmentation)

[HuSHeM](./resources/HuSHeM.md) (2D Microscopic imaging, 216 Cases, 4 Categories of Sperm Classification)

[Malaria Cell Images](./resources/Malaria.md) (2D Microscopic imaging, 27558 Cases, 2 Categories of Malaria Classification)

[DigestPath2019](./resources/DigestPath2019.md) (2D Pathological imaging, 250 Cases, 1 Category of Digestive System Pathology Segmentation and Detection)

[ICIAR 2018 BACH Task1](./resources/ICIAR_2018_BACH_Task1.md) (2D Histology imaging, 400 Cases, 4 Categories of Breast Cancer Classification)

[ICIAR 2018 BACH Task2](./resources/ICIAR_2018_BACH_Task2.md) (2D Histology imaging, 30 Cases, 3 Categories of Breast Cancer Segmentation)

[Complete Blood Count](./resources/CompleteBloodCount.md) (2D Blood Smear, 360 Cases, 3 Categories of Blood Cell Count)

[ANHIR](./resources/ANHIR.md) (2D Pathological imaging, 481 Cases, Pathological image lung lobes and breast tissue registration)

[SICAPv2](./resources/SICAPv2.md) Prostate Pathology Segmentation Dataset (2D Pathological imaging, 18783 Cases, 4 Categories of Prostate Cancer Grade)

[ICPR-HEp-2](./resources/ICPR-HEp-2.md) (2D Cell Fluorescence Microscopy imaging, 14K, 6 Categories of Cell Classification)

[Bone Marrow Cytomorphology](./resources/BoneMarrowCytomorphology.md) (2D Pathological imaging, 171,375 Cases, 21 Categories of Bone Marrow Cell Morphological Classification)

[PatchCamelyon](./resources/PatchCamelyon.md) (2D Pathological imaging, 327,680 Cases, 2 Categories of Breast Cancer Metastasis Classification)

[Leukemia](./resources/Leukemia.md) (2D Microscopic imaging, 1867 Cases, 2 Categories of Leukemia Cell Classification)

## Image text dataset

[VQA-RAD](./resources/VQA-RAD.md) (VQA, 3515  Cases QA Pair)

[SLAKE](./resources/SLAKE.md) (VQA, 14028  Cases QA Pair)

[PathVQA](./resources/PathVQA.md) (VQA, 32799 Cases QA Pair)

[ROCOV2](./resources/ROCOV2.md) (caption, 80080  Cases image-caption Pair)

[ImageClef-2019-VQA-Med](./resources/ImageClef-2019-VQA-Med.md) (VQA, 15292  Cases QA Pair)

[RP3D-Caption](./resources/RP3D-Caption.md) (caption, 69523 Cases image-caption Pair)

[Montgomery County CXR Set](./resources/MontgomeryCounty.md) (2D X-Ray, 138例, 2 Categories of CXR Image Abnormality Diagnosis)

[PMC-OA](./resources/PMC-OA.md) (VQA, 1.6M QA Pair)

[MMMU Health&Medicine](./resources/MMMU_Health&Medicine.md) (VQA, 1752 Cases QA Pair)

[MedICaT](./resources/MedICaT.md) (VQA, 217060 Cases QA Pair)

[CT-RATE](./resources/CT-RATE.md) chest CT and its radiology diagnostic report data set (Caption, 47149 Cases)

[Quilt-1M](./resources/Quilt-1M.md) Visual-Language Histopathology Dataset (Caption, 768826 Cases)

## Text dataset

[MedQA](./resources/MedQA.md) (QA, 61,097 Cases QA Pair)

[MedMCQA](./resources/MedMCQA.md) (QA, 193,155 Cases QA Pair)

[PubMedQA](./resources/PubMedQA.md) (QA, 1000 Cases Expert annotation QA Pair)

[HealthSearchQA](./resources/HealthSearchQA.md) (QA, 3173 Cases QA Pair)

[webMedQA](./resources/webMedQA.md) (QA, 63,284 Cases QA Pair)

[LiveQA](./resources/LiveQA.md) (QA, 634例 QA Pair)

[CMExam](./resources/CMExam.md) (QA, 68K Cases QA Pair)

[CMB](./resources/CMB.md) (QA, 270K Cases QA Pair)

[MedDialog-CN](./resources/MedDialog-CN.md) (QA, 1.1M Cases QA Pair)

[Chinese Medical Dialogue Dataset](./resources/ChineseMedicalDialogueDataset.md) (QA, 792K Cases QA Pair)

[cMedQA](./resources/cMedQA.md) v2.0 (QA, 108K Cases QA Pair)

[Huatuo-26M](./resources/Huatuo-26M.md) (QA, 26M Cases QA Pair)

[ShenNong-TCM-Dataset/EB](./resources/ShenNong-TCM.md) (QA, 113K Cases QA Pair)

[MedBench](./resources/MedBench.md) (QA, 113K Cases QA Pair)











