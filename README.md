# Group Project 2

## Table of Contents

<details>
<ol>
<li>
Motivation & Summary Slide
<li>
Data Collection and Clenaing
<li>
Training model
<li>
Visualization
<li>
Postmortem
<li>
Questions
<li>
Contributions
</li>
</ol>
</details>

## Motivation & Summary Slide

- Define the core message or hypothesis of your project. 
    - There has been numerous exploits in crypto
    - We want to use machine learning tools to help us make decision when furture exploits happen
    - We will evaluate the effects of exploits on Ethereum blockchain by extracting different sources of data
    - We will choose and compare the perfromance of differenct machine learning models we used when evaluating the effects of exploits 
    - Our goal for this project is to predict how the market will respond when explots happen

## Data Collection & Cleaning

- Describe the exploration and cleanup process.
- Discuss any problems that arose with preparing the data or training the model that you didn't anticipate.
- Discuss the overall training process and highlight anything of interest with the training process: Cloud resources used, training time required, issues with training.

## Training model 

- Elaborate on the predictive model used, describing why it was the best choice for the data.
- Types of models we will use:
    - Kyle
    - Meek 
    - Rich
    - Angel
- Discuss your findings. 
- Was the model sufficient for the predictive task? 
- If not, why not? 
- What inferences or general conclusions can you draw from your model performance?

## Visualization

- 

## Postmortem

- Discuss any difficulties that arose, and how you dealt with them.
- Discuss any additional questions or problems that came up but you didn't have time to answer.
- What would you research next if you had two more weeks?

## Questions

- Open-floor Q&A with the audience.

## Contributions

- Meek Msaki @mmsaki
    - Get historical gas prices and clean data. 
        - Source: Etherscan
    - Get historical exploit data happening in crypto
        - Source: [Crypto Hacks](https://cointelegraph.com/magazine/crypto-exchange-hacks/)
    - Choose Training model
    - Explain choice of model used
    - How did your model perform
    - Project organization
    - Readme

- Kyle Plathe @kyleplathe
    - Get historical eth prices and clean data
        - Source: Kaggle
    - Get S&P 500 historical
        - Source: Alpaca API
    - Get US savings historical data
        - Source: FRED api
    - Choose model 
    - Explain choice of model used
    - How did your model perform


- Richard Melvin @rgmelvin
    - Get historical sentiment for crypto. 
        - Source: News api
    - Twitter api sentiment. 
        - Source: twitter-api
    - Get energy costs
        - Source: EIA energy information administration
    - Choose model 
    - Explain choice of model used
    - How did your model perform

- Angel 
    - Choose model
    - Explain choice of model used
    - How did your model perform
    - Visualization
    - Evaluate model performaces and compare models 

## Technical Requirements

- [x] Create notebook

- [ ] Optionally, apply a dimensionality reduction technique

- [ ] Chose models.

- [ ] Fit the model(s) to the training data.

- [ ] Evaluate the trained model(s) using testing data. 

- [ ] Include any calculations, metrics, or visualizations

- [ ] Show the predictions using a sample of new data. 

- [ ] Compare the predictions if more than one model is used.

- [ ] Save PNG images

- [ ] Use one new machine learning library, machine learning model, or evaluation metric that hasn't been covered in class.

- [x] Create a README.md 

- [ ] Include any usage instructions to set up and use the model.

- - -
