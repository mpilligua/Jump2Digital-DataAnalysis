# Jump2Digital-DataAnalysis

In this repository we include 2 different files. 
- crear_basedatos.ipynb: Used to clean and prepare the data for the back and front end solution 
- transformacion_analysis.ipynb: Where we analyze try to find patterns and implement algorithms to find relations

Interesting plots and analysis extracted


** Correlation matrix between the different barris of barcelona in terms of locals of each sectors, habitants, density, price to rent a local, medium income per habitant.**
![image](https://github.com/mpilligua/Jump2Digital-DataAnalysis/assets/28900735/aa4e94e9-3460-48d3-a335-5f00940b4c4a)

### Example of use
Imagine I want to open a new local in "la Barceloneta", this app would give you information like: 
![image](https://github.com/mpilligua/Jump2Digital-DataAnalysis/assets/28900735/6e4dcb3a-3a2e-4eee-b6cf-f54a9300daa0)

Futhrer more we can analyze the current number of locals we have per sector 
![image](https://github.com/mpilligua/Jump2Digital-DataAnalysis/assets/28900735/08b62d0e-f5dd-49e6-9660-d11b36bd263b)

And compare it with the other barris in barcelona (the mean of all the other barris)
![image](https://github.com/mpilligua/Jump2Digital-DataAnalysis/assets/28900735/308ccc0a-e2c1-4b33-91a8-199a12107eed)

From here we can extract data like: There is a need of automoció bussiness compared to other barcelona barris, which can be useful information to decide what kind of bussiness we want to open

### Recomendation of other barris
From this data we can also implement a recomendator that can compute the similarity between barris in the terms of features related to bussines activity, which can be a useful information to compare different alternatives.

![image](https://github.com/mpilligua/Jump2Digital-DataAnalysis/assets/28900735/23e30fa2-75a2-49bf-9c7b-6ea47ade0a69)

In a future implementation we can implement a complete recommender system that ranks not only barris but locals based on your preferences making even easier the task of opening a new bussines and fomenting overall "comerci local".
