# I don't Beleive this analysis is valid because the underlying precinct populations don't follow Benford's law


# First digit visualization of in selected counties/cities in the 2020 presidential election.

Jupyter notebooks to analyze various precincts/wards for the 2020 election. Each notebook has either a source URL for the dataset or a link to the spreadsheet that was downloaded and parsed.

[Benford's Law](https://en.wikipedia.org/wiki/Benford%27s_law), also called the Newcomb–Benford law, the law of anomalous numbers, or the first-digit law, is an observation about the frequency distribution of leading digits in many real-life sets of numerical data. The law states that in many naturally occurring collections of numbers, the leading digit is likely to be small. For example, in sets that obey the law, the number 1 appears as the leading significant digit about 30% of the time, while 9 appears as the leading significant digit less than 5% of the time. If the digits were distributed uniformly, they would each occur about 11.1% of the time. Benford's law also makes predictions about the distribution of second digits, third digits, digit combinations, and so on.

### Here's mathematician James Grime explaining Benford's law:
[![Benford's Law - How mathematics can detect fraud!](https://img.youtube.com/vi/vIsDjbhbADY/0.jpg)](https://www.youtube.com/watch?v=vIsDjbhbADY)



## Here's plots of the first digits of counts in various precincts and wards for selected counties/cities:

N is the total number of precincts and wards. P is the p value for the chi sqaure test for testing benford's law. P value means the chance of getting a result this extreme by chance. P values less than 0.001(0.1%) are displayed in scientific notation. The lower the P value more likely the distribution doesn't fit benford's law. 

### Fulton County, GA:
![Fulton County](/images/fulton.png)

### Miami-Dade, FL
![Miami-Dade](/images/miami_dade.png)

### Milwaukee, WI
![Milwaukee](/images/milwaukee.png)

### Chicago, IL
![Chicago](/images/chicago.png)

### Allegheny, PA
![Allegheny](/images/allegheny.png)
