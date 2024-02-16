
# Datasheets J Lawrence 02/24

## Outcomes dataset (y)

### Motivation

The outcome data was created by the market supervisor in Peru the Superintencia del Mercado de Valores from listed corporations required to make annual reports of their compliance with a corporate governance code

### Composition

The data are held as individual company records comprising corporations’ responses to 88 questions answered wither “Si” or “No”

There are c 210 records for every year 2014 to 2020

There is very little missing data, if it is, the SMV recommend taking the absence as a “No”.

The data is not confidential

### Collection

Data are collected annually – corporations send their completed returns to the SMV who enter the data onto the online records at  [www.SMV.gov.pe](http://www.smv.gov.pe/)

### Pre-processing

The data have been downloaded and compiled into a serios of annual worksheets.

The data has been digitized ie “Si” or “No” are replaced by “1” and “0”.

Any gaps have been replaced by “0”.

Data have then been categorized according to the nature of the rule:

· Constitutive rules - If third parties are introduced into governance

· Regulative rules – if nothing material regarding third parties is involved

###  Uses

The data are used to keep a record of corporations’ compliance record

They are available to other agencies, in particular the Lima stock exchange (Bolsa de Valore de Lima) which uses the data to compile, in conjunction with EY, an annual report on the state of corporate governance in Peru called La Voz del Mercado

### Distribution

The data is available online, but otherwise is not distributed

The data is maintained by the SMV

There are not direct feeds from the SMV

Currently on excel

## Features data (X)

### Motivation

The motivation for the features data is to explain the outcome data

### Composition

Consists of 10 features for all listed corporations in Peru in 2017 , covering: regulator, sector, shareholding structure, local equity activity, local bond issuance, international equity listing, international bond issuance, group structure , multiple BVL listings, and ownership by a major family.

### Collection

Collected by author from a range of sources

### Pre-processing

Each feature has been dichotomized as “1” or “0”.

### Uses

In the complied state, the feature data is used exclusively for this task

### Distribution

Not applicable

Currently on excel
