# *VaccineLies*: A Natural Language Resource for Learning to Recognize Misinformation about the COVID-19 and HPV Vaccines

This repository contains the annotations utilized in the following research paper:

[VaccineLies: A Natural Language Resource for Learning to Recognize Misinformation about the COVID-19 and HPV Vaccines](https://arxiv.org/abs/2202.09449)

Please cite as the following:

```
@InProceedings{weinzierl2022vaccinelies,
  author    = {Weinzierl, Maxwell  and  Harabagiu, Sanda},
  title     = {VaccineLies: A Natural Language Resource for Learning to Recognize Misinformation about the COVID-19 and HPV Vaccines},
  booktitle      = {Proceedings of the Language Resources and Evaluation Conference},
  month          = {June},
  year           = {2022},
  address        = {Marseille, France},
  publisher      = {European Language Resources Association},
  pages     = {6967--6975},
  url       = {https://aclanthology.org/2022.lrec-1.753}
}
```

## *VaccineLies* v1
The *VaccineLies* v1 collection is provided in the following file structure:

    ├── covid19                   # CoVaxLies - COVID-19 vaccine misinformation
    │   ├── annotations           # [tweet, MisT] human judgements
    │   │   ├── dev.jsonl         # development split of {Accept, Reject, No Stance, Not Relevant} human judgements
    │   │   ├── test.jsonl        # testing split of {Accept, Reject, No Stance, Not Relevant} human judgements
    │   │   └── train.jsonl       # training split of {Accept, Reject, No Stance, Not Relevant} human judgements
    │   └── taxonomy              # MisT taxonomy judgements
    │       ├── misinfo.json      # MisTs with text as a json dictionary
    │       ├── mist-concerns.csv # MisT concerns
    │       ├── mist-themes.csv   # MisT themes
    │       ├── mists.csv         # MisTs with m_ids which map to MisT concerns
    │       └── questions.csv     # Questions used to discover MisTs
    ├── hpv                       # HpVaxLies - HPV vaccine misinformation
    │   ├── annotations           # [tweet, MisT] human judgements
    │   │   ├── dev.jsonl         # development split of {Accept, Reject, No Stance, Not Relevant} human judgements
    │   │   ├── test.jsonl        # testing split of {Accept, Reject, No Stance, Not Relevant} human judgements
    │   │   └── train.jsonl       # training split of {Accept, Reject, No Stance, Not Relevant} human judgements
    │   └── taxonomy              # MisT taxonomy judgements
    │       ├── misinfo.json      # MisTs with text as a json dictionary
    │       ├── mist-concerns.csv # MisT concerns
    │       ├── mist-themes.csv   # MisT themes
    │       ├── mists.csv         # MisTs with m_ids which map to MisT concerns
    │       └── questions.csv     # Questions used to discover MisTs
    ├── LICENSE
    └── README.md

You will need to use the Twitter API to download the text of the annotated tweets, as we cannot directly provide this info
due to our IRB and Twitter's API policy.
