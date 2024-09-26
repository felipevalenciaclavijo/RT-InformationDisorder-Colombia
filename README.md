# Dataset: Russian Information Disorder in Colombia? The Case of RT’s Inna Afinogenova on Twitter

This repository contains the dataset associated with the paper titled "[Russian Information Disorder in Colombia? The Case of RT’s Inna Afinogenova on Twitter](LINK_TO_DOI)." The dataset includes anonymised user behaviour data obtained from the Twitter API. This data is made available under the [Creative Commons Attribution 4.0 International (CC BY 4.0) License](https://creativecommons.org/licenses/by/4.0/).

# Data Description

The dataset has been anonymised to ensure user privacy. Usernames have been replaced with anonymised IDs, and sensitive variables such as location have been removed to mitigate the risk of re-identification. The remaining data includes user behaviour metrics, and account creation years.

## Dataset Files

### `anon_data.csv`

- **Description**: This file contains the raw data obtained from Botometer. It includes the initial data as collected before any preprocessing and also includes the classification of Nimmo (2019).

### `fix_anon_data.csv`

- **Description**: This file contains the cleansed dataset. The data has been cleaned and processed to ensure accuracy and consistency. Details about the data cleansing actions are provided in the paper.

## Dataset Variables

The dataset contains the following variables:

- **anon_id**: Anonymised user account ID.
- **year**: Year of account creation.
- **TPpW**: Total Publications per Week, where Publications = Tweets + ReTweets.
- **percentage_RT**: Percentage of ReTweets from Total Publications.
- **RTpW**: ReTweets per Week.
- **TpW**: Tweets per Week.
- **NDLW**: Number of Days in the Last Week where publications were made.
- **classification**: Classification of the account as one of the following categories:
  - Inorganic
  - Highly Suspicious
  - Suspicious
  - Organic

## Data Privacy and Anonymisation

- **Anonymisation**: Usernames in the dataset have been anonymised to protect individual identities.
- **Removed Variables**: Variables such as location and gender, which could potentially identify individuals, have been removed from the dataset.

## License

This dataset is available under the [Creative Commons Attribution 4.0 International (CC BY 4.0) License](https://creativecommons.org/licenses/by/4.0/). You are free to use, share, and adapt the data, including for commercial purposes, as long as you provide appropriate credit to the original creators. For full terms, please refer to the [LICENSE.md](LICENSE.md) file in this repository.

## Contact

For any questions or further information, please contact Gustavo Rivero at gariveroo@gmail.com
