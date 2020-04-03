# COVID19 BID Data

On March 25th, 2020, as a response to COVID-19 emergency,  [Citibeats](https://citibeats.net/), alongside with the [Inter-American Development Bank (IADB, or BID in Spanish)](https://www.iadb.org/), published an observatory to listen and help better understand the needs of people in Latin America and the Caribbean based on Twitter data:

- [COVID-19 Observatory](https://covid19-civiclytics.citibeats.com/)


The observatory has been created using [Citibeats](https://citibeats.net/)’s proprietary AI, which uses ML and NLP to detect changes in the needs of people in Latin America and the Caribbean.

As COVID-19 is a worldwide emergency, IADB & Citibeats have decided to release the aggregated results used for the observatory, and make it available through this repository.

The data has been obtained and analyzed with the utmost urgency to inspire civic actions and inform the decisions of key actors, and must, therefore, be treated carefully. Since the current situation may change rapidly and in unexpected ways, more data will become available as events develop, which can lead to alternative (even contradictory) analyses. This repository will be kept up-to-date with revised data while the crisis persists. Note that, as new sources are added to the system, records from earlier dates could change.

The goal of this repository is to enable everyone to integrate the data into their own research, or build their own solutions on top of this data. If you have any feedback on how to improve our analysis, please write an email to: labs@citibeats.net


## Origin of the data

The data has been obtained from public tweets related to COVID-19 using the Twitter API. The tweets include the words *COVID-19*, *coronavirus*  or other terms that are closely related to them.

The data has been limited to people that explicitly indicate their geolocation in their profiles, so their opinions and needs can be placed and compared among regions. It is important to bear in mind that not all users are equally likely to specify their location, whether for privacy, computer literacy, or some other reason. This can skew the collected data towards specific segments, which must, therefore, be interpreted accordingly.

The data is constantly updated with new tweets.

Citibeats is actively looking for other text-based sources so they can be added to the analysis, in order to increase the reach and representativity. If you have data relevant for the observatory that you'd like to share with Citibeats, please fill out this form (Spanish):

- [Añadir fuentes al Observatorio Ciudadano COVID-19 del Grupo BID](https://go474190.typeform.com/to/YRNlNe)

_NOTE: all data is subject to quality, technical, and ethical requirements before being added to the system._


## How to interpret the data

Every analysis based on Internet data has to deal with representativity. Not everyone is connected to the Internet, and not everyone shares their opinion.

The Internet penetration of the countries present in the data varies between 55% and 93%. Additionally, the following biases must be taken into account:
1. Gender: Twitter usage varies 4-17% between population, and the users registered online are usually twice men than women.
2. Age: both ends of the strip are less represented, and the majority is concentrated in the 30 - 50 age group.
3. Social: people with fewer resources may not be properly represented.



CSV columns:
- ```id```: code of the country as defined by [ISO 3166-1 alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3#Officially_assigned_code_elements)
- ```date```: day in which the raw data was published in YYYY-MM-DD format (UTC timezone)
- ```name```: name of the country in Spanish
- ```docs-N```: number of documents for the category N on a given day.
- ```docs-delta-percent-N```: variation of documents (%) for the category N respect the previous day
- ```docs-percent-N```: percent of documents in the category N respect all the other categories in that day

NOTE: each row in the CSV corresponds to one day of data for a specific country.

Categories:
- ```ID 1 - Crisis actions```: conversation regarding the public response at containing and mitigating the health crisis. It reflects the responsibility of the government to implement the state of emergency, the quarantine and impact policies.
- ```ID 2 - Food safety```: perception regarding food shortages and supply chains.
- ```ID 3 - Financial security. (homes)```: tracking the impact of the crisis on the domestic economy. Includes testimonials from employees, freelancers, and caretakers.
- ```ID 4 - Financial security. (business)```: perception of the impact of the crisis on the markets, capturing macroeconomic trends and business concerns.
- ```ID 5 - Healthcare security```: perception of the strength of the healthcare system and its ability to cope with the pandemic (including personnel, infrastructure, and authorities).
- ```ID 6 - Cultural impact```: the cultural dimension of the response to coronavirus, including hygiene practices, nursing, and social distancing.
- ```ID 7 - Remote work```: perceptions about remote work and the existing tools to facilitate it.
- ```ID 8 - Education```: impact of the crisis on the education system and learning alternatives during the lockdown, from kindergarten to college.
- ```ID 9 - Mental health```: the reflection about the effects of the crisis and the lockdown on mental health.
- ```ID 10 - Vulnerable people```: visibility of collectives at risk from the standpoint of healthcare (elderly people and people with respiratory problems) and socioeconomic level (migrants, homeless people, etc.)
- ```ID 11 - Environment```: impact of the economic downturn on the environment.
- ```ID 12 - Citizens' initiatives```: reflects the strengthening of the social fabric during a crisis. Includes citizen initiatives to flatten the curve of the pandemic, sensitize and reduce the effects of the lockdown.
- ```ID 13 - Fake news```: the spread of fake information, whether related to healthcare or politics and any information aimed at manipulating the public opinion to induce panic, chaos or discrimination against minorities.


## More info
- [COVID-19: Escuchar y comprender a la ciudadania en momentos decisivos](http://wiconnect.iadb.org/noticias/covid-19-escuchar-y-comprender-a-la-ciudadania-en-momentos-decisivos-para-tomar-las-mejores-decisiones/)


## Contact & Feedback

labs@citibeats.net
