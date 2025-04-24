# Bridging Modal Gaps in Multimodal Sentiment Analysis: A Self-Supervised Text-Guided Fusion Approach

<br/>

## Main Contributions

Our main contributions can be summarized as follows:

●    Recognizing the differential contributions of modalities on sentiment analysis, a novel TGFM is introduced to achieve the consistency among three modalities including text, audio, and video via two key components: (1) text-oriented multi-head attention and (2) text-guided cross-modal mappings, providing a comprehensive solution to multimodal fusion challenges.

<br/>

●    The relationship between representations and features is integrated through the introduction of a unimodal representation learning module. This module is designed to capture temporal dependencies within feature sequences while mining global attributes, ensuring that the model effectively understands and represents single-peak features.

<br/>

●    A multi-task learning framework is employed to jointly train four tasks for co-learning, thereby enabling effective sentiment polarity prediction even in the absence of unimodal labels.

<br/>

●    This work discovers that the utilisation of single modal labels in conjunction with multi-task joint learning proves efficacious in enhancing fine classification, which provides a few thoughts for the improvement of Acc-5 and Acc-7 in the future.

## Backgroud and Significance

●    With the rapid proliferation of multimodal content—such as text, audio, and video—on social media and short video platforms, multimodal sentiment analysis (MSA) has emerged as a vital research direction in the field of artificial intelligence. Despite notable advancements in multimodal dataset construction and fusion strategies, MSA continues to face two fundamental challenges.

## The Framework

●   The framework of SETGF. For more details, please wait for the review.

## Usage

### Prerequisites

●    Python ==3.8.18

●    Pytorch==1.13.0

●    CUDA ==12.7

### Datasets and pre-trained berts

Download dataset features and pre-trained berts from the following links.

●   Dataset [Google Cloud Drive](https://drive.google.com/drive/folders/1E5kojBirtd5VbfHsFp6FYWkQunk73Nsv?usp=sharing)

●   Pre-trained berts [BERT](https://github.com/google-research/bert)

For more details, please refer to  [Self-mm](https://github.com/thuiar/Self-MM)

### Run the codes

●   You can first set the training dataset name in ./run.py as "mosei" , "mosi" or "sims", and then run.

### Results

●   You can view the results in the logs folder.

## Notes

● Please wait for the review to end for more details。