# MoralityBank Corpus

## TL;DR
MoralityBank is a large-scale corpus with more than 300k morality-bearing sentence examples. It supports Language Models' (continual) pre-training to inject moral knowledge derived from moral words (see section 4.1 of our paper: Moral Word Knowledge Augmentation).

## Directory organization

- ```moral_word_memory_bank.json``` Follow this [link](https://drive.google.com/drive/folders/1BH5iDruCvvqAJ_4q1FnrcizkZ4eBnL3X?usp=sharing) to download the MoralityBank Corpus. It's stored as a dictionary with the following structure:
```
"Moral Word/Cluster ID":
    [
        (
            "Sentence",
            "Moral Mention",
            {
                "Embodied Morality",
                ...
            }
        ),
        ...
    ],
    ...
```

- ```moral_word_clusters_final.json``` prints out moral mentions encountered for each moral word cluster. One can easily infer the base form, i.e., moral word, through inspection.
