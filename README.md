This lab was created  by José Antonio Esteban, professor from mIA-X master's degree at BME Institute. It necessarily needed to be solved using Microsoft Azure.

Check out his LinkedIn profile.

<a href="https://www.linkedin.com/in/joseaesteban/" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a> 

### Introduction

### Instructions

we will use different services offered by Microsoft Azure. We will create a series of Logic Apps to ingest sentiment data on Twitter for the Bitcoin hashtag and the prices of the cryptocurrency itself. On the page https://www.blockchain.com/api/exchange_rates_api we can obtain the exchange values ​​of said cryptocurrency in real time.

Subsequently, we will use Microsoft Azure Machine Learning Studio (classic) with which we will implement a linear regression model to predict the price of Bitcoin based on the correlation between the sentiment expressed towards the cryptocurrency on Twitter and its exchange value. Once we obtain the prediction of the model, sales recommendations will be made once it is detected that the cryptocurrency is overvalued compared to the market value. These recommendations will be sent via SMS to our mobile phone using the Trilio text messaging service (https://www.trilio.io).

### Deliverable
