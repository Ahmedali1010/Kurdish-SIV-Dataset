# Kurdish-SIV-Dataset
"A comprehensive Kurdish speech corpus for Speaker Identification and Verification (SIV) in a low-resource language environment."

# Central Kurdish Speaker Identification Dataset (SIV)

This repository provides a sample and documentation for the "Central Kurdish Speech Corpus for Speaker Identification and Verification in a Low-Resource Language Environment".

## Abstract / General Description
This dataset comprises a proprietary acoustic corpus specifically developed for text-independent Speaker Identification and Verification (SIV) within a low-resource language environment (Central Kurdish). The dataset contains 86,505 discrete audio utterances recorded from 200 demographically diverse native speakers. It provides a robust empirical foundation for training deep learning biometric architectures, structurally optimized for researchers extracting high-dimensional acoustic representations (2D log Mel-spectrograms) for Convolutional Neural Networks (CNNs).

## Data Access
The full acoustic corpus (86,505 utterances) is hosted on Mendeley Data. You can access and download the complete dataset via the following DOI:

**DOI:** [[10.17632/7rv22xjmdx.4](https://doi.org/10.17632/7rv22xjmdx.4)](https://data.mendeley.com/drafts/7rv22xjmdx.3)

**Citation:**
Abdulrahman, Ayub Othman; Ali, Ahmad; jamal, Muhamad Jamal; Bakr, Zhyar (2026), “A Comprehensive Kurdish Speech Corpus for Speaker Identification and Verification in a Low-Resource Language Environment”, Mendeley Data, V4, doi: 10.17632/7rv22xjmdx.4

## Dataset Metrics
- **Total Participants:** 200 native speakers (101 Male, 99 Female).
- **Total Samples:** 86,505 independent acoustic samples.
- **Audio Format:** Raw audio stored in .ogg format.
- **Utterance Duration:** Uniformly normalized to 1.0 second per clip.
- **Density:** Minimum of 400 discrete audio samples per individual participant.

## Dataset Partitioning
- **Training and Validation Sets (73,538 files):** Divided into an 85% training set and 15% validation set using stratified sampling.
- **Isolated Test Set (12,967 files):** A separate directory of unseen audio samples for final model assessment.

## Recommended Usage
This corpus is engineered for advanced audio-to-image classification tasks, supporting the extraction of Mel-spectrograms (64 Mel-frequency bins and 44 temporal frames) for training 2D-CNN topologies. It facilitates protocols for both multi-class closed-set speaker identification and open-set biometric security verification.

## License
This dataset is published under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.
