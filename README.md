# data-512-homework_2

## Goal
The goal of this project is to do some simple analysis on the number of articles and high quality articles per country and region for politicians.

## Notes
 - Population values and the per capita values are in terms of millions of people.

## Intermediary Files
wp_countries-no_match.txt contains a list of countries that I was not able to match between my initial politican and country file and population by country file. 


## Research Implications
I learned that the countries with the most articles per capita are all western nations, with the fewest being Asian countries. The countries with the highest quality articles per capita are almost entirely in Southern Europe, while the countries with the lowest quality articles per capita aooears to be decently spread. Unsuprisingly then, European and wester n regions outperfom asian and even african regions in articles per capita and quality articles per capita.

I expected to see bias towards English speaking countries since we were looking at English Wikipedia, which is somewhat represented in the fact that European countries were the highest performing. There seems to be more of a divide between east and west rather than along language lines. These results suggest that English Wikipedia focuses on European and Western countries over Asian ones. To improve these issues, an interested party could modify the data with articles from other languages in Wikipedia.

## Known Problems
he file creation script takes a while to execute because there is a set delay for each article request. The file creation script can take up to 20 or 30 minutes to run.

## Licensing
The data is licensed under CC-BY-SA 3.0 (https://creativecommons.org/licenses/by-sa/3.0/) and GFDL (https://www.gnu.org/licenses/fdl-1.3.html) licenses Wikimedia REST API Terms and Conditions: https://www.mediawiki.org/wiki/Wikimedia_REST_API#Terms_and_conditions

## API Documentation
Documentation for the Wikipedia API Can be found at the link below: General Rest API Documentation: https://wikimedia.org/api/rest_v1/#/Pageviews%20data/get%20metrics%20pageviews%20aggregate%20project%20access%20agent%20granularity%20start%20end

Analytics/AQS/Pageviews: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews
