# Final Project Purwadhika 2020
## Bank Marketing Campaign (During Crisis)
### Jonathan Aditia
[Github : Jonathan Aditia](https://github.com/JonathanAditia)

- dataset : https://archive.ics.uci.edu/ml/datasets/Bank+Marketing


#### Programming Languages

  <img align="left" alt="Python" width="26px" src="https://raw.githubusercontent.com/rhoit/mode-icons/dump/icons/python.png" />
  <img align="left" alt="HTML5" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png" />
  <img align="left" alt="CSS3" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png" />

<br />
<br />

![](/GithubImage/BancoDePortugal.png)

During 2008-2010, World Financial Crisis Affects Portugal, Damaging Banks and Other Financial Institutions. Often Times, Banks Suffered From Liquidity Problems Due To Massive Amount of Depositors Cashing Out Their Money. And The Problems Gets Severe, When There's Spike In (Non-Performing Loan) Credits.


## PRESENTATION


[PDF](https://github.com/JonathanAditia/BankMarketingDuringCrisis/blob/main/BankMarketingCampaign.pptx)

## STEPS

- All About Data Information [File](https://github.com/JonathanAditia/BankMarketingDuringCrisis/blob/main/BankMarketingDataInformation.ipynb)
- Short Analysis (Data) [File](https://github.com/JonathanAditia/BankMarketingDuringCrisis/blob/main/BankMarketingCampaignShortEDA.ipynb)
- Visualized Exploratory Data Analysis (Full Analysis)[File](https://github.com/JonathanAditia/BankMarketingDuringCrisis/blob/main/BankMarketingCampaignVisualizedEDA.ipynb)
- Visualized Exploratory Data Analysis Indonesian Version (Full Analysis)[File](https://github.com/JonathanAditia/BankMarketingDuringCrisis/blob/main/BankMarketingCampaignVisualizedEDA_id.ipynb)
- Machine Learning & Hyperparameter Tuning [File](https://github.com/JonathanAditia/BankMarketingDuringCrisis/blob/main/BankCampaignMachineLearning.ipynb)
- Machine Learning & Hyperparameter Tuning (Pipe) [File](https://github.com/JonathanAditia/BankMarketingDuringCrisis/blob/main/BankCampaignMachineLearningPipe.ipynb)
- Conclusion

## PROBLEMS

Customers Saving Rates Drop Significantly During Crisis and Affects Marketing Performance on Term Deposits. But At The Same Time, The Operating Expenses Remain High. Therefore, Banks Needs to Enhance The Marketing Performance, and Reduce The Marketing Expenses In Order to Utilize The Capital Wisely

## GOALS
    
- Finding Out Customers Characteristics That Has A Decent Chance to Put Term Deposits
- Finding Out Marketing Inefficiency
- Creating Machine Learning to Analyze The Potential of Each Customers to Put Term Deposits

### EXPLORATORY DATA ANALYSIS (general)
- Understading Data, Finding Major Problems

#### Data Information

![](/Image/DataInfoUCI.png)


#### Economic Landscape

![](/Image/PortugalGDPCapita.png)


#### Non-Performing Loan

![](/Image/PortugalNPL.png)


### Analysis on Customer

![](/Img2/AnalysisOnCustomer.png)

#### Elders Are The Most Likely to Put A Term Deposits, This Due To A Much Higher Savings Rate Among Elders Compare to Other Age Groups

#### People With Higher Education, Slightly More Likely To Put A Term Deposits, But The Differences Is Still Small Compared to Other Eurozone Countries

#### Single Customers Are The Most Likely To Put A Term Deposits, This Due To Higher Saving Rate Of Single Compare To Married And Divorced Customers
    This Due To Higher Spending Rate For Married Couple, Especially Families With Children

### Analysis on Campaigns

![](/Img2/AnalysisOnCustomerCampaign.png)

#### The Highest Success Rate Is at The First Contact of The Campaign, The Rest Has A Relatively Lower Success Rate
    This Indicate That Some Customers Wouldn't Change Their First Response
#### Previously Contacted Customers Has A Far Higher of Successful Campaign Rate
    As Shown Below, The Customers That Put Term Deposits on Previous Campaign, Have More Average Previous Contact History
    This Is Some of Recurring Customers But There Might Be Some Other Factors Such As Familiarity And Trust
    Previous Contact Existence Are Signs, The Person Has Already Been A Loyal Customer At Least Since The Previous Campaign

### Analysis on Contact Month and Day of Week
    Monday And Friday Has The Least Successful Campaign Rate

#### This Might Be Linked To A Psychological "Mid-Week of Weekdays" Factor, But Still Unclear And Need A Further Research
    Journal Referrence : https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0134555
    
#### March, September ,October And December Are The Months With Highest Rate of Successful Campaign

    But Despite The Higher Rate Of Successful Campaign, The Total Number Of Successful Campaigns Still Less Than Average
    May, June, July, August, And November Are The Months With Lowest Rate of Successful Campaign

#### This Due To Lower Rate Of Savings During Summer, And Too Much Uneffective Contact Performed

    But Despite The Lower Rate Of Successful Campaign, The Total Number Of Successful Campaigns Are More Than Average


![](/Image/MidWeekWeekdays.png)

![](/Img2/PortugalSavingRate.png)

### Analysis on Economic Factor

![](/Img2/AnalysisOnEconomicFactor.png)

![](/Image/InkedEuriborRate.png)

![](/Img2/AnalysisOnWorkingPopulation.png)

#### The Successful Campaign Rate Is Lower During Higher Euribor Rate

    Euribor Is The Average Rates of Interbank Borrowing Rates Based on Supply And Demand

    The Raise And Lower Interest Rate For Bank Customers, Mirrors Euribor Rates

    High Euribor Rates Is A Sign on Low Saving Rates

    When Borrowings Are High And Saving Rates Are Low, Euribor And Bank Rates Is Raised to Make Borrowings More Expensive

#### Lower Saving Rates Causes Euribor To Raise, Vice Versa

#### Successful Campaign Rate Are Lower During Higher Number Of Employee

    This Is Because Too Many Calls Performed on The Same Customers

    As Shown Before, 2nd Call And More Has Lower Rate Of Successful Campaign
    The Number of Employee Are Volatile During 2008-2010, This Is Due To Extreme Economic Factors, Not Working Population Changes

## Machine Learning

![](/GithubImage/BancoDePortugal.png)

### Machine Learning
#### Classify Potential And Unpotential Customers On Accepting Term Deposit Offers

### Machine Learning Conclusion
#### Random Forest Classifier Is The Best Model For Marketing Bank Term Deposit During Crisis

#### Random Forest Classifier Has A Good Recall, Accompanied With A Relatively Good Precision

#### This Model Might Dramaticaly Reduce The Marketing Expenses, Yet Still Highly Effective To Reach A Wide Number of Potential Customers


## Recommendation

### Marketing Expenses Can Be Lowered By Making It More Efficient, Especially on Customers With Low Potential

### There Are Ways To Make Campaign on May, June, July And August More Efficient, Since There's A Lot of Repeat Contact on The Same Customer Between This Months

### Marketing Should Be More Focused on Elders, Since Successful Campaign Rate And Saving Rate Are Higher Among Elders

### Marketing Should Be More Fucused To Students And Retired Customers, Since Successful Campaign Rate Are Higher Among This Group

### Marketing Via Cellular Are More Efficient, But Still Considering About Customers Age, Job, Time And Number of Contact on The Same Campaign

### Term Deposit Marketing, Should Be Used For Liquidity Purpose, And Not Making Loans Aggresively, Since The Non-Performing Loan Ratio Is Rising During Crisis

### During Crisis, Management Should Be More Careful on Approving Customer Loan Proposal, This Is To Keep Non-Performing Loans Under Control

### It's Far Better To Have Temporary Excess Liquidity, Rather Than Approving Risky Loans

    As Warren Buffett Believes, Good Managers Are Always Looking For Ways To Cut Costs, And Very Rarely Make Risky Loans

        Referrence:
            Warren Buffett Portofolio "Mastering The Power of Focus Investment

## DASHBOARD

![](/GitHubImage/Purwadhika.png)

### REFERENCES ON PORTUGAL BANKING AND ECONOMIC LANDSCAPE

#### Banco Português de Investimento Annual Report 2007-2010

#### Millenium Banco Comercial Português Annual Report 2009-2010

#### Millenium Banco Comercial Português Sustainability Report 2009-2010

#### www.ceicdata.com

#### www.worldbank.org

#### www.oecd.org

#### www.ec.europa.eu

#### www.journals.plos.org


### TRIBUTE TO

#### Team of Purwadhika Coding School :

    Mr. Khumaeni
    Mr. Muhammad Nurrokim
    Mr. Alfazrin Banapon 

    Purwadhika Admin
    Fellow Friends From JCDS 10 

#### Purwadhika

![](/GitHubImage/Purwadhika.png)

#### Mas Kim

![](/GitHubImage/MasKim.jpg)

#### Mas Alfa

![](/GitHubImage/MasAlfa.jpg)

### CONNECT WITH ME

[<img align="left" alt="giovaldir | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="giovaldir | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />][instagram]

[instagram]: https://www.instagram.com/jonajonajons
[linkedin]: https://www.linkedin.com/in/jonathan-aditia-234140193



