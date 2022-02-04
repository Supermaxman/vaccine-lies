# *CoVaxLies*: Identifying the Adoption or Rejection of Misinformation Targeting COVID-19 Vaccines in Twitter Discourse

This repository contains the annotations utilized in the following research paper:

[Identifying the Adoption or Rejection of Misinformation Targeting COVID-19 Vaccines in Twitter Discourse](https://doi.org/10.1145/3485447.3512039)

Please cite as the following:

```
@inproceedings{weinzierl-acs,
	title        = {Identifying the Adoption or Rejection of Misinformation Targeting COVID-19 Vaccines in Twitter Discourse},
	author       = {Weinzierl, Maxwell and Harabagiu, Sanda},
	year         = 2022,
	booktitle    = {Proceedings of the Web Conference 2022},
	publisher    = {Association for Computing Machinery},
	address      = {New York, NY, USA},
	isbn         = 9781450390965,
	url          = {https://doi.org/10.1145/3485447.3512039},
	doi			 = {10.1145/3485447.3512039},
	numpages     = 10
}
```

## *CoVaxLies* v2
The *CoVaxLies* v2 collection is provided in the following file structure:

    ├── annotations          ~~~~ # [tweet, MisT] human judgements
    │   ├── dev.jsonl         # development split of {Accept, Reject, No Stance, Not Relevant} human judgements
    │   ├── test.jsonl        # testing split of {Accept, Reject, No Stance, Not Relevant} human judgements
    │   └── train.jsonl       # training split of {Accept, Reject, No Stance, Not Relevant} human judgements
    └── taxonomy              # MisT taxonomy judgements
       ├── misinfo.json      # MisTs with text as a json dictionary
       ├── mist-concerns.csv # MisT concerns
       ├── mist-themes.csv   # MisT themes
       ├── mists.csv         # MisTs with m_ids which map to MisT concerns
       └── questions.csv     # Questions used to discover MisTs

You will need to use the Twitter API to download the text of the annotated tweets, as we cannot directly provide this info
due to our IRB and Twitter's API policy.


## Code
Code for the above research paper is provided in the following repository:
[Link](https://github.com/Supermaxman/covid19-vaccine-nlp)


## *CoVaxLies* v1
The *CoVaxLies* v1 collection is provided for historical purposes at the following repository:
[Link](https://github.com/Supermaxman/covid19-vaccine-twitter)
