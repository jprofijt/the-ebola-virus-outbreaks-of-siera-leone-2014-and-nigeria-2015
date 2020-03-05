# Simulating the Ebola outbreaks in Sierra Leone (2014) and Nigeria (2015)
Since traveling is a lot easier than 50 jears ago, we travel a lot more. Globalisation is not a bad thing but
it comes with a huge risk, the risk of easily spreading infection deceases. Ebola virus disease (EVD) is one
of these infection deceases. On 20 july, 2014 a infected passenger landed in Nigeria and started a outbreak.
This outbreak was a pretty small one of only 20 cases, this was because of the quick response of only 3 days.
Showing how important it is to react quickly to an infection. In this paper we tried to match an EVD model
to the outbreaks of Nigeria 2015 and Sierra Leone 2014 to show the value of a quick reaction and to replicate the 
results that where achieved in the paper of C.L. Althaus et al. [1]

## Getting started
### Installation
The files and the model can be downloaded by cloning the repository
```bash
git clone https://RinzePieterJonker@bitbucket.org/Rinze-Pieter/the-ebola-virus-outbreaks-of-siera-leone-2014-and-nigeria-2015.git
```

### Prerequisites
To run the simulation the coding language R (version 3.X ) is needed. The packages that are needed for the code are
DeSolve and pander, these packages can both be installed by using the R command install.package(<Package\>).

## Files Included
 - __Data/__
    - __Previous-case-counts.csv__ - A csv file containing all the data that was used for the creation of the model
 - __docs/__
    - __Opgaven/__ - A directory containing all the lectures and deliverables that where done during this project
    - Model Ebola.Rmd - The code behind the report
    - Model Ebola.pdf - The PDF of the report
    - Verslag_Week4 - A report containing a model that simulates the function of Glucocorticoids, this was made to get a
    feel over how the DeSolve Package works
 - __img/__ - A directory containing all the images that where used for the reports

## Authors
 - __Jouke Profijt__ (J.profijt@gmail.com)
 - __Rinze-Pieter Jonker__ (rinze.pieter.jonker@gmail.com)
 
## References
[1]. Althaus, C. L., Low, N., Musa, E. O., Shuaib, F., & Gsteiger, S. (2015, 21 april). Ebola virus
disease outbreak in Nigeria: Transmission dynamics and rapid control. Retrieved from https://www.
sciencedirect.com/science/article/pii/S1755436515000341 on 01-06-2018