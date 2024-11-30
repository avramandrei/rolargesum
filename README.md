# RoLargeSum

This repository contains RoLargeSum, a dataset with 615,679 articles and their corresponding summary, title, keywords, topic and dialect (either `romanian` or `moldavian`).

You can read more about the dataset in the following paper: work in progress...

**Note**: The dataset is available for research purposes upon request by emailing us at: dumitru.cercel@upb.ro

## Loading

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
Work in progress.
