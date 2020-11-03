# IMEMNet
IMEMNet Dataset is for continuous emotion-based image and music matching. For more detail, please refer to our paper:

Emotion-Based End-to-End Matching Between Image and Music in Valence-Arousal Space
https://arxiv.org/abs/2009.05103
	

## Original Dataset Downloading
First, download music dataset DEAM here:
http://cvml.unige.ch/databases/DEAM/

DEAM dataset consists of 1802 excerpts and full songs annotated with valence and arousal values both continuously (per-second) and over the whole song. The detailed description of the dataset is given in the Manual. The metadata describing the audio excerpts (their duration, genre, folksonomy tags) is in the metadata archive.
Plus, we also provide the music clips in format ‘.wav’. 

Google Drive download:https://drive.google.com/file/d/1pP0iW7AGZtwzpunSTBt0A3UiNzA5tIgx/view?usp=sharing

For China mainland, please download here: https://pan.baidu.com/s/19Zf_vU-R7KIP4e3NXT1nlg 
code: eomf 

Second, download the image dataset IAPS, NAPS and EMOTIC.

## Matching Dataset IMEMNET
Download the train, test and validation files here.

The file format is:

music_clip_id image_id matching_score

eg:

1967-11 COCO_train2014_000000318807 0.8757995366765425
