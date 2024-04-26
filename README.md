# StoryTTS

> [STORYTTS: A HIGHLY EXPRESSIVE TEXT-TO-SPEECH DATASET WITH RICH TEXTUAL EXPRESSIVENESS ANNOTATIONS](https://ieeexplore.ieee.org/document/10446023)

StoryTTS is a highly expressive text-to-speech dataset that contains rich expressiveness both in acoustic and textual perspective, from the recording of a Mandarin storytelling show (评书), which is delivered by a female artist, Lian Liru(连丽如). It contains 61 hours of consecutive and highly prosodic speech equipped with accurate text transcriptions and rich textual expressiveness annotations.

[Demos](https://goarsenal.github.io/StoryTTS/)


## Dataset Statistics

<img src="figures/table1.png" alt="table1" style="width: 50%;" />

<img src="figures/table2.png" alt="table2" style="width: 50%;" />

## Download

* Please download the speech data from [Google Drive (5.06 GB)](https://drive.google.com/file/d/1KuD-6c2yxLqPhNJHCaE1jIee-8TjjsB6/view?usp=drive_link) or [百度云盘(提取码：u79a)](https://pan.baidu.com/s/1hKc1hKUcEfnnVZYRLDyYwA?pwd=u79a)

  ### Note

  * The dataset is **ONLY** for research purposes.
  * The ownership of the speech data remains with the original owner. Downloading this dataset defaults to agreeing to sign our [licensing agreement](storytts_license_agreement.pdf). lt's important to note that these materials may be removed at any time upon request from the original owner.

## File Description

* `dataset/transcript` : The transcripts of StoryTTS in simplified Chinese with puncuations.

* `dataset/utt2dur`: The duration (in seconds) of each utterance.

* `dataset/utt2spk`: The speaker name of each utterance, i.e. the name of the only speaker in StoryTTS.

* `dataset/label` : The annotation labels of StoryTTS. The format of this file is as follows:

  ```
  utt-ID 句式(Sentence Pattern)|修辞手法(Rhetoric Device)|场景(Scene)|情感色彩(Emotional colors)|模仿人物(Imitated Characters)
  ```

* `dataset/prompt_claude2`: Prompt and instruction for Claude2.

* `dataset/prompt_gpt4`: Prompt and instruction for GPT4.

* `dataset/wav.scp`: Path of wav files. Note: might be changed according to your location of storing the speech data.

## Citation

```
@inproceedings{storytts,
  author={Sen Liu and Yiwei Guo and Xie Chen and Kai Yu},
  title={{StoryTTS: A Highly Expressive Text-to-Speech Dataset with Rich Textual Expressiveness Annotations}},
  year={2024},
  booktitle={ICASSP 2024 - 2024 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  pages={11521-11525},
  doi={10.1109/ICASSP48485.2024.10446023}
}
```

