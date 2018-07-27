# Project McNulty MVP Summary

## Harmeet Hora

## Domain

 

For Project McNulty, I will be working with a 2015’s LendingClub.com data. Lending Club is a website that allows individuals to be lend and borrow money from each other which will be paid back with interest. The conditions for these loans are based on a variety of different factors such as previous loans open, number of delinquent debts, credit score, and income, to name a few. This is not a domain that I am deeply knowledgeable about, but I do have some general knowledge of how a borrower’s financial history can impact the conditions of a loan. I would like to use the borrower’s information to predict outcome of loan and/or the grade that is assigned by lending club.

 

## Data

 

The dataset currently has more than 100 columns, which I am working on condensing. Below are a few of the features I believe are essential to the analysis.

 

| **Field**                                                    | **Data Type** |
| ------------------------------------------------------------ | ------------- |
| Loan Status – (Essentially outcome of loan) – Value to   predict | String        |
| Loan Amount                                                  | Int           |
| Interest Rate                                                | Float         |
| Term (length of loan)                                        | Int           |
| Lending Club Grade                                           | string        |
| Lending Club Subgrade                                        | string        |
| Employment Length                                            | string        |
| Home Ownership Status                                        | String        |
| Self Reported Annual Income                                  | Int           |

 

 

## Known Unknowns:

 

- Since loan id and customer ids are omitted from the dataset, all loans will be treated as independent borrowers, so it is possible that multiple loans can be from the same borrower
- There are many columns that convey what seems to be redundant information (ex: # of trades in last 12 months vs # of trades within 24 months). It will take some feature analysis to determine which data points are significant to the model