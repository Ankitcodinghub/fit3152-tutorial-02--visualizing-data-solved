# fit3152-tutorial-02--visualizing-data-solved
**TO GET THIS SOLUTION VISIT:** [FIT3152 Tutorial 02- Visualizing data Solved](https://www.ankitcodinghub.com/product/fit3152-data-analytics-tutorial-02-visualizing-data-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119395&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;FIT3152 Tutorial 02- Visualizing data Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Pre-tutorial activity:

● How is the data format different to what was analyzed in week 1. Note: More discussion over relevant concepts will be done under tidy data and data transformations in Week 4.

● Use faceted histograms to compare pedestrian count distributions at the four locations: Melbourne.Central, Southern.Cross.Station, Southbank and The.Arts.Centre.

Tutorial activities:

base R installation. To reproduce the lattice plots, you will need to load lattice. To reproduce the ggplot2 graphics you will need to install and load ggplot2 – this will then give you access to the ‘diamonds’ data which are required for question 2. Commands are below:

library(lattice)

install.packages(“ggplot2”)

library(ggplot2)

# note help site for ggplot2 is https://ggplot2.tidyverse.org/reference/

When you are installing packages, you might get the following message:

There are binary versions available but the source versions are later:

binary source needs_compilation XXXXXX 0.2.3 0.2.4 TRUE

XXXXXX 1.2.2 1.2.4 TRUE

Do you want to install from sources the packages which need compilation? (Yes/no/cancel)

My advice is to choose “no”, which means you might not get the absolute latest version of the package – but you will still get a good enough recent working version.

Major Tip

A good resource to use is the ggplot2 cheat sheet. See link below, and on

Moodle

https://rstudio.com/wp-content/uploads/2015/03/ggplot2-cheatsheet.pdf

Tips

2. Create some simple graphs to gain a better understanding of the mpg data, which comes as part of the ggplot2 package. For information on the data set use ? mpg. Use this simple, data set to create the best looking graphs you can using base graphics and ggplot2. Review the elements of a figure (Slide 54) as design factors you should consider. For example, think about the weight of lines, colours used, size of typefaces, position of elements to create simple stylish figures.

Some motivating questions to investigate:

(a) What is the relationship between city (cty) fuel consumption and highway (hwy) consumption?

(b) How is fuel consumption (cty/hwy) related to manufacturer, transmission, class etc.? Are there manufacturers or car types with particularly high or low fuel consumption?

(c) How is fuel consumption related to the number of cylinders (cyl), or engine displacement (displ)?

(d) Are there any other interesting relationships you can find in the data?

(e) Did cars become more or less fuel efficient over time? How strong is your evidence (perhaps use a non-graphical justification for this last part)?

3. The ‘diamonds’ data set comes packaged with ggplot2 and contains data about the price of

diamonds as well as information on size as well as the 4 Cs affecting diamond price: carat (size), cut, colour and clarity. The diagram below, copied from Wickham, Ggplot2: Elegant graphics for data analysis, gives you the details.

(a) Taking a random sample using the code below, create a subset of the diamonds data set: ‘dsmall’ to use in the following analysis.

set.seed(9999) # Random seed to make subset reproducible

dsmall &lt;- diamonds[sample(nrow(diamonds), 1000), ] # sample of 1000 rows

(b) Using the data ‘dsmall’ investigate the factors affecting diamond price. Using a variety of graphs and/or tables, show systematically the effect of the 4 Cs on diamond price. Which single variable has the greatest effect on price? Which has the least? Use ggplot2 for your graphics.

Try and plot price as a function of each of the variables.

You can add extra dimensions to plot by varying size or colour of the plotted points.

Tips

4. The file “body.dat.csv” contains data from a study on the relationship between body dimensions. The study measured 500+ active individuals. A legend to the data is below.

The data was obtained from http://www.amstat.org/publications/jse/jse_data_archive.htm

A related article is http://www.amstat.org/publications/jse/v11n2/datasets.heinz.html

Using the data, investigate the following:

(a) Which variables are the best predictors of height? Does this vary between men and women? For examples, are some variables better at predicting height in one gender over the other?

(b) Using the same approach, which variables are best for predicting weight in each gender?

(c) Which pairs of variables are most highly correlated? Are the same variables most highly correlated for men and women?

(d) Which measure is the best means of distinguishing between men and women? Show your results and analysis graphically.

Consider the correlation between height and other variables.

Tips

Tell me as much as you can about those customers using descriptive statistics. Using one or more graphics – such as histograms, boxplots, scatterplots, facets and anything else you can think of make a visual display to show the differences and similarities between the customers. Are there particular customers whose next visit, and spend, would be easier or harder to predict than the cohort in general? Use ggplot2 for your graphics.

For plotting, start with something easy. Try and plot a histogram of amount spent during visit for all customers. Once you can plot that use faceting to create individual histograms for each customer.

Tips

Extension: (a former sample exam question given without solution)

6. A World Health study is examining how life expectancy varies between men and women in different countries and at different times in history. The table below shows a sample of the data that has been recorded. There are approximately 15,000 records in all.

Country Year of Birth Gender Age at Death

Australia 1818 M 9

Afghanistan 1944 F 40

USA 1846 F 12

India 1926 F 6

China 1860 F 32

India 1868 M 54

Australia 1900 F 37

China 1875 F 75

England 1807 M 15

France 1933 M 52

Egypt 1836 M 19

USA 1906 M 58

Using one of the graphic types from the Visualization Zoo (see formulae and references for a list of types) suggest a suitable graphic to help the researcher display as many variables as clearly as possible.

Think about the number of dimensions in the data, and how each attrbitue would be best shown.

Tips
