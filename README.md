#  BID CivicLytics data

On March 25th, 2020, amidst the COVID-19 emergency, [Citibeats](https://citibeats.com/), alongside with the [Inter-American Development Bank (IADB, or BID in Spanish)](https://www.iadb.org/), published an observatory to listen and help better understand the needs of people in Latin America and the Caribbean based on Twitter data:

- [BID CivicLytics Observatory](https://bidciviclytics.citibeats.com/)


The observatory has been created using [Citibeats](https://citibeats.com/)’s proprietary AI, which uses ML and NLP to detect changes in the needs of people in Latin America and the Caribbean.

IADB & Citibeats have decided to release the aggregated results used for the observatory, and make it available through this repository.
Since the civic situation is constantly evolving and social needs are wide-ranging, there is a need for real-time data to serve the decisions of key actors. At the same time, this data must be treated carefully, as the data query and categories are subject to change along with the conversation. This repository will be kept up-to-date with revised data, and changes noted here. Note that, as new sources are added to the system, records from earlier dates could change.
The goal of this repository is to enable everyone to integrate the data into their own research, or build their own solutions on top of this data. If you have any feedback on how to improve our analysis, please write an email to: labs@citibeats.com



## Origin of the data

The data has been obtained from public posts related to civic topics, using the Twitter API and data aggregators of public sources such as forums, message boards, blogs and comments in news. Please keep in mind that this is only a sample of all civic discussion.

The data is updated each day with new posts.

_NOTE: all data is subject to quality, technical, and ethical requirements before being added to the system._


## How to interpret the data

Every analysis based on Internet data has to deal with representativity. Not everyone is connected to the Internet, and not everyone shares their opinion.

The Internet penetration of the countries present in the data varies between 55% and 93%. Additionally, the following biases must be taken into account. These depend on the exact sources; examples are given below:
1. Gender: Twitter usage varies 4-17% between population, and the users registered online are usually twice men than women.
2. Age: both ends of the strip are less represented, and the majority is concentrated in the 30 - 50 age group.
3. Social: people with fewer resources may not be properly represented.

CSV columns:
- ```id```: code of the country as defined by [ISO 3166-1 alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3#Officially_assigned_code_elements)
- ```date```: day in which the raw data was published in YYYY-MM-DD format (UTC timezone)
- ```name```: name of the country in Spanish
- ```docs-N```: number of documents for the category N on a given day
- ```docs-delta-percent-N```: variation of documents (%) for the category N respect the previous day
- ```docs-percent-N```: percent of documents in the category N respect all the other categories in that day

NOTE: each row in the CSV corresponds to one day of data for a specific country.

Categories:
- ```ID 01 Governance```: Citizen reactions, doubts and criticisms of the measures to contain the pandemic and the reactivation of the economy. It reflects the responsibility of institutions to implement them and anticipate exit opportunities from the crisis.
- ```ID 02 Food Safety```: Perceptions regarding the risk of shortages of food and basic supplies (water, energy), as well as the risk of famine as a result of the loss of income among the most vulnerable.
- ```ID 03 Household economies```: Monitoring the impact of the crisis on the domestic economy, reflecting the risk of poverty for those most affected. It includes testimonials from employees, unemployed, self-employed and citizens. It also shows the perception of the gender gap in the workplace.
- ```ID 04 Markets and SMEs```: Requests for economic and fiscal policy based on the perception of the impact of the crisis on the markets, reactivation of SMEs and larger companies.
- ```ID 05 Health system```: Perception of the capacity of the health system (including personnel, health infrastructure and authorities), to face the pandemic. Includes comments on the lack of medical supplies and access to treatments and vaccines.
- ```ID 06 Citizen security and risk```: Effectiveness of protocols by spaces, companies and groups to avoid contagion. Citizen security in urban displacements in the "new normal".
- ```ID 07 Consumption options```: Consumption habits, limits and changes: non-basic goods, mobility, tourism and leisure in the new normal.
- ```ID 08 Employment and inequality```: Perceptions about the future of work: digitization of companies, consolidation of teleworking and barriers to it. In addition, it measures labor problems such as unemployment, irregularity, precariousness and gender inequality at work and new opportunities.
- ```ID 09 Access to education```: Impact of the crisis on education, from childhood to university, as well as the loss of educational level due to the digital divide and isolation, especially among rural populations and women.
- ```ID 10 Mental health```: Cases and concerns about changes in mental health due to the crisis, uncertainty and future prospects. Attention to differences in impact by gender.
- ```ID 11 Vulnerable groups```: Groups or individuals in vulnerable situations; obstacles to their economic and social reintegration: women, immigrants, groups of indigenous peoples, Afro-descendants.
- ```ID 12 Climate change impact```: Impact of the economic decline and displacement due to environmental emergencies that aggravate the crisis of vulnerable groups, families, companies (floods, natural catastrophes, fires, deforestation).
- ```ID 13 Reactivation and innovation```: Civic and business initiatives and innovations that respond to civic needs in the new normal, generation of new jobs and opportunities.
- ```ID 14 Fake news```: Dissemination of false health or political information, manipulating public opinion to induce panic, chaos or discriminate against minorities.


## More info
- [COVID-19: Escuchar y comprender a la ciudadania en momentos decisivos](http://wiconnect.iadb.org/noticias/covid-19-escuchar-y-comprender-a-la-ciudadania-en-momentos-decisivos-para-tomar-las-mejores-decisiones/)


## Contact & Feedback

labs@citibeats.com
