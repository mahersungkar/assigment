# Assignment-DataScience-Hacktiv8
## 1. Assignment 1
#### BACKGROUND <a name='background'></a>
A LSOA is a census area containing 1,000 to 3,000 people. SOAs were designed to improve the reporting of small area statistics and are built up from groups of output areas
(OA). Statistics for lower layer super output areas (LSOA) and middle layer super output areas (MSOA) were 
originally released in 2004 for England and Wales. Scotland also released statistics for data zones (DZ), that 
were equivalent to LSOAs, in 2004 and intermediate geographies (IG),  that were equivalent to MSOAs, in 2005. 
Northern Ireland introduced LSOAs in 2005 but do not have an MSOA geography.

### ABOUT THE DATASET <a name='about_the_dataset'></a>
This data, represented by the file `london_crime_by_lsoa.csv`, covers the number of criminal reports by month, 
LSOA borough, and major/minor category from Jan 2008-Dec 2016 in Greater London (central London and the 
surrounding metropolitan area) by providing 13,490,604 samples with 7 variables 
each.

The variables `lsoa_code`, `borough`, `major_category`, `minor_category`, `year` and `month` are **categorical** 
variables, while `value` is a **discrete numerical** variable. The variables' meanings are the followings:

* `lsoa_code`: code for Lower Super Output Area in Greater London;
* `borough`: common name for London borough;
* `major_category`: high level categorization of crime;
* `minor_category`: low level categorization of crime within major category;
* `year`: year of reported counts, 2008-2016;
* `month`: month of reported counts, 1-12;
* `value`: monthly reported count of categorical crime in given borough;

## 2. Assignment 2
### Background

This dataset contains the location, address, type, sale price, and sale date of building units sold. A reference on the trickier fields:
* BOROUGH : A digit code for the borough the property is located in; in order these are Manhattan (1), Bronx (2), Brooklyn (3), Queens (4), and Staten Island (5).
* BLOCK; LOT :The combination of borough, block, and lot forms a unique key for property in New York City. Commonly called a BBL.
* BUILDING CLASS AT PRESENT and BUILDING CLASS AT TIME OF SALE: : The type of building at various points in time.


Note that because this is a financial transaction dataset, there are some points that need to be kept in mind:
* Many sales occur with a nonsensically small dollar amount: $0 most commonly. These sales are actually transfers of deeds between parties: for example, parents transferring ownership to their home to a child after moving out for retirement.
* This dataset uses the financial definition of a building/building unit, for tax purposes. In case a single entity owns the building in question, a sale covers the value of the entire building. In case a building is owned piecemeal by its residents (a condominium), a sale refers to a single apartment (or group of apartments) owned by some individual.

## 3. Assingment 3
### Project overview
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.
There are four datasets:
* <strong>bank-additional-full.csv</strong>  with all examples (41188) and 20 inputs, ordered by date (from May 2008 to November 2010), very close to the data analyzed in [Moro et al., 2014]
* <strong>bank-additional.csv</strong>  with 10% of the examples (4119), randomly selected from 1), and 20 inputs.
* <strong>bank-full.csv</strong>  with all examples and 17 inputs, ordered by date (older version of this dataset with less inputs).
* <strong>bank.csv</strong>  with 10% of the examples and 17 inputs, randomly selected from 3 (older version of this dataset with less inputs).

* link dataset : <a href="https://archive.ics.uci.edu/ml/datasets/Bank+Marketing"> disini</a>

The smallest datasets are provided to test more computationally demanding machine learning algorithms (e.g., SVM).
The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y).
