# BCI-Resources

All resources related to BCI Devices, Models and Devices

# EEG (Electroencephalogram)

## Datasets

| **Dataset** | **Subjects** | **Task & Stimuli** | **Classes / Categories** | **Data Format** | **Paper / Ref** | **EEG Setup** |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Visual Touch EEG**<br>(Smit et al., 2025) | 80 | **Task:** Observing touch (hand/object)<br>**Stim:** Video clips (12 types) | 12 Touch types<br>28 Objects<br>8 Materials | [📁 OpenNeuro ds005662](https://openneuro.org/datasets/ds005662)<br>(BIDS format) | Smit et al., 2025<br>*(bioRxiv)* | **64-ch** BioSemi<br>2,048 Hz |
| **MSS-EEG**<br>(Xue et al., 2025) | 32 | **Task:** Object Rec. (RSVP + Slow)<br>**Stim:** 10,000 Natural images | 20 Categories<br>(500 images each) | [📁 OpenNeuro ds005589](https://openneuro.org/datasets/ds005589)<br>(BIDS format) | Xue et al., 2025<br>*(Scientific Data)* | **122-ch** Neuroscan<br>1,000 Hz |
| **Alljoined1**<br>(Xu et al., 2024) | 8 | **Task:** Image Reconstruction (RSVP)<br>**Stim:** 10,000 Natural scenes | Diverse objects<br>(No fixed classes) | [📁 Linktree](https://linktr.ee/alljoined1)<br>(NumPy / BIDS) | Xu et al., 2024<br>*(arXiv)* | **64-ch**<br>(Setup varies) |
| **Natural-Object EEG**<br>(Anwar et al., 2025) | 32 | **Task:** Classification<br>**Stim:** Simple images (Apple, Car...) | 4 Classes:<br>Apple, Flower, Car, Face | [📁 Mendeley Data](https://data.mendeley.com/datasets/g9shp2gxhy/2)<br>(CSV, EDF) | Anwar et al., 2025<br>*(Mendeley Data)* | **14-ch** Emotiv<br>128 Hz |
| **EAV**<br>(Lee et al., 2024) | 42 | **Task:** Conversational Emotion<br>**Stim:** Video/Audio cues | 5 Emotions:<br>Neu, Ang, Hap, Sad, Calm | [📁 Zenodo](https://doi.org/10.5281/zenodo.10205702)<br>(.mat Matrices) | Lee et al., 2024<br>*(Scientific Data)* | **30-ch** BioSemi<br>500 Hz |
| **EmoEEG-MC**<br>(Xu et al., 2025) | 60 | **Task:** Cross-context Emotion<br>**Stim:** Videos + Imagery | 7 Emotions:<br>Joy, Fear, Disgust, etc. | [📁 OpenNeuro ds005540](https://openneuro.org/datasets/ds005540)<br>(BIDS format) | Xu et al., 2025<br>*(Scientific Data)* | **64-ch** g.HIamp<br>(Sampling N/A) |
| **EEG-ImageNet**<br>(Xie et al., 2024) | 16 | **Task:** Object Recognition<br>**Stim:** 4,000 ImageNet images | 40 Coarse +<br>40 Fine categories | [📁 OpenReview](https://openreview.net/forum?id=d8ed3d701e1632becf07e8260cc64a9a0fc588a8)<br>(Likely BIDS) | Xie et al., 2024<br>*(OpenReview)* | **Unspecified**<br>(High-density likely) |
| **Edzná VR EEG**<br>(Alonso-Valerdi, 2025) | 51 | **Task:** VR Museum Tour<br>**Stim:** Visual vs. Audiovisual VR | 3 Conditions:<br>Baseline, Vis, AV | [📁 OpenNeuro ds005628](https://openneuro.org/datasets/ds005628)<br>(BIDS format) | Alonso-Valerdi, 2025<br>*(Data Brief)* | **14-ch** Unicorn<br>(Sampling N/A) |

## Models/ Research Works


## Devices


# MEG (Magnetoencephalography)

## Datasets
## MEG Datasets

| **Dataset** | **Stimuli / Task** | **Subjects** | **Data Specs** | **Status & Access** |
| :--- | :--- | :--- | :--- | :--- |
| **NOD-MEG** (2025)<br>*(Zhang et al.)* | **Stim:** Images (Natural scenes)<br>**Task:** Object recognition (Animacy) | 30 Adults<br>(18 Female) | **MEG-BIDS**<br>275-ch CTF<br>1200 Hz (Raw) | [**Public** (OpenNeuro ds005810)](https://openneuro.org/datasets/ds005810)<br>*Sci. Data 2025* |
| **ForrestGump-MEG** (2022)<br>*(Liu et al.)* | **Stim:** Movie ("Forrest Gump")<br>**Task:** Natural viewing | 11 Adults<br>(Mixed) | **MEG-BIDS**<br>275-ch CTF<br>600 Hz | [**Public** (OpenNeuro ds003633)](https://openneuro.org/datasets/ds003633)<br>*Sci. Data 2022* |
| **THINGS-MEG** (2022)<br>*(Hebart et al.)* | **Stim:** Images (Object concepts)<br>**Task:** Oddball detection | 4 Adults<br>(Deep sampling) | **MEG-BIDS**<br>272-ch CTF<br>1200 Hz | [**Public** (OpenNeuro ds004212)](https://openneuro.org/datasets/ds004212)<br>*eLife 2022* |
| **BABA-MEG** (2025)<br>*(Li et al.)* | **Stim:** TV Show ("Where Are We Going?")<br>**Task:** Viewing + Comprehension | 30 Adults<br>(16 Female) | **MEG-BIDS**<br>64-ch OPM<br>1000 Hz | [**Public** (OpenNeuro ds005346)](https://openneuro.org/datasets/ds005346)<br>*Sci. Data 2025* |

## Models/ Research Works


## Devices

# fMRI (functional Magnetic Resonance Imaging)

## Datasets

| **Dataset** | **Year** | **Stimuli Type** | **Subjects** | **Access / Download** | **Citation** |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **BOLD5000** | 2019 | Static natural images<br>(≈5,000 total) | 4 | [📁 OpenNeuro ds001499](https://openneuro.org/datasets/ds001499) | Chang et al. 2019 |
| **Natural Scenes Dataset (NSD)** | 2021 | Static natural scenes<br>(Tens of thousands) | 8 | [📁 NSD Website](http://naturalscenesdataset.org) | Allen et al. 2022 |
| **NSD-Synthetic** | 2025 | Static synthetic images<br>(284 images) | 8 | [📁 NSD Website](http://naturalscenesdataset.org) | Gifford et al. 2025 |
| **Natural Object Dataset (NOD)** | 2023 | Static natural images<br>(57,120 total) | 30 | [📁 OpenNeuro ds004496](https://openneuro.org/datasets/ds004496) | Gong et al. 2023 |
| **THINGS-fMRI** | 2023 | Static object images<br>(8,740 unique) | 3 | [📁 OpenNeuro ds004192](https://openneuro.org/datasets/ds004192) | Hebart et al. 2023 |
| **iEEG–fMRI** (Short Film) | 2022 | Naturalistic film<br>(Short movie) | 51 iEEG<br>30 fMRI | [📁 OpenNeuro ds003688](https://openneuro.org/datasets/ds003688) | Berezutskaya et al. 2022 |
| **CineBrain** (EEG+fMRI) | 2025 | Dynamic TV episodes<br>(~6 hr each) | 6 | [📁 HuggingFace](https://huggingface.co/datasets/CineBrain) | Gao et al. 2025 |
| **Human Action Dataset (HAD)** | 2023 | Natural video clips<br>(21,600 action videos) | 30 | [📁 OpenNeuro ds004488](https://openneuro.org/datasets/ds004488) | Zhou et al. 2023 |
| **BOLD Moments (BMD)** | 2024 | Short video clips<br>(1,102 × 3s clips) | 10 | [📁 OpenNeuro ds005165](https://openneuro.org/datasets/ds005165) | Lahner et al. 2024 |
| **Spacetop** | 2025 | Naturalistic movie/video<br>(120 min total) | 101 | [📁 OpenNeuro ds005256](https://openneuro.org/datasets/ds005256) | Jung et al. 2025 |
| **Emo-FilM** | 2025 | Short emotional films<br>(14 clips, ~2.5 hr) | 30 | [📁 OpenNeuro ds004892](https://openneuro.org/datasets/ds004892) | Morgenroth et al. 2025 |
| **NFED** | 2024 | Facial expression videos<br>(1,320 × 3s clips) | 5 | [📁 OpenNeuro ds005047](https://openneuro.org/datasets/ds005047) | Chen et al. 2024 |
                             
## Models/ Research Works

## Devices

# fNIRS (functional Near-Infrared Spectroscopy)

## Datasets

| **Dataset** | **Year** | **Subjects** | **Task / Stimuli** | **Modality** | **Access / Link** | **Citation** |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Finger/Foot Tapping**<br>(Bak et al.) | 2019 | 30 | **Motor:** Left/right finger tap, foot tap | **fNIRS**<br>(ΔHbO, ΔHbR) | [📁 Figshare](https://figshare.com/articles/dataset/Open_Access_Dataset_of_fNIRS_Signals_During_Finger_Tapping_and_Foot_Tapping_Tasks/9783755) | Bak et al., 2019 |
| **HEFMI-ICH**<br>(Shi et al.) | 2025 | 37<br>(20 ICH, 17 Healthy) | **MI:** Left/right hand motor imagery | **Hybrid**<br>EEG + fNIRS | [📁 Figshare](https://figshare.com/)<br>*(Search via DOI)* | Shi et al., 2025 |
| **Spatial Attention**<br>(Ning et al.) | 2024 | 11 | **Audio-Visual:** "Cocktail party" attention (L/R) | **fNIRS**<br>(ΔHbO, ΔHbR) | [📁 GitHub / Drive](https://github.com/) | Ning et al., 2024 |
| **Stroop Task**<br>(Chen et al.) | 2023 | 21 | **Cognitive:** Stroop color-word conflict | **Hybrid**<br>EEG (34ch) + fNIRS (20ch) | [📁 Figshare](https://figshare.com/) | Chen et al., 2023 |
| **Tufts fNIRS2MW**<br>(Visual n-back) | 2021 | 68 | **Workload:** Visual n-back (0, 1, 2, 3) | **fNIRS**<br>(HbO, HbR) | [📁 Box (Tufts)](https://sites.tufts.edu/liin/datasets/) | Huang et al., 2021 |
| **Tufts fNIRS2MW**<br>(Audio n-back) | 2024 | 53 | **Workload:** Audio n-back (0, 1, 2, 3) | **fNIRS**<br>(HbO, HbR) | [📁 Box (Tufts)](https://sites.tufts.edu/liin/datasets/) | Wang et al., 2024 |
| **Emotion IAPS**<br>(Eser & Erdoğan) | 2025 | 20 | **Emotion:** Images (Pos, Neu, Neg) | **fNIRS**<br>(22ch Prefrontal) | [📁 Kaggle](https://www.kaggle.com/) | Eser & Erdoğan, 2025 |
| **Lower-Limb MI**<br>(Khan et al.) | 2025 | 22<br>(1 Amputee) | **MI:** Ankle/Knee flexion & extension | **fNIRS**<br>(20ch, 8S×8D) | [📁 Figshare](https://figshare.com/) | Khan et al., 2025 |
| **Upper-Limb Multi-Joint**<br>(Yi et al.) | 2025 | 18 | **MI:** 8 Tasks (Hand, Wrist, Elbow, Shoulder) | **Hybrid**<br>EEG + fNIRS | [📁 Figshare](https://figshare.com/) | Yi et al., 2025 |
## Models

## Devices




# Hybrid FNIRS + EEG

| **Study**                        | **Modalities**            | **Task / Application**                             | **Key Findings**                                                                                                                                                                                                                                   |
| -------------------------------- | ------------------------- | -------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Wang *et al.*, 2025              | EEG + fNIRS (hybrid)      | Motor Imagery (left/right hand; grasp vs rest)     | Proposed a dynamic GCN + Capsule network. Achieved ~92% MI accuracy, outperforming single-modality models by >4%. Cross-modal attention fusion improved robustness across sessions and subjects.                                                   |
| Chiarelli *et al.*, 2018         | EEG + fNIRS               | Motor Imagery (left vs right hand)                 | Early deep learning approach: a simple DNN trained on hybrid features beat EEG-only and fNIRS-only classification. Demonstrated complementary nature of EEG and hemodynamic signals for MI.                                                        |
| Khan *et al.*, 2020 (reviewed)   | EEG + fNIRS + others      | Neuroergonomics (various, e.g. driving simulators) | Surveys 33 studies showing hybrid EEG-fNIRS yields higher mental state decoding accuracy than EEG or fNIRS alone. Noted improvements in domains like vigilance and mental workload through data fusion.                                            |
| Hu *et al.*, 2025                | EEG + fNIRS               | Multi-task (public datasets: workload & MI)        | Developed CNN-Transformer hybrid model. On 3 datasets, hybrid fusion outperformed unimodal CNN or Transformer, highlighting that temporal-spatial features from both modalities are complementary.                                                 |
| Putze *et al.*, 2014 (TU Berlin) | EEG + fNIRS (+ eye-track) | Auditory vs Visual workload tasks (multiclass)     | Pioneering work on hybrid BCI for multiple mental tasks. Achieved higher classification accuracy by combining modalities (EEG detected fast responses; fNIRS differentiated tasks via PFC activation). Released an open dataset for the community. |

