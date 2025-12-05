# BCI-Resources

All resources related to BCI

# EEG (Electroencephalogram)

## Datasets

| **Dataset** | **Use / Paradigm** | **Subjects** | **Ch.** | **Device / Amp** | **Montage** | **Hz** | **Notes** |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **TUH EEG Corpus (TUEG)**<br>[📄 Paper](https://arxiv.org/abs/1804.03669)<br>[📁 Dataset](https://isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml) | Clinical EEG (routine) | >10,000 | 19–25 | Clinical (Natus, Nihon-Kohden) | 10–20 clinical | Var. | Largest public clinical EEG corpus |
| **TUH Abnormal (TUAB)**<br>[📄 Paper](https://arxiv.org/abs/1811.06700)<br>[📁 Dataset](https://isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml) | Normal vs Abnormal | ~3,000 | 19–25 | Clinical (Natus, etc.) | 10–20 | Var. | Gold-standard for classification |
| **TUH Seizure (TUSZ)**<br>[📄 Paper](https://arxiv.org/abs/1809.05348)<br>[📁 Dataset](https://isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml) | Seizure detection | >600 sz | 19–25 | Clinical amplifiers | 10–20 | Var. | Most-used seizure benchmark |
| **TUH Artifacts (TUAR)**<br>[📄 Paper](https://arxiv.org/abs/2001.05502)<br>[📁 Dataset](https://isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml) | Artifact detection | >400 | 19–25 | Clinical | 10–20 | Var. | Eye/muscle/electrode artifacts |
| **TUH Events (TUEV)**<br>[📄 Paper](https://arxiv.org/abs/2005.00137)<br>[📁 Dataset](https://isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml) | Epileptiform events | >100 | 19–25 | Clinical | 10–20 | Var. | Spike/slow wave annotations |
| **CHB-MIT**<br>[📄 Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3815230/)<br>[📁 Dataset](https://physionet.org/content/chbmit/1.0.0/) | Pediatric epilepsy | 22 | 23 | Hospital (Natus) | 10–20 | 256 | Most cited seizure dataset |
| **Siena Scalp EEG**<br>[📄 Paper](https://www.nature.com/articles/s41597-023-02052-2)<br>[📁 Dataset](https://physionet.org/content/siena-scalp-eeg/) | Adult epilepsy | 14 | 19 | EB Neuro Galileo / Natus | 10–20 | 512 | BIDS-formatted |
| **Bonn University**<br>[📄 Paper](https://pubmed.ncbi.nlm.nih.gov/23122771/)<br>[📁 Dataset](https://neurophysicsbonn.de/downloads) | Epilepsy (controlled) | 5×100 | 1 | Not reported | Single | 173 | **Updated Link** (Official) |
| **Helsinki Neonatal**<br>[📄 Paper](https://academic.oup.com/brain/article/138/5/1327/360433)<br>[📁 Dataset](https://zenodo.org/record/2547147) | Neonatal seizure | 79 | ~10 | Nicolet / Natus | Neonatal | 256 | Gold standard neonatal EEG |
| **Pediatric HFO**<br>[📄 Paper](https://www.nature.com/articles/s41597-021-00885-w)<br>[📁 Dataset](https://zenodo.org/record/4961307) | HF Oscillations | ~30 | 16–32 | Clinical | 10–20 | ~1k | HFO-annotated |
| **ADHD – TDBRAIN**<br>[📄 Paper](https://www.nature.com/articles/s41597-022-01381-w)<br>[📁 Dataset](https://zenodo.org/record/4302324) | Clinical ADHD | 169 | 26 | TMSi Refa | 10–20 | 500 | Part of TDBRAIN |
| **Alzheimer’s / Dementia**<br>[📄 Paper](https://www.mdpi.com/2306-5729/8/6/95)<br>[📁 Dataset](https://openneuro.org/datasets/ds004504) | Cognitive decline | 88 | 19 | Nihon Kohden | 10–20 | 500 | **Repl.** (Dortmund link dead) |
| **Sleep-EDFx**<br>[📁 Dataset](https://physionet.org/content/sleep-edfx/) | Sleep staging | 197 | 2 | PSG system | Fpz-Cz, Pz-Oz | 100 | Hypnogram labels |
| **Simons Sleep**<br>[📁 Dataset](https://www.synapse.org/) | Adolescents sleep | >200 | 1–4 | Consumer headband | Forehead | 128+ | Multi-night sleep study |
| **EEGMMIDB**<br>[📄 Paper](https://pubmed.ncbi.nlm.nih.gov/20403792/)<br>[📁 Dataset](https://physionet.org/content/eegmmidb/1.0.0/) | Motor Ex. + Img. | 109 | 64 | BCI2000 + Neuroscan | 10–10 | 160 | BCI classic benchmark |
| **BCI Comp IV-1**<br>[📄 Paper](https://hal.science/hal-00681340/document)<br>[📁 Dataset](https://www.bbci.de/competition/iv/) | MI (left/right) | 7 | 64 | BrainProducts BrainAmp | 10–10 | 1k | Standard MI benchmark |
| **BCI Comp IV-2a**<br>[📄 Paper](https://ieeexplore.ieee.org/document/7040783)<br>[📁 Dataset](https://www.bbci.de/competition/iv/) | MI (4-class) | 9 | 22 | g.tec g.HIamp | 10–20 | 250 | Most-used MI benchmark |
| **BCI Comp IV-2b**<br>[📄 Paper](https://hal.science/hal-00681340/document)<br>[📁 Dataset](https://www.bbci.de/competition/iv/) | MI (binary) | 9 | 3 | g.USBamp | Minimal | 250 | Very low-channel MI |
| **High-Gamma Motor**<br>[📄 Paper](https://www.nature.com/articles/sdata2018110)<br>[📁 Dataset](https://github.com/robintibor/high-gamma-dataset) | Motor (Gamma) | 14 | 128 | BP / BioSemi | High-density | 1–2k | Used for deep CNNs |
| **WAY-EEG-GAL**<br>[📄 Paper](https://www.nature.com/articles/sdata201626)<br>[📁 Dataset](https://physionet.org/content/waggle/1.0.0/) | Grasp & Lift | 12 | 32 | BioSemi ActiveTwo | 10–20 | 500 | Grip force + movement |
| **c-VEP Dataset**<br>[📄 Paper](https://www.frontiersin.org/articles/10.3389/fnins.2016.00150/full)<br>[📁 Dataset](https://github.com/svendaehne/c-vep-eeg-dataset) | Code-mod. VEP | 9 | 32 | g.HIamp / BrainAmp | Occipital | 256+ | Benchmark for c-VEP spellers |
| **SSVEP Visual Search**<br>[📁 Dataset](https://ieee-dataport.org/documents/ssvep-visual-search) | SSVEP + Images | 30 | 14 | Emotiv / gUSBamp | Occipital | 128+ | SSVEP with complex stimuli |
| **Resting-State 72ch**<br>[📄 Paper](https://www.nature.com/articles/s41597-021-00907-7)<br>[📁 Dataset](https://openneuro.org/datasets/ds003775) | Baseline EEG | 22 | 72 | BioSemi / Neuroscan | 10–10 | 500+ | Eyes-open/closed |
| **DEAP**<br>[📄 Paper](https://www.frontiersin.org/articles/10.3389/fnins.2012.00025/full)<br>[📁 Dataset](https://www.eecs.qmul.ac.uk/mmv/datasets/deap/) | Emotion Rec. | 32 | 32 | BioSemi ActiveTwo | 10–20 | 512 | Gold-standard affective EEG |
| **SEED**<br>[📄 Paper](https://ieeexplore.ieee.org/document/6138862)<br>[📁 Dataset](https://bcmi.sjtu.edu.cn/~seed/seed.html) | Emotion (Video) | 15 | 62 | NeuroScan SynAmps2 | 10–10 | 200 | Highly cited |
| **SEED-IV**<br>[📄 Paper](https://ieeexplore.ieee.org/document/8103795)<br>[📁 Dataset](https://bcmi.sjtu.edu.cn/~seed/seed-iv.html) | Emotion (4-class) | 15 | 62 | SynAmps2 | 10–10 | 200 | Four emotion classes |
| **AMIGOS**<br>[📄 Paper](https://ieeexplore.ieee.org/document/7742913)<br>[📁 Dataset](https://zenodo.org/record/2549562) | Emotion/Personality | 40 | 14 | Wearable (Shimmer) | Frontal | 128 | Group vs solo stimuli |
| **MODMA**<br>[📄 Paper](https://www.sciencedirect.com/science/article/pii/S0167876020301593)<br>[📁 Dataset](http://modma.lzu.edu.cn/data/) | Depression | 108 | 128 | Dense cap + Wearable | Dense | 250 | Clinical labels |
| **VR-EEG P300**<br>[📄 Paper](https://www.nature.com/articles/s41597-022-01254-w)<br>[📁 Dataset](https://osf.io/2qh6f/) | P300 in VR | 21 | 16 | gTec / BrainAmp | 10–20 | 512 | VR vs monitor comparison |
| **THINGS-EEG**<br>[📄 Paper](https://www.biorxiv.org/content/10.1101/2021.06.03.447008v1)<br>[📁 Dataset](https://osf.io/hd6zk/) | Object Decoding | 50 | 64 | BP actiCHamp | Easycap | 1k | 1.6M trials (Rapid Visual) |
| **EEGCVPR40**<br>[📄 Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Singh_Learning_Robust_Deep_Visual_Representations_From_EEG_Brain_Recordings_WACV_2024_paper.pdf)<br>[📁 Dataset](https://github.com/perceivelab/eeg_visual_classification) | Visual (40 class) | 6–10 | 128 | BioSemi ActiveTwo | Dense | 1k | Used in CVPR papers |
| **MindBigData-MNIST**<br>[📄 Paper](https://arxiv.org/abs/2212.14746)<br>[📁 Dataset](https://mindbigdata.com/opendb/db-mnist.html) | Digit Decoding | 1 | 8–16 | Emotiv Epoc | Headset | 128 | 1.2M digit trials |
| **MindBigData-ImgNet**<br>[📄 Paper](https://arxiv.org/abs/2212.14746)<br>[📁 Dataset](https://mindbigdata.com/opendb/imagenet.html) | ImageNet Decode | 1 | Multi | Emotiv Epoc | Headset | 128 | ~70k ImageNet images |

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

