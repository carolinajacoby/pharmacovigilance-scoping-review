This folder contains the CSV files with the article data used in this scoping review.

## File Descriptions:

- **`articles.csv`**: Contains the 490 articles included after Rayyan automatically removed duplicates, which proceeded to the first stage of title and abstract screening.

- **`reference.csv`**: Contains the 162 articles included after the first stage of title and abstract screening.

- **`exploded_technique.csv`**: Contains the structured classification of techniques, algorithms, and methods extracted from the final included articles. This file is formatted for statistical analysis, where each row represents a single technique linked to an article_id.

## Classification of Techniques (`exploded_technique.csv`)
The techniques in this file are categorized into:

- **disproportionality_techniques**: Classical pharmacovigilance methods (PRR, ROR, IC, etc.).

- **data_mining_algorithms_techiniques**: Machine learning and advanced data mining approaches.

- **other_techniques**: Complementary statistical methods (Descriptive statistics, TTO, etc.).

## **Usage Note**

These datasets are consumed by the Google Colab notebooks located in the /scripts folder.

## **Copyright**

All copyrights belong to the original authors and the corresponding journals. Any PDFs or metadata provided here are for academic and reference purposes only.
