# GDS_TwoTime

## Data

To reproduce the results from the report, you need to download the dataset **`995,000_rows.csv`**.

If the `data/` directory does not exist in the root of the repository, create it by running:

```sh
mkdir -p data
```
Place the 995,000_rows.csv file inside the data/ directory.

### note to contributers
.gitignore file is already configured to ignore everything inside the data/, you can verify that the file is ignored by running:
```sh
git check-ignore -v data/995,000_rows.csv
```
for data documentation see
```sh
https://github.com/several27/FakeNewsCorpus
```

## Required Libraries
The script requires the following Python libraries:

1. **nltk** - Natural Language Toolkit for text processing.
2. **pandas** - Data manipulation and analysis.
3. **numpy** - Numerical computing.
4. **sklearn (scikit-learn)** - Machine learning utilities
5. **matplotlib** - Plots.
6. **cleantext** - Corpus Cleaning
7. **pandarallel** - paralisation
8. **gensim**
9. **joblib**
10. **clean-text**

## Pre-trained models
- If you're within the institution of UCPH, you can access a repostoire of our models, pre-trained and ready for testing. This includes the Doc2Vec models, which can take a long time to train otherwise. The link is below:
https://alumni-my.sharepoint.com/:f:/g/personal/mrs530_alumni_ku_dk/EoXl2FTCYhtAha9IFT6XmG4BEJvQKtrX2t61GiMmLc8Byw?e=zVcP8w

## Installation Instructions
To install the required libraries, ensure you have Python installed on your system. You can install the dependencies using `pip` by running the following command in your terminal or command prompt:

```bash
pip install nltk pandas numpy scikit-learn matplotlib cleantext pandarallel
```


