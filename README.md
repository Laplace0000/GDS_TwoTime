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

## Installation Instructions
To install the required libraries, ensure you have Python installed on your system. You can install the dependencies using `pip` by running the following command in your terminal or command prompt:

```bash
pip install nltk pandas numpy scikit-learn
```


