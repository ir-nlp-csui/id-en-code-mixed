# Indonesian-English Code-Mixed Tweet Dataset
One of prominent issues in Twitter is code-mixing, which is combining multiple languages in single conversation. Tweets in Indonesian language may intermingle with English vocabulary. This dataset contain 825 tweet instances of Indonesian-English, corresponding to four NLP tasks, i.e., <b>tokenization</b>, <b>language identification</b>, <b>lexical normalization</b>, and <b>word translation</b>.


## Citation
```
@inproceedings{barik-etal-2019-normalization,
    title = "Normalization of {I}ndonesian-{E}nglish Code-Mixed {T}witter Data",
    author = "Barik, Anab Maulana  and
      Mahendra, Rahmad  and
      Adriani, Mirna",
    booktitle = "Proceedings of the 5th Workshop on Noisy User-generated Text (W-NUT 2019)",
    month = nov,
    year = "2019",
    address = "Hong Kong, China",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/D19-5554",
    doi = "10.18653/v1/D19-5554",
    pages = "417--424",
    abstract = "Twitter is an excellent source of data for NLP researches as it offers tremendous amount of textual data. However, processing tweet to extract meaningful information is very challenging, at least for two reasons: (i) using nonstandard words as well as informal writing manner, and (ii) code-mixing issues, which is combining multiple languages in single tweet conversation. Most of the previous works have addressed both issues in isolated different task. In this study, we work on normalization task in code-mixed Twitter data, more specifically in Indonesian-English language. We propose a pipeline that consists of four modules, i.e tokenization, language identification, lexical normalization, and translation. Another contribution is to provide a gold standard of Indonesian-English code-mixed data for each module.",
}
```

Cleaner data for <b>lexical normalization</b> task has been included in <a href="https://aclanthology.org/2021.wnut-1.55/">MultiLexNorm</a> dataset.

```
@inproceedings{van-der-goot-etal-2021-multilexnorm,
    title = "{M}ulti{L}ex{N}orm: A Shared Task on Multilingual Lexical Normalization",
    author = {van der Goot, Rob  and
      Ramponi, Alan  and
      Zubiaga, Arkaitz  and
      Plank, Barbara  and
      Muller, Benjamin  and
      San Vicente Roncal, I{\~n}aki  and
      Ljube{\v{s}}i{\'c}, Nikola  and
      {\c{C}}etino{\u{g}}lu, {\"O}zlem  and
      Mahendra, Rahmad  and
      {\c{C}}olako{\u{g}}lu, Talha  and
      Baldwin, Timothy  and
      Caselli, Tommaso  and
      Sidorenko, Wladimir},
    booktitle = "Proceedings of the Seventh Workshop on Noisy User-generated Text (W-NUT 2021)",
    month = nov,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.wnut-1.55",
    doi = "10.18653/v1/2021.wnut-1.55",
    pages = "493--509",
    abstract = "Lexical normalization is the task of transforming an utterance into its standardized form. This task is beneficial for downstream analysis, as it provides a way to harmonize (often spontaneous) linguistic variation. Such variation is typical for social media on which information is shared in a multitude of ways, including diverse languages and code-switching. Since the seminal work of Han and Baldwin (2011) a decade ago, lexical normalization has attracted attention in English and multiple other languages. However, there exists a lack of a common benchmark for comparison of systems across languages with a homogeneous data and evaluation setup. The MultiLexNorm shared task sets out to fill this gap. We provide the largest publicly available multilingual lexical normalization benchmark including 13 language variants. We propose a homogenized evaluation setup with both intrinsic and extrinsic evaluation. As extrinsic evaluation, we use dependency parsing and part-of-speech tagging with adapted evaluation metrics (a-LAS, a-UAS, and a-POS) to account for alignment discrepancies. The shared task hosted at W-NUT 2021 attracted 9 participants and 18 submissions. The results show that neural normalization systems outperform the previous state-of-the-art system by a large margin. Downstream parsing and part-of-speech tagging performance is positively affected but to varying degrees, with improvements of up to 1.72 a-LAS, 0.85 a-UAS, and 1.54 a-POS for the winning system.",
}
```
