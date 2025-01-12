# RoLargeSum

This repository hosts RoLargeSum, a comprehensive dataset comprising 615,679 articles along with their corresponding summaries, titles, keywords, topics, and dialect classifications (either `romanian` or `moldavian`).

You can read more about the dataset in the following paper: work in progress...

**Note**: The dataset is available for research purposes upon request by emailing us at: dumitru.cercel@upb.ro

## Loading

Install the `datasets` library via pip:

```bash
pip install datasets
```

To load the dataset, simply run:

```Python
from datasets import load_dataset

dataset = load_dataset("avramandrei/rolargesum")
```

Each sample respects the following format:
```json
{
  "text": "This is the main text of the article",
  "summary": "This is the summary",
  "title": "Title of article",
  "keywords": "keyword1,keyword2,keyword3",
  "dialect": "romanian",
  "topics": "politica",
  "url": "www.example.com",
  "author": "John Doe"
}
``` 

## Citation
```
@article{avram2024rolargesum,
  title={RoLargeSum: A Large Dialect-Aware Romanian News Dataset for Summary, Headline, and Keyword Generation},
  author={Avram, Andrei-Marius and Timpuriu, Mircea and Iuga, Andreea and Matei, Vlad-Cristian and T{\u{a}}iatu, Iulian-Marius and G{\u{a}}in{\u{a}}, Tudor and Cercel, Dumitru-Clementin and Pop, Florin and Cercel, Mihaela-Claudia},
  journal={arXiv preprint arXiv:2412.11317},
  year={2024}
}
```
