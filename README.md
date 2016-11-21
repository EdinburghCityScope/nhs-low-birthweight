# nhs-low-birthweight
Low weight live full term singleton births (under 2500g). The 3 year aggregate shown is for financial year ending 31 March and refers to the year of discharge from hospital.

Low birthweight (LBW) is a major determinant of infant mortality and morbidity. In addition, as it is associated with a variety of social and environmental factors, it is often used as a health status indicator. Low birthweight may result from being born too soon (i.e. a preterm birth), from poor intrauterine growth or from a combination of the two.

A number of factors are associated with low birthweight and/or preterm births. These include maternal smoking, maternal age (older and younger mothers are more likely to have a low birthweight baby), deprivation, previous obstetric history, low pre-pregnancy maternal weight, drug/alcohol use, hypertension and multiple births.

More information is available on the [ISD website](http://www.isdscotland.org/Health-Topics/Maternity-and-Births/Births/).

Statistics provided by NHS Information Services Division:  http://statistics.gov.scot/data/low-birthweight

## License

Data is licensed under the Open Government License: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/2/

## Requirements

- NodeJS
- npm

## Installation

Clone the repository

```
git clone https://github.com/EdinburghCityScope/nhs-low-birthweight.git
```

Install npm dependencies

```
cd nhs-low-birthweight
npm install
```

Run the API (from the nhs-low-birthweight directory)

```
node .
```

Converting the extracted data into loopback data.

```
node scripts/featureCollectionToLoopbackJson.js
```

Re-build data files from the statistics.gov.scot API

```
node scripts/build-data.js
```
