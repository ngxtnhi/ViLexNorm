# ViLexNorm: A Lexical Normalization Corpus for Vietnamese Social Media Text

The **ViLexNorm** corpus is a collection of comment pairs in Vietnamese, designed for the task of lexical normalization. For more details, please refer to the accompanying [paper](https://aclanthology.org/2024.eacl-long.85), which has been accepted at the [EACL 2024](https://2024.eacl.org/) Main Conference.

## Description

The corpus contains 10,467 comment pairs, carefully curated and annotated for lexical normalization purposes. These comment pairs are partitioned into three subsets: training, development, and test, distributed in an 8:1:1 ratio.

## Data Format

The data is provided in CSV format, with each row representing a comment pair. The CSV files contain two columns: `original` and `normalized`, where:

- `original`: Represents the original comment with unnormalized text.
- `normalized`: Represents the normalized version of the original comment.

## Citation

If you use the **ViLexNorm** corpus, please cite the following paper:

```
@inproceedings{nguyen-etal-2024-vilexnorm,
    title = "{V}i{L}ex{N}orm: A Lexical Normalization Corpus for {V}ietnamese Social Media Text",
    author = "Nguyen, Thanh-Nhi  and
      Le, Thanh-Phong  and
      Nguyen, Kiet",
    editor = "Graham, Yvette  and
      Purver, Matthew",
    booktitle = "Proceedings of the 18th Conference of the European Chapter of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = mar,
    year = "2024",
    address = "St. Julian{'}s, Malta",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.eacl-long.85",
    pages = "1421--1437",
    abstract = "Lexical normalization, a fundamental task in Natural Language Processing (NLP), involves the transformation of words into their canonical forms. This process has been proven to benefit various downstream NLP tasks greatly. In this work, we introduce Vietnamese Lexical Normalization (ViLexNorm), the first-ever corpus developed for the Vietnamese lexical normalization task. The corpus comprises over 10,000 pairs of sentences meticulously annotated by human annotators, sourced from public comments on Vietnam{'}s most popular social media platforms. Various methods were used to evaluate our corpus, and the best-performing system achieved a result of 57.74{\%} using the Error Reduction Rate (ERR) metric (van der Goot, 2019a) with the Leave-As-Is (LAI) baseline. For extrinsic evaluation, employing the model trained on ViLexNorm demonstrates the positive impact of the Vietnamese lexical normalization task on other NLP tasks. Our corpus is publicly available exclusively for research purposes.",
}
```

## License

The **ViLexNorm** corpus is released under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

---

For any inquiries or issues regarding the corpus, please contact the following emails:

- Ms. Thanh-Nhi Nguyen: 21521232@gm.uit.edu.vn
- Mr. Thanh-Phong Le: 21520395@gm.uit.edu.vn
