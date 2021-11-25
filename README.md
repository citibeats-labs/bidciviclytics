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
- `id`: code of the country as defined by [ISO 3166-1 alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3#Officially_assigned_code_elements)
- `date`: day in which the raw data was published in YYYY-MM-DD format (UTC timezone)
- `name`: name of the country in Spanish
- `docs-N`: number of documents for the category N on a given day
- `docs-delta-percent-N`: variation of documents (%) for the category N respect the previous day
- `docs-percent-N`: percent of documents in the category N respect all the other categories in that day
- `docs-female-N`: number of documents for the category N on a given day, which are estimated to be from females
- `docs-male-N`: number of documents for the category N on a given day, which are estimated to be from males
- `docs-questions-N`: number of documents for the category N on a given day, which were questions
- `docs-complaints-N`: number of documents for the category N on a given day, which were complaints

NOTE: each row in the CSV corresponds to one day of data for a specific country.

Categories:
- ```ID 01 Agriculture and rural development```: Emerging problems and solutions in agriculture, agricultural technology and its products. It includes different agricultural sectors and points in the agricultural production chain.

- ```ID 02 Education```: Cases and concerns related to the educational world, including different educational stages and modalities, as well as tools, resources and emerging challenges in the field of education.

- ```ID 03 Energy```: Trends, applications and technological development derived from energy innovation, specifically in renewable sources. Challenges, doubts and criticisms related to energy, including access, natural resources and employment.

- ```ID 04 Environment```: Concerns and risk perception about climate change and environmental preservation. This includes requests and criticisms of environmental policies, views on sustainable development and economic, technological and social solutions to reduce the carbon footprint.

- ```ID 05 Access to credit```: Impact of the crisis on access to credit, including concerns and risks when making financial transactions such as requesting microcredits. Public perception of banking transparency, scholarships and grants, and also financial inclusion.

- ```ID 06 Health```: Updates and concerns about health and the health system, including specific information about health centers and resources. It also includes information on vaccines, without a special focus on COVID-19.

- ```ID 07 Employment and entrepreneurship```: Impact of the crisis on employment, perceptions about unemployment. It also includes the latest trends on entrepreneurship, business development and private companies.

- ```ID 08 Social investment```: Social policy requests, citizen participation processes for the democratization of different social realities. It also includes updates on citizen creativity and culture.

- ```ID 09 Sustainable tourism```: Opportunities and needs related to sustainable tourism. It also includes updates on artisan work.

- ```ID 10 Trade```: Trends on trade development and the impact of the crisis on the production chain, exports and imports. Includes the different forms of foreign investment.

- ```ID 11 Infrastructure```: Reactions and requests on infrastructure, mobility and transportation. This includes roads, airports and ports. Identification of areas with coverage or connectivity problems.

- ```ID 12 Urban development and housing```: Concerns and trends on urban development, including historical heritage and associated environmental impact. Reflects the impact of the crisis on urban housing and neighborhoods.

- ```ID 13 Water and sanitation```: Perceptions of water quality, including sanitation infrastructure. Problems related to supply and access to piped water, satisfaction with infrastructures, supply basins. Information on the impact of flooding.

- ```ID 14 Perception of cost of living```: Perception of impoverishment and loss of purchasing power. Problems and concerns about quality of life and its cost, inflation and lack of economic resources.

- ```ID 15 Migrations```: Needs expressed by the migrant population, individuals who are in displacement or by citizens in general, related to the migratory phenomenon. Includes border tensions and updates on regularization of papers.

- ```ID 16 Food security```: Cases and concerns associated with food security, including food shortages and famine.

- ```ID 17 Citizen security```: Citizen perceptions of security and justice, including altercations with police and criminals.

- ```ID 18 Governance```: Allows to detect sectors in which citizens consider institutions distant (lack of access to digital government) and the needs for public policies.


## More info
- [COVID-19: Escuchar y comprender a la ciudadania en momentos decisivos](http://wiconnect.iadb.org/noticias/covid-19-escuchar-y-comprender-a-la-ciudadania-en-momentos-decisivos-para-tomar-las-mejores-decisiones/)


## Contact & Feedback

labs@citibeats.com
