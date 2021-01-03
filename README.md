# Data Visualization Considerations or Best Practices

<a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" alt="Creative Commons License" /></a>
This tutorial is licensed under a <a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

# Table of Contents
- [Overview](#overview)
- [Choosing a Chart Type](#choosing-a-chart-type)
- [Working With Visual Cues](#working-with-visual-cues)
- [Essential Visualization Elements](#essential-visualization-elements)
- [Data Communication, Justice, and Power](#data-communication-justice-and-power)
- [Additional Resources](#additional-resources)
  * [Books](#books)
  * [Websites and Blogs](#websites-and-blogs)
  * [Podcasts](#podcasts)

# Overview

When first learning how to programatically generate data visualizations, it's easy to be overwhelmed by syntax nuances.

Let's take a step back and think through ***why*** we want or need to visualize data.

A quote from NYU engineering faculty Enrico Bertini, whose reserach looks at visual representations of information:

"Visualization projects with high visibility focus on two main purposes: inspiration and explanation. Visualization can however be used (and is actually used) to increase understanding of complex problems through data analysis. These project are less visible but by no means less important...The main goal here is to extract information out of data with the purpose of answering questions and advancing understanding of some phenomenon of interest"

Citation: Enrico Bertini, ["From Data Visualization to Interactive Data Analysis"](https://medium.com/@FILWD/from-data-visualization-to-interactive-data-analysis-e24ae3751bf3) *Medium* (28 November 2017).

We can think of data visualization as a means or tool that enables us to do things like...
- Analyze an unmanageably large body of primary source materials
- Bring together a range of data sets that require computation tools to connect, integrate, or synthesize disparate elements

This page is not designed to be an exhaustive resource on how to approach data visualization as an act of communication.

What it does attempt to do is highlight resources and approaches that cover some preliminary condsiderations.

It also highlights work that grounds data visualization in the core tenents of intersectional feminist theory and activism.

# Choosing a Chart Type

At its core, data visualization highlights or draws attention to aspects of an underlying dataset.

<p align="center"><a href="https://github.com/kwaldenphd/data-viz-intro/blob/main/figures/Figure_1.jpg?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/data-viz-intro/blob/main/figures/Figure_1.jpg?raw=true" /></a></p>

Image source: A. Abela, [Extreme Presentation Method](http://extremepresentation.typepad.com/files/choosing-a-good-chart-09.pdf)

A few of the ways visualizations can highlight a dataset:
- Comparison
- Relationship
- Distribution
- Composition
- Connection
- Location

Some core questions to ask when building a visualization:
- What aspect(s) of the data do you want to highlight?
- What is the number of variables (and data types)?
- Is this going to be a static visualization, or is there a dynamic component (i.e. showing change over time)?

Once you have a sense of what you want the visualization to accomplish, you can make strategic choices about visualization options.

The [A. Abela graphic](http://extremepresentation.typepad.com/files/choosing-a-good-chart-09.pdf) featured above is a good place to start.

Peter Aldhous's *Intro Data Viz* course (Fall 2016) includes useful questions to consider.
- ["Data visualization: basic principles"](http://paldhous.github.io/ucb/2016/dataviz/week2.html)

<p align="center"><a href="https://github.com/kwaldenphd/data-viz-intro/blob/main/figures/Figure_2.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/data-viz-intro/blob/main/figures/Figure_2.png?raw=true" /></a></p>

Image source: [Ferdio's DataVizProject](https://datavizproject.com/)

Ferdio's DataVisProject also includes examples of a wide range of visualization types.

You can explore the library by visualization type, data structure, function, and shape.

# Working With Visual Cues

The wide range of customization or styling options when building a visualization can be overwhelming.

We can think of these style elements as visual cues that can help a visualization achieve a desired communication or rhetorical goal.

<p align="center"><a href="https://github.com/kwaldenphd/data-viz-intro/blob/main/figures/Figure_3.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/data-viz-intro/blob/main/figures/Figure_3.png?raw=true" /></a></p>

Image source: Peter Aldhous, ["Data visualization: basic principles"](http://paldhous.github.io/ucb/2016/dataviz/week2.html), *Intro Data Viz* (Fall 2016)

Common visual cues:
- Length
- Slope
- Color hue
- Volume
- Angle
- Area
- Color intensity

To have meaningful visual cues, make sure the math adds up.

That is, make sure you know what arithemtic operations are happening in the process of generating the visualization.

One component of making sure the math adds up is knowing how the chart type you have chosen interacts with the underlying data.

Another component, particularly for more complex statistical visualizations, is to make sure the visualization is communicating what you intend.

A great place to start for making sure the math adds up is Carl Bregstrom and Jevin West's *Calling Bullshit: Data Reasoning in a Digital World* open curriculum and book.

The [open curriculum](https://www.callingbullshit.org/index.html) covers topics like causality, statistical traps, sample size, correlation, and selection bias in relation to data analysis and visualization.

Their book [*Calling Bullshit: The Art of Skepticism in a Data-Driven World*](https://www.penguinrandomhouse.com/books/563882/calling-bullshit-by-carl-t-bergstrom-and-jevin-d-west/) (Penguin Random House, 2020) is also a useful resource.

Meaningful visual cues are also true to the 'feel' of the data. 

This requires knowing enough about the underlying dataset to know when a visualization is not accurately representing the underlying data.

Summary statistics or descriptive statistics are a useful place to start.
- Non-programming resources
  * [DataBasic.io](https://www.databasic.io/)
- Python resources
  * [Introduction to `pandas` tutorial](https://github.com/kwaldenphd/pandas-intro)
  * [EDA in `pandas` tutorial](https://github.com/kwaldenphd/eda-pandas)
  * Wes McKinney, [*Python for Data Analysis: Data Wrangling With pandas, Numpy, and IPython*](https://www.oreilly.com/library/view/python-for-data/9781491957653/) (O'Reilly, 2017)
  * Jake VanderPlas, [*Python Data Science Handbook: Essential Tools for Working with Data*](https://jakevdp.github.io/PythonDataScienceHandbook/) (O'Reilly, 2016)
- R/RStudio resources
  * [Introduction to `dplyr` tutorial](https://github.com/kwaldenphd/dplyr-intro)
  * [Getting started with statistics tutorial](https://github.com/kwaldenphd/intro-statistics-rstudio)
  * Danielle Navarro, [*Learning Statistics With R: A Tutorial for Psychology Students and Other Beginners*](https://learningstatisticswithr.com/book/) (2019)
  * [Stats2Labs](https://stat2labs.sites.grinnell.edu/) project website
  
One overarching principle to keep in mind is that data visualization is an act of communication, and visual representation of information is inherently a form of storytelling.

Spending time thinking abstractly or conceptually about what a data visualization needs to accomplish or communicate is immensely valuable.

There are a range of words or terms that can describe this activity, including storyboarding or sketching.

A wonderful place to start is the work of data artist Giorgia Lupi.
- [Data Humanism, The Revolution will be Visualized](http://giorgialupi.com/data-humanism-my-manifesto-for-a-new-data-wold) *PrintMag* (30 January 2017)
- [*Dear Data*](http://www.dear-data.com) (Princeton Architectural Press, 2016)
- [*Observe, Collect, Draw!: A Visual Journal*](http://giorgialupi.com/publications) (Princeton Architectural Press, 2018)

In April 2019, data visualization designer and artist Nadieh Bremer in collaboration with Google Trends released a ["Why do cats * dogs ...?"](https://whydocatsanddogs.com) project featuring interactive visualizations exploring the how and why behind common pet-related Google search questions.

Bremer wrote a detailed blog post about the design process for the project.
- ["The Design Process of 'Why Do Cats & Dogs ...?'](https://www.visualcinnamon.com/2019/04/designing-google-cats-and-dogs) *personal blog* (11 April 2019)

Another wonderful resource is data artist and former Library of Congress Innovator-In-Residence Jer Thorp's book [*Living in Data: A Citizen's Guide to a Better Information Future*](https://us.macmillan.com/books/9780374720513) (Macmillan, 2020).

These resources are a useful starting place to explore strategies and practices for designing rich, meaningful data visualizations.

# Essential Visualization Elements

When building data visualizations, it is useful to keep in mind the core elements needed for a visualization to be legible, accessible, and meaningful.

The following elements can appear in a data visualization via a wide range of design options:
- Title and subtitle
- Axis labels
- Coordinate system
- Scale
- Legend
- Source information

It is also critically important to make sure the visualization will be accessible to the widest range of possible users.

Prioritizing accessibility shapes color choices and visual style options, but also underscores the need to have a deep grasp on what you are trying to accomplish in a visualization.

Some of the questions to consider include...

Is your visualization's color scheme/pallete/map accessible for individuals with color blindness?

Are your visualization's color components or other visual cues going to be legible in the final publishing medium or format? 
- For example, you may have a visualization that is readable on a large projection screen but not on letter-size paper.

Can someone interacting with your visualization easily access the data driving the visualization? 
- In situations where you are working with proprietary, sensitive, or licensed data, providing the full back-end dataset may not always be possible.
- At the very minimum, a citation to the data source is needed.
- When possible, document the steps taken and changes made to the data from its original form in the process generating the visualization
- The gold standard here is reproducibility, with code/scripts and data available to end users

Is the visualization the only way or place this information is communicated?
- Imagine a situation where a visually impaired person is interacting with your visualization. 
- Having multiple points of entry or forms of representation for the information contained in the visualization ensures this information is available to the widest possible range of users.

Things like alt text, plain-text tables, captions, narrative text, etc. can all help improve the accessibility of data visualizations.

Axis Maps's [Colorbrewer2.0](https://colorbrewer2.org/) is a useful tool for finding accessible color palletes.

# Data Communication, Justice, and Power

As scholar Virginia Eubanks addresses at length in [*Automating Inequality: How High-Tech Tools Profile, Police, and Punish the Poor*](https://us.macmillan.com/books/9781250074317) (St. Martin's Press, 2017), the United States has a long history of using its most cutting-edge science and technology to discriminate, marginalize, oppress, and surveil. The poorhouse and scientific charity of an earlier era have been replaced by digital tracking and automated decision-making systems like facial recognition and risk prediction algorithms.

Data and data visualization are fundamentally implicated in these technologies and practices.

Data can be used to create communities, advance research, and expose injustice. But data can also be used to discriminate, marginalize, and surveil. Scholarship in critical data studies draws on intersectional feminist theory and activism to identify models for challenging existing power differentials in data-related fields, with the aim of using data-driven methods and tools (including visualization) to work towards justice.

Understanding the fundamental relationship between data (visualization) and power prompts us to consider the impact data visualizations we create have.

We could spend an entire semester addressing this historical context and considering how patterns of injustice and inequity relate to the work of data analysis and communication.
- *ND students--Professor Walden's "Data Feminism" course does just this and is typically offered alternating fall semesters (2022, 2024).

For now, a few resources that are leading the way in this area.

[Feminist Data Manifest-No](https://www.manifestno.com/)
- "The Manifest-No is a declaration of refusal and commitment. It refuses harmful data regimes and commits to new data futures." 
- Cifor, M., Garcia, P., Cowan, T.L., Rault, J., Sutherland, T., Chan, A., Rode, J., Hoffmann, A.L., Salehi, N., Nakamura, L. (2019). Feminist Data Manifest-No. Retrieved from: https://www.manifestno.com/.

[Design Justice Network](https://designjustice.org/)
- "The Design Justice Network is an international community of people and organizations who are committed to rethinking design processes so that they center people who are too often marginalized by design." 
- [Design Justice Network Principles](https://designjustice.org/read-the-principles)
- Sasha Constanza-Chock, [*Design Justice: Community-Led Practices to Build the Worlds We Need*](https://mitpress.mit.edu/books/design-justice) (MIT Press, 2020).

[Data Feminism](datafeminism.io/)
- "Data Feminism offers strategies for data scientists seeking to learn how feminism can help them work toward justice, and for feminists who want to focus their efforts on the growing field of data science. But Data Feminism is about much more than gender. It is about power, about who has it and who doesn’t, and about how those differentials of power can be challenged and changed."
- [Data Feminism infographics](http://datafeminism.io/blog/book/data-feminism-infographic/) by Catherine D’Ignazio, Lauren Klein and Marcia Diaz. 2020
- Data Feminism Reading Group [archived materials](http://datafeminism.io/blog/book/data-feminism-reading-group/)
- Catherine D'Ignazio and Lauren F. Klein, [*Data Feminism*](https://direct.mit.edu/books/book/4660/Data-Feminism) (MIT Press, 2020)

[Our Data Bodies](https://www.odbproject.org/)
- Our Data Bodies is "a five-person team concerned about the ways our communities’ digital information is collected, stored, and shared by government and corporations. Based in marginalized neighborhoods in Charlotte, North Carolina, Detroit, Michigan, and Los Angeles, California, we look at digital data collection and our human rights, work with local communities, community orginizations, and social support networks, and show how different data systems impact re-entry, fair housing, public assistance, and community development."
- Virginia Eubanks, [*Automating Inequality: How High-Tech Tools Profile, Police, and Punish the Poor*](https://us.macmillan.com/books/9781250074317) (St. Martin's Press, 2017)

[Data for Black Lives](https://d4bl.org/)
- "Data as protest. Data as accountability. Data as collective action."

# Additional Resources

There are a WIDE range of texts and resources on data visualization. 

This is a partial list of resources not mentioned above.

## Books

- Kieran Healy, *Data Visualization: A Practical Introduction* (Princeton University Press, 2019)
- Andy Kirk, *Data Visualisation: A Handbook for Data Driven Design* (SAGE Publications, 2019)
- Alberto Cairo, *The Truthful Art: Data, Charts, and Maps for Communication* (New Riders, 2016)
- Alberto Cairo, *How Charts Lie: Getting Smarter about Visual Information* (W.W. Norton, 2019)
- Nathan Yau, *Data Points: Visualization That Means Something* (Wiley, 2013)
- Nathan Yau, *Visualize This: The FlowingData Guide to Design, Visualization, and Statistics* (Wiley, 2011) 
- Scott Berinato, *Good Charts: The Harvard Business Review Guide to Making Smarter, More Persuasive Data Visualizations* (Harvard Business Review Press, 2016)
- Stephanie Evergreen, *Effective Visualization:  The Right Chart for the Right Data* (SAGE Publications, 2019)
- Cole Nussbaumer Knaflic, *Storytelling With Data: A Data Visualization Guide for Business Processionals* (Wiley, 2015)
- Cole Nussbaumer Knaflic, *Storytelling With Data: Let's Practice!* (Wiley, 2019)
- Edward Tufte, *The Visual Display of Quantitative Information, 2nd edition* (Graphics Press, 2001)
- Edward Tufte, *Envisioning Information* (Graphics Press, 1990)
- Edward Tufte, *Visual Explanations: Images and Quantities, Evidence and Narrative* (Graphics Press, 1997)
- Edward Tufte, *Beautiful Evidence* (Graphics Press, 2006)

## Websites and Blogs

- Alberto Cairo, [The Functional Art](http://www.thefunctionalart.com/)
- Nathan Yau, [FlowingData](https://flowingdata.com/)
- Andy Kirk, [Visualising Data](https://www.visualisingdata.com/)
- Nadiah Bremer, [Visual Cinnamon](https://www.visualcinnamon.com/blog/)
- Cole Nussbaumer Knaflic, [Storytelling With Data](http://www.storytellingwithdata.com/)
- [Information is Beautiful](https://informationisbeautiful.net/)
- Kaiser Fung, [Junk Charts](https://junkcharts.typepad.com/)
- The Economist, [Graphic Detail](https://www.economist.com/graphic-detail/)
- Gregor Aisch, [Driven by Data](https://driven-by-data.net/)

## Podcasts
- Enrico Bertini and Moritz Stefaner, [Data Stories](https://datastori.es/)
- Alli Torban, [Data Viz Today](https://dataviztoday.com/)
- Cole Nussbaumer Knaflic, [Storytelling With Data](http://www.storytellingwithdata.com/podcast)
- Lea Pica, [The Present Beyond Measure](http://leapica.com/podcast/)
