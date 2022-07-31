# CollegeCodes
This repository aims to be a time machine. I hope I check it in the future and feel proud looking into a hard, but steady, progress ladder. It's been nearly three years since I took my first programming class, and I have been using coding skills almost daily. 

This is a summary of the main work I've done during my Economics undergraduate at Fundacao Getulio Vargas (2019 - 2022). Those were four years of intense learning, a lot of economic theory, and discoveries. Four years ago, I simply didn't know the universe of **really interesting** things I would discover over that journey. This repository is just a piece of it all.

## 2020.2 – Meat Production: a Worldwide Analysis
##### Pyhon Class Final Project
My first contact with programming languages was actually in Python. I would just discover R months later. It was a 60h introductory course with the basic syntax and helpful libraries on explanatory data analysis (EDA). 

The final project was composed of a simple task: clean a dataset and analyze it. By that time, I was enrolled in a research project on the Brazillian meat market, and I picked a dataset related to it. 

So, I've downloaded a 15k rows FAO time series with meat production, by country, since 1990. That main challenge was to clean it, in such a way that I could present the main producers over time, by meat type. It took me some two weeks - and a lot of help from Stack Overflow - to make the interactive charts with Plotly. 

Here you can find the [script](https://1drv.ms/u/s!AjVW0s-wFcYmhYgJmcyQMpTK9krPlQ?e=kOgAeq) and the original [database](https://1drv.ms/u/s!AjVW0s-wFcYmhYgKZr6RKEd7aflbsg?e=qJvmBw).

<p align="center">
  <img width="800" src="https://github.com/HecVini/CollegeCodes/blob/main/Computacao_CodePrint.png" >
</p>

_(Seriously, I have no idea what I was doing in that piece of script. Luckily, now I regularly comment codes and understandably call stuff)_

It is so interesting to check it two years later. Progress since then is clear and it has been worth spending hours learning Python with a real-life example. 

## 2021.1 – Economic Policy in Brazil, Chile and Argentina
##### R Class Final Project and PIBIC
Then, I stepped into R. In early 2021 I took a 60h R course, and since then, I've been using it regularly. In that semester, a had two main projects with it: the course final one, and an undergraduate research (PIBIC). Both were about the same topic: the Economic History of Brazil, Chile, and Argentina, during the 70s and the 80s. 

In both projects, I compiled data on the macroeconomics of those countries, including time series on inflation, GDP, population, growth rates, international trade, and government spending. Sources include the World Bank, IBGE, Indec, INE, and the Fed.

Codes [here](https://1drv.ms/u/s!AjVW0s-wFcYmhYgSVCJS8-vBJxYHCQ?e=q8KhMh) and [here](https://1drv.ms/u/s!AjVW0s-wFcYmhYgmqHDzj2AW57vpBg?e=uhgAZt).

![](https://github.com/HecVini/CollegeCodes/blob/main/DoubleLoop_PIBIC.png)
_(I can't believe I used double loops. If this project taught me something thing it was: that there is a package for everything you need.)_

This was the first contact I had with R. It is so interesting to see how my coding skills have improved since then. By that time, I didn't know many useful packages like {lubridate} and {tidylog}. I clearly remember that I spent a whole day trying to covert a wide-format table into a long one. I solved it with an inefficient double loop, that could be easily replaced by tidyr::pivot_longer( ).

Since then, I've learned a lot of new DataViz techniques and kept studying this incredible tool. The next step is to learn machine learning and sophisticated DataViz tools.

## 2021.2 – Forecasting Deforestation with a VAR Model
##### Econometrics II Final Project
In late 2021, I took a course on the time series. In Econometrics 2, we learned AR, MA, ARMA, ARCH/GARCH, VAR, and PCA models. As a final project, we could apply one of them to a real-life problem. 

As I was T.A. on a course on the Amazon, I tried to forecast Brazilian deforestation soon. So, I estimated a VAR model, using deforestation, cattle slaughtering, and government spending data. 

Then, I run the diagnosis tests on the data. First, I used an augmented Dickey-Fuller test (ADF) to check if the time series were stationary. Then, I used the information criteria to select the optimal lag. In the end, the candidates were VAR models with one, four, five, and twelve lags.

To choose the best model, another four tests were put into practice: the Ljung-Box (LB) test to check the absence of serial autocorrelation, the Grager test to check the presence of Grange causality, and the Breusch-Pagan (BP) test to check the homoscedasticity of residuals.

After it all, the best performing model was a VAR(5), which was estimated by OLS. Unfortunately, all candidates failed the Granger test for causality, on the deforestation component. This led to weak, but consistent models. 

Lastly, I showed the OLS-estimated coefficients, impulse-response functions, and future deforestation estimates. 

Here you can find the [script](https://1drv.ms/u/s!AjVW0s-wFcYmhYhPQu05pd0zBwMX4g?e=cYDnyd), [original datasets](https://1drv.ms/u/s!AjVW0s-wFcYmhYkPkW54k8HwvBArVQ?e=cMTKfH), and the [final report](https://1drv.ms/b/s!AjVW0s-wFcYmhYhTUfnNTSiEk8n7dg?e=lrhtWb).

Coefficients table. Only 14 of the 48 coefficients passed the significance test.
![](https://github.com/HecVini/CollegeCodes/blob/main/VAR_CoefficientsEstimates.png)
_In this project, alongside the ordinary EDA packages, I used {aTSA}, {vars}, {stats} and {lmtest} to perform the econometrics._

I clearly remember spending days understanding the econometrics of time series. [Econometrics with R](https://www.econometrics-with-r.org/14-ittsraf.html) helped me a lot. This was the first time I coined a model with real data. Unfortunately, the lack of Granger causality led to inefficient results.

## 2022.1 – How Effective was the EU ETS?
##### Environmetal Economics Paper Presentation
In early 2022 I was intern at [Observatório de Bioeconomia](https://eesp.fgv.br/centros/observatorios/bioeconomia), the FGV depertament responsable to research environemnt-related topics. By that time, we have published a [report](https://eesp.fgv.br/sites/eesp.fgv.br/files/ocbio_mercado_de_carbono_1.pdf) on the Brazilian voluntary carbon market, and I was passionate about it. That's why I enrolled in an environmental economics course.

In this semester, we learned the theory and saw some of its applications. As a final project, we had to present a paper about one of the discussed topics. So, I presented [Bayer and Aklin (2020)](https://www.pnas.org/doi/pdf/10.1073/pnas.1918128117). In this paper, the authors estimated the effectiveness of the EU Emissions Trading System using a Synthetic Control Method. Using UNFCCC and EU data, they found that in the absence of the ETS, between 2008 and 2016, the bloc's emissions would be nearly 4% higher than they were. That is, the EU would have emitted additional 1.2 bn tons of CO2.

![](https://github.com/HecVini/CollegeCodes/blob/main/Environmental_BayerAndAklin.png)<br/>

To show the paper results, I used the common EDA packages and DataViz techniques. This was an opportunity to get in touch with causal inference literature and improve DataViz skills. The presentation slides were done in Canva, and it is all available [here](https://1drv.ms/p/s!AjVW0s-wFcYmhYkaJUfy8fB1D2oSIA?e=g1Fc3h). 

## 2022.1 – Coase and Carbon Markets: could Brazil import EU Regulation?
##### Law and Economics Final Project
