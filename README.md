# ViLexNorm: A Lexical Normalization Corpus for Vietnamese Social Media Text

The **ViLexNorm** corpus is a collection of comment pairs in Vietnamese, designed for the task of lexical normalization. For more details, please refer to the accompanying [paper](https://arxiv.org/abs/2401.16403), which has been accepted at the [EACL 2024](https://2024.eacl.org/) Main Conference.

## Description

The corpus contains 10,467 comment pairs, carefully curated and annotated for lexical normalization purposes. These comment pairs are partitioned into three subsets: training, development, and test, distributed in an 8:1:1 ratio.

## Data Format

The data is provided in CSV format, with each row representing a comment pair. The CSV files contain two columns: `original` and `normalized`, where:

- `original`: Represents the original comment with unnormalized text.
- `normalized`: Represents the normalized version of the original comment.

## Citation

If you use the **ViLexNorm** corpus, please cite the following paper:

```
@misc{nguyen2024vilexnorm,
      title={ViLexNorm: A Lexical Normalization Corpus for Vietnamese Social Media Text}, 
      author={Thanh-Nhi Nguyen and Thanh-Phong Le and Kiet Van Nguyen},
      year={2024},
      eprint={2401.16403},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```

## License

The **ViLexNorm** corpus is released under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

---

For any inquiries or issues regarding the corpus, please contact the following emails:

- Ms. Thanh-Nhi Nguyen: 21521232@gm.uit.edu.vn
- Mr. Thanh-Phong Le: 21520395@gm.uit.edu.vn
