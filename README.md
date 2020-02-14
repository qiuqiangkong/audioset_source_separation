# Source separation with weakly labelled data: An approach to computational auditory scene analysis

This repo contains supplementary materials for our paper: **Source separation with weakly labelled data: An approach to computational auditory scene analysis**. The source separation system is trained on AudioSet [2].

## Separation demo
https://www.youtube.com/watch?v=g9NaNVhyCbY

https://www.youtube.com/watch?v=QleD1YF0nHU

## System
1. Use [sound event detection system](https://github.com/qiuqiangkong/audioset_tagging_cnn#sound-event-detection-using-pretrained-models) to detect anchor segments. Anchor segments are short segments (for example, 2 s) that most likely to contain a sound event.

2. Build source separation system following [1].

## Cite
[1] Kong, Qiuqiang, Yuxuan Wang, Xuchen Song, Yin Cao, Wenwu Wang, and Mark D. Plumbley. "Source separation with weakly labelled data: An approach to computational auditory scene analysis." arXiv preprint arXiv:2002.02065 (2020).

## Reference
[2] Gemmeke, J.F., Ellis, D.P., Freedman, D., Jansen, A., Lawrence, W., Moore, R.C., Plakal, M. and Ritter, M., 2017, March. Audio set: An ontology and human-labeled dataset for audio events. In IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), pp. 776-780, 2017
