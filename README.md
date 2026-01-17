# EasyDipreo 

## Introduction

The core principle behind our ‘EasyDipreo’ Accounting Package is “Accumulated Depreciation,” a key concept in accounting's subsequent measurements. Our understanding of this concept has been greatly enhanced by the classroom lectures from the IS-1210 module, particularly the lecture on “Property, Plant, and Equipment.” This lecture covered the fundamentals of accumulated depreciation, its real-world applications, and various methods for calculating it, all of which have been instrumental in the development of this software package.

## Accumulated Depreciation

Accumulated Depreciation refers to the systematic allocation of the depreciable amount of an asset over its useful life.

<img width="902" height="624" alt="{513369B8-7E43-4129-BB9C-777A116231CB}" src="https://github.com/user-attachments/assets/9e32c203-80aa-4512-b86f-acf5d04144f2" />

## Methods of Calculating Depreciation

There are three primary methods for calculating depreciation:

### 1. Straight Line Basis (SLB) Method

This method requires the cost, scrap value, and useful life of the asset. Depreciation is calculated using the following formula:

Depreciation = (Cost - Scrap Value) / Useful Life

<img width="898" height="622" alt="{5A842BA8-15B5-4DA6-8160-6981A5F9E5C1}" src="https://github.com/user-attachments/assets/5226d5d8-9530-42a0-981f-5034646fe7c2" />


### 2. Reducing Balance Basis (RBB) Method

This method also requires the cost, scrap value, and useful life of the asset. First, the depreciation rate is calculated using the following formula:

Rate = [1 - (Scrap Value / Cost)^(1/n)] x 100%

Where `n` is the useful life of the asset in years.

After calculating the rate, the depreciation for each year is calculated as follows, where the carrying value for the first year is equal to the cost value:

Depreciation = Carrying Value x Rate

<img width="900" height="625" alt="{A73CC6CF-BD11-47B9-8737-E9881A06CD96}" src="https://github.com/user-attachments/assets/2895abe9-b45c-4a33-814e-3588dc2f8935" />


### 3. Production Unit Basis (PUB) Method

This method requires the cost, scrap value, and production units for each year. First, calculate the total production units. Depreciation is then calculated using the following formula:

Depreciation = [(Cost - Scrap Value) / Total Production Units] x Production Units per Year

<img width="905" height="622" alt="{DC321900-0306-4064-A671-E7468192FD84}" src="https://github.com/user-attachments/assets/6ca8fc9a-b39e-4dc4-b1ca-173d2cde493e" />




