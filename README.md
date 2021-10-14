## Programming_for_DA_Project (Programming for Data Analysis Project)

This document consists of simulation for the passenger profile of Dublin Airport for the year 2018 (latest available public data), the data were simulated based on the information provided on the website of **[Dublin Airport](https://www.dublinairport.com/corporate/about-us)**.

***

### Methodology and Approach

In the **[About Us](https://www.dublinairport.com/corporate/about-us)** section of the web page of Dublin Airport, there are some key facts of the classification of the passengers. Based on these facts and figures, I was able to simulate a data set which represents some of the following facts of the passenger profiles.

#### DateTime

Generating a random array which represents a a random fragments of _one hour_ in the year 2018 based on the total amounts of passengers who used the airport during the year.

#### Gender 

Generating a random array of Gender of passengers who used the airport during that time based on the representation percentage provided. It was validated by statistics model of binomial 
distribution for verification.

#### Age

Generating a random array of the age of passengers based on the classified representaioin of passengers' age groups provided by the source.

#### Country of Residence

Generating a random sample array of the country of residence of passengers as per classification and categorisation of the source.

#### Socio-Economic Class

Generating a random sample array of the passengers socio-economic class based on the classification and categorisation of the source.

***

### Libraries Used

Numpy

Pandas

Matplotlib

Seaborn


***

## Quick steps

You can view the notebook at the following URL:

[![nbviewer](https://user-images.githubusercontent.com/2791223/29387450-e5654c72-8294-11e7-95e4-090419520edb.png)](https://nbviewer.org/github/G00387867/Programming_for_DA_Project/blob/main/DA_Passengers.ipynb)

### To run the Jupyter Notebook

- Initially you should have no issues to view the contents of the file TDA_Passengers.ipynb that contains the main body of work. If you would like to interact and edit the contents please be advised that you should have the following requirements:
Download and Install [**Anaconda**](https://www.anaconda.com/) latest release from it's official and licensed source. The anaconda package includes the python code and the packages (libraries) needed for the computation and visualisation of the contetnts of the Tasks.ipynb file.

1. Navigate to the code `DA_Passengers.ipynb` in the repository

2. Choose to clone/download the repository and copy the link (make sure you copy the link statrts with https and not the SSH)

3. Open the `CLI` or `cmd` on the machine navigate to the required directory insert `$ git clone` `link of the repository`

4. insert `jupyter notebook`

5. A web browser is automatically initiated, where you can see the file DA_Passengers.ipynb.

***
### License
This repository was enrolled under GNU license. Please click [**HERE**](https://github.com/G00387867/Programming_for_DA_Project/blob/main/LICENSE) for further information.
