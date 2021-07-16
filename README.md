 ## Machine Learning Algorithm for Options Trading
 
 
<img width="848" alt="Screen Shot 2021-07-07 at 6 32 48 PM" src="https://user-images.githubusercontent.com/80833988/124848463-bcee2200-df51-11eb-886d-85228b6cbc85.png">


> "In 2018, the Chicago Board Options Exchange reported that over $1 quadrillion worth of options
were traded in the US.
"



📌 In this Project, we assumed the role of a quantitative analyst for using a FinTech investing platform. This platform aims to offer investor sophisticated Options Trading mechanism. Using Machine Learning to evaluate our trading algorithm written in Python we strive to remove uncertainty and a human factor to automate Options investment decision making.



## Table of content 📔
- [An executive summary](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#an-executive-summary)
    - [How this project relates to fintech and machine learning?](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#how-this-project-relates-to-fintech-and-machine-learning)
- [Software Version Control](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#software-version-control)
- [Data Collection and Preparation](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#data-collection-and-preparation-10-points)
    - [Libraries](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#libraries)
- [Machine learning](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#machine-learning-40-points)
- [Documentation](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#documentation)
- [Presentation](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#presentation)
- [How to install](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#how-to-install)
- [Our team](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#team)
- [Licence](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#license)
- [Links](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#links)



## An executive summary

> " For out second project we decided to take challenging, but most rewarding approach - to work on our passion project.
"
##### How this project relates to fintech and machine learning?

We are using the power of Python, machine learning and neural network to build a sophisticated algorithmic trading bot. 
Specifically, we would like to in depth explore stock options trading 

>“Option contracts are a financial derivative that represents the right, but not the obligation, to buy (call) or sell (put) a particular security before expiration date…..
Because of the huge diversity of historical options data and their relatively few applications, no open source dataset exists."



## Software Version Control 


- Repository [ML_Algo_Options_Trading](https://github.com/JonahLeggett/ML_Algo_Options_Trading.git) was created on GitHub.

- Our team made sure files were frequently committed to repository. 

- Commit messages with appropriate level of detail included with each commit. Moreover you can find well  commented code in our Jypyter Notebook with analyses and explained results for user lacking a technical understanding

- Repository organized, relevant information about the project files included. 




## Data Collection and Preparation 

* API calls from multiple sourses, working on different databases created by using Python and following Python libraries. 

<img width="767" alt="Screen Shot 2021-07-15 at 10 57 50 AM" src="https://user-images.githubusercontent.com/80833988/125835128-09f829cf-16a4-4b23-a205-56fb1b2ea2d0.png">

#### Libraries 

*  Pandas - is a software library designed for data analytics that makes it easier to work with data from practically any type of file. Pandas supplies powerful tools for working with time data in particular, and time is a key aspect of financial analysis. Analysts typically compare and measure financial assets—from single stocks to large portfolios—across time.
* With the combination of Pandas and Jupyter Notebook, you can efficiently import, prepare, and analyze data of any type or quantity.
* We created a Google Collab group to take advantage of the speed and convenience of collaborative cloud environment.
* Following libraries were used to analyze the data 


[
<img width="686" alt="Screen Shot 2021-07-14 at 7 31 39 PM" src="https://user-images.githubusercontent.com/80833988/125718772-f6bdf922-fdff-4b1d-87e3-f5a9dc2b2f63.png">
](url)




🆕 We used following new libraries not covered in Bootcamp course 

<img width="361" alt="Screen Shot 2021-07-13 at 6 53 33 PM" src="https://user-images.githubusercontent.com/80833988/125548152-09ff4209-0955-4c09-bb42-23c2e1f96a18.png">



〰️ [yfinance](https://finance.yahoo.com/quotes/Historical,Option,DATA,Implied,Volatility,EOD/view/v1) is a popular open source library developed by Ran Aroussi as a means to access the financial data available on Yahoo Finance.
Yahoo Finance offers a range of market data on stocks, bonds etc. It also offers market news, reports and analysis and additionally options and fundamentals data- setting it apart from some of it’s competitors

〰️ FinTA (Financial Technical Analysis) supports over 80 trading indicators.

〰️ [sentiment-investor](https://sentimentinvestor.com/) APIs for stock social media data
Get high quality, granular data, on what people are saying on various social platforms about stocks and cryptocurrencies




## Machine Learning 
* Jupyter notebook and Google Colab. We used group work feature in Google Collab to be able to simultaneously work on code and make a changes in real time.
* We created 2 mashine learning models: 

   ##### SVC model (Support Vector Classification) 
>" Support-vector machines are supervised learning models with associated learning algorithms that analyze data for classification and regression analysis"

<img width="394" alt="Screen Shot 2021-07-15 at 2 22 19 PM" src="https://user-images.githubusercontent.com/80833988/125859439-a95b5fea-6f68-4b3d-a015-ebe0e610f3f9.png">

   ##### LR model(Multinomial Logistic Regression) - new machine learning model that the class hasn't already covered

>"Multinomial Logistic Regression is a statistical test used to predict a single categorical variable using one or more other variables. It also is used to determine the numerical relationship between such sets of variables."

<img width="264" alt="Screen Shot 2021-07-15 at 11 45 53 AM" src="https://user-images.githubusercontent.com/80833988/125840928-4b17f8f3-b82c-48da-a217-82d0cd1265c9.png">

* Models fit to the training data. 

<img width="695" alt="Screen Shot 2021-07-15 at 11 34 42 AM" src="https://user-images.githubusercontent.com/80833988/125839625-3768e99b-269e-4244-8599-83ecf58c5645.png">

* Trained models evaluated by using the testing data. Calculations, metrics, or visualizations that are needed to evaluate the performance included. 

<img width="576" alt="Screen Shot 2021-07-15 at 11 32 24 AM" src="https://user-images.githubusercontent.com/80833988/125839344-0c54bb57-d3f8-40cf-a0f2-7e37267eadeb.png">


* Predictions shown by using a sample of new data. Predictions compared 

<img width="602" alt="Screen Shot 2021-07-15 at 11 35 17 AM" src="https://user-images.githubusercontent.com/80833988/125839697-ad440f6d-f5e9-48a5-9763-816e749fe79a.png">

* We created a paper trade account on [TD AmeriTrade](https://www.tdameritrade.com/) and chose Multinomial Logistic Regression (lr_predicted_signals) as it perfomed better, to make a decision to call or put

[
<img width="1134" alt="Screen Shot 2021-07-14 at 8 09 19 PM" src="https://user-images.githubusercontent.com/80833988/125853138-d9a75fa0-a782-42da-a26a-f7f701556d68.png">
](url)

# Documentation 

* You can find Code in Jupyter Notebook is well commented with concise, relevant notes. 

* GitHub README.md file includes a concise project overview. We followed step by step [Technical requirements](https://courses.bootcampspot.com/courses/740/pages/16-dot-16-dot-5-technical-requirements?module_item_id=194212) for grading team convenience.

* GitHub README.md file includes detailed usage and installation instructions [How to install](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/README.md#how-to-install)
* GitHub README.md file includes examples of the application AND the results with progected revenue.



# Presentation 

<img width="1001" alt="Screen Shot 2021-07-15 at 12 48 03 PM" src="https://user-images.githubusercontent.com/80833988/125848526-be01eb85-377b-49c1-bbc0-a58ce6e47d25.png">

### Project overview

<img width="872" alt="Screen Shot 2021-07-15 at 10 55 06 AM" src="https://user-images.githubusercontent.com/80833988/125834755-ecba15cb-c67c-47c9-b575-84818c2095fc.png">

### Work with data

 
  * Source of data 
    
     The main difficulty we encountered was finding the data. The original source we planned to use - Alpaca - worked for some data. But we needed to find some alternative sourses of data. Some of the ones we tried, like [QuantConnect](https://www.quantconnect.com) - didnt work. After trial and error we end up using following libriries

<img width="969" alt="Screen Shot 2021-07-15 at 11 50 09 AM" src="https://user-images.githubusercontent.com/80833988/125841460-cb6d6369-070e-492c-bac5-c70585523c51.png">

  * Collection, cleanup, and preparation process:
Some sourses return data in json format, which has different frame construction. Our solution was to create new data frames, change indexes, concatinate or join some data frames together.
The following steps needed to be done:

 * make an API call
 * change indexes
 * drop null values and not used columns
 * create new columns
 * concatenate 

It took a lot of time and creative solutions, but we were able to do it.

<img width="776" alt="Screen Shot 2021-07-15 at 1 01 55 PM" src="https://user-images.githubusercontent.com/80833988/125850187-7fb9109b-55e0-4aaf-a48c-30ec0022fbbd.png">

##### The following concatenated dataframe includes all indicators, as well as opening and closing prices.

<img width="1504" alt="Screen Shot 2021-07-15 at 12 56 41 PM" src="https://user-images.githubusercontent.com/80833988/125849516-08477319-c588-4b10-859a-0153e6831f35.png">


### Technical Analysis

 * We used yfinance to get ohlcav data from yahoo finance for a period of time
  Technical Indicator is essentially a mathematical representation based on data sets to forecast price trends. Choosing the right set of indicators  and incorporating them into code was another challange. 
 
 >"([Investopedia](https://www.investopedia.com/))"
 
  <img width="833" alt="Screen Shot 2021-07-15 at 2 08 13 PM" src="https://user-images.githubusercontent.com/80833988/125857939-5527387f-1239-4b1a-965e-50f11d95641f.png">


 * Using the indicators we added a signal column to indicate when we should buy a call or sell our call


### Sentiment Analysis

Another challenge was to convert data for [sentiment analyses](https://sentimentinvestor.com/) into a single data frame and working through that data

<img width="957" alt="Screen Shot 2021-07-15 at 12 23 45 PM" src="https://user-images.githubusercontent.com/80833988/125845717-4cde782e-3553-40b5-af03-358c04376a9c.png">

### Combined Strategy


<img width="813" alt="Screen Shot 2021-07-15 at 12 33 44 PM" src="https://user-images.githubusercontent.com/80833988/125849108-a783f984-972b-47c6-a1e6-931225f8152f.png">

### Machine Lerning 

<img width="1214" alt="Screen Shot 2021-07-15 at 2 47 06 PM" src="https://user-images.githubusercontent.com/80833988/125862140-88ef2689-c0d3-419e-abb9-df463bfd62dd.png">


### Working on issues

>" Discuss any unanticipated insights or problems that arose and how you resolved them."

1. Finding data. 
2. Unifying the data
3. Difficulty in pricing options 
 Very hard to put  into code a process of forecasting option contract prices. Our solution was to changed the strategy. Instead we are forecasting stock prices. Because stock price directly correlates with option contracts price change we can use machine learning strategies we developeped to make a desision to buy or sell stock.
 

### Next steps
 * Potential next steps for the project would be 
    * Adding more indicators or trying different set of indicators
    * Try the strategy on different stocks
    * Incorporate Deep Learning Network 
 
 * If we had more time we would continue our research in following areas:
    * Build a bot or some other interface to automatically placed orders or execute buy/sell in real time
    * Link real accounts to the algorithm and actually start executing our strategy
    * Explore more complex trading strategies, like Iron Condor 

>"An iron condor is an options strategy consisting of two puts (one long and one short) and two calls (one long and one short), and four strike prices, all with the same expiration date. The iron condor earns the maximum profit when the underlying asset closes between the middle strike prices at expiration. In other words, the goal is to profit from low volatility in the underlying asset."


### How to install

##### Repository

* Save remote repo from GitHub to your computer (Desktop): 
in Terminal type:

```
cd desktop

git clone https://github.com/
```

Now you can find repo on your desktop


* Open a Jupyter Lab: In Terminal type command

```
jupyter lab
```

* In Jupyter Lab access saved repo folder 
* Choose [ .ipynb ] file to see the analysis report.


##### Alpaca API call

In order to successfully  run the file you have to generate your own Alpaca key and save it to .env file. Those files are hidden so Hold down the Command, Shift and Period keys (for Mac) to be sure you have it in the same folder as Jupyter Lab notebook

```
 cmd + shift + [.]
```
To generate Alpaca key you have to create your own account and request a new key. Save it in .env file, make sure to name the variables ALPACA_API_KEY and ALPACA_SECRET_KEY 
```

ALPACA_API_KEY = '<your key>'
ALPACA_SECRET_KEY = '<your key>'

```

Those steps are necessary to maintain a security of private information. 




## Team
📩 [Natalia Burrey](https://github.com/nataliaburrey)
📩 [Jonah Leggett](https://github.com/JonahLeggett)
📩 [Miguel Ortega](https://github.com/Miggs00)
📩 [Samuel Yang](https://github.com/samjinyang)

<img width="1263" alt="Screen Shot 2021-07-15 at 10 52 49 AM" src="https://user-images.githubusercontent.com/80833988/125834406-7c8ce5a6-1823-478c-9073-7fe222ea2786.png">



## License

:star: MIT [LICENSE](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/LICENSE)

## Links

* [CODE](https://github.com/JonahLeggett/ML_Algo_Options_Trading/blob/main/MLAlgoOptionsTrading.ipynb)
* [Repository copy link](https://github.com/JonahLeggett/ML_Algo_Options_Trading.git)
* [Presentation Prezi Website](https://prezi.com/view/IW1jrYNpMi6QvMPH7DrA/)


