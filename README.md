# CollegeCodes
This repository aims to be a time machine. I hope I check it in the future and feel proud looking into a hard, but steady, progress ladder. It's been nearly three years since I took my first programming class, and I have been using coding skills almost daily. 

This is a summary of the main work I've done during my Economics undergraduate at Fundacao Getulio Vargas (2019 - 2022). Those were four years of intense learning, a lot of economic theory, and discoveries. Four years ago, I simply didn't know the universe of **really interesting** things I would discover over that journey. This repository is just a piece of it all.

## 2020.2 – Meat Production: a Worldwide Analysis
##### Pyhon Class Final Project
My first contact with programming languages was actually in Python. I would just discover R months later. It was a 60h introductory course with the basic syntax and helpful libraries on explanatory data analysis (EDA). 

The final project was composed of a simple task: clean a dataset and analyze it. By that time, I was enrolled in a research project on the Brazillian meat market, and I picked a dataset related to it. 

So, I've downloaded a 15k rows FAO time series with meat production, by country, since 1990. That main challenge was to clean it, in such a way that I could present the main producers over time, by meat type. It took me some two weeks - and a lot of help from Stack Overflow - to make the interactive charts with Plotly. 

Here you can find the [script](https://1drv.ms/u/s!AjVW0s-wFcYmhYgJmcyQMpTK9krPlQ?e=kOgAeq) and the original [database](https://1drv.ms/u/s!AjVW0s-wFcYmhYgKZr6RKEd7aflbsg?e=qJvmBw).

![](https://github.com/HecVini/CollegeCodes/blob/main/Computacao_CodePrint.png)<br/>
<br/>
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
