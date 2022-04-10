## WORLD BANK GDP DATA ANALYSIS!
Gross domestic product(GDP) is quantitative measure for signifying the health of a country’s economy defined across a timespan! I analyzed the GDP of countries and the World Development indicators like Health, Military, Education and Population using the data provided by the data.un.org. and the authorized company.

## DATA and Python Libraries

1. the dataset provided was uploaded to github and retrived from there.
2. Health, Military, Education and Population data along with their Countries names was retrived from World Bank opendata list of indicators.
3. Gapminder Dataset explaning Life expectancy was used
4. Exclusive list of Python libraries and packages were used for manipulation, developing reports, visualizations and widgets
5. Some of them are Pandas, Plotly, Dataprep from reporting, IpyWidgets, Raceplotly, Bubbleplot and Matplotlib
6. Countries in each Continent after grouping. Africa      48, Americas    24, Asia        29, Europe      30, Oceania      2
7. 
 
# DATA PROCESSING AND FEATURES ENGINEERING
1. Health and Education are % of GDP converted amount actually spent for analysis
2. Transforming the scientific notation to float variable
3. Meging dataframes into Single frame for Analysis by designing a preprocessing function[ preproboom ]
4. Subseting nations on basis of list using a self designed function and labelling their respective continent.
5.  

* FEATURES:
1. CONTINENT
2. SPENDING IN USD IN HEALTH
3. SPENDING IN USD IN EDUCATION
## Show the recent picture from 2017 - 2020 for world GDP?
* Aftering performing the sorting operation and removing regions, the barplot signifies US with highest GDP and Mexico with lowest for top 15 countries.
* After US followed China and then Japan, All three nation competing with each other for world class technology, product relibility and a healtier competition.
* It is evident from Visualization and futher inspection is required about GDP change of these nations. China shows positive growth even after Pandemic where as Japan was able to sustain the negative level but US lost some share of the GDP and so many lives to the pandemic even after Stimulus packages to the industry.

## Divide and Analyze top 20 countries on basis of Alliances made by nations.
* To promote competition and support rising fellow nations and protect the interest of Nations, Stretegic alliances by countries exist namely UNSC - United Nations Security council, G-7 Group of 7 ( Developed nations of the World), E-7 also known as Emerging 7 countries that work along each other to protect business interests and challenge status quo of evolution at every step.

## How does the GDP line chart depicts the growth of nations?
* A interactive plot with feature of unselecting nations helps better analyse the trend of nations.
#### UNSC
* UNITED STATES OF AMERICA is known for innovation and stands out in every group as new startups technology and research is the backbone of the country.
* All Fellow nations have a linear trend but China disrupted in 2008 after lot of forign investor looked into reverse mergers into US Stock market with chinese companies to support the stock maket crash.

#### Group of 7
* USA ranks top followed by Japan which is working hard to gain more stretegic alliances worldwide to boost theor economy and lend other nations for supporting their governments develop infrastructures and technology and create a demand for japanese products.
* UK and France are competing themselves and a race to be better than one other is visible in the trend,
* Canada has lowest GDP in the group which is rising a low steady rate and precedes Italy which is very small country with very less economic resources as compared.

#### Emerging 7
* China has outperformed the group and shows upward growth trend which makes it the market leader of todays world.
* As we unselect China, India surprises us by outperforming growth from American countries like Brazil, Mexico and even Russia.
* A very clear indication is present in 2014, which shows Russian economy falls back all emerging nations with maybe bad decision making of invading Ukraine for first time and getting opposed by world.
* Indonesia has least economy and was able to develop the products and services and challenges Mexico in present day and even growing fast.

## Group all contries on basis of Continent and see the contribution in world GDP using a widget icon as Year and Pie chart?
* In 2000, the world GDP was ruled by Europeon and Americas, making around 2/3 of World GDP
* This status quo was challenged in coming years and in 2010, Asian markets started Exports of products and services and started gaining lot of maket share. 2009 Depression was lifted by attraction of lot of investors and capital for growth in Emeging Nations and even setting up foreign offices in other nations for cheaper business operations.
* By 2015, Asian Markets started taking over Europen market and gaining more tourist and industrial attraction
* Finally in 2019-2020, Asian and American countries make more than 2/3 of the world GDP challenging the whole trend that was in 2000.

## How does these countries look over other Economic development indicators of life apart from GDP?
#### Military Expenditure, Health Expense  % of GDP, Education Expense  % of GDP and Population
* GDP GROWTH FOR UNSC, G7 and E7 Countries along with Military, Health, Education and Population Data from World Bank OpenData using the world bank library for data retrival
* 

### As the preprocessing part is done, Data report gives idea about the data ( Cardinality, Skewness, Missing Values and histograms of variables)
* Generating a report for data statistis to have an estimate of Number of rows, Missing Variables, Duplicacy. Importantly; finding skewness and same distribution in data.
* Visualize and see Missing data , similarity of distributions and verify skewness of dataset
* High Cardinality due to lot of Countries and only 5 values in Continents
* Missing values identified and handled by Median of each column
* Data is highly skewed
#### Pearson coorelation Plot signals:
* Health strongly correlated with Military expense and GDP of a nation and weakly with Population and education
* Military is Linear function of GDP
* Population does not relate strong with any factor but has identification with GDP
* Education has linkage with GDP but not srong coorelation is present!
* Maybe due to high population in Asia, these values are misleading!

### GDP Barplots of Natios state the growth in GDP for following nations
* The mean growth states the leaders and benefeciaries in each alliance!
* 
### Population boxplot for Yearwise trend from 1990 to 2020
* Population As we can see, the general global trend of is mostly in the high range.
* However, the median is rising for E7 countries as their population is rising in Billions where as G7 countries have slow rising population and have controlled procedures.
* Again, we have a lot of outliers that do not necessarily follow this average though. United States is an outlier as it has more population than compared countries.
## IMPACT OF COVID PANDEMIC ON NATIONS AND GDP CHANGE
## Compare GDP change for Emeging-7 anf Group-7 countries!
* The analysis state that Emeging 7 nations are developing at a much faster rate compared to developed nations of the world with huge industriization, Foreign Direct Investments and cheap labour costs available for developing products and providing services.
* China, Indonesia, India developed 544%, 270% and 224% from 2005 to 2020. The growth could have been more if the pandemic was not the situation, The chances of Brazil being in the list was very high but Pandemic hit so bad that they approximately 1/4 share of the pie in 2019 to 2020.
* Russia performed well trying to suppress western influence but its growth was impacted by 2014 impact of invasion of Kremlim area of Ukraine and so will be ther 2022 GDP decline
* UK, Japan and Italy are developed countries with great Human development Index and their GDP change for last 15 years was really steadt at 9, 5 and 1 % change.

## Which nation shows a strong and Fastest economic growth?
* United States has the highest economy in the world but its growth is challenged by China to great extent after 2008 crisis.
* Foreign investment and domestic policies have impacted the business and services arena which made China the fasted growing nation of the world with 544% growth from 2005 to 2020, US indexes shows 60% growth in GDP within same time frame.
* 
## How was GDP change and find countries that performed well as well as worst in Covid Pandemic?
* GDP change has been a crucial factor to determine the growth of a nation. Many countries tried their best to support economies.
* From results we can depict, CHINA was only able to outperform with positive growth of 3% whereas leading countries like USA, Germany with thir huge economy boost stimulus packages were able to maintain but had negative impact at end of day with Germany with least negative impact followed by Japan and USA.
* Italy and Canada suffered huge losses though being developed economies and were showcasing a loss like India and Indonesia.
* Emerging economies got a strong hit with Brazil losing 23% of their economic growth where as Indonesia and India took a downward trend but maintained themselves at 5-6% loss.

## What is the Military budget story for the Developed and developing markets as it is an indicator of strength for respective nations
* A racing horizental barplot showcases the trend with range till 500 Billion !
* USA always had highest Defence budgets and top technology and warfare equipments and spends more that 500 Billion (800B to be exact) on Military.
* UK and Japan, Russia were following the same trend improvising their military till 2010 followed by Germany and Italy!
* European countries have NATO as alliance which helps lower cost of development for new technology and shared among EU nations to support each other.
* China took the lead after US in 2010 and 5 years later India also joined the race surpassing Russia, UK and France
* Indonesia and Mexico never spent a lot on their military development as they dont face lot of threat from neighbouring nations

## What information is in Population growth trend from 1990 till 2020 ?
* Asia accounts for 2/3 of population for the major countries due to which it is able to provide cheap labour and services worldwide.
* Europeon has the least population and a very stable economy and people tend to live longer in these Regions.
* Germany, UK, France and Italy are historically developed regions of the world.
* USA has most of the population followed bt Brazil, Mexico which are also impacted by businesses and migration to North America!
* Turkey was growing fast in the population and crossed France and Germany in 30 years timeframe.
* Turkey has the least population whereas China has most around 20X of Turkey.

## Stacked Bar chart for Health, Education and Military insights!
* Very evident from the chart, Every nation loves to spend on Health morethan Education followed by Military
* These stacks and lines represent different contries and the amount they are contributing to Military, Education and Healthcare.
* With Rising GDP , Countries are spending more on Healthcare, Education, Military in defined order. Health is crucial factor and is linearaly linked with GDP.
* Hovering over shows limits and amount of expenditure differnt countries are doing on these sectors of development indicators. The least stack is US followed by China and top most are Brazil and Mexico.

### THE ABOVE FACTS ARE PROVED BY GROUPING BY REGION AND ESTIMATING CONTRIBUTION OF COUNTRIES OF DIFFERENT CONTINENTS TO WORLD ECONOMY as GDP, and EXPENDITURE THEY ENGAGE IN FOR HEALTCARE, EDUCATION AND MILITARY IN THE PIE CHART

##### MILITARY
* USA  spends more more than world expense on MILITARY China, India and other European allied combined.
* Asian countries have equivalent military budget like Europe but are not united like Europen allies. 
##### EDUCATION
* Europe spends the most on Education followed by Americas and Asia, Though Huge population expenditure in Education is relatively low in Asian countries.
##### HEALTH
* Americas spends most in health sector followed by Europe, Asia tries to follow up but will take a lot of time to reach world standards.



#### Population index shows asian countries has 3/5 population followed by Africa and Americas.
#### Its really sad to see though Asia has highest population and military budgets they are parsimonious on their approach towards spending on Education and Health.
#### A country always spends more on healthcare and education rather than military; Healthcare spending is linear function of GDP.
#### American countries spend more on military followed by China & India with US and China are becoming Arch Rivals in Control competition!


# DATASET and Analysis REFERENCES 
# Raceplotly reference
https://towardsdatascience.com/making-a-bar-chart-race-plot-using-plotly-made-easy-8dad3b1da955
# BUBBLE PLOT -- Hans Rosling Youtube video
https://www.youtube.com/watch?v=jbkSRLYSojo

1. https://github.com/CSSEGISandData/COVID-19
2. https://data.worldbank.org/indicator/SH.XPD.CHEX.GD.ZS
3. https://data.worldbank.org/indicator/MS.MIL.XPND.GD.ZS?year=2016
4. https://data.worldbank.org/indicator/NY.GDP.MKTP.CD
5. https://data.worldbank.org/indicator/SE.XPD.TOTL.GD.ZS
6. https://data.worldbank.org/indicator/SP.POP.TOTL
7. Using Gapminder Dataset a restriction is found that I am not able to go beyond 2007 due to inner joins I am doing on that dataset>> https://pypi.org/project/gapminder/
## GDP per Capita , feature could be enginnered bu dividing GDP / Population but was not used as it was available in Gapminder dataset for final buubble plot

