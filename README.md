# BCI-Resources

All resources related to BCI

# EEG (Electroencephalogram)

## Datasets
| **Dataset**  | **Use / Paradigm** | **Subjects / Size** | **Channels** | **Amplifier / Device (Company & Model)** | **Montage / Layout** | **Sampling Rate** | **Notes** |
| --- | --- | --- | --- | --- | --- | --- | --- |
| **TUH EEG Corpus (TUEG)** 📄 Paper: https://arxiv.org/abs/1804.03669 📁 Dataset: https://isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml | Clinical EEG (routine) | >10,000 sessions | 19–25 | Hospital clinical systems (Natus, Nihon-Kohden, Grass etc.) | 10–20 clinical montages | Heterogeneous | Largest public clinical EEG corpus |
| **TUH Abnormal EEG (TUAB)** 📄 Paper: https://arxiv.org/abs/1811.06700 📁 Dataset: https://isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml | Normal vs abnormal | ~3,000 curated | 19–25 | Same as TUH | 10–20 | Varied | Gold-standard for classification |
| **TUH Seizure Corpus (TUSZ)** 📄 Paper: https://arxiv.org/abs/1809.05348 📁 Dataset: https://isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml | Seizure detection | >600 seizures | 19–25 | Clinical amplifiers | 10–20 | Varied | Most-used seizure benchmark |
| **TUH Artifacts (TUAR)** 📄 Paper: https://arxiv.org/abs/2001.05502 📁 Dataset: https://isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml | Artifact detection | >400 subjects | 19–25 | Clinical | 10–20 | Varied | Eye/muscle/electrode artifacts |
| **TUH Events (TUEV)** 📄 Paper: https://arxiv.org/abs/2005.00137 📁 Dataset: https://isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml | Epileptiform events | >100 subjects | 19–25 | Clinical | 10–20 | Varied | Spike/slow wave annotations |
| **CHB-MITCHB-MIT** 📁 Dataset: [https://physionet.org/content/chbmit/1.0.0/](https://physionet.org/content/chbmit/1.0.0/?utm_source=chatgpt.com) 📄 Paper: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3815230/ | Pediatric epilepsy | 22 subjects | 23 | Hospital monitoring (Natus) | 10–20 “double-banana” | 256 Hz | Most cited seizure dataset |
| **Siena Scalp EEG** 📁 Dataset: https://zenodo.org/records/7794839 📄 Paper: https://www.nature.com/articles/s41597-023-02052-2 | Adult epilepsy | 14 patients | 19 | EB Neuro Galileo / Natus Quantum LTM | 10–20 | 512 Hz | BIDS-formatted |
| **Bonn University Dataset** 📁 Dataset: http://epileptologie-bonn.de/cms/front_content.php?idcat=193&lang=3 📄 Paper: https://pubmed.ncbi.nlm.nih.gov/23122771/ | Epilepsy (controlled) | 5×100 segments | 1 | Not reported | Single electrode | 173.61 Hz | Classic benchmarking dataset |
| **Helsinki Neonatal** 📁 Dataset: https://zenodo.org/record/2547147 📄 Paper: https://academic.oup.com/brain/article/138/5/1327/360433 | Neonatal seizure | 79 neonates | ~10 | Nicolet / Natus | Neonatal montage | 256 Hz | Gold standard neonatal EEG |
| **Pediatric HFO dataset** 📁 Dataset: https://zenodo.org/record/4961307 📄 Paper: https://www.nature.com/articles/s41597-021-00885-w | High-frequency oscillations | ~30 | 16–32 | Clinical | 10–20 | ~1 kHz | HFO-annotated |
| **ADHD – TDBRAIN** 📁 Dataset: https://zenodo.org/record/4302324 📄 Paper: https://www.nature.com/articles/s41597-022-01381-w | Clinical | 169 | 26 | TMSi Refa (TMSi, Netherlands) | 10–20 | 500 Hz | Part of TDBRAIN |
| **Alzheimer’s EEG** 📁 Dataset (DementiaBank EEG): https://dementia.tu-dortmund.de/ 📄 Paper: https://www.sciencedirect.com/science/article/pii/S1746809420300445 | Cognitive decline | 200+ | 19 | Clinical | 10–20 | 250–500 Hz | Resting state |
| **Sleep-EDFx** | Sleep staging | 197 nights | 2 EEG + EOG | PSG system | Fpz-Cz, Pz-Oz | 100 Hz | Hypnogram labels |
| **Simons Sleep** | Adolescents sleep | >200 | 1–4 (headband) | Consumer headband | Forehead electrodes | 128–256 Hz | Multi-night sleep study |
| **EEGMMIDB (PhysioNet)** 📁 [https://physionet.org/content/eegmmidb/1.0.0/](https://physionet.org/content/eegmmidb/1.0.0/?utm_source=chatgpt.com) 📄 https://pubmed.ncbi.nlm.nih.gov/20403792/ | Motor execution + imagery | 109 | 64 | BCI2000 + Neuroscan SynAmps | 10–10 | 160 Hz | BCI classic benchmark |
| **BCI Competition IV-1** 📁 [https://www.bbci.de/competition/iv/](https://www.bbci.de/competition/iv/?utm_source=chatgpt.com) 📄 https://hal.science/hal-00681340/document | MI (left/right) | 7 | 64 | BrainProducts BrainAmp | 10–10 | 1,000 Hz | Standard MI benchmark |
| **BCI Comp IV-2a** 📁 [https://www.bbci.de/competition/iv/](https://www.bbci.de/competition/iv/?utm_source=chatgpt.com) 📄 https://ieeexplore.ieee.org/document/7040783 | MI (4-class) | 9 | 22 | g.tec g.HIamp | 10–20 | 250 Hz | Most-used MI benchmark |
| **BCI Comp IV-2b** 📁 [https://www.bbci.de/competition/iv/](https://www.bbci.de/competition/iv/?utm_source=chatgpt.com) 📄 https://hal.science/hal-00681340/document | MI (binary) | 9 | 3 | g.USBamp | Minimal montage | 250 Hz | Very low-channel MI |
| **High-Gamma Motor Dataset** 📁 https://gin.g-node.org/HIghGammaMotor 📄 https://www.nature.com/articles/sdata2018110 | Motor execution (gamma band) | 14 | 128 | BrainProducts / BioSemi HD | High-density cap | 1–2 kHz | Used for deep CNNs |
| **WAY-EEG-GAL** (Grasp & Lift) 📁 https://physionet.org/content/waggle/1.0.0/ 📄 https://www.nature.com/articles/sdata201626 | Movement decoding | 12 | 32 | BioSemi ActiveTwo | 10–20 | 500 Hz | Grip force + movement |
| **c-VEP Dataset**📁 https://github.com/svendaehne/c-vep-eeg-dataset 📄 https://www.frontiersin.org/articles/10.3389/fnins.2016.00150/full | Code-modulated VEP | 9 | 32 | g.HIamp / BrainAmp | Occipital-heavy | 256–1k Hz | Benchmark for c-VEP spellers |
| **SSVEP Visual Search** 📁 https://ieee-dataport.org/documents/ssvep-visual-search | SSVEP + natural images | 30 | 14 | Emotiv / gUSBamp | Occipital | 128–256 Hz | SSVEP with complex stimuli |
| **Resting-State 72ch** 📁 https://openneuro.org/datasets/ds003775 📄 https://www.nature.com/articles/s41597-021-00907-7 | Baseline EEG | 22 | 72 | BioSemi / Neuroscan | 10–10 | 500–1k Hz | Eyes-open/closed |
| **DEAP** 📁 [https://www.eecs.qmul.ac.uk/mmv/datasets/deap/](https://www.eecs.qmul.ac.uk/mmv/datasets/deap/?utm_source=chatgpt.com) 📄 [https://www.frontiersin.org/articles/10.3389/fnins.2012.00025/full](https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2012.00025/full) | Emotion recognition | 32 | 32 EEG + 12 physio | BioSemi ActiveTwo | 10–20 | 512 Hz | Gold-standard affective EEG |
| **SEED**📁 https://bcmi.sjtu.edu.cn/~seed/seed.html 📄 https://ieeexplore.ieee.org/document/6[138862](https://ieeexplore.ieee.org/document/6138862) | Emotion (video stimuli) | 15 | 62 | NeuroScan SynAmps2 | 10–10 | 200 Hz | Highly cited |
| **SEED-IV** 📁 https://bcmi.sjtu.edu.cn/~seed/seed-iv.html 📄 https://ieeexplore.ieee.org/document/8103795 | Emotion 4-class | 15 | 62 | SynAmps2 | 10–10 | 200 Hz | Four emotion classes |
| **AMIGOS** 📁 https://zenodo.org/record/2549562 📄 https://ieeexplore.ieee.org/document/7742913 | Emotion / personality | 40 | 14–20 | Wearable EEG (Shimmer/Emotiv) | Frontal-heavy | 128–256 Hz | Group vs solo stimuli |
| **MODMA** 📁 http://modma.lzu.edu.cn/data/ 📄 https://www.sciencedirect.com/science/article/pii/S0167876020301593 | Depression / mental disorder | 108 | 128 + 3 wearable | 128-channel cap + wearable | Dense cap | 250–500 Hz | Clinical labels |
| **VR-EEG P300** 📁 https://osf.io/2qh6f/ 📄 https://www.nature.com/articles/s41597-022-01254-w | P300 in VR/active Ag/AgCl electrodes/**Active wet electrodes**, Ag/AgCl | 21 | 16 | gTec / BrainAmp | 10–20 | 512 Hz | VR vs monitor comparison |
| **THINGS-EEG / AllJoined 1.6M** 
📁 https://osf.io/3jk4b/ 
📄 https://www.biorxiv.org/content/10.1101/2021.06.03.447008v1 | Visual object decoding/
Active wet Ag/AgCl electrodes/**1,000 Hz** (downsampled to 250 Hz in published data) | 20 | 32 | BrainProducts **actiCHamp**64-ch 

actiCAP | 32-wet cap | 500–1k Hz | 1.6M trials |
| **EEGCVPR40 / Object40 EEG** 📁 [https://github.com/perceivelab/eeg_visual_classification](https://github.com/perceivelab/eeg_visual_classification?utm_source=chatgpt.com) 
 [https://openaccess.thecvf.com/content/WACV2024/papers/Singh_Learning_Robust_Deep_Visual_Representations_From_EEG_Brain_Recordings_WACV_2024_paper.pdf](https://openaccess.thecvf.com/content/WACV2024/papers/Singh_Learning_Robust_Deep_Visual_Representations_From_EEG_Brain_Recordings_WACV_2024_paper.pdf?utm_source=chatgpt.com) | Visual classification (40 classes) | 6–10 | 128 | BioSemi **ActiveTwo**128-ch 

BioSemi cap | 10–5 dense | 1,000 Hz | Used in CVPR papers |
| **MindBigData-MNIST** 📁 https://mindbigdata.com/opendb/db-mnist.html 📄 https://arxiv.org/abs/2212.14746 | Visual decoding | 1 | multi (8–16) | Emotiv Epoc | Headset montage | 128 Hz | 1.2M digit trials |
| **MindBigData-ImageNet** 📁 [https://mindbigdata.com/opendb/imagenet.html](https://mindbigdata.com/opendb/imagenet.html?utm_source=chatgpt.com) 📄 https://arxiv.org/abs/2212.14746 | ImageNet decoding | 1 | multi | Emotiv Epoc | Headset | 128 Hz | ~70,000 ImageNet images |\

## Models

## Devices

# fMRI (functional Magnetic Resonance Imaging)

## Datasets

## Models

## Devices

# fNIRS (functional Near-Infrared Spectroscopy)

## Datasets

## Models

## Devices

# MEG (Magnetoencephalography)

## Datasets

## Models

## Devices

