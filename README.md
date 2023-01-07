# CSMSA

Dataset for COLING 2022 "[Towards Exploiting Sticker for Multimodal Sentiment Analysis in Social Media: A New Dataset and Baseline](https://aclanthology.org/2022.coling-1.591.pdf)"

Currently we only offer downloads with labeled data. The unlabeled data will be released soon.

# How to get the dataset

Signed the following copyright announcement with your name and organization. Then complete the form online(https://forms.gle/n9NxWsm1k7hZCcYq5) and **mail** to logosg@foxmail.com ('#'->'@'), we will send you the corpus by e-mail when approved.

# Copyright

The original copyright of all the conversations belongs to the source owner. The copyright of annotation belongs to our group, and they are free to the public. The dataset is only for research purposes. Without permission, it may not be used for any commercial purposes and distributed to others.

# What's in the dataset

`stickers_labeled`: stores all the stickers in the labeled dataset.

`CSMSA_labeled`: stores the labeled dataset.

# Data Sample

| Json Key Name    | Description                                                  |
| ---------------- | ------------------------------------------------------------ |
| text             | input text                                                   |
| image            | image name in `stickers`                                     |
| multimodal_label | the sentiment of the text and image. 0 indicates Neutral, 1 indicates Postive, 2 indicates Negative |
| text_label       | the sentiment of the text                                    |
| image_label      | the sentiment of the sticker                                 |
| img_helps_text   | 0 indicates no. 1 indicates yes.                             |
| sticker_group    | the series number of the sticker                             |



# Citation

```
@inproceedings{ge-etal-2022-towards,
    title = "Towards Exploiting Sticker for Multimodal Sentiment Analysis in Social Media: A New Dataset and Baseline",
    author = "Ge, Feng  and  Li, Weizhao  and  Ren, Haopeng  and  Cai, Yi",
    booktitle = "Proceedings of the 29th International Conference on Computational Linguistics",
    month = oct,
    year = "2022",
    address = "Gyeongju, Republic of Korea",
    publisher = "International Committee on Computational Linguistics",
    url = "https://aclanthology.org/2022.coling-1.591",
    pages = "6795--6804",
}
```

