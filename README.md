# *VaccineLies*: A Natural Language Resource for Learning to Recognize Misinformation about the COVID-19 and HPV Vaccines

This repository contains the annotations utilized in the following research paper:

[VaccineLies: A Natural Language Resource for Learning to Recognize Misinformation about the COVID-19 and HPV Vaccines]()

Please cite as the following:

```

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
